```{mermaid}
%%| fig-width: 2
flowchart LR
    O[Ollama] --> C(CLI)
    O --> UI(UI)
    O --> A(API)
    A --> P(Python)
    A --> JS(Javascript)

    style O fill:#f96
```
