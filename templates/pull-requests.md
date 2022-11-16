# PR Review

```mermaid
flowchart LR
   a[Pull Request]-->Icebox;
   a[Pull Request]-->Review;
    subgraph  
    Icebox-->
    Review-->
    Triage-->Blocked;
    Triage-->Ready-->Closed;
    Blocked-->Icebox;
    end
```