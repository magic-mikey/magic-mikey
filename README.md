Hey! I'm Mikey, and I code things sometimes!

Here's the very scientific process:

```mermaid
flowchart TD
    A[💡 think of thing] --> B[caffeinate]
    B --> C[make thing]
    C --> D{does thing work?}
    D -- "no" --> E[kill bug fix thing]
    E --> C
    D -- "yes" --> F[🚀 full send]
    F --> G[think of more thing]
    G --> B
    A -. "wait, new thing" .-> G
    B -. "wait, new thing" .-> G
    C -. "what if instead..." .-> G
    D -. "wait, new thing" .-> G
    E -. "bug? new thing" .-> G

    classDef idea fill:#fff3b0,stroke:#e09f3e,color:#3d2c00,stroke-width:2px
    classDef build fill:#cdeffd,stroke:#2496c8,color:#123447,stroke-width:2px
    classDef question fill:#eadcff,stroke:#8b5cf6,color:#2e1657,stroke-width:2px
    classDef bug fill:#ffd6d6,stroke:#e05252,color:#4a1111,stroke-width:2px
    classDef ship fill:#d6f5d6,stroke:#39a96b,color:#123d25,stroke-width:2px

    class A,G idea
    class B,C build
    class D question
    class E bug
    class F ship
```

<!---
magic-mikey/magic-mikey is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
