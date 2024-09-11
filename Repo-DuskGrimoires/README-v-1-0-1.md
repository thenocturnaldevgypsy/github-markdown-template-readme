## DuskGrimoires: good 'old Java library/source codes that I've coded and used for lecturing CS/IT subjects and topics

> [!NOTE]
> `DuskGrimoires` is an old library that contains Java source codes I've coded and used during my career as Assistant Professor for BSCS, BSIT and BSCOE way back late 2012 to 2015. If you want to ask some questions and provide feedback, feel free to start a discussion or an issue, I'll try my best to answer.

> [!IMPORTANT]
> *I've created this repo as a reminder to myself that Java was one of the programming languages I got **heavily** exposed when I was teaching in College/University. It's also a good way to refresh my Java, GitHub and Markdown skills. And just a reminder, the codes here were initially made way back 2012 and been updated regularly until 2015. So I only did some **best effort** to make sure that the codes that are in this repo can be compiled and can be read thru by users.*

If you find this repo helpful, please don't forget to `star` to keep yourself updated at GitHub, also, maybe `buy me a coffee` at Ko-Fi?

### Updates/Progress

- **06/09/2024**
   - Recreated repo from `duskgrimoire-java-lab-exercises` to `duskgrimoires-java-lab-exercises`
   - Continued separating source codes per subject / topic via subdirectory.
      - Renamed subdirectory `data-structure-algorithm-analysis` to `datastructurealgorithmanalysis`
         - Created `DataStrucAlgoAnalysis.java` to serve as the Table of Contents for the Apps under `Data Structure and Algorithm Analysis`
      - Created subdirectory `programmingessentialsoop`
         - Created `ProgEssentialsOOP.java` to serve as the Table of Contents for the Apps under `Programming Essentials to OOP`
      - Updated `App.java` to serve as the Table of Contents for the overall App.

- **01/09/2024**
   - Started separating source codes per subject / topic via subdirectory. Created `data-structure-algorithm-analysis`
    
- **29/08/2024**
   - Cloned the original repo `java-labcodes-exercises-dsaa` to the new repo `duskgrimoires-java-lab-exercises` for public viewing purposes.

- **07/05 to 08/05, 2024**
   - 08/05 7:00 AM [GMT+7/Hanoi] : Done with updating all renamed classes, noticed that `Prefinal_Exercise1_Trees.java` has incomplete codes. Will be looking for my backup (or just rewrite it) and I'll upload it in this repo soon.
   - 07/05 10:42 PM [GMT+7/Hanoi] : Tried pulling the repo to my local unit using VS Code, need to retweak `App.java`, especially if some users wanted to try it out and won't get confused with the menu, reuploaded all required folders and source codes.
   - 07/05 3:15 PM [GMT+7/Hanoi] : Created `java-labcodes-exercises-dsaa` GitHub `public` repository, added MIT License, and uploaded the original Java codes that I've used way back 2012.

### Folder Structure, IDE and JDK Used

The workspace contains two folders by default, where:

- `datastructurealgorithmanalysis`: the folder that contains the source codes of the programs I've coded for `Data Structure and Algorithm Analysis`
- `programmingessentialsoop`: the folder that contains the source codes of the programs I've coded for `Programming Essentials to OOP`

I am currently using `VSCode Version: 1.89.0 (Universal)` as my IDE with the JDK below
```
OpenJDK version "21.0.3" 2024-04-16 LTS
OpenJDK Runtime Environment Temurin-21.0.3+9 (build 21.0.3+9-LTS)
OpenJDK 64-Bit Server VM Temurin-21.0.3+9 (build 21.0.3+9-LTS, mixed mode)
```

## Contents and Breakdown
- [Under Data Structures and Algorithm Analysis](#under-data-structures-and-algorithm-analysis)
   - [All Activities under Prelim Period](#all-activities-under-prelim-period)
      - Demo
      - Exercises (conditions and expected output)
   - [All Activities under Midterm Period](#all-activities-under-midterm-period)
      - Demo
      - Exercises (conditions and expected output)
   - [All Activities under Pre-finals Period](#all-activities-under-pre-finals-period)
      - Exercises (conditions and expected output)
   - [All Activities under Finals Period](#all-activities-under-finals-period)
      - Exercises (conditions and expected output)

### Under Data Structures and Algorithm Analysis
#### All Activities under Prelim Period
**Demo**
1. Demo # 1: One Dimensional Array (Demo_OneDimArray.java)
2. Demo # 2: One Dimensional Array - Debug (Demo_OneDimArray_Debug)
3. Demo # 3: One Dimensional Array - Input (Demo_OneDimArray_Input.java)
4. Demo # 4: Two Dimensional Array (Demo_TwoDimArray.java)
5. Demo # 5: Two Dimensional Array - String (Demo_TwoDimArray_String.java)
6. Demo # 6: Two Dimensional Array - Storing (Demo_TwoDimArray_Storing.java)
7. Demo # 7: Method (Demo_Method.java)
8. Demo # 8: Method - Return (Demo_Method_Return.java)
9. Demo # 9: Method - Void (Demo_Method_Void.java)
10. Demo # 10: Stack (Demo_Stack.java)
11. Demo # 11: String - Reversed Word (Demo_String_ReverseWord.java)
12. Demo # 12: Stack - Decimal To Binary (Demo_Stack_DecToBin.java)

**Exercises (conditions and expected output)**
1. Exercise # 1: Java Refresher (Prelim_Exercise1_JavaRefresher.java)
```
Create a Java Program with the following output:

Hi, what's your name: <name>
Hello <name>, nice to meet you, how old are you? <age>
-  If 20 and above: Eww, too old...
-  Else: So young
Give me anumber at mag-mamagic ako: <number> e.g. 4
Magic Box:
****
****
****
****
Isa pa, magic tatsulok!
*
**
***
****
Kaya mo pa? <oo/yes> or <hinde/no>
-  Yes/Oo: Good
-  No/Hindi: Gutom lang yan.
Nice meeting you <name>, sa uulitin!
```
2. Exercise # 2: One Dimensional Array - Minimum, Maximum, Average (Prelim_Exercise2_OneDimArray_MinMaxAve.java)
```
Create a Java Program with the following requirements:

1. Create a One/Single Dimensional Array for storing ten (10) whole numbers
(integer)

int[] minmaxave = new int[10];

2. Prompt the user to enter ten (10) whole numbers. Those numbers must be stored
in the array minmaxave.

Ex.

Enter a number: 1
Enter a number: 2
Enter a number: 3
Enter a number: 4
Enter a number: 5
Enter a number: 6
Enter a number: 7
Enter a number: 8
Enter a number: 9
Enter a number: 10

3. After inputting the ten (10) numbers, display the minimum (lowest number),
maximum (highest number) and the average (add all the elements of your array,
then divide to the number of elements (ex. 1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9 +
10 = 55 / 10 = 5.5 is the average))

Ex.

The minimum is 1
The maximum is 10
The average is 5.5
```
3. Exercise # 3: Two Dimensional Array - Minimum, Maximum, Average (Prelim_Exercise3_TwoDimArray_MinMaxAve.java)
```
Create a Java Program with the following requirements:

1. Create a Two Dimensional Array  with size [4][4], allowing to store sixteen (16) whole numbers (integer)

int[][] minmaxave = new int[4][4];

2. Prompt the user to enter sixteen (16) whole numbers. Those numbers must be stored in the array minmaxave. You must also display the index address while asking for a value:

Ex.

Enter a number [0][0]: 1
Enter a number [0][1]: 1
Enter a number [0][2]: 1
Enter a number [0][3]: 1
Enter a number [1][0]: 1
Enter a number [1][1]: 1
Enter a number [1][2]: 100
Enter a number [1][3]: 1
Enter a number [2][0]: 1
Enter a number [2][1]: 1
Enter a number [2][2]: 1
Enter a number [2][3]: 1
Enter a number [3][0]: 0
Enter a number [3][1]: 1
Enter a number [3][2]: 1
Enter a number [3][3]: 1

3. After inputting sixteen (16) numbers, display the minimum (lowest number), maximum (highest number) and the average (add all the elements of your array, then divide to the number of elements (ex. 1 + 1 + 1 + 1 + 1 + 1 +100 + 1 + 1 + 1 + 1 + 1 + 0 + 1 + 1 + 1 = 114 / 16 = 7 is the average)). For the minimum and maximum, you must display the array index of the value's location.

Ex.

The minimum is 0, stored at [3][0]
The maximum is 100, stored at [1][2]
The average is 7.0
```
4. Exercise # 4: Arrays - Faculty Listing, Type, Rate and Salary (Prelim_Exercise4_FacultyPayslip.java)
```
Create a Java program with the following requirements:

1. Your program should have the 3 following single/one dimensional array:

String[] facultyname = new String[5];
String[] facultytype = new String[5];
double[] facultyrate = new double[5];

2. The user will be prompted to enter five (5) faculty records.

Example:

Faculty Name: Abby Nucup
Faculty Type (FT=Full Time/PT=Part Time): FT
Faculty Rate: 150.00

Make sure that the following information must be stored to their respective arrays.

Faculty Name must be stored in facultyname 
Faculty Type must be stored in facultytype
Faculty Rate must be stored in facultyrate

3. After inputting and storing the five records, the program will ask for the array index number of the record he/she want to use. Note that the only allowed numbers to be inputted must range from 0 to 4. Numbers 5 and above are no longer allowed. If the is valid, you must get/retrieve the name and type information stored in the respective array element using the index as tracker.

Example:

Enter record number: 5
Invalid number!
Enter record number: 3

Faculty Name: Nicanor Gustavo
Faculty Type: FT

4. After retrieving the information, the user must input either the number of hours or day. If the faculty is a FT (Full Time), then it should ask for the "Number of Days". If the faculty is a PT (Part Time), then it should ask for the "Number of Hours".

Ex. if FT:

Enter Number of Days: 5

Ex. if PT:

Enter Number of Hours: 8

5. For computing the salary, you must use the following formulas:

FT Formula:

salary = (facultyrate x 8 hours) x Number of Days

double salary = (facultyrate[index] * 8) * numberinputted

PT:

salary = facultyrate x Number of Hours

double salary = facultyrate[index] * numberinputted

6. After inputting the salary, the final output should be:

=For FT=

Salary Report
Faculty Name: Nicanor Gustavo
Faculty Type: FT
Rate: 150.00
Number of Days: 10
Salary: 12,000.00

=For PT=

Salary Report
Faculty Name: Nicanor Gustavo
Faculty Type: PT
Rate: 150.00
Number of Hours: 10
Salary: 1,500.00
```
5. Exercise # 5: Arrays - BubbleSort (Prelim_Exercise5_BubbleSort.java)
```
Output:

Enter number 1: 1
Enter number 2: 10
Enter number 3: 2
Enter number 4: 9
Enter number 5: 3
Enter number 6: 8
Enter number 7: 4
Enter number 8: 7
Enter number 9: 5
Enter number 10: 6

Display unsorted list: 1 10 2 9 3 8 4 7 5 6 

Simulation using Bubble Sort. Start.

[0] 1 > [1] 10 ? FALSE. No swap.
[1] 10 > [2] 2 ? TRUE. Swap 10 and 2.
[2] 10 > [3] 9 ? TRUE. Swap 10 and 9.
[3] 10 > [4] 3 ? TRUE. Swap 10 and 3.
[4] 10 > [5] 8 ? TRUE. Swap 10 and 8.
[5] 10 > [6] 4 ? TRUE. Swap 10 and 4.
[6] 10 > [7] 7 ? TRUE. Swap 10 and 7.
[7] 10 > [8] 5 ? TRUE. Swap 10 and 5.
[8] 10 > [9] 6 ? TRUE. Swap 10 and 6.
Reached the end of the list. Swap > 0? TRUE. Repeat process.

[0] 1 > [1] 2 ? FALSE. No swap.
[1] 2 > [2] 9 ? FALSE. No swap.
[2] 9 > [3] 3 ? TRUE. Swap 9 and 3.
[3] 9 > [4] 8 ? TRUE. Swap 9 and 8.
[4] 9 > [5] 4 ? TRUE. Swap 9 and 4.
[5] 9 > [6] 7 ? TRUE. Swap 9 and 7.
[6] 9 > [7] 5 ? TRUE. Swap 9 and 5.
[7] 9 > [8] 6 ? TRUE. Swap 9 and 6.
[8] 9 > [9] 10 ? FALSE. No swap.
Reached the end of the list. Swap > 0? TRUE. Repeat process.

[0] 1 > [1] 2 ? FALSE. No swap.
[1] 2 > [2] 3 ? FALSE. No swap.
[2] 3 > [3] 8 ? FALSE. No swap.
[3] 8 > [4] 4 ? TRUE. Swap 8 and 4.
[4] 8 > [5] 7 ? TRUE. Swap 8 and 7.
[5] 8 > [6] 5 ? TRUE. Swap 8 and 5.
[6] 8 > [7] 6 ? TRUE. Swap 8 and 6.
[7] 8 > [8] 9 ? FALSE. No swap.
[8] 9 > [9] 10 ? FALSE. No swap.
Reached the end of the list. Swap > 0? TRUE. Repeat process.

[0] 1 > [1] 2 ? FALSE. No swap.
[1] 2 > [2] 3 ? FALSE. No swap.
[2] 3 > [3] 4 ? FALSE. No swap.
[3] 4 > [4] 7 ? FALSE. No swap.
[4] 7 > [5] 5 ? TRUE. Swap 7 and 5.
[5] 7 > [6] 6 ? TRUE. Swap 7 and 6.
[6] 7 > [7] 8 ? FALSE. No swap.
[7] 8 > [8] 9 ? FALSE. No swap.
[8] 9 > [9] 10 ? FALSE. No swap.
Reached the end of the list. Swap > 0? TRUE. Repeat process.

[0] 1 > [1] 2 ? FALSE. No swap.
[1] 2 > [2] 3 ? FALSE. No swap.
[2] 3 > [3] 4 ? FALSE. No swap.
[3] 4 > [4] 5 ? FALSE. No swap.
[4] 5 > [5] 6 ? FALSE. No swap.
[5] 6 > [6] 7 ? FALSE. No swap.
[6] 7 > [7] 8 ? FALSE. No swap.
[7] 8 > [8] 9 ? FALSE. No swap.
[8] 9 > [9] 10 ? FALSE. No swap.
Reached the end of the list. Swap > 0? FALSE. Process complete.

Display sorted list: 1 2 3 4 5 6 7 8 9 10
```
6. Exercise # 6: Arrays - Linear Binary Search (Prelim_Exercise6_LinearBinarySearch.java)
```
Create a Java program with the following requirements:

1. You must ask the user for the size of the array. Note that you must use one/single dimensional array and the size of your array is dynamic.

Enter the size of the array: 5

2. Ask the user to enter a whole X times. X is based on the size of your array defined by your user. You must also show the array index while asking for a value.

Enter value for [0] : 
1
Enter value for [1] : 3
Enter value for [2] : 6
Enter value for [3] : 2
Enter value for [4] : 8

3. Ask the user for the target value for searching. Note that the user can input any number, even it does not belong to the elements stored in the array.

Enter the target values to be searched: 6

4. Let the user choose if he/she want to use linear or binary searching. Note that just in case that the user typed in an invalid input, the program must be notify and asked for an input again.

[1] Linear Search | [2] Binary Search
Choose the searching algorithm to be used [1 or 2]: 4
Invalid input! Choose the searching algorithm to be used [1 or 2]: 2

5. When the user typed in a valid input. You must show the simulation for each searching algorithm. Your out must look like the following sample outputs below:

*for Linear Searching*

You choose Linear Searching

- Is array[0] : 
1 == 6? FALSE
- Is array[1] : 3 == 6? FALSE
- Is array[2] : 6 == 6? TRUE, stored at [2]

*for Binary Searching*

You choose Binary Searching

Let us sort the array first
[0][1][2][3][4]
[1][2][3][6][8]
Done sorting

middle = [0 + 4 = 4 / 2 = 2] = 2
- Is array[2] : 
3 <, >, =  6? <, FALSE
middle = [3 + 4 = 7 / 2 = 3.5] = 4
- Is array[4] : 8 <, >, =  6? >, FALSE
middle = [3 + 3 = 6 / 2 = 3] = 3
- Is array[3] : 6 <, >, =  6? =, TRUE, stored at [3]
```
7. Exercise # 7: Arrays - InsertionSort and SelectionSort (Prelim_Exercise7_InsertionSortSelectionSort.java)
```
Create a Java program with the following requirements/0utput:

Enter number 1: 3
Enter number 2: 2
Enter number 3: 0
Enter number 4: 9
Enter number 5: 1
Enter number 6: 4
Enter number 7: 7
Enter number 8: 8
Enter number 9: 5
Enter number 10: 6

Display unsorted list: 3 2 0 9 1 4 7 8 5 6 

[1] Insertion Sort | [2] Selection Sort

Choose which sort algorithm to be used: 4
Invalid Input! Choose which sort algorithm to be used: 7
Invalid Input! Choose which sort algorithm to be used: 

== IF 1 or INSERTION SORT ==

You choose Insertion Sort.

Insert 2
[1]: 2 < [0]: 3 ? TRUE. Shift 3, insert 2.
Current sorted list: 2 3 

Insert 0
[2]: 0 < [1]: 3 ? TRUE. Shift 3, insert 0.
[1]: 0 < [0]: 2 ? TRUE. Shift 2, insert 0.
Current sorted list: 0 2 3 

Insert 9
[3]: 9 < [2]: 3 ? FALSE. Location OK.
Current sorted list: 0 2 3 9 

Insert 1
[4]: 1 < [3]: 9 ? TRUE. Shift 9, insert 1.
[3]: 1 < [2]: 3 ? TRUE. Shift 3, insert 1.
[2]: 1 < [1]: 2 ? TRUE. Shift 2, insert 1.
[1]: 1 < [0]: 0 ? FALSE. Location OK.
Current sorted list: 0 1 2 3 9 

Insert 4
[5]: 4 < [4]: 9 ? TRUE. Shift 9, insert 4.
[4]: 4 < [3]: 3 ? FALSE. Location OK.
Current sorted list: 0 1 2 3 4 9 

Insert 7
[6]: 7 < [5]: 9 ? TRUE. Shift 9, insert 7.
[5]: 7 < [4]: 4 ? FALSE. Location OK.
Current sorted list: 0 1 2 3 4 7 9 

Insert 8
[7]: 8 < [6]: 9 ? TRUE. Shift 9, insert 8.
[6]: 8 < [5]: 7 ? FALSE. Location OK.
Current sorted list: 0 1 2 3 4 7 8 9 

Insert 5
[8]: 5 < [7]: 9 ? TRUE. Shift 9, insert 5.
[7]: 5 < [6]: 8 ? TRUE. Shift 8, insert 5.
[6]: 5 < [5]: 7 ? TRUE. Shift 7, insert 5.
[5]: 5 < [4]: 4 ? FALSE. Location OK.
Current sorted list: 0 1 2 3 4 5 7 8 9 

Insert 6
[9]: 6 < [8]: 9 ? TRUE. Shift 9, insert 6.
[8]: 6 < [7]: 8 ? TRUE. Shift 8, insert 6.
[7]: 6 < [6]: 7 ? TRUE. Shift 7, insert 6.
[6]: 6 < [5]: 5 ? FALSE. Location OK.

Display sorted list: 0 1 2 3 4 5 6 7 8 9

== IF 2 or SELECTION SORT ==

You choose Selection Sort.

Current Minimum for [0]: 3. Look for a possible new minimum.
[0]: 3 > [1]: 2 ? TRUE. Change new current minimum from 3 to 2. Search the list again.
[1]: 2 > [2]: 0 ? TRUE. Change new current minimum from 2 to 0. Search the list again.
[2]: 0 > [3]: 9 ? FALSE. Current minimum 0 retain.
[2]: 0 > [4]: 1 ? FALSE. Current minimum 0 retain.
[2]: 0 > [5]: 4 ? FALSE. Current minimum 0 retain.
[2]: 0 > [6]: 7 ? FALSE. Current minimum 0 retain.
[2]: 0 > [7]: 8 ? FALSE. Current minimum 0 retain.
[2]: 0 > [8]: 5 ? FALSE. Current minimum 0 retain.
[2]: 0 > [9]: 6 ? FALSE. Current minimum 0 retain.
Reached the end of the list. Found new minimum. Swap [0]: 3 with [2]: 0.

Current Minimum for [1]: 2. Look for a possible new minimum.
[1]: 2 > [2]: 3 ? FALSE. Current minimum 2 retain.
[1]: 2 > [3]: 9 ? FALSE. Current minimum 2 retain.
[1]: 2 > [4]: 1 ? TRUE. Change new current minimum from 2 to 1. Search the list again.
[4]: 1 > [5]: 4 ? FALSE. Current minimum 1 retain.
[4]: 1 > [6]: 7 ? FALSE. Current minimum 1 retain.
[4]: 1 > [7]: 8 ? FALSE. Current minimum 1 retain.
[4]: 1 > [8]: 5 ? FALSE. Current minimum 1 retain.
[4]: 1 > [9]: 6 ? FALSE. Current minimum 1 retain.
Reached the end of the list. Found new minimum. Swap [1]: 2 with [4]: 1.

Current Minimum for [2]: 3. Look for a possible new minimum.
[2]: 3 > [3]: 9 ? FALSE. Current minimum 3 retain.
[2]: 3 > [4]: 2 ? TRUE. Change new current minimum from 3 to 2. Search the list again.
[4]: 2 > [5]: 4 ? FALSE. Current minimum 2 retain.
[4]: 2 > [6]: 7 ? FALSE. Current minimum 2 retain.
[4]: 2 > [7]: 8 ? FALSE. Current minimum 2 retain.
[4]: 2 > [8]: 5 ? FALSE. Current minimum 2 retain.
[4]: 2 > [9]: 6 ? FALSE. Current minimum 2 retain.
Reached the end of the list. Found new minimum. Swap [2]: 3 with [4]: 2.

Current Minimum for [3]: 9. Look for a possible new minimum.
[3]: 9 > [4]: 3 ? TRUE. Change new current minimum from 9 to 3. Search the list again.
[4]: 3 > [5]: 4 ? FALSE. Current minimum 3 retain.
[4]: 3 > [6]: 7 ? FALSE. Current minimum 3 retain.
[4]: 3 > [7]: 8 ? FALSE. Current minimum 3 retain.
[4]: 3 > [8]: 5 ? FALSE. Current minimum 3 retain.
[4]: 3 > [9]: 6 ? FALSE. Current minimum 3 retain.
Reached the end of the list. Found new minimum. Swap [3]: 9 with [4]: 3.

Current Minimum for [4]: 9. Look for a possible new minimum.
[4]: 9 > [5]: 4 ? TRUE. Change new current minimum from 9 to 4. Search the list again.
[5]: 4 > [6]: 7 ? FALSE. Current minimum 4 retain.
[5]: 4 > [7]: 8 ? FALSE. Current minimum 4 retain.
[5]: 4 > [8]: 5 ? FALSE. Current minimum 4 retain.
[5]: 4 > [9]: 6 ? FALSE. Current minimum 4 retain.
Reached the end of the list. Found new minimum. Swap [4]: 9 with [5]: 4.

Current Minimum for [5]: 9. Look for a possible new minimum.
[5]: 9 > [6]: 7 ? TRUE. Change new current minimum from 9 to 7. Search the list again.
[6]: 7 > [7]: 8 ? FALSE. Current minimum 7 retain.
[6]: 7 > [8]: 5 ? TRUE. Change new current minimum from 7 to 5. Search the list again.
[8]: 5 > [9]: 6 ? FALSE. Current minimum 5 retain.
Reached the end of the list. Found new minimum. Swap [5]: 9 with [8]: 5.

Current Minimum for [6]: 7. Look for a possible new minimum.
[6]: 7 > [7]: 8 ? FALSE. Current minimum 7 retain.
[6]: 7 > [8]: 9 ? FALSE. Current minimum 7 retain.
[6]: 7 > [9]: 6 ? TRUE. Change new current minimum from 7 to 6. Search the list again.
Reached the end of the list. Found new minimum. Swap [6]: 7 with [9]: 6.

Current Minimum for [7]: 8. Look for a possible new minimum.
[7]: 8 > [8]: 9 ? FALSE. Current minimum 8 retain.
[7]: 8 > [9]: 7 ? TRUE. Change new current minimum from 8 to 7. Search the list again.
Reached the end of the list. Found new minimum. Swap [7]: 8 with [9]: 7.

Current Minimum for [8]: 9. Look for a possible new minimum.
[8]: 9 > [9]: 8 ? TRUE. Change new current minimum from 9 to 8. Search the list again.
Reached the end of the list. Found new minimum. Swap [8]: 9 with [9]: 8.

Display sorted list: 0 1 2 3 4 5 6 7 8 9 
```
8. Exercise # 8: Method - Operations (Prelim_Exercise8_Method_Operations.java)
```
Create a Java Program based on the output below:

Enter 2 numbers
7
3

7 + 3 = 10
7 - 3 = 4
7 x 3 = 21
7 / 3 = 2.0

Condition: Each operation (addition, subtraction, multiplication and division) must be coded and perfomed in separate methods, meaning you must have one void main and four methods in your program (one java method for addition, one java method for subtraction, one java method for multiplication and one java method for division).
```
9. Exercise # 9: Method - Factorial (Prelim_Exercise9_Method_Factorial.java)
```
Create a Java Program based on the output below:

Enter a number: 7
The factorial of 7 is 5040
 
Condition: The computation of the factorial must be coded and perfomed in a method, meaning you must have one void main and one method in your program (one java method for the factorial).
```
10. Exercise # 10: Method - TriangularNumber (Prelim_Exercise10_Method_TriangularNumber.java)
```
Create a Java program with the following requirements/output:

Enter a number: 6

*
**
***
****
*****
******

The triangular number of 6 is 21.

Condition: The generation of the asterisk and computing the triangular number must be coded and perfomed in methods, meaning you must have one void main and two methods in your program (one java method for generating the asterisk of the triangular number and one method for computing the triangular number).
```
11. Exercise # 11: Stack - Reversed Word (Prelim_Exercise11_Stack_ReverseWord.java)
```
Create a Java program with the following requirements/output:

Enter a word: TIME
Reversed Word: EMIT

Condition: You must use stack and the .push() and .pop() methods in this program.
```
12. Exercise # 12: Stack - Leave Bracket Alone (Prelim_Exercise12_Stack_Brackets.java)
```
Create a Java program with the following requirements/output:

Enter a string statement, make sure to include { and } in it: fg{{}][ds{}}ksa123{{{}
Trimmed statement: {{}{}}{{{}

Condition: You must use stack and the .push() and .pop() methods in this program.
```
13. Exercise # 13: Stack - Decimal Conversion (Prelim_Exercise13_DecimalConversion.java)
```
Create a Java program with the following requirements/output:

Enter a decimal number: 10
Binary: 1010
Octal: 12
Hexadecimal: A

Condition: You must use stack and the .push() and .pop() methods in this program. You must have a separate method for the following:

- from Decimal to Binary
- from Decimal to Octal
- from Decimal to Hexadecimal

This means you have one static void main and three customed methods in your program.
```

### All Activities under Midterm Period
**Demo**
1. Demo # 1: Linked List (Demo_LinkedList.java)

**Exercises (conditions and expected output)**
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

### All Activities under Pre-finals Period
**Exercises (conditions and expected output)**
1. Exercise # 1: Trees (Prefinal_Exercise1_Trees.java)
```
Create a Java program with the following requirements: 

REQUIREMENTS: use one dimensional array for storing the values in the tree. Note of the assigned array index for each level:
 
int[] array = new int[15]; 

Level 1: array[0]
Level 2: array[1], array[2]
Level 3: array[3], array[4], array[5], array[6]
level 4: array[7], array[8], array[9], array[10], array[11], array[12], array[13], array[14]

Skip the delete option at the moment.
 

Output:

Current nodes of the tree:

*show the updated triangular shape of the tree here*

[1-Insert|2-Find|3-Delete|4-Inorder Traversal|5-Preorder Traversal|6-Postorder Traversal|7-Quit]
What do you want to do? 1

Value to be inserted: 45

Current nodes of the tree:

*show the updated triangular shape of the tree here*

[1-Insert|2-Find|3-Delete|4-Inorder Traversal|5-Preorder Traversal|6-Postorder Traversal|7-Quit]
What do you want to do? 2

Search for: 45

45 is stored at Level 3.

[1-Insert|2-Find|3-Delete|4-Inorder Traversal|5-Preorder Traversal|6-Postorder Traversal|7-Quit]
What do you want to do? 4

Inorder Traversal: 30 40 45 50 55 60 80

[1-Insert|2-Find|3-Delete|4-Inorder Traversal|5-Preorder Traversal|6-Postorder Traversal|7-Quit]
What do you want to do? 5

Preorder Traversal: 50 40 30 45 60 55 80

[1-Insert|2-Find|3-Delete|4-Inorder Traversal|5-Preorder Traversal|6-Postorder Traversal|7-Quit]
What do you want to do? 6

Postorder Traversal: 30 45 40 55 80 60 50

[1-Insert|2-Find|3-Delete|4-Inorder Traversal|5-Preorder Traversal|6-Postorder Traversal|7-Quit]
What do you want to do? 7

Current nodes of the tree:

*show the updated triangular shape of the tree here*

Process Complete.
```

### All Activities under Finals Period
**Exercises (conditions and expected output)**
1. Exercise # 1: N-sort (Finals_Exercise1_NSort.java)
```
Create a Java program with the following requirements: 

REQUIREMENTS:
- create a one dimensional array, the size will be based on the answer in the "Enter the number of values to be inserted". Example: if the user inputted 8, that means you must create a one dimensional array with the size of 8.
- prompt the user to input number (the number of input based on the answer in the "Enter the number of values to be inserted"). save the numbers inputted in your one dimensional arrray.
- ask the user for the required N-sort. please note of the two rules in N-sorting under shellsort: (1) zero (0) is not valid N and (2) it can only be ranging from one (1) up to the half of the inputted number of elements. so if the number of elements is 8, that means the valid N is ranging from 1 to 4 only.
- after the user inputted the valid value for N, display the numbers inputted earlier and stored in your one dimensional array.
- implement the shellsorting afterwards.

OUTPUT:

Enter the number of values to be inserted: 8

Type a number: 8
Type a number: 7
Type a number: 6
Type a number: 5
Type a number: 4
Type a number: 3
Type a number: 2
Type a number: 1

Enter the required N-sort: 7
The N is either less than or more than the required N sort value.

Enter the required N-sort: 0
The N is either less than or more than the required N sort value.

Enter the required N-sort: 4

Current content of the 4-sorted:

8  7  6  5  
4  3  2  1  

Sorted content of the 4-sorted:

4  3  2  1  
8  7  6  5
```
2. The End - Feedback to the Course (TheEnd_Feedback.java)
3. Exercise # 3: Compilation of all Programs (App.java)

<!-- ### Exercises under Prelim Period
**Demo Codes before Exercises**
1. Prelim_Method_Demo.java x
2. Prelim_Method_ReturnDemo.java x
3. Prelim_Method_VoidDemo.java x
4. Prelim_OneDimArray_Demo.java x
5. Prelim_OneDimArray_Input.java x
6. Prelim_OneDimArray_Debug.java x
7. Prelim_TwoDimArray_Demo.java x
8. Prelim_TwoDimArray_Storing.java x
9. Prelim_TwoDimArray_String.java x

**Individual Exercises Description and Filenames**
1. Prelim_Individual.java

2. Prelim_OneDimArray_MinMax.java

3. Prelim_TwoDimArray_MinMax.java

4. Prelim_BubbleSort.java

5. Prelim_Method_Operations.java

6. Prelim_Method_Factorial.java

7. Prelim_Method_TriangularNumber.java



**Group Exercises Description and Filenames**
1. Prelim_Array_FacRate.java

2. Prelim_LinearBinarySearch.java

3. Prelim_InsertionSortSelectionSort.java


### Exercises under Midterm Period
**Demo Codes before Exercises**
1. Midterm_Stack_Demo.java x
2. Midterm_String_ReversedWord.java x 
3. Midterm_Stack_DecToBin.java x
4. Midterm_LinkedList_Demo.java

**Individual Exercises Description and Filenames**
1. Midterm_Stack_ReversedWord.java x 

2. Midterm_Stack_DecimalConversion.java

3. Midterm_Stack_LeaveBracket.java

4. Midterm_LinkedList_LinearSearch.java

5. Midterm_LinkedList_ReversedLinearSearch.java

**Group Exercises Description and Filenames**
1. Midterm_LinkedList_DataManipulation.java


### Exercises under Prefinal Period
**Individual Exercises Description and Filenames**
1. Prefinal_OneDimArray_Queue.java

2. Prefinal_LinkedList_Queue.java


**Group Exercises Description and Filenames**
1. Prefinal_Trees.java


### Exercises under Final Period
**Individual Exercises Description and Filenames**
1. Finals_Shellsort.java


**Group Exercises Description and Filenames**
1. App.java
```
Create a Java program with the following requirements: 

REQUIREMENTS:

- link all of your works since Prelim to Finals in your program
- do not post programs that you or your group didn't created. if you were not able to create the program, just simply put (unable to finish) next to the name of the program

Here's the full list of the program listing (in order) way back Prelim to Finals:

PRELIM:

- LastnameFM_Section_Individual
- MinMaxAve
- MinMaxAveTwoDim
- BubbleSort
- MethodOperations
- MethodFactorial
- TriangularNumbers
- FacultyRate
- LinearBinarySearch
- InsertionSortSelectionSort

MIDTERM:

- Stack_ReversedWord2
- Stack_DecimalConversions
- Stack_TrimBrackets
- LinkedList_LinearSearch
- LinkedList_ReversedLinearSearch
- LinkedList_DataManipulation

PRE-FINAL:

- Queue_OneDimArray
- Queue_SinglyLinkedList
- Prefinals_Trees

FINALS:

- Finals_ShellSort


OUTPUT:

<Group Name> - Compilation of Works in Data Structures.

C - Juan dela Cruz
G - Nicanor Gustavo

Enter a choice [press 0 to go back to the main menu]: g

1 - Access all Prelim Activities
2 - Access all Midterm Activities
3 - Access all Pre-final Activities
4 - Access all Finals Activities
5 - Individual Summary Report for Data Structures and Alogorithm Analysis

Enter a choice [press 0 to exit program]: 1

Prelim Activities. What do you want to view?
I - Individual Works
G - Activities Groups

Enter a choice [press 0 to go back to the main menu]: I



Nicanor Gustavo's individual work for Prelim

1 - Gustavo_Individual
2 - Prelim_OneDimArray_MinMax

Enter a choice which program to run [press 0 to go back to the main menu]: 1

(Run the program to the same window. After running the program, return the user to the main menu)

<Group Name> - Compilation of Works in Data Structures.

1 - Access all Prelim Activities
2 - Access all Midterm Activities
3 - Access all Pre-final Activities
4 - Access all Finals Activities
5 - Individual Summary Report for Data Structures

Enter a choice [press 0 to exit program]: 1

Prelim Activities. What do you want to view?
I - Individual Works
G - Activities Groups

Enter a choice [press 0 to go back to the main menu]: G

<Group Name> activities for Prelim:
1 - FacultyRate
2 - LinearBinarySearch

Enter a choice which program to run [press 0 to go back to the main menu]: 1

(Run the program to the same window. After running the program, return the user to the main menu)
```
 -->