```mermaid
classDiagram
    class Car {
        +Engine engine
    }
    class Engine {
        +String type
    }
    Car *-- Engine : composition
```
