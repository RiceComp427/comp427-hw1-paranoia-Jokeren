# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Keren Zhou

_Student NetID_: kz21

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: Documents
- Assumptions:
  - Some people want to steal secret, forge, or destroy documents stored in the law firm.
  - An IT manager has all the rights to operate, move, and close the IT system.
  - All the documents are stored in a database which is on a storage cluster which is physically safe. In other words, we have security guards to protect the cluster.
- Assets:
  - Important documents about sensitive legal, financial, or political matters. We need to ensure:
    1. Confidentiality. Some documents can only be visible be a particular group of people.
    2. Integrity. No one but the owners of the documents could make changes.
    3. Authenticity. Third parties are not able to forge the documents.
    4. Availability. The IT system always keeps a copy of every document, unless the owner requires to delete it.
  
- Threats:
  - People who want to steal their competitors' secret files.
  - People who want to forge the documents.
  - People who want to destroy the database.
  - Hackers who want to take files to make profits.
- Countermeasures:
  - Confidentiality and Integrity.
  
  We can isolate the system in a warehouse without internet connections, which costs a substantial amount of money, as we need to build or rent the warehouse. In addition, we only give some staff the right to access the IT system. The solution is relatively safe because hackers cannot attack the system through a virus or malicious software unless they enter the warehouse and transfer files to their disks. But the solution is vulnerable when hackers steal the tokens from the staff and know where the warehouse locates.
  
  - Authenticity.
  
  We can assign each document a uniform code bar that can only be read by machines in the law firm company, which requires high cost but is quite effective.
 
  - Availability. 
  
  To prevent the system from being destroyed, we distribute the system into several pieces and always keep a copy of each document. The solution can be quickly implemented and does not need high cost. However, it slows down the database access and updates time. For an access request, the system first locates which databases have the required data; for an update request, the copy of the document also needs to be updated.
  
## Problem 2
- Scenario: Grading
- Assumptions:
  - Some students may cheat.
  - An anti-cheating system could effectively detect similar answers.
- Assets:
  - The fairness of homework grading, which protects students who finish homework by themselves and punishes those which cheat.
- Threats:
  - Students who cheat by exchanging answers, copying from the web, or stealing other students' answers.
  - Students who bribe other TAs to obtain high scores.
- Countermeasures:
  - Buy an anti-cheating system to calculate the similarities among students and manually check those with high similarities. We punish cheating students by letting them fail. Because we only need to pay for the system once, the solution is both money saving and useful. However, as far as I know, only very few systems can identify answers copied from the web.
  - Swap each TA's homework to check if the scores are reasonable. In this way, we could prevent the bribing phenomenon to some extent.
  - Let the teacher of the course examine every student's homework, which costs a significant amount of time.
  
## Problem 3
- Scenario: When we park our cars in a public parking garage or an oil station, we need to prevent our assets in the vehicle from being stolen.
- Assumptions:
  - The public parking garage or oil station is not safe.
  - We have plenty of assets in the car.
- Assets:
  - Personal assets such as phones, laptops, credit cards, etc.
- Threats:
  - Thieves who have utilities to break into the car and grab assets.
- Countermeasures:
  - We can put large bags in the back trunk and bring phones and credit cards with us. The solution does not take any cost, while it is not safe at all if the thieves steal our keys or break our trunks.
  - We can upgrade car windows to be more hard and anti-theft, which is promising but requires some money.
  - Always avoid free parking garage and instead pay for garages that have security guards. 
