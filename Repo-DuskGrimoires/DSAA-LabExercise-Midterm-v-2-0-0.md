<!-- <p align="center"><img src="/md_assets/octocat.gif" alt="Logo" width="130" height="130"></p> -->
<h3 align="center">DuskGrimoires</h3>
<p align="center"><em>Good 'old Java library/source codes that I've coded and used for lecturing CS/IT subjects and topics</em></p>
<p align="center"><strong>You like the Repo? Don't forget to 🌟, 👁️, 🔱 and ❤️!</strong></p>
<p align="center">
   <img src="https://img.shields.io/badge/Purpose-EDUCATION/LEARNING-%2300416a?logoColor=white&labelColor=%2300416a&color=%2324292e&textColor=white" alt="Purpose-EDUCATION/LEARNING">
   <img src="https://img.shields.io/badge/Version-2.1.1-%2300416a?logoColor=white&labelColor=%2300416a&color=%2324292e&textColor=white" alt="Version 2.1.1">
   <img src="https://img.shields.io/badge/Lang-Java%2022.0.2-%2300416a?logoColor=white&labelColor=%2300416a&color=%2324292e&textColor=white" alt="Lang-Java 22.0.2">
   <img src="https://img.shields.io/badge/Contribute-OPEN-%2300416a?logoColor=white&labelColor=%2300416a&color=%2324292e&textColor=white" alt="Contribute-OPEN">
   <img src="https://img.shields.io/badge/License-MIT-%2300416a?logoColor=white&labelColor=%2300416a&color=%2324292e&textColor=white" alt="License MIT">
   <img src="https://img.shields.io/badge/Last%20Update-14.09.2024-%2300416a?logoColor=white&labelColor=%2300416a&color=%2324292e&textColor=white" alt="Last Update 14.09.2024">
   <a href="https://ko-fi.com/thenocturnaldevgypsy">
      <img src="https://img.shields.io/badge/Support%20me%20via%20Ko--Fi-%2300416a?logo=ko-fi&logoColor=white&color=%2300416a&textColor=white" alt="Support me via Ko-Fi">
   </a>
</p>

## ![SECTION Documentation](https://img.shields.io/badge/📚-Documentation-%2300416a?logoColor=white&labelColor=%2300416a&color=%2324292e&textColor=white)

#### 📖 Contents and Breakdown > Under Data Structures and Algorithm Analysis > All Activities under Midterm Period
Back to [Main](README.md)

👨‍🏫 **Demo** 
1. Demo # 1: Linked List (Demo_LinkedList.java)

🏃 **Exercises (conditions and expected output)**
1. Exercise # 1: Linked List - Linear Search (Midterm_Exercise1_LinkedList_LinearSearch.java)
```
Create a Java program with the following requirements/output:

Enter name to be added in our Linked List: Anna
Add new record to our linked list [1-Yes|0-No] ? 1
Enter name to be added in our Linked List: Karen
Add new record to our linked list [1-Yes|0-No] ? 1
Enter name to be added in our Linked List: Nina
Add new record to our linked list [1-Yes|0-No] ? 0

Let's show the records stored in our linked list [Anna, Karen, Nina]

Type in the name that you want to search: Karen
> Is [0]: Anna == Karen? FALSE
> Is [1]: Karen == Karen? TRUE, stored at [1]
```
2. Exercise # 2: Linked List - Reversed Linear Search (Midterm_Exercise2_LinkedList_ReversedLinearSearch.java)
```
Create a Java program with the following requirements/output:

Enter name to be added in our Linked List: Anna
Add new record to our linked list [1-Yes|0-No] ? 1
Enter name to be added in our Linked List: Karen
Add new record to our linked list [1-Yes|0-No] ? 1
Enter name to be added in our Linked List: Nina
Add new record to our linked list [1-Yes|0-No] ? 0

Let's show the records stored in our linked list [Anna, Karen, Nina]

Type in the name that you want to search: Anna
> Is [2]: Nina == Anna? FALSE
> Is [1]: Karen == Anna? FALSE
> Is [0]: Anna == Anna? TRUE, stored at [1]
```
3. Exercise # 3: One Dimensional Array - Queue (Midterm_Exercise3_OneDimArray_Queue.java)
```
Create a Java program (REQUIREMENT: Use a one dimensional array for storing the information) with the following requirements/output:

This program will demonstrate how to represent Queue in One-Dimensional Array.

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 1

ENQUEUE [0]: abby
abby Enqueued at [0]

= Current content of the Queue =
[2] :  
[1] :  
[0] : abby

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 1

ENQUEUE [1]: jeff
jeff Enqueued at [1]

= Current content of the Queue =
[2] :  
[1] : jeff
[0] : abby

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 1

ENQUEUE [2]: jacob
jacob Enqueued at [2]

= Current content of the Queue =
[2] : jacob
[1] : jeff
[0] : abby

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 3
PEEK: abby

= Current content of the Queue =
[2] : jacob
[1] : jeff
[0] : abby

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 2

DEQUEUE [abby]

= Current content of the Queue =
[2] :  
[1] : jacob
[0] : jeff

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 2

DEQUEUE [jeff]

= Current content of the Queue =
[2] :  
[1] :  
[0] : jacob

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 2

DEQUEUE [jacob]

= Current content of the Queue =
[2] :  
[1] :  
[0] :  

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 4

= Current content of the Queue =
[2] :  
[1] :  
[0] :  

Process completed.
```
4. Exercise # 4: Linked List - Queue (Midterm_Exercise4_LinkedList_Queue.java)
```
Create a Java program (REQUIREMENT: Use a linked list for storing the information) with the following requirements/output:

This program will demonstrate how to represent Queue in Linked List.

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 1

ENQUEUE [0]: abby
abby Enqueued at [0]

Current content of the Queue [abby]

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 1

ENQUEUE [1]: jeff
jeff Enqueued at [1]

Current content of the Queue [abby, jeff]

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 1

ENQUEUE [2]: jacob
jacob Enqueued at [2]

Current content of the Queue [abby, jeff, jacob]

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 3

PEEK: abby

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 2

DEQUEUE [abby]

Current content of the Queue [jeff, jacob]

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 2

DEQUEUE [jeff]

Current content of the Queue [jacob]

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 2

DEQUEUE [jacob]

Current content of the Queue []

What do you want to do [1-Enqueue|2-Dequeue|3-Peek|4-Quit]? 4

Current content of the Queue []

Process completed.
```
5. Exercise # 5: Linked List - Data Manipulation (Midterm_Exercise5_LinkedList_DataManipulation.java)
```
Create a Java program with the following requirements/output:

Enter name to be added in our Linked List: Anna
Add new record to our linked list [1-Yes|0-No] ? 1
Enter name to be added in our Linked List: Karen
Add new record to our linked list [1-Yes|0-No] ? 1
Enter name to be added in our Linked List: Nina
Add new record to our linked list [1-Yes|0-No] ? 1
Enter name to be added in our Linked List: Paulo
Add new record to our linked list [1-Yes|0-No] ? 1
Enter name to be added in our Linked List: Renz
Add new record to our linked list [1-Yes|0-No] ? 0

Let's show the records stored in our linked list [Anna, Karen, Nina, Paulo, Renz]

Type in the name that you want to search: Karen
> Is [0]: Anna == Karen? FALSE
> Is [1]: Karen == Karen? TRUE, stored at [1]

What do you want to do [1-Update|2-Delete] ? 2

Updated records stored in our linked list [Anna, Nina, Paulo, Renz]

Type in the name that you want to search: Anna
> Is [0]: Anna == Anna? TRUE, stored at [0]

What do you want to do [1-Update|2-Delete] ? 1
New name to be stored: Kuracha

Updated records stored in our linked list [Kuracha, Nina, Paulo, Renz]

Condition: The program will only stop asking for the value to be searched and perform update/delete in the linked list if there is no more existing nodes (if all of the nodes are deleted).
```