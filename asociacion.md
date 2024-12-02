```java
class Student {
    String name;
    Teacher teacher; // Asociación con la clase Teacher

    void displayTecherInfo() {
        System.out.println("Assigned Teacher: " + teacher.name);
    }
}

class Teacher {
    String name;
}
```
```mermaid
classDiagram
    class Student {
        +String name
    }
    class Teacher {
        +String name
    }
    Student --> Teacher : association
```

