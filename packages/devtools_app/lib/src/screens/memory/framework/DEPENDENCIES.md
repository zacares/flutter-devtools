<!---
Generated by https://github.com/polina-c/layerlens
Dependencies that create loops (inversions) are marked with `!`.
-->

```mermaid
flowchart TD;
memory_controller.dart-->offline_data;
memory_screen.dart-->screen_body.dart;
memory_tabs.dart-->memory_controller.dart;
screen_body.dart-->memory_controller.dart;
screen_body.dart-->memory_tabs.dart;
```

### Inversions
In this folder: 0

Including sub-folders: 0

