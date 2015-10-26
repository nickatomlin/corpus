# Corpus Linguistics in Haskell

Corpora
-------

| **Corpus Name** | File Name    | Description                             |
| -------------   | ------------ | --------------------------------------- |
| Brown Corpus    | `brown.txt`  | one million words; no tags or line numbers |

Procedures
----------

| **Procedure Name** | Purpose                            | 
| ------------------ | ---------------------------------- | 
| `addWord`          | adds a word to a list if the word is not already in the list |
| `averageLength`    | finds the average length of words in a list of words |
| `bigram`           | finds bigrams of a list of words |
| `freqBrown`        | finds the number of times a word appears in the Brown corpora |
| `freqList`         | finds the frequency map of a list of words |
| `palindrome`       | checks if a word is a palindrome or not |
| `removeDuplicates` | removes the duplicates in a list of words |
| `skipBigrams`      | finds sentence-order tuples of a list of words |
| `splitTokenize`    | primitive parsing function for input |
| `typeToken`        | the number of unique tokens over the total number of tokens |
