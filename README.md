# CheatSheets

## Architecture / How it Works

```mermaid
flowchart LR
    A[User] --> B[Cheatsheets]
    B --> C{Logic}
    C --> D[(Data)]
    C --> E[Output]
    D --> C
```
