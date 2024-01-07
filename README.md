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