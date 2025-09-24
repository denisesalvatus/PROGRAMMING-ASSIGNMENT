# PROGRAMMING ASSIGNMENT 1

# Python Programming Exercises

## Intended Learning Outcomes

1. Identify the basic codes and functions in Python programming.
2. Apply different codes and functions to create working Python programs.

---

## Activities and Explanations

### 1. **Alphabet Soup Problem**

#### Objective:

Create a function that accepts a string and returns a new string with its letters sorted in alphabetical order.

#### How It Works:

* Convert the string into a list of characters.
* Sort the list.
* Join it back into a string.

#### Output:

```
alphabet_soup("jhoram") ➝ ahjmor  
alphabet_soup("ascorbate") ➝ aabceorst
```

---

### 2. **Emoticon Problem**

#### Objective:

Create a function that replaces specific emotion words in a sentence with corresponding emoticons.

#### How It Works:

* Define a dictionary of word–emoticon pairs.
* Split the sentence into words.
* Replace any matching word using the dictionary.
* Join the words back into a full sentence.

#### 🔍 Emoticon Replacements:

| Word  | Emoticon |
| ----- | -------- |
| Smile | :)       |
| Grin  | :D       |
| Sad   | :((      |
| Mad   | >:(      |

#### ✅ Output:

```
You are making me :)
I am always >:(
You are making me :D
I am always :((
```

---

### 3. **Unpacking List Problem**

#### Objective:

Use Python's unpacking syntax to separate the **first**, **middle**, and **last** elements of a list.

#### How It Works:

* Use `first, *middle, last = list` to unpack.
* Print each part of the list.

#### ✅ Output:

```
First: 1  Middle: [2, 3, 4, 5]  Last: 6
```

---

## Summary

| Problem             | Concept Practiced            |
| ------------------- | ---------------------------- |
| Alphabet Soup       | String sorting, list methods |
| Emoticon Translator | Dictionary mapping, loop     |
| Unpacking List      | Tuple unpacking, f-strings   |

These exercises reinforce basic Python operations such as string manipulation, conditionals, list operations, and dictionary usage.

