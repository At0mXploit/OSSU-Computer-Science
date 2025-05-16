# Strings

- Concatenate `a+b` 
- `len()` retrieve length of character.
- Slicing: `s=abc` then `s[0]` gives `a`. Index starts with 0.
- `s[-1]` gives us `c` its just opposites direction.

## Slicing to get a SubString

- Syntax `[start:stop:stop]`
- Get characters at start up to and including stop-1 taking every step characters.
- +ve means go left to right.
- -ve means go right to left.
- Examples:

`a= abcdefgh`
`s[3:6]` evaluate to `def` same as `s[3:6:1]`
`s[:]` evaluates to `abcdefgh`, same as `[0:len(s):1]`
`s[::-1]` evaluates to `hgfedcba`
`s[4:1:-2]` evaluates to `ec`

## Immutable Strings

- Strings that cannot be modified.
- Variable name can only bound to only one object

# Input/Output

## Print

```python
a = "the"
b = 3
c = "musketters"

print(a + str(b) + c)
```

- Need to change type whenever printing diff data type.

## Input

```python
text = input("Type anything: ")
print(5*text)
```

- Input always return an `str` must case if working with numbers.

```python
number = int(input("Type anything: "))
print(5*number)
```

```python
question = input("Type anything: ")
print('I can', question, 'better than you')
print((question+' ')*5)
```


## Netwon's Raphson Method

- Find roots of polynomial
- Eg: find `g` such that $f(g,x)=g^3-x=0$
- Algorithm uses a successive approximation
- `next_guess` = guess - $f(guess)/f'(guess)$
- Where `f'` is derivative of `f`

```python
# Newton Rhapson for cube root
x = int(input("What x to find cube root of?"))
g = int(input("What is your guess?"))
print("Current esmiate cubed =", g**3)

next_g = g - ((g**3 - x) / (3*g**2))
print("Next Guess to try =", next_g)
```


## Fstrings

- The `f` before the string lets you insert variables directly using `{}` — it's short for **formatted string**.
- So we can do this instead of always casting types.

```python
name = "Alice"
print(f"Hello, {name}!")
```


# Branching

- `variable` = `value` - Change stored value of variable to value.
- `some_expression` == `other_expression` - A test for equality shows in boolean.

```python
if <condition>:
   <operation>
elif <condition>:
   <operation>
else:
   <operation>
<rest of program>
```

- **Indentation** matters in python meaning space blocks arrangement matters.

---
