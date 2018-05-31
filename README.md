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
(1, 2, 3).class and I would get array. Don't know how to put brackets so used parenthesis

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
