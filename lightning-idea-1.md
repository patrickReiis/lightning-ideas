# Small 1600s village

## What is Bitcoin
If I could illustrate what Bitcoin is in a **poorly** manner, I would summarize it like this:  
A king exists, the king has a big bank in his kingdown that keeps track of all transactions. There are many small villages situated within the country,
the citizens can call the king's carriage to see all the transactions ever made for free and they can also ask the carriage to take their transaction so it stays 
in the king's bank, however, to do that they need to pay a small fee.

## The problem
The problem with is that if a citizen likes to buy a lot of things, he would have to pay a fee for each time he buys something, 
even if it's a cheap thing like a coffee. Also, it takes a while for the carriage to get to the king's bank, so if the citizen 
wants his transaction to be recorded fast enough he would need to pay a big fee.

## The solution
Since the citizen writes a letter with his transaction and puts it in the king's carriage, a potential solution would be to make so all citizens use the **same** letter, and when the letter is full, a.k.a, has run out of blank space, then they can call the king's carriage so it is recorded in the king's bank.  
The citizens do not need to wait until the letter is full, they just need to make a consensus before stating that once a letter has X amount of transactions, the king's carriage WILL be called.

## Tl;dr / Conclusion
A transaction with an X limit is created, users sign the amount they want to send and the recipient address, once the transaction fills the X amount, it can be broadcasted to the blockchain.  A simple and a lot of http servers could be created with the purpose of keeping a list of open transactions that haven't hit the X amount yet.  
This solution would be reliable and decentralized, depending on the X amount, it could be fast as well.  

Bear in mind that speed is not that relevant if a user **knows** he will receive a transaction at some point. For instance, if it is **guaranteed** that I will receive a billion dollars in the next 30 days, I would still be happy regardless.

Timelocks could be added such that a user can't spend his bitcoin if he sent it to a transaction pool.
