# Wordle-AI
A decent AI that solves daily "Wordle" puzzles. Works with different websites with similar wordlists.

When prompted with "Word:" enter the word you used for your last guess on Wordle. 
Ex -- bagel [Note: You can leave this and the status blank to receive a word recommendation]

When prompted with "Status:" enter the status [using characters: c (for correct), p (for present), and a (for absent)] of the word you used on your last guess. 
Ex -- (let's say in our guess "bagel" that b and a were in the right spot, g and e were absent, and l was present somewhere) -- ccaap

The bot will then recommend a word for you to use. 
[Note: You don't have to use the recommendation--you can skip--but you must enter the word you used to receiving a better recommendation]

When prompted with "Found? (y):" you can click ENTER or type any key EXCEPT y to continue guessing. y will trigger the AI to stop executing the script.

From here, it just repeats. Usually the bot will get it within 3-5 tries. 
