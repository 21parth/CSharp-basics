# Types in c#
- There are two types in c#. 
    - Value types
    - Reference types
## Value types
- Stored in a stack.
    - What is Stack? 
        - When your program is being executed a limited amount of memory is given to each thread. All value types are stored there and they have a short   lifetime  so as soon as they are out of the scope they are kicked off by runtime.

## Reference types
- Stored in a heap ( larger amount of memory).
- We store objects in a heap which require a longer lifetime.
- Basically all classes Object, Array, String etc.