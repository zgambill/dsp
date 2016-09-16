# Learn Python

Read Allen Downey's [Think Python](http://www.greenteapress.com/thinkpython/) for getting up to speed with Python 2.7 and computer science topics. It's completely available online, or you can buy a physical copy if you would like.

<a href="http://www.greenteapress.com/thinkpython/"><img src="img/think_python.png" style="width: 100px;" target="_blank"></a>

For quick and easy interactive practice with Python, many people enjoy [Codecademy's Python track](http://www.codecademy.com/en/tracks/python). There's also [Learn Python The Hard Way](http://learnpythonthehardway.org/book/) and [The Python Tutorial](https://docs.python.org/2/tutorial/).

---

###Q1. Lists &amp; Tuples

How are Python lists and tuples similar and different? Which will work as keys in dictionaries? Why?

Lists and tuples are both sets of data, but lists are mutable and tuples are immutable. Because dictionary keys must be immutable, tuples can be dictionary keys, while lists cannot.

---

###Q2. Lists &amp; Sets

How are Python lists and sets similar and different? Give examples of using both. How does performance compare between lists and sets for finding an element. Why?

Lists and sets are almost identical, except for lists being ordered, while sets are unordered. With that said, hash functions

---

###Q3. Lambda Function

Describe Python's `lambda`. What is it, and what is it used for? Give at least one example, including an example of using a `lambda` in the `key` argument to `sorted`.

Lambda is used to make anonymous functions. Rather than defining a whole new function and calling that, lambda can easily be integrated into code. As far as I have seen, it is mostly useful for one-time functions that don't have to be called many times, where the function code fits fairly well on a single line. Lambda can also greatly benefit code readability, as the function is defined right there in the code, and if there are a variety of single-use functions, it's much easier to read the function integrated into the code right there rather than having to go find where it was defined, figure out what's happening, and then go back to reading.

"Siblings" is a series of tuples representing myself and my 3 siblings, and the sorted command will be sorting by the second index, which is our age. I could have also defined `siblings` as a new object class with self.age and sorted by calling that rather than an index.
```
siblings = [
('Tyler', 27)
('Sam', 13)
('Mollie', 25)
('Zach', 19)
]

sorted(siblings, key=lambda siblings: siblings[1])
```


---

###Q4. List Comprehension, Map &amp; Filter

Explain list comprehensions. Give examples and show equivalents with `map` and `filter`. How do their capabilities compare? Also demonstrate set comprehensions and dictionary comprehensions.

List comprehensions are ways to create expanded lists without writing everything out yourself. A great way to explain this is with a numerical list of some sort, perhaps within a given range. If you're creating a list of even numbers in `range(500)`, it's much easier to type `list = [x for x in range(500) if x % 2 == 0]` than to type out every even number between 0 and 500. List comprehensions are not solely for numbers-based lists, though, and can be used for all sorts of other applications.

The map function is similar to list comprehensions, as it also allows for an expression to be evaluated to create a larger list. The map function, `map(function, iterable_object)`, is similar to using a `for` loop in that it takes a function and a sequence/some iterable object, and puts each item in the sequence through the provided function, ultimately returning a list. A very basic example of this could be to take a predefined function, `def sqr(x) = return x**2`, and an iterable object such as a list, `list = range(50)`, where you could then use `map(sqr, list)` to return a list of all the numbers in `range(50)` squared. Plus, writing `map(sqr, list)` is much cleaner and simpler than writing an entire `for` loop. 

The filter function has nearly identical syntax to map, `filter(function, iterable_object)`, but, as the name suggests, filters through the list and returns only values in the iterable that make the function true. A simple example of this could be to define an `if` function called "evens" that returns True `if x % 2 == 0` and `else: return False`. With that function, we could take any list of integers and return a list of even numbers by using `filter(evens, list)`. 


---

###Complete the following problems by editing the files below:

###Q5. Datetime
Use Python to compute days between start and stop date.   
a.  

```
date_start = '01-02-2013'    
date_stop = '07-28-2015'
```

>> REPLACE THIS TEXT WITH YOUR RESPONSE (answer will be in number of days)

b.  
```
date_start = '12312013'  
date_stop = '05282015'  
```

>> REPLACE THIS TEXT WITH YOUR RESPONSE (answer will be in number of days)

c.  
```
date_start = '15-Jan-1994'      
date_stop = '14-Jul-2015'  
```

>> REPLACE THIS TEXT WITH YOUR RESPONSE  (answer will be in number of days)

Place code in this file: [q5_datetime.py](python/q5_datetime.py)

---

###Q6. Strings
Edit the 7 functions in [q6_strings.py](python/q6_strings.py)

---

###Q7. Lists
Edit the 5 functions in [q7_lists.py](python/q7_lists.py)

---

###Q8. Parsing
Edit the 3 functions in [q8_parsing.py](python/q8_parsing.py)





