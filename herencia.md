
```mermaid
classDiagram
    class Animal {
        +String name
        +void makeSound()
    }
    class Dog {
        +void makeSound()
    }
    Animal <|-- Dog : inheritance
```
