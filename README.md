# **Part One: Exploring the Data**

What is each column use for?
The Wylie transliteration system is a method for transliterating Tibetan script into the Latin alphabet which is required for the AI model to tranlste the Tibetan column.

WHat is the other column used for?
The other column offers context of the Tibetan.

Part Two: Data Cleaning
Fixed issue with output file with encoding issue.
I took the "/" out of the column.

Part Three: Openai API
Decreased cost from $300 to $30 for tranlating all the sheet of data of different languages.
Decreased API cost by 90%!
Created function that allows to choose the input and output languange. 
I had to take two prompt engineering courses to engineer the prompt to give me the output I needed in the format required.
