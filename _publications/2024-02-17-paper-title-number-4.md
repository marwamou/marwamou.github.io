---
title: "Asynchronus Authentication"
authors: "Marwa Mouallem and Ittay Eyal"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'If the communication between the user and the authenticator is asynchronous, every authentication mechanism is dominated by one defined by a monotonic Boolean function based on credential availability. A scenario-based greedy algorithm can approximate optimal mechanisms by focusing on the most likely scenarios, and surprisingly, even weak credentials can significantly enhance security when used strategically.'
To be published in: "CCS'24"
paperurl: 'http://marwamou.github.io/files/Asynchronous_authentication_ext.pdf'
---

Authors: Marwa Mouallem and Ittay Eyal

**Abstract**  

A myriad of authentication mechanisms embody a continuous evolution from verbal passwords in ancient times to contemporary multi-factor authentication: 
Cryptocurrency wallets advanced from a single signing key to using a handful of well-kept credentials, 
and for online services, the infamous “security questions” were all but abandoned. 
Nevertheless, digital asset heists and numerous identity theft cases illustrate the urgent need to revisit the fundamentals of user authentication.

We abstract away credential details and formalize the general, common case of asynchronous authentication, with unbounded message propagation time. 
Given credentials’ fault probabilities (e.g., loss or leak), we seek mechanisms with maximal success probability.
Such analysis was not possible before due to the large number of possible mechanisms. 
We show that every mechanism is dominated by some Boolean mechanism—defined by a monotonic Boolean function on presented credentials. 
We present an algorithm for finding approximately optimal mechanisms by leveraging the problem structure to reduce complexity by orders of magnitude.

The algorithm immediately revealed two surprising results: Accurately incorporating easily-lost credentials improves cryptocurrency wallet security by orders of magnitude. And novel usage of
(easily-leaked) security questions improves authentication security
for online services.

[download](http://marwamou.github.io/files/Asynchronous_authentication_ext.pdf)
