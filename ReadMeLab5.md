**Lab 5 Questions**

  

1.  Why does LinkedStack not require an explicit constructor?

  

- This is because Java will provide us with a default constructor implicitly, thus there is no need to create a constructor.

  

2.  What is the time and (extra) space complexity of each of the LinkedStack methods, as well as ReverseLines.main?

  

- Both the time and space complexity of push, pop, peek, and isEmpty methods are T(n) = S(n) = O(1). Time complexity of asList is T(n) = O(n) and Space complexity is S(n) = O(1).

  

  

3.  How else (not using Node) could we have implemented LinkedStack in such a way that it is still based on a linked list but the asList method uses constant time and space?

  

- I would use an ArrayList as the container in order to have O(1).

  

4. Is it better for push and pop to return the item or the stack itself? Briefly discuss the pros and cons of each design.

  

- Pushing the stack method will probably not require immediate usage of the object value. So in this case reference to the stack is of more use than the value. While the pop method is probably followed by the usage of popped object so returned item value is more usable than reference to stack.
