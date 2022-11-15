---
title: "Exercise: Javascript Types" 
--- 

# Types

Look at the following code, then figure out the type of each `foo`.

```java
// Java
String foo1 = "Hello";
void foo2(int bar){
    System.out.println("Goodbye.");
}
int[] foo3 = new int[] {1,2,3,4,5};
```

Any example function calls will help with figuring out the type of each function!

```python
# Python
foo4 = [1, 2, 3, 4, 5, 'hi']
foo5 = {'bar': 'baz', 2: 3}
def foo6(bar):
    return bar + 1
# foo6(3) >>> 4
```

```javascript
// Javascript
var foo7 = [1, 2, 3, 4, 5, 'hi']
var foo8 = {'bar': 'baz', 2: 3}
var foo9 = x => x + 5
// foo9("hello") >>> "hello5"
// foo9(4) >>> 9
function foo10(x){
    return function(y){
        return x + y
    }
}
//foo10(3)(5) >>> 8
//foo10("hello")("world") >>> "helloworld"
```

## Type coercion

What is the result of this code?

```java
    // Java
    1. 0 == false;
    2. 
        String foo = "bar"; 
        foo = 1;
```

```python
    # Python
    1. 0 == False 
    2. 
        foo = "bar"
        foo = 1
    3.
```

```javascript
    // Javascript
    1. 0 == false // is there another operator we can use to return another result? 
    2. 
        var foo = "bar"
        foo = 1 

```
