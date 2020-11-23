# Word Cloud

Word cloud is a picture with the most used words in a text, could be a conversation, book, webpage, etc.
The function get_wrds opens the file and goes through every character in each line to ignore punctuation marks; adding all the characters(even spaces) to a string and then returning this string as a list of words.
The function get_freq iterate over the list of words given and if the word is not a uninteresting_words is add to a dictionary as a key and 1 as value; every time the loop matches that word will add +1 to the value(the count)

Here's an example from the poem "The Raven" by Edgar Allan Poe:   
![alt text](https://raw.githubusercontent.com/dsalzedon/word_cloud/main/img/theraven.jpg)   
![alt text](https://raw.githubusercontent.com/dsalzedon/word_cloud/main/img/theraven2.jpg)   


Here's an example from a What's App chat:   
![alt text](https://raw.githubusercontent.com/dsalzedon/word_cloud/main/img/chat_manu.jpg)   
