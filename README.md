Download Link: https://assignmentchef.com/product/solved-cse654-484-homework-02
<br>
In this homework we will develop a statistical language model of Turkish that will use N-grams of Turkish syllables.

Follow the steps below for the rest of the homework and for your homework report

<ol>

 <li>Download the Turkish Wikipedia dump <a href="https://www.kaggle.com/mustfkeskin/turkish-wikipedia-dump">https://www.kaggle.com/mustfkeskin/turkish</a><a href="https://www.kaggle.com/mustfkeskin/turkish-wikipedia-dump">wikipedia</a><a href="https://www.kaggle.com/mustfkeskin/turkish-wikipedia-dump">–</a><a href="https://www.kaggle.com/mustfkeskin/turkish-wikipedia-dump">dump</a></li>

 <li>Separate each word into its syllables using the same program that you used for HW1</li>

 <li>Calculate the 1-Gram, 2-Gram, 3-Gram, 4-Gram and 5-Gram tables for this set using 95% of the set (If the set is too large, you may use a subset). Note that your N-gram tables will be mostly empty, so you need to use smart ways of storing this information. You also need to use smoothing, which will be GT smoothing that we have learned in the class.</li>

 <li>Calculate perplexity of the 1-Gram to 5-Gram models using the chain rule with the Markov assumption for each sentence. You will use the remaining 5% of the set for these calculations. Make a table of your findings in your report and explain your results.</li>

 <li>Produce random sentences for each N-Gram model. You should pick one of the best 5 letters</li>

</ol>

randomly. Include these random sentences in your report and discuss the produced sentences.




Prepare your report and submit it to the Teams page. You may use any programming language for the implementation. You may also use N-gram library software to calculate the N-Grams efficiently. Please indicate which library you have used.




Notes

<ol>

 <li>Do not forget to use logarithm of the multiplication of the chain rule formula</li>

 <li>Convert all the letters to small case letters first. You may convert all Turkish characters to English ones. For example, ş -&gt; s and ğ -&gt; g</li>

 <li>Do not forget to include punctuation marks (end of sentences and space characters as syllables in your N-grams. Just lower case letters and space character will be enough.</li>

 <li>You will demo your homework result online</li>

</ol>