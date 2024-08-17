Before we proceed, keep in mind that variables and datatypes are interrelated. So don't worry if you are not able to understand a particular topic in this section. Just keep on reading this section and proceed to the next section (Variables) and then come back here. That will allow you to understand everything written here.

# Data Types

Data Type specifies the type of data or a value that a variable can hold. Hence the name "Data Type". Some examples of datatypes are: String, Integer and Boolean

- # String

If you want the code to print a word or a sentence then you can not write it as `print(a big elephant)`
It will output an error message. Instead you have to write it as:

**CODE**
```python
print("There are 365 days in a year.")
```

**OUTPUT**
```
There are 365 days in a year.
```

Here the apostrophe symbol `"     "` represents a **string value** which is a **Data Type**.

Basically the code knows that you are writting a **string datatype** if you put the apostrophe symbole at the ends of your words/sentence. 

If you do not keep the apostrophe symbols then the code will not understand that you are trying to write a string value and will output an error.

Now, why do we need string? Well, if we ever want to write any alphanumeric values with symbols then we have to use the string datatype. As seen in the example above, we got an output `There are 365 days in a year.` which has an alphabet (both uppercase and lowercase), a number (356) and a symbol (dot).

- # Integer

To output an integer value, we have to use the **integer data type**. Though integers can even be written inside string datatype.

As we learned before that in order to write a string value, we need to put apostrophe symbol at the ends of the words/sentence for the code to understand but for outputing an integer datatype we don't need to specify it with any symbols.

An example to out an integer value with an **integer datatype**:

**CODE**
```python
print(5)
```

**OUTPUT**
```
5
```

Now, as we stated before that strings can accept any alphanumeric values with symbols, therefore it can even accept integers. For example:

**CODE**
```python
print("100000")
```

**OUTPUT**
```
100000
```

But the difference here is that the number 100000 is a string value and not an integer value (even tho the number is an integer). You can check the data type of any input here.

Now, why do we need an **integer datatype** as we have **string datatype** which can even store integers. 

It is because integer datatype can be used to do calculations which is not possible with a string datatype. For example:

**CODE**
```python
print(5+5)
```

**OUTPUT**
```
10
```

Whereas if we use a string datatype we get:

**CODE**
```python
print("5+5")
print("5"+"5")
```

**OUTPUT**
```
5+5
55
```
