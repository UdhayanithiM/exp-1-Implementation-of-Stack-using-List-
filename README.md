# Ex.No: 1.1  Implementation of Stack using List 
### DATE: 10.04.2025                                                                          
### REGISTER NUMBER : 212222220054  

### AIM:  
To write a Python program to implement Stack using list with its built-in methods `append()` and `pop()`.

### Algorithm:  
1. Start the program.  
2. Create an empty list to act as the stack.  
3. Prompt the user to input five items.  
4. Use the `append()` method to push each item into the stack.  
5. Display the stack before popping.  
6. Use the `pop()` method to remove the top two elements from the stack.  
7. Display the stack after popping.  
8. Stop the program.  

### Program:
```python
def stack_operations():
    stack = []

    # Getting 5 elements from user
    print("Enter five items to push into the stack:")
    for i in range(5):
        item = input(f"Item {i+1}: ")
        stack.append(item)

    # Stack before pop
    print("\nStack before elements are popped:")
    print(stack)

    # Popping two elements
    popped1 = stack.pop()
    popped2 = stack.pop()
    print(f"\nPopped elements: {popped1}, {popped2}")

    # Stack after pop
    print("\nStack after elements are popped:")
    print(stack)

# Driver code
stack_operations()

# Output:

![image](https://github.com/user-attachments/assets/cf1b1027-b243-4359-9dd8-11c8e31ccb3c)




### Result:
Thus the breadth first search order was found sucessfully.""""'take an example give this format



