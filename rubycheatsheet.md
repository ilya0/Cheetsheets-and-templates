# Ruby Cheatsheet

How do you define variables, instances, constants?

Variables - variable whose name begins with a lowercase letter (a-z) or underscore (_) is a local variable or method invocation.
```
array1 = []
variable =

```

Instances - A variable whose name begins with '@' is an instance variable of self. An instance variable belongs to the object itself. Uninitialized instance variables have a value of nil.
```
def initialize(name)
@name = name
end

```

Constants - A variable whose name begins with '$' has a global scope; meaning it can be accessed from anywhere within the program during runtime.

CONSTANTVAR = []


def initialize
end


## How do you write conditionals?

```
if heroic = true
   go_crazy
end  

```
How do you write arrays, hashes and blocks?

* arrays = []
* hashes = {}
* blocks = 

```
(1...3).each do |i|
   a = 2*i
   puts a
end
```
How do you get values from an array?

* arr[index]

How do you put values into an array?

*arr.push()

How do you get values from a hash?

* hash


How do you get values from an array?

```
a = [1,2,3,4,5]
a.include?(3)   # => true
a.include?(9)   # => false
```

a.pop


How do you put values into an array?
a = [1,2,3,4,5]
a.push(3)   # => true




How do you get values from a hash?
How do you add key-values to a hash?
How do you get values from a hash that is inside an array?
How do you get values from an array that is a value in a hash?
How do you loop through an array?
How do you loop through a hash?
How do you create a block?
How do you create a class?
How do you create methods in a class?
How do initialize constants in a class?

def initialize 
@constant1 = 1
@constant2 = 2
end

How do you add setters and getters in a class?


How do you create an object from a class?


