# fuzzy-matching
Fuzzy matching for duplicate detection on a large number of records

### Purpose
During the construction of this project, I worked at a bank, and we were discussing how to know if two records referred to the same customer if they didn't match exactly. I knew the answer had something to do with fuzzy matching, but I hadn't used it before outside of Excel, and we had a very large number of transactions.

O(n^2) for even 5,000 records would take in excess of a minute or two in Python, so I decided to learn how to do this with much larger datasets in a faster language, so this project is written in C which I did not know at the time.

### Dependencies
MinGW GCC

### Process
I first installed the necessary dependencies.
Then, I created fake data for 6,000 records and duplicated 100 of those 6,000 records for a total of 6,100 records.