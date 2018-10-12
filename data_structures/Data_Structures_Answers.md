Add your answers to the questions below.

1. What is the runtime complexity of your `depth_first_for_each` method?

2. What is the space complexity of your `depth_first_for_each` function?

3. What is the runtime complexity of your `breadth_first_for_each` method?

4. What is the space complexity of your `breadth_first_for_each` method?

5. What is the runtime complexity of your `heapsort` function?

6. What is the space complexity of the `heapsort` function? Recall that your implementation should return a new array with the sorted data. What would be the space complexity if your function instead altered the input array?

#### Answers

1. The runtime complexity of my implementation of `dfs` would be O(n), since we have to traverse all nodes

2. The space complexity of my implementation of `dfs` would be O(n), since we're using a stack to keep track of the next nodes

3. The runtime complexity of my implementation of `bfs` would be O(n), same reason as 1

4. The space complexity of my implementation of `bfs` would be O(n), same reason as 2 but using a queue

5. The runtime complexity of my implementation of `heapsort` would be O(n log n), because we iterate through each item of the array, and then perform a log n insert operation. We do this two times, but we ignore the 2.

6. Space complexity would be O(n), if we did the heapsort in place, the space complexity would be O(1). However, it would really depend on our implementation, and we have the luxury of using our heap class, which would cost O(n) space.