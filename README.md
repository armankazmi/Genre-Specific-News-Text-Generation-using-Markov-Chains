# News-Text-Generation-using-Markov-Chains

**This project is about experimenting with Markov Chains to generate News text having a writing style similiar to that of Fiction or Non-Fiction
texts .**

For more detail kindly follow report.pdf

**Steps to generate the text**

## **Markov class methods**


```Class:- Markov(text_corpus)```

```show_summary()```

```generate(n,start,length,alpha)```

```mixed_n_generate(start,length,alpha)```

**show_summary() is a function to print the summary of the text**

**generate() is the function to generate text with the following arguments:-**

  * **n: - previous n words to consider**

  * **start:- seed words to generate the text**

  * **length:- number of words to generate in the text**

  * **alpha :- Hyperparameter, perferably 0 for better results**

**mixed_n_generate() is the function to generate text by using a combination of 1-word, 2-word, 3-word markov chains. The arguments are same as that of generate()**

## **Sample:-**

**To generate using a single n-word markov chains:-**

open the terminal in the file location and ```run python markov.py path_to_text_corpus n seed length alpha 1 ```

example: ```run python markov.py path_to_text_corpus 2 "He is" 50 0 1 ```

**To generate using a mixed markov chain model:-**

open the terminal in the file location and ```run python markov.py path_to_text_corpus seed length alpha 2 ```

example: ```run python markov.py path_to_text_corpus "He is at" 50 0 2 ```


