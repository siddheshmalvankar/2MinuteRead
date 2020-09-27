### Evolution of Pattern Matching in C# 8.0
C# 8.0 Essentially have three new ways to express a pattern, all of which have a specific use case. They are:


* Property pattern
* Tuple pattern
* Positional pattern

##### Example : The property pattern enables you to match on properties of the object examined.  
Consider an eCommerce site that must compute final price of Mobile product based on the selected colour. 
The following method uses the property pattern to compute the final amount from the primarycolor and the price:

![alt text](/resources/5_PropertyPattern.png "Null-coalescing") 
