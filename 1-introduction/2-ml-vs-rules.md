__

# ID

* Rule-based: Data + Rule => Output, Jika A>90, maka cumlaude
* ML: Data + Output=> Rule, Data=>Rule=>Output
* Hasil dari rules adalah sebuah output, sedangkan hasil dari ML adalah rules, dimana rules tersebut untuk memahami pola/tren dari data
* Contohnya misal membedakan email spam/non-spam

Rule-based:
* If sender promotion@online, then Spam
* If contains "tax review', then Spam
* If bod of email contains "deposit", then Spam
* again and again...

ML:
1. Get Data
2. Define & Calculated Features
3. Train & Use the Model

Features:
* Length of tittle> 10 (Yes/No)
* Lenghth of boday> 10 (Yes/No)
* Sender "promotions@online.com" (Yes/No)


| Index Email | Length of Title > 10 | Length of Body > 10 | Sender "promotions@online.com" | Spam/Not Spam |
|-------|----------------------|---------------------|------------------------------|---------------|
|   1   |        Yes           |        Yes          |             Yes              |     Not Spam |
|   2   |        No            |        Yes          |             No               |      Spam    |
|   3   |        Yes           |        No           |             Yes              |     Not Spam |

| Index Email | Length of Title > 10 | Length of Body > 10 | Sender "promotions@online.com" | Spam/Not Spam |
|-------|----------------------|---------------------|------------------------------|---------------|
|   1   |        1          |        1         |             1              |     0 |
|   2   |        0          |        1         |             0               |      1    |
|   3   |        1          |        0           |             1              |     0 |


| Index | Email | Length of Title > 10 | Length of Body > 10 | Sender "promotions@online.com" | Spam/Not Spam | Probability |
|-------|-------|----------------------|---------------------|------------------------------|--------------|-------------|
|   1   |   1   |          1           |          1          |              1               |      0       |     0.6   |
|   2   |   0   |          0           |          1          |              0               |      1       |     0.8    |
|   3   |   1   |          1           |          0          |              1               |      0       |     0.4    |



> **Start with rules and then use these rules as features**

by: itsmecevi.github.io




