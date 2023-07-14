# Understanding Python's Counter

In this project, I have used the story 'The Fox and the grapes':


The Fox & the Grapes

A Fox one day spied a beautiful bunch of ripe grapes hanging from a vine trained along the branches of a tree. The grapes seemed ready to burst with juice, and the Fox's mouth watered as he gazed longingly at them.

The bunch hung from a high branch, and the Fox had to jump for it. The first time he jumped he missed it by a long way. So he walked off a short distance and took a running leap at it, only to fall short once more. Again and again he tried, but in vain.

Now he sat down and looked at the grapes in disgust.

"What a fool I am," he said. "Here I am wearing myself out to get a bunch of sour grapes that are not worth gaping for."

And off he walked very, very scornfully.

1. Data Preparation: 
   After getting the text the first step is to clean the text from any punctuations. Here, I used regular expressions. Also, changed the text to lowercase so that the counts are same.
2. Storing the cleaned text in a list.
3. Passing the iterable in Counter()
4. Output we would get words as 'keys' and the counts as 'values' in a dictionary.
5. Getting the most_common() words
6. Visualizing the frequency of words
