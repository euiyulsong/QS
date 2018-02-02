{\rtf1\ansi\ansicpg1252\cocoartf1504\cocoasubrtf830
{\fonttbl\f0\fmodern\fcharset0 Courier;\f1\fswiss\fcharset0 ArialMT;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red26\green26\blue26;\red255\green255\blue255;
}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;\cssrgb\c13333\c13333\c13333;\cssrgb\c100000\c100000\c100000;
}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sl280\partightenfactor0

\f0\fs24 \cf2 \expnd0\expndtw0\kerning0
# Query Search Engine\
\
## Website Link\
\pard\pardeftab720\sl420\partightenfactor0

\f1\fs35\fsmilli17600 \cf3 \cb4 yorih2.cloudapp.net
\f0\fs24 \cf2 \cb1 \
\pard\pardeftab720\sl280\partightenfactor0
\cf2 \
## Screenshot\
![alt text]({\field{\*\fldinst{HYPERLINK "https://user-images.githubusercontent.com/12638560/35718543-ead888c4-0799-11e8-9401-31fd4268c7a1.png"}}{\fldrslt \cf2 https://user-images.githubusercontent.com/12638560/35718543-ead888c4-0799-11e8-9401-31fd4268c7a1.png}})\
\
## Github Link\
\pard\pardeftab720\sl420\partightenfactor0
{\field{\*\fldinst{HYPERLINK "https://github.com/euiyulsong/QS"}}{\fldrslt 
\f1\fs35\fsmilli17600 \cf3 \cb4 https://github.com/euiyulsong/QS}}\
\pard\pardeftab720\sl280\partightenfactor0
\cf2 \
## Write up\
\pard\pardeftab720\ri0\sl276\slmult1\partightenfactor0

\f1\fs22 \cf0 \kerning1\expnd0\expndtw0 First, I created Windows Azure account with the key our TA, Chris Oh provided. Using the Windows Azure account, I created resource groups and storage accounts. On the storage account, I dragged my wiki.txt file to the blob.\
\
Using Visual Studio, I wrote my web service in C# and AJAX. I downloaded the wiki.txt to System.IO.Path.GetTempPath() using CloudBlockBlob on ASMX file utilizing C#. With the completion on downloading, I created the TrieNode. I built my TrieNode with the array instead of List and the index in the array means certain alphabet. For example, index 0 means \'91a\'92, index 26 means \'91z\'92, and index 27 means \'91 \'91. Along with the TrieNode, I built Trie class. Working on Trie class took roughly 30 hours. For instance, building a Trie with given list of word did not take too much time. However, I had to change my Search Method several time to make my code cost and memory efficient. For example, I used DFS for my Search Method utilizing StringBuilder. In addition to TrieNode and Trie, I built index.html showing textbox and submit button, and implemented AJAX search. This API returns query suggestions in JSON. \
\
The result was success.\
}