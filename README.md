# Learn_Python
You are a teacher and playing with "word guessing game" with students. You choose six words relating to recent conversational themes and write sets of clues to help students. Student get 3 chances to guess the three letters word given below
Create a word set=["cat", "hat", "pop", "sea", "row", "cup"] like and take user input display like "Let's play a word guessing game . The word has 3 letters in it. You get 3 guesses. Guess a letter " if you guess correct it will display(6 marks)

 Great Guess!
 You got it!
 The word was cat. Thanks for playing!
 Exiting
If your guess wrongly your code will ask three times to guess the word as shown in the below example(4 marks)

 Sorry, try again. was
 Sorry, try again. the
 Sorry, try again. are
 Exiting
 
 ##Code
 word_set=["cat", "hat", "pop", "sea", "row", "cup"]
word=input("Let's play a word guessing game ")
for i in range (3):
    if word in word_set:
        print("Great Guess!")
        print("You got it!")
        print("The word was ", word , ". Thanks for playing!")
        print('Exiting')
        break
    else:
        word=input("Let's play a word guessing game ")
