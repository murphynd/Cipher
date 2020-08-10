# Practice writing functions for encoding a sentence from your user, as if you wanted to keep someone from reading it. To complete this exercise review previous lessons and the JavaScript methods we've covered thus far.

* Create a JavaScript file and an HTML file in VS Code for this project so that you can load your JavaScript in the browser.

* Start by prompting your user to enter a sentence. Then, store the sentence in a variable and print it to the console.

* Next, create a function that will take the first and last letter of the sentence, capitalize them, and return this as a new string.

* Create another function that will reverse the order of these two letters and return the result.

* Create a third function that calls the other two functions you've just created. For example, if I enter the sentence "I am a sentence", it should enter your first function (which should output "IE"), then call your second function, passing in the output value from the previous. It would return "EI" to me.

* Add code to your third function to concatenate the new two-letter string together with the original phrase. It should add the two-letter string at the end, forming the final result "I am a sentenceEI."

* Create a fourth function to count the number of letters in the original sentence, divide it by two (rounding down if necessary), and output the letter at this index. Concatenate this letter at the beginning of the original sentence. For example, if "I am a sentence" is my original input, and it has 15 total characters in it. If I divide this by 2, I get 7.5, which rounds down to 7. The letter at the 7th position in the sentence is "s". So my final result is "sI am a sentenceEI".

* ### Bonus: Take the final result and reverse it: "IEecnetnes a ma ls".

* Use jQuery to create two clickable images or pieces of text in your HTML page. When you click on the left one, it should show you the original sentence. If you click the other one, it should hide the original sentence and show the encoded one. Use Bootstrap to organize and style your page.

* This may seem somewhat impractical, but writing multiple functions that have the ability to call each other will prepare you to write code in small, manageable chunks. This makes code easier to debug, and complex problems easier to approach. Rather than attempting to do everything all at once, we break things down into little pieces!