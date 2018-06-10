# AveriJ_Prework.md
Response to questions in BE-prework

# Day 2
#### What command is entered into the command line to enter an 'irb' session?
``` irb ```

#### What is the expression used to express a number squared?
``` 2 ** 3 = 8 ```

#### What is the ruby command used to output something to the terminal?
``` puts ```

#### How is a ruby file run from the command line?
``` ruby filename.rb ```

#### If a # is at the beginning of a ruby line in Atom, what does that indicate?
``` Its a comment for fellow coders and for ruby to ignore ```

#### What will "turing".length return?
``` 6 ```

# Day 3
### POMODORO BREAK
The Pomodoro Break is a time management technique developed by Francesco Cirillo in the mid 1980's. He used a timer (shaped like a tomato, hence the name pomodoro) to break down his work into 25 minute intervals. These intervals are called pomodoro and were separated by 3-5 minute breaks. After 4 pomodoro's, you're suppose to take a 15-30 minute break and then start over.

Personally, I like to work for 90 minutes with a 10-15 minute break. During the break I like to take a walk outside to get some fresh air and a bit of nature.


## VARIABLES            

#### How do you create a variable?
``` Name it whatever you want and set it equal to something ```

#### What did you learn about the rules for naming variables?
``` Cannot start with numbers and no dashes (bad-- last-name) (good-- last_name) ```

#### How do you change the value of a variable?
``` Name it anything you want: ```
``` shouting = "Hey you!" ```
    
``` Later in the code, you can rename it: ```
``` shouting = "Bitch plz!" ```


## DATATYPES

#### How can you find out the class of a variable?
``` [1, 2, 3].class and I would get array. ```

#### What are two string methods?
```.length ```

``` .reverse ```

#### How can you change an integer to a string?
``` .to_s ```


## STRINGS

#### Why might you use double quotes instead of single quotes in Ruby?
``` String interpolation ```

#### What is this used for in Ruby: #{}?
``` It lets you embed a Ruby statement in another string and only works with double quotes ```

#### How would you remove all the vowels from a string?
``` .delete('aeiou') ```


## INPUT & OUTPUT

#### What do 'print' and 'puts' do in Ruby?
``` Puts---prints info to the user and has a return value of nil ```

``` Print---does the same thing but doesn't make a new line ```

#### What does 'gets' do in Ruby?
``` Waits for the user to type something and hit enter ```

# Day 4
## NUMERICS AND ARITHMETIC

#### What is the difference between integers and floats?
``` Floats are decimals--5.0 ```

``` Integers are whole numbers--5 ```

#### What is the ruby command to find 2 to the 2nd power?
``` 2 ** 2 ```

## BOOLEANS

#### What do each of the following symbols mean?
``` ==  equals ```

``` >=  greater than or equal to ```

``` <=  less than or = to ```

``` !=  not equal to ```

``` &&  and ```

``` ||  or ```

#### What are two Ruby methods that return booleans?
``` True and False ```


## CONDITIONALS
#### What is flow control?
``` If, else, elsif and end. ```

``` Allowing our program to make decisions for us based on the values in the program. ```

#### What will the following code return? 

##### apple_count = 4
##### if apple_count > 5
##### puts "Lots of apples!"
##### else
##### puts 'Not many apples...'
##### end

``` Not many apples... ```

#### What is an infinite loop, and how can you get out of one?
``` A piece of code that lacks an exit and so it repeats indefinitely. ```

``` Ctrl + c ```


## NIL
#### What is nil?
``` It means nothing, a variable hasn't been assigned anything yet. ```

## SYMBOLS
#### How can symbols be beneficial in Ruby?
``` Uses less memory ```

#### Does naming symbols use the same rules for naming variables?
``` Symbols are constant(letters, numbers) so they can't be assgned a value. ```

## ARRAYS
#### What method can you call to find out how many elements are in an array?
``` .length ```

#### What is the index of pizza in this array: ["pizza", "ice cream", "cauliflower"]?
``` Zero ```

#### What do 'push' and 'pop' do?
``` Push adds to the array at the end. ```

``` Pop deletes from the array, starting at the end ```

## HASHES
#### Describe some differences between arrays and hashes.
``` Hashes store pairs of items associating keys with values. ```

``` Array store an ordered list of items. ```

#### What is a case when you might prefer an array? What is a case when you might prefer a hash?
``` Arrays--when I want to store peoples birthdays or who has senority at work based on how long they've been there. ```

``` Hashes--when I want to group large amounts of info ```

# Day 5 
## ATOM AND TERMINAL
#### Regarding the string, “Turing”. What ruby command would we use to get:
* The “T” from “Turing”.

``` "Turing"[0] ```

* The length of “Turing”.

``` "Turing".length ```

* Make the whole string capital letters.

``` "Turing".upcase ```

* Delete the “n” from “Turing”.

``` "Turing".delete('n') ```

* Assign “Turing” to a variable.

``` best_school = "Turing" ```

#### What does gets do?
``` Waits for the user to type something and hit enter ```

#### What is the difference between the input without the .chomp and the input with the .chomp?
``` Input without .chomp you get the newline character at the end ```

``` gets -- Averi\n ```

``` Input with .chomps you dont ```

``` gets.chomp -- Averi ```

#### What does fav_num.to_i do?
``` Changes your favorite number into an interger if it isn't already. ```

#### What does animals.length return?
``` 4 ```

#### What does animals[0] return?
``` Dog ```

#### What does animals.empty? return?
``` False ```

#### What are two different ruby commands that add to the animals?
``` .push() ```

``` << ```

#### What ruby command is used to remove the last element from the array?
``` .pop ```

# Day 7
## CODE FOR GAME
#### Were you able to get through the work? Did you rush to finish, or take your time?
``` I was able to take my time because I started 4 weeks before. ```

#### What do you feel most confident about?
``` I understand strings, arrays, booleans, datatypes and numeric & arithmetic. ```

#### What do you feel least confident about?
``` Writing and understanding code. ```

#### What are you most looking forward to learning more about?
``` Writing and understanding code. ```

#### What topics would you most like to see reinforced by instructors?
``` Writing and understanding code, how to use atom and all the handy-dandy shortcuts (mac/atom). ```

#### What is most confusing to you about what you've learned?
``` Everything makes sense except for writing and understanding code. ```

#### What questions do you have for your student mentor or for your instructors?
``` Whats the best way to learn to write and understand code? ```
``` Whats the best way to study? ```
``` Any tips for single parents entering the program? ```

#### What do you feel was most successful in your game?
``` That it worked and I did it all by myself. When I got stuck I researched it on the internet and when that didn't work I reached out for help. ```

#### What was the most challenging part about creating the game?
``` Figuring out how to add a "cheat" and "hint" capability. ```

#### When you reached a challenging part of the game, how did you move forward?
``` I looked on line and then asked for help from our pre-work guides. ```
