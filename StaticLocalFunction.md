### Static local function
Local functions **(C# 7.0)** are private methods of a type that are nested in another member. They can only be called from their containing member. 
Wheareas Static local function **(C# 8.0)** ensures it does not reference any variable from the enclosing or surrounding scope.
If static local function tries to access the variable from the enclosed scope, then the compiler will throw an error. 
( *CS8421 - A static local function can't contain a reference to <variable>.*).

##### Example 1: Local function Vs Static local function

![alt text](/resources/2_StaticLocalFunction_1.png "Static ocal Function throws compilation error") 

##### Example 2: Static local function

![alt text](/resources/2_StaticLocalFunction_2.png "Static local function without error") 
