# AveriJ_Prework.md
Response to questions in BE-prework

### What command is entered into the command line to enter an 'irb' session?
Simply type "irb"

### What is the expression used to express a number squared?
2 ** 3 = 8

### What is the ruby command used to output something to the terminal?
puts

### How is a ruby file run from the command line?
ruby filename.rb

### If a # is at the beginning of a ruby line in Atom, what does that indicate?
Its a comment for fellow coders and for ruby to ignore

### What will "turing".length return?
6


## VARIABLES
### How do you create a variable?
Name it whatever you want it to be and set it equal to something

### What did you learn about the rules for naming variables?
Cannot start with numbers and no dashes (bad-- last-name) (good-- last_name)

### How do you change the value of a variable?
Just rename shouting = "Hey you!". Later in the code shouting = "Bitch plz!"


## DATATYPES
### How can you find out the class of a variable?
[1, 2, 3].class and I would get array. 

### What are two string methods?
.length

.reverse

### How can you change an integer to a string?
.to_s


## STRINGS
### Why might you use double quotes instead of single quotes in Ruby?
String interpolation

### What is this used for in Ruby: #{}?
It lets you embed a Ruby statement in another string and only works with double quotes

### How would you remove all the vowels from a string?
.delete('aeiou')


## INPUT & OUTPUT
### What do 'print' and 'puts' do in Ruby?
Puts---prints info to the user and has a return value of nil
Print---does the same thing but doesn't make a new line

### What does 'gets' do in Ruby?
Waits for the user to type something and hit enter


## NUMERICS AND ARITHMETIC
### What is the difference between integers and floats?
Floats are decimals--5.0
Integers are whole numbers--5

### What is the ruby command to find 2 to the 2nd power?
2 ** 2

## Booleans
### What do each of the following symbols mean?
==  equals

>=  greater than or equal to 

<=  less than or = to

!=  not equal to 

&&  and 

||  or

### What are two Ruby methods that return booleans?
true and false

## Conditionals
### What is flow control?
if, else, elsif and end. Allowing our program to make decisions for us based on the values in the program.

### What will the following code return? apple_count = 4
### if apple_count > 5
### puts "Lots of apples!"
### else
### puts 'Not many apples...'
### end
Not many apples...

### What is an infinite loop, and how can you get out of one?
A piece of code that lacks an exit and so it repeats indefinitely. Ctrl + c

## Nil
### What is nil?
It means nothing, a variable hasn't been assigned anything yet.

## Symbols
### How can symbols be beneficial in Ruby?
Uses less memory

### Does naming symbols use the same rules for naming variables?
Symbols are constant(letters, numbers) so they can't be assgned a value.

## Arrays
### What method can you call to find out how many elements are in an array?
.length

### What is the index of pizza in this array: ["pizza", "ice cream", "cauliflower"]?
Zero

### What do 'push' and 'pop' do?
Push adds to the array at the end.
Pop deletes from the array, starting at the end

## Hashes
### Describe some differences between arrays and hashes.
Hashes store pairs of items associating keys with values.
Array store an ordered list of items.

### What is a case when you might prefer an array? What is a case when you might prefer a hash?
Arrays--when I want to store peoples birthdays or who has senority at work based on how long they've been there.

Hashes--when I want to group large amounts of info
