```{mermaid}
%%| fig-width: 2
flowchart LR
    O[Ollama] --> C(CLI Komut Satırı)
    O --> UI(UI)
    UI --> UI1[Open WebUI]
    UI --> UI2[Ollama UI]
    UI --> UI3[Chat Ollama]
    UI --> UI4[AI Studio]
    UI --> UI5[.....]
    C --> A
    UI --> A 
    O --> A(API JSON)
    A --> P(Python)
    A --> JS(Javascript)
    A --> PL(JSON/REST çağrısı yapabilen herhangi bir dil)

    style O fill:#f96
```
