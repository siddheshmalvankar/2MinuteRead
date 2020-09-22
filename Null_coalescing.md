### Null-coalescing assignment
**C# 8.0** introduces the null-coalescing assignment operator **??=**. 
You can use the **??=** operator to assign the value of its right-hand operand to its left-hand operand only if the left-hand operand evaluates to null.

##### Example : 2 calls made to the function 'Print' displays the use of **??=**

![alt text](/resources/3_Null-coalescing.png "Null-coalescing") 

##### Advantage
* Clean coding style.
* Limit the use of ** if ** blocks.
* Avoid getting runtime InvalidOperationException exception.
* Define default value for null conditions.
