# Boxing and Unboxing In C#
## Boxing
- It is the process of converting a value type instance to an object reference.
- CLR creates an object in a heap and creates a reference in a stack that points to that object.<br>
example <br>
int number = 10;<br>
Object obj = number; // here value 10 get boxed by the CLR and stored in a heap.<br>