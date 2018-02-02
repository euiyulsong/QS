# Query Search Engine

## Website Link
yorih2.cloudapp.net

## Screenshot
![alt text](https://user-images.githubusercontent.com/12638560/35718543-ead888c4-0799-11e8-9401-31fd4268c7a1.png)


## Github Link
https://github.com/euiyulsong/QS

## Write up
I created Windows Azure account with the key our TA, Chris Oh provided. Using the Windows Azure account, I created resource groups and storage accounts. On the storage account, I dragged my wiki.txt file to the blob.

Using Visual Studio, I downloaded the wiki.txt to System.IO.Path.GetTempPath() using CloudBlockBlob on ASMX file utilizing C#. With the completion on downloading, I created the TrieNode. I built my TrieNode with the array instead of List and the index in the array means certain alphabet. For example, index 0 means ‘a’, index 26 means ‘z’, and index 27 means ‘ ‘. Along with the TrieNode, I built Trie class. Working on Trie class took roughly 30 hours. For instance, building a Trie with given list of word did not take too much time. However, I had to change my Search Method several time to make my code cost and memory efficient. For example, I used DFS for my Search Method utilizing StringBuilder. In addition to TrieNode and Trie, I built index.html showing textbox and submit button and implemented AJAX search with JSON.

The result was success.
