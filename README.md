# PROGRAMMING-ASSIGNMENT
PROGRAMMING ASSIGNMENT #1
ALPHABET SOUP PROBLEM

def alphabet_soup(jhoram):
    return'' .join(sorted(jhoram))
print(alphabet_soup("jhoram"))

def alphabet_soup(ascorbate):
    letters = list(ascorbate)
    letters.sort()
    return ''.join(letters)
print(alphabet_soup("ascorbate"))

Explanation: 
For the fisrt code I the sorted function which splits the string into character and sorts them aphabetically. For the second code I used the function list wherein it turns the string into a list of characters then letters.sort to set them in plce. Both codes uses .join to combine back into a string.

EMOTICON PROBLEM

def emotify(sentence):
    replacements = {
        "smile":":)",
        "grin":":D",
        "sad":":((",
        "mad":">:("
    }
    words = sentence.split()
    result = [replacements.get(word.lower(), word) for word in words]
    return ' '.join(result)

print(emotify("You are making me smile"))
print(emotify("I am always mad"))
print(emotify("You are making me grin"))
print(emotify("I am always sad"))

Explanation:
This program aims to replace certain words with emoticons. I used replacement dictionary to map the specific words to change it with emoticons. Then I used .split to break the sentence into words. Lastly, I used .join so that it joins the modified list of words back into sentence.

UNPACKING LIST PROBLEM
lst=[1,2,3,4,5,6]
first, *middle, last = lst
print(f"First: {first}  Middle: {middle}  Last: {last}")

Explanation:
This program aims to extract the first and last items then put everything else on the middle. For this code i used the extended unpacking then print it in one line.
