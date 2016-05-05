# Prescreen-Form-Validation-for-Textarea

Create an HTML document called prescreen.html containing a textarea, a button.
Each line in the textarea should be expected to contain a key, separated from a count by a colon character. The key may be any string not containing a colon. The count should be expected to be able to be parsed to an integer.

The textarea should have the following default value:

John: 2
Jane: 3
John: 4
Jane: 5

My objective is to sum the counts for each key in the textarea, and display the totals for each key within the HTML document. The default value should result in the output, "The total for John is 6. The total for Jane is 8."

The following classes should be applied to the elements: prescreen-input, prescreen-button, prescreen-output.

Extra Credit: Palindromes

Everybody likes extra credit, right?

If the key entered in the keycount textarea happens to be a palindrome, like "Bob", "Hannah", or "Ah, Satan sees Natasha!", add a classname of "prescreen-palindrome" to that keycount in the output produced by the exercise above.

Palindrome checker should ignore spaces and punctuation, and treat uppercase and lowercase letters as the same.
