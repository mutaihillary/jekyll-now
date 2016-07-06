## Introduction
Accessors (also known as getters and setters) are methods that let you read and write the value of an instance variable of an object.Its used to control changes to a variable. They are also widely known as setter methods. Often a setter is accompanied by a getter (also known as an accessor), which returns the value of the private member variable.

## Setter and Getter Methods   

### Getter
Accessor method for getting the current value of the selected fields.
### Setter
Mutator method for setting specified values to the selected fields.
### Getter and Setter

Both methods for the selected fields.

## Why Accessors?
There are actually many good reasons to consider using accessors rather than directly exposing fields of a class

Getter and Setter make API more stable. For instance, consider a field public in a class which is accessed by other classes. Now later on, you want to add any extra logic while getting and setting the variable. This will impact the existing client that uses the API. So any changes to this public field will require change to each class that refers it. On the contrary, with accessor methods, one can easily add some logic like cache some data, lazily initialize it later. Moreover, one can fire a property changed event if the new value is different from the previous value. All this will be seamless to the class that gets value using accessor method.

## Example 

Consider the following code:

public class MyClass {
    int aInteger;
}
    
public class Cat {
    private var name:*;
}


After generating the getter and setter the following code will be produced:

public class MyClass {
    int aInteger;
 public int getAInteger() {
     return aInteger;
 }
 public void setAInteger (int myAIntegerParam) {
     aInteger = myAIntegerParam;
 }
}
    
public 
      class  Cat {
    private  var _name:*;


    public 
      function 
      get  name():* {
        return  _name;
    }

    public 
      function 
      set  name(value:*):void  {
        _name = value;
    }
}


