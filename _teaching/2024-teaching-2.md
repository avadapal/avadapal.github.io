---
title: "Secure Computation"
collection: teaching
type: "Postgraduate course"
permalink: /teaching/2024-teaching-2
venue: "IIT Kanpur, Computer Science and Engineering"
date: 2024-01-01
location: "Kanpur, Uttar Pradesh"
---
About the Course
-------------------------
The last couple of decades have seen a significant proliferation of the Internet in our daily lives. From essential services like banking and health to entertainment like movies and music, have moved online. The Covid-19 pandemic only accelerated these trends. While these trends have made our lives easier and brought great conveniences, it has also resulted in a substantial infringement on the privacy of individuals. Privacy Enhancing Technologies (PETs) are technologies that help protect the privacy of individuals or groups. There are several ways in which PETs can constructed. In this course, we will look at some of the cryptographic approaches to achieving privacy. In particular, some of the topics that will be covered are: (i) Can one stream a movie on, say, Netflix while Netflix has no idea what one watched? (Private Information Retrieval); (ii) Can two millionaires find out who is richer without revealing to each other their wealth (Secure Multi-Party Computation)? (iii) Can you convince your friend that you know a solution to the Graph 3-coloring problem without them learning the 3-coloring or any new information? (Zero Knowledge Proofs); (iv) Can you outsource storage to a remote server and access data from it while all your access patterns are hidden? (Oblivious Random Access Memory). 

Course Organization
-----------------------

### Where and When?
KD102. Monday, Wednesday, and Friday, 5.00 PM to 6.00 PM.

## Course Staff
- Instructor: Adithya Vadapalli

### Teaching Assistants
- Anindya anindyag@cse.iitk.ac.in

### Office Hours
By Appointment.

### Quizzes

-  [Quiz1 Redressal Form](https://docs.google.com/forms/d/e/1FAIpQLSeUPCbHEFq07B5MkZfcEcoMj-QKj-7B9iAKUW_X77PPz-RiKw/viewform)
-  [Quiz2 Redressal Form](https://docs.google.com/forms/d/e/1FAIpQLSfg8KP8CabiYJLwS_UT0OyHfvwQn6aXBK_jMwgPsAKJAKr5mg/viewform)

Students are welcome to meet the instructor and discuss any thing from the course during the office hours.

### Assignments

- Assignment 1 can be downloaded [here](https://github.com/avadapal/avadapal.github.io/raw/master/files/cs670-2024/A1.pdf).

Course Schedule
------------------------------

| #  | Module      | Date     | Topic                  | Compulsory Reading | Optional Reading | 
|----|-------------|----------|------------------------|--------------------|------------------|
| 1  | 0: Intro     | 8.1.24   | Why Privacy            | [I have nothing to hide](https://scholarship.law.gwu.edu/cgi/viewcontent.cgi?article=1159&context=faculty_publications) | TBD              |
| 2  | 0: Intro     | 10.1.24  | Crypto Refresher       | TBD                | TBD               | TBD              |
| 3  | 1: PIR       | 15.1.24  | Quiz 1 + Information  Theoretic Private Information Retrieval                  | Section 1 to Section 3.2 , Section 5 in [Chor et al's Paper](https://madhu.seas.harvard.edu/papers/1995/pir-journ.pdf)                | Section 3.3, 3.4, and 4 [Chor et al's Paper](https://madhu.seas.harvard.edu/papers/1995/pir-journ.pdf)               | 
| 4  | 1: PIR       | 17.1.24  | Information  Theoretic Private Information Retrieval                     | [Goldberg's Paper](https://cypherpunks.ca/~iang/pubs/robustpir.pdf), [Shamir's Secret Sharing](https://www.youtube.com/watch?v=iFY5SyY3IMQ&t=7)               | [Optimally Robust PIR](https://eprint.iacr.org/2012/083.pdf), [How to share a secret](https://web.mit.edu/6.857/OldStuff/Fall03/ref/Shamir-HowToShareASecret.pdf)             | 
| 5  | 1: PIR       | 22.1.24  | Distributed Point Functions          | Section 2.1.1 from [Duoram paper](https://eprint.iacr.org/2022/1747.pdf), Figure 1 from [DPF paper](https://eprint.iacr.org/2018/707.pdf), Section II-A from [Sabre Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9833601), Section 6.1 from the [Pirsona Paper](https://petsymposium.org/popets/2021/popets-2021-0059.pdf), Section 4.1 to 4.3 in the [Riposte paper](https://www.freehaven.net/anonbib/cache/riposte2015.pdf)  | Section 3 from [Grotto Paper](https://eprint.iacr.org/2022/1747.pdf) , [The original DPF paper](https://dl.acm.org/doi/pdf/10.1145/2976749.2978429), [DPF based PIR scheme](https://petsymposium.org/popets/2019/popets-2019-0061.pdf)       | 
| 6  | 1: PIR       | 24.1.24  | Review Lecture                   | TBD                | TBD               | 
| 7  | 1: PIR       | 29.1.24  | Computational PIR        | [Survey on CPIR](https://eprint.iacr.org/2007/059.pdf)                | TBD               | 
| 8  | 1: PIR       | 31.1.24  | Quiz 2 + Pirsona       | [Pirsona Paper](https://petsymposium.org/popets/2021/popets-2021-0059.pdf)                | TBD               | 
| 9  | 1: PIR       | 5.2.24   | Pirsona                | [Pirsona Paper](https://petsymposium.org/popets/2021/popets-2021-0059.pdf)                | TBD               | 
| 10 | 2: MPC       | 7.2.24   | Introduction to MPC    | Chapter 2 [MPC Book](https://securecomputation.org/docs/pragmaticmpc.pdf), [MPC](https://eprint.iacr.org/2020/300.pdf)                | [How To Simulate It](https://eprint.iacr.org/2016/046.pdf)               | 
| 11 | 2: MPC       | 12.2.24  | Oblivious Transfer                    | TBD                | TBD               | 
| 12 | 2: MPC       | 14.2.24  | Garbled Circuits (GC)      | TBD                | [Introduction to Garbled Circuits](https://web.mit.edu/sonka89/www/papers/2017ygc.pdf)               | 
|  |         | 19.2.24  | Midsems     |                 |                |   
|  |        | 21.2.24  |   Midsems      |                 |                | 
| 13 | 2: MPC       | 26.2.24  | Optimizatios of GC, GMW protocol              | TBD                | TBD               | 
| 14 | 2: MPC       | 28.2.24  | Quiz 3 + Beaver Triples     | TBD                | TBD               | 
| 15 | 2: MPC       | 4.3.24  | MPC Applications      | TBD                | TBD               | 
| 16 | 2: MPC       | 6.3.24  |  Review Lecture on MPC  | TBD                | TBD               | 
| 17 | 3: ORAM       | 9.3.24 (Extra Class)   | Squareroot ORAM       |     Sections 1 to 4 [here](https://users.cs.utah.edu/~lifeifei/papers/oramvldb16.pdf)            |     [Original ORAM Paper](https://dl.acm.org/doi/pdf/10.1145/233551.233553)            |    
| 18 | 3: ORAM      | 11.3.24   | Hierarchical ORAM     | Chapter 1 from [here](https://repository.library.northeastern.edu/files/neu:rx917826p/fulltext.pdf), Original [Tree ORAM paper](https://eprint.iacr.org/2011/407.pdf)               | TBD               |  
| 19 | 3: ORAM      | 13.3.24  | ORAM for MPC, Floram              | Revisiting Square Root ORAM [paper](https://www.cs.umd.edu/~jkatz/papers/sqoram.pdf), Original [Floram Paper](https://eprint.iacr.org/2017/827.pdf)                | TBD               | 
| 20 | 3: ORAM      | 18.3.24  | ORAM for MPC, Floram              | Revisiting Square Root ORAM [paper](https://www.cs.umd.edu/~jkatz/papers/sqoram.pdf), Original [Floram Paper](https://eprint.iacr.org/2017/827.pdf)                | TBD               | 
| 21 | 3: ORAM      | 21.3.24  | ORAM for MPC, Floram              | Revisiting Square Root ORAM [paper](https://www.cs.umd.edu/~jkatz/papers/sqoram.pdf), Original [Floram Paper](https://eprint.iacr.org/2017/827.pdf)                | TBD               | 
| 22 | 3: ORAM      | 13.4.24 (Extra Class)  | ORAM Recap              | Revisiting Square Root ORAM [paper](https://www.cs.umd.edu/~jkatz/papers/sqoram.pdf), Original [Floram Paper](https://eprint.iacr.org/2017/827.pdf)                | TBD               | 
| 23 | 4: ZKP      | 13.4.24 (Extra Class)  | ORAM Recap              | Revisiting Square Root ORAM [paper](https://www.cs.umd.edu/~jkatz/papers/sqoram.pdf), Original [Floram Paper](https://eprint.iacr.org/2017/827.pdf)                | TBD               | 
| 24 | 4: ZKP      | 14.4.24 (Extra Class)  | ORAM Recap              | Revisiting Square Root ORAM [paper](https://www.cs.umd.edu/~jkatz/papers/sqoram.pdf), Original [Floram Paper](https://eprint.iacr.org/2017/827.pdf)                | TBD               | 
| 25 | 4: ZKP      | 15.4.24   | ORAM Recap              | Revisiting Square Root ORAM [paper](https://www.cs.umd.edu/~jkatz/papers/sqoram.pdf), Original [Floram Paper](https://eprint.iacr.org/2017/827.pdf)                | TBD               | 
| 26 | End Sem Prep      | 17.4.24   | ORAM Recap              | Revisiting Square Root ORAM [paper](https://www.cs.umd.edu/~jkatz/papers/sqoram.pdf), Original [Floram Paper](https://eprint.iacr.org/2017/827.pdf)                | TBD               | 

### References

- [1] Private Information Retrieval  _Chor, Goldreich, Kushilevitz_   [here](https://dl.acm.org/doi/pdf/10.1145/293347.293350)
- [2] Gentle Introduction to Yao's Garbled Circuits [here](https://web.mit.edu/sonka89/www/papers/2017ygc.pdf)
- [3] Blog on TEE [here](https://sergioprado.blog/introduction-to-trusted-execution-environment-tee-arm-trustzone/)
- [4] Resources for MPC: [here](https://u.cs.biu.ac.il/~lindell/MPC-resources.html), and [here](https://github.com/rdragos/awesome-mpc)
- [5] [Winter School on MPC](https://www.youtube.com/playlist?list=PLXF_IJaFk-9BFn8M-dsEm5x3-5Cvji3V9)

### Additional Resources

The are of Privacy and Security really benefits from some outstanding lectures available online. Some of them are below. 
1. Kevin Yeo's [talk](https://www.youtube.com/watch?v=8eqJztvaT1w) at CrySP on Private Information Retrieval 
2. Ryan Henry's [tutorial](https://www.youtube.com/watch?v=XEYwMPwPxNI&t=450s) on PIR at ACM CCS 2017


Course Resources
------------------------
There is no one textbook for this course. There are few useful books though. 
- Modern Cryptography by _Katz and Lindell_
- Pragmatic MPC by _Evans, Koselnikov, and Rosulek_


Grading
-----------------------------

|              |      | 
|--------------|------|
|Assignment 1  | 20%  | 
|--------------|------|
|Assignment 2  | 20%  | 
|--------------|------|
|Assignment 3  | 40%  | 
|--------------|------|
|Quizzes       | 5%   |
|--------------|------|
|Final Exam    | 15%  |  
|--------------|------|


Academic Integrity
---------------------------
See CSE Department's Policy [here](https://www.cse.iitk.ac.in/pages/AntiCheatingPolicy.html)

Mental Health Support
---------------------------
See Counselling Service of CSE Deparment [here](https://www.cse.iitk.ac.in/pages/Counselling.html)
