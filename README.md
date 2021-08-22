## Java core
- What is platform independence
- Why is Java so popular
  - Object oriented
  - Platform independence
- Why string is immutable
- How ArrayList works internally
- How HashMap works internally
- How get method of HashMap works internally
- Why the key of HashMap must be immutable
- How many exception types are there in Java
- Difference between fail fast/fail safe collections
- Difference between List and Set
  - List
    - Contains duplicate values
    - Elements are continuos (maintains insertion order)
    - Using ArrayList, LinkedList, Vector...
    - Example
    ```
    List<Integer> numbers = new ArrayList<>(2);
    numbers.add(1);
    numbers.add(2);
    numbers.add(3); // What will happen
    ```
    How to improve performance for below code
    ```
    List<Integer> numbers = new ArrayList<>();
    for(int i = 0; i < 10_000_000) {
      numbers.add(1);
    }
    ```
    
  - Set
    - Not contain duplicate values
    - Elements are not continuos (not maintains insertion order)
    - Using HashSet, LinkedHashSet...
- Difference between String, String Builder, and String Buffer
- Difference between HashSet and TreeSet

## OOP
- Why we need constructor inside an abstract class
- What is meant by Method Overriding
- What is meant by Overloading

## Java 8
- What is functional interface
- Example
```
List<Integer> numbers = Arrays.asList(1, 2, 3, 4, 5);
  numbers
      .stream()
      .filter(number -> {
          System.out.println(number);
          return true;
      })
  ```
