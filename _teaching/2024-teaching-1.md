---
title: "Cryptographic Techniques for Privacy Preservation"
collection: teaching
type: "Postgraduate course"
permalink: /teaching/2024-teaching-1
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
KD101. Monday and Wednesday, 5.15 PM to 6.30 PM.

## Course Staff
- Instructor: Adithya Vadapalli

### Teaching Assistants
- Anindya anindyag@cse.iitk.ac.in
- Dhananjay dhananjayg@cse.iitk.ac.in
- Hrithik hrithik@cse.iitk.ac.in
- Naman prgmaz@cse.iitk.ac.in

### Office Hours
Location: KD-317, Time: Monday 11 AM to 12 PM 

### Quizzes

-  [Quiz1 Redressal Form](https://docs.google.com/forms/d/e/1FAIpQLSeUPCbHEFq07B5MkZfcEcoMj-QKj-7B9iAKUW_X77PPz-RiKw/viewform)
-  [Quiz2 Redressal Form](https://docs.google.com/forms/d/e/1FAIpQLSfg8KP8CabiYJLwS_UT0OyHfvwQn6aXBK_jMwgPsAKJAKr5mg/viewform)

Students are welcome to meet the instructor and discuss any thing from the course during the office hours.

### Assignments

- Assignment 1 can be downloaded [here](https://github.com/avadapal/avadapal.github.io/raw/master/files/cs670-2024/A1.pdf).

Course Schedule
------------------------------

| #  | Module      | Date     | Topic                  | Compulsory Reading | Optional Reading | Lecture Material |
|----|-------------|----------|------------------------|--------------------|------------------|------------------|
| 1  | 0: Intro     | 8.1.24   | Why Privacy            | [I have nothing to hide](https://scholarship.law.gwu.edu/cgi/viewcontent.cgi?article=1159&context=faculty_publications) | TBD              | TBD              |
| 2  | 0: Intro     | 10.1.24  | Crypto Refresher       | TBD                | TBD               | TBD              |
| 3  | 1: PIR       | 15.1.24  | Quiz 1 + Information  Theoretic Private Information Retrieval                  | Section 1 to Section 3.2 , Section 5 in [Chor et al's Paper](https://madhu.seas.harvard.edu/papers/1995/pir-journ.pdf)                | Section 3.3, 3.4, and 4 [Chor et al's Paper](https://madhu.seas.harvard.edu/papers/1995/pir-journ.pdf)               | TBD              |
| 4  | 1: PIR       | 17.1.24  | Information  Theoretic Private Information Retrieval                     | [Goldberg's Paper](https://cypherpunks.ca/~iang/pubs/robustpir.pdf), [Shamir's Secret Sharing](https://www.youtube.com/watch?v=iFY5SyY3IMQ&t=7)               | [Optimally Robust PIR](https://eprint.iacr.org/2012/083.pdf), [How to share a secret](https://web.mit.edu/6.857/OldStuff/Fall03/ref/Shamir-HowToShareASecret.pdf)             | TBD              |
| 5  | 1: PIR       | 22.1.24  | Distributed Point Functions          | Section 2.1.1 from [Duoram paper](https://eprint.iacr.org/2022/1747.pdf), Figure 1 from [DPF paper](https://eprint.iacr.org/2018/707.pdf), Section II-A from [Sabre Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9833601), Section 6.1 from the [Pirsona Paper](https://petsymposium.org/popets/2021/popets-2021-0059.pdf), Section 4.1 to 4.3 in the [Riposte paper](https://www.freehaven.net/anonbib/cache/riposte2015.pdf)  | Section 3 from [Grotto Paper](https://eprint.iacr.org/2022/1747.pdf) , [The original DPF paper](https://dl.acm.org/doi/pdf/10.1145/2976749.2978429), [DPF based PIR scheme](https://petsymposium.org/popets/2019/popets-2019-0061.pdf)       | TBD              |
| 6  | 1: PIR       | 24.1.24  | Review Lecture                   | TBD                | TBD               | TBD              |
| 7  | 1: PIR       | 29.1.24  | Computational PIR        | [Survey on CPIR](https://eprint.iacr.org/2007/059.pdf)                | TBD               | TBD              |
| 8  | 1: PIR       | 31.1.24  | Quiz 2 + Pirsona       | [Pirsona Paper](https://petsymposium.org/popets/2021/popets-2021-0059.pdf)                | TBD               | TBD              |
| 9  | 1: PIR       | 5.2.24   | Pirsona                | [Pirsona Paper](https://petsymposium.org/popets/2021/popets-2021-0059.pdf)                | TBD               | TBD              |
| 10 | 2: MPC       | 7.2.24   | Introduction to MPC    | Chapter 2 [MPC Book](https://securecomputation.org/docs/pragmaticmpc.pdf), [MPC](https://eprint.iacr.org/2020/300.pdf)                | [How To Simulate It](https://eprint.iacr.org/2016/046.pdf)               | TBD              |
| 11 | 2: MPC       | 12.2.24  | Oblivious Transfer                    | TBD                | TBD               | TBD              |
| 12 | 2: MPC       | 14.2.24  | Garbled Circuits (GC)      | TBD                | [Introduction to Garbled Circuits](https://web.mit.edu/sonka89/www/papers/2017ygc.pdf)               | TBD              |
| 13 |         | 19.2.24  | Midsems     | TBD                | TBD               | TBD              |
| 14 |        | 21.2.24  |   Midsems      | TBD                | TBD               | TBD              |
| 15 | 2: MPC       | 26.2.24  | Optimizatios of GC, GMW protocol              | TBD                | TBD               | TBD              |
| 16 | 2: MPC       | 28.2.24  | Quiz 3      | TBD                | TBD               | TBD              |
| 17 | 2: MPC       | 4.3.24   | ABY       | TBD                | TBD               | TBD              |
| 18 | 3: ZKP      | 6.3.24   | Client-Server ORAM     | TBD                | TBD               | TBD              |
| 19 | 3: ZKP      | 11.3.24  | Hierarchical ORAM      | TBD                | TBD               | TBD              |
| 20 | 3: ZKP      | 13.3.24  | Tree ORAM              | TBD                | TBD               | TBD              |
| 21 | 3: ZKP      | 18.3.24  | Path ORAM              | TBD                 | TBD              | TBD              |
| 22 | 4: ORAM        | 20.3.24  |                      |                     |                  |               |
|    |                | 25.3.24 |                       |                     |                  |               |
|    |                | 27.3.24 | OTR                    | TBD                | TBD              | TBD              |
| 23 | 5: Application | 1.4.24  | Anonymous Messaging    | TBD                | TBD              | TBD              |
| 24 | 5: Application | 3.4.24  | Anonymous Messaging    | TBD                | TBD              | TBD              |
| 25 | 5: Application | 8.4.24  | Anonymous Messaging    | TBD                | TBD              | TBD              |
| 26 | 4: ORAM | 10.4.24  | Anonymous Messaging    | TBD                | TBD              | TBD              |
| 27 | 5: Application | 15.4.24  | Anonymous Messaging    | TBD                | TBD              | TBD              |
| 28 | 5: Application | 17.4.24  | Anonymous Messaging    | TBD                | TBD              | TBD              |

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
