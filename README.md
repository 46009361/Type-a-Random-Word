# Type a Random Word

> [!NOTE]
> 
> If the internet connection is faulty, the project will get stuck in an infinite loop trying to filter for inappropriate words.
> However, this alone will not crash your computer.

Press the green flag and a random word will show up. Your goal is to type that word, but the keyboard is missing.

Press NEXT to go to the next letter in the alphabet and START to type that letter. If you accidentally press NEXT on the wrong letter, you have to cycle through the entire alphabet again, and if you press START on the wrong letter, it's game over.

## Credits

Scrabble word list from Jeff Boulter. It's an old list because I want to ensure the words are being used long term. I promise you won't find modern brainrot in the list.

[Bad word detector](https://scratch.mit.edu/projects/408135462/) from Dhananjaya_Test.

## Example

1. You get ODD.
2. You press NEXT 15 times, then START.
3. You press NEXT 4 times, then START.
4. You repeat step 3.
5. You win!

## Running locally

```zsh
git clone https://github.com/46009361/Type-a-Random-Word.git
cd Type-a-Random-Word
python3 -m webbrowser "index.html"
```