### Evolution of Pattern Matching in C# 8.0
**C# 8.0** brings **Switch expressions** that enables you to use more concise expression syntax. There are fewer repetitive case and break keywords, and fewer curly braces.


##### Swich Expression instead of Switch Statement
As shown here is a simple example of Calculate function which accepts 2 values and an operator. 'operation' variable determines the type of operation to be performed and return the end result.
![alt text](/resources/4_SwitchExpression.png "Switch Expression") 

##### Key Highlights
* Different order of the **swtich** keyword which is visually easily to distinguish.
* The case and : elements are replaced with =>. It's more concise and intuitive.
* The default case is replaced with a _ discard.
* The bodies are expressions, not statements.
