# SingletonClass

# Eager and Lazy initialization

###### Eager initialization is when the object is already created. When the client requests for an object, we can return the object directly.

###### Lazy initialization is when the object is NOT there, but when the client requests for an object, the server creates an object and then we can return the object.


## Blocks

class Test{

  Variables
  
    - local variables
    
    - instance variables
    
    - static variables
    

  Methods
  
    - instance methods
    
    - static methods
    

  Constructors
  
    - default constructor
    
    - user defined construtor
    

  Blocks
  
    - instance blocks
    
    - static blocks
    
}

・ In a class we have variables, methods, constructors and blocks. There are 3 types of variables which are local variables, static variables and instance variables. We also have methods. There are 2 types of methods which are instance methods and static methods. We also have constructors. There are 2 types of constructors which are default constructor and user defined constructor. Last but not least we have blocks. There are 2 types of blocks which are instance blocks and static blocks.


Blocks are '{}'.

{
}   is called an instance blocks.

Instance blocks are executed when the object is created. Constructors are also executed when the object is created too. But instance blocks are executed first.


##### Constructor logics are specific to an object but instance object logics are common to all objects. Whenever the object is created, blocks will always be executed first.

static 

{
} is called a static block.

Static blocks are executed when the '.class' file is loaded, once.

##### Static blocks are executed once, and they are executed first.


#### When to use static and instance blocks

▹ If you want to execute the data once, you can go for the static blocks.

▹ If you want to execute the data whenever the object is created, you can use the instance blocks.
