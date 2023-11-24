# Boxing and Unboxing In C#
## Boxing
- It is the process of converting a value type instance to an object reference.
- CLR creates an object in a heap and creates a reference in a stack that points to that object.<br>
example <br>
int number = 10;<br>
Object obj = number; // here value 10 get boxed by the CLR and stored in a heap.<br>

## Unboxing
- Getting back the value from heap to stack.<br>
Object obj = 10;<br>
int number = (int)obj; //Here we get a new variable called number and value 10 in a stack.

### With using Boxing/Unboxing we have some performance penalty.
- For Example when you declare an arrayList in a code it will take object type as argument.
- so when you assign an int to it boxing will happen as int is gonna be assigned to object type. 
- With String it is not gonna happen. 
- With Value type boxing is gonna happen and vice versa when we are getting those values and try to cast it unboxing will happen so we have some performance penalty while using arrayList so Remember when you are using a method that expect object as a argument you have to think about boxing/unboxing performance penalty.

