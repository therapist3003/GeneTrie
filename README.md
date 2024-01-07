**_KEY IDEA: A Substring is a prefix of a suffix_**
_Reference: https://youtube.com/watch?v=llTjA5SeS7k&list=PL2mpR0RYFQsDFNyRsTNcWkFTHTkxWREeb&index=2 (15:00)_

**Why SUFFIX TRIE and why not TRIE (Prefix Tree)?**
_Tries may not be as suitable for DNA sequence matching due to their limitation in efficiently handling variable-length sequences and managing common prefixes without redundancy._

This project creates a **Suffix Trie** of large **DNA dataset** and given any sufficiently long DNA sequence, it outputs
whether a match is found with **O(n) time** , where **n** is the length of the query sequence.

Additionally, there are few smaller sequences along with the characteristics of the person with that sequence stored in separate
text files (Data created manually for testing purpose). Using this, given any query sequence, if a person is found with the match
it outputs the **possible characteristics** he/she may possess.

**Can be extended (Ideas to improve the project):**
1) Persons' characteristics can be stored at leaf node. So that when a query is matched, corresponding traits can be outputted.

**_Resources :_**
1) https://stackoverflow.com/questions/4737904/difference-between-tries-and-trees?newreg=d8d036e486f14fd4a5417a1085ca1501
2) https://romankurnovskii.com/en/posts/tree-vs-trie-data-structures/
3) Trie, Suffix Trie, Suffix Tree - Playlist:     
   https://youtube.com/watchv=llTjA5SeS7k&list=PL2mpR0RYFQsDFNyRsTNcWkFTHTkxWREeb&index=2
