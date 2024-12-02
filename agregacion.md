```java
class Classroom {
    String roomNumber;
    List<Student> students; // Agregación con la clase Student
}

class Student {
    String name;
}
```
```mermaid
classDiagram
    class Classroom {
        +String roomNumber
        +List~Student~ students
    }
    class Student {
        +String name
    }
    Classroom o-- Student : aggregation
```
