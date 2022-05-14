BRIEF

Create a morse code translator using OOP in Javascript. Design mobile first.

ABOUT MORSE CODE TRANSLATION
Each English alphabet letter has a morse code equivalent in the form of dots & slashes, these are combined to make words.

BREAKING IT DOWN

- An input box for user to enter their text
- Output box to display translation
- Button to activate the translate OR show translation as type

APPROACH

1. Have an initial object of each alpahbet letter and their translation.
2. User enters value via input box, store this and convert to an array of letters using split method.
3. Map over object to find the matching key (passed in as parameter) and return the value (translatied letter)
4. Join results and show to user by changing the value of the input box.
5. Morse to English was different as user needs to separate characters.
