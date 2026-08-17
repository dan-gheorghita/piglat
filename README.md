# pigLat.py

**English to Pig Latin Translator**

This Python code is a translator that converts English text into Pig Latin. Pig Latin is a playful language game where words are altered by moving the first consonant (or consonant cluster) to the end of the word and adding the sound "ay."

**How it Works:**

1. The code first asks the user to enter an English message to translate into Pig Latin.
2. It splits the input message into individual words.
3. For each word, it separates any non-letter characters at the start and end of the word.
4. It checks if the word starts with a consonant cluster. If it does, it moves the cluster to the end of the word and adds "ay." If not, it simply adds "yay" to the end of the word.
5. It preserves the original case of the word (uppercase, title case, or lowercase).
6. Finally, it joins all the translated words back together into a single string and