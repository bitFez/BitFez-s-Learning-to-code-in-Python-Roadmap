# 2 - Printing & Escape codes

# Datatypes

When we output text using the `print()` function, we are displaying what is known as a string. We use different types of name for different types of data.

| Text | String |
| --- | --- |
| A whole number | Integer |
| A number with decimals | Float |

A string can contain alphanumeric, numeric and also symbol characters. The only rule is that they must be placed inside a set of quotes `" "`.

<aside>
π‘ So another rule you need to learn is that quotes can be in the form of double quotes `" "`
or they can be in the form of single quotes `' '` . These are basically just a set of apostrophe.

</aside>

for example:

[https://replit.com/@bitFez/ex1#main.py](https://replit.com/@bitFez/ex1#main.py)

What if I wanted to use an apostrophe or a quote in my string?

For example what if I wrote `print('I'm Groot')`?

Python would think that the string would start at the first apostrophe and end at the second. It would cause an error because it would not be sure about what the remainder of the text was.

[https://replit.com/@bitFez/ex2#main.py](https://replit.com/@bitFez/ex2#main.py)

We can get around this in 2 ways:

## 1. Mixing and matching Quotes (not Recommended)

The first method is that you can use double quotes for the above example where a apostrophe is used in the sentence. 

```python
print("I'm Groot")
```

## 2. Using Escape codes

A useful feature in python is using escape codes. They can be used to ignore a single or a double quote as well as a few other features (which you will explore soon).

The problem above can be solved like this:

```python
print('I\'m Groot')
```

Similarly, If I had a statement with quotes in the string such:

```python
print("She said, \"she loves you\", and you know that can be bad")
```

## Practice

<aside>
π‘ Donβt think about skipping this part. This is tedious but you need to practice to get good and build muscle memory. Do each exercise below, typing each one out diligently π

</aside>

output the following:

- [ ]  Using single quotes β βBobβs Burgersβ
- [ ]  Using single quotes β βBe sure to like and subscribe to BitFezβs YouTube channel, βCodeFezββ
- [ ]  Using double quotes β βBitFezβs most commonly used phrase in class is β<insert here>β, which just demonstrates how much of a humble person he isβ
- [ ]  Using double quotes β βBitFez is also commonly head criticising those that make a βRookie <insert here>β, although he is often referring to himselfβ

## Now find out what the following do and make note of them.

- [ ]  `\n`
- [ ]  `\tab`

## More tasks

- [ ]  Read [https://learnpythonthehardway.org/book/ex6.html](https://learnpythonthehardway.org/book/ex6.html)
