```mermaid
classDiagram
    class Printer {
        +void print(Document doc)
    }
    class Document {
        +String getContent()
    }
    Printer ..> Document : dependency
```
