# Map reduce

- Google wanted to somehow improve the computation time of costly computations that they had to do - like web indexing / link analyzer etc.
- They were looking for a framework so that non-specialists to be able to write and run giant distributed computations
- The application programmer just had to write a simple map function or a simple reduce function and the MapReduce Framework would just take care of everything else.
- ```
  Input1 -> Map 
  Input 2 -> Map 
  Input 3 -> Map
  ```
- Input is a file and the map function outputs Key value pairs.
- Examples :
  - Map(k,v)
    - split v into words for each word w emit ( w, "1")
  - Reduce(k,v)
    - has it's on emit function
    - emit(len(v))
