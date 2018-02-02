# Query Search Engine

## Website Link
yorih2.cloudapp.net

## Screenshot
![alt text](https://user-images.githubusercontent.com/12638560/35718543-ead888c4-0799-11e8-9401-31fd4268c7a1.png)

## Website
![alt text](https://user-images.githubusercontent.com/12638560/35719055-383726aa-079c-11e8-8d05-3ac3d194a29d.png)

## Github Link
https://github.com/euiyulsong/QS

## Write up
Using the Windows Azure account, I created resource groups and storage accounts. On the resource groups, I created Azure instance and on the storage account, I moved my wiki.txt file to the blob.

Using Visual Studio, I downloaded the wiki.txt to System.IO.Path.GetTempPath() using CloudBlockBlob on ASMX file utilizing C#. With the completion on downloading, I created the TrieNode. I built my TrieNode with the array. Each index in the array means certain alphabet. For example, index 0 means ‘a’, index 26 means ‘z’, and index 27 means ‘[space]'. Along with the TrieNode, I built the Trie. With the given string, I built TreeNode of each character in the string iteratively. Furthermore, I implemented searching algorithm utilizing recursion and depth-first-search.

After complemention of Trie and TrieNode, I built index.html that calls AJAX search of user's input on the Trie. This call returns JSON format of the list that is relevant to the user's input. The result was success where it was cost and memory efficient.
