>   **SENG 637 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: Group Number      |
|-----------------|
| Ahmad Al Asad                |   
| Saad Zafar Khan              |   
<!-- | Student 3 name               |    -->
<!-- | Student 4 name                |    -->


**Table of Contents**
<!-- 
(When you finish writing, update the following list using right click, then
“Update Field”) -->

[1 Introduction](#_Toc439194677)

[2 High-level description of the exploratory testing plan](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was divided](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons learned](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself](#_Toc439194683)

# Introduction

This Assignment 1 involved testing for bugs in a software and writing a defect report. We conducted Exploratory testing and Scripted Testing on the [ATM System - Lab 1 Version 1.0.jar](https://github.com/seng637-winter2025/a1-ExGranite/blob/main/Assignment%201%20-%20artifacts/ATM%20System%20-%20Lab%201%20Version%201.0.jar) which was provided in the zip archive [seng637-a1-artifacts.zip](https://github.com/seng637-winter2025/a1-ExGranite/blob/main/seng637-a1-artifacts.zip).

We used [Atlassian Jira](https://www.atlassian.com/software/jira) as a tool for tracking the defects and bugs in our test. This better helped us collaborate as a team. Following the identification of defects, we performed regression testing on the updated version of the system, [ATM System - Lab 1 Version 1.1.jar](https://github.com/seng637-winter2025/a1-ExGranite/blob/main/Assignment%201%20-%20artifacts/ATM%20System%20-%20Lab%201%20Version%201.1.jar), and updated the reported issues accordingly.

Prior to this assignment, our knowledge of exploratory and scripted testing was minimal. Our experience was limited to non-structured testing, where we simply checked whether our programs worked as expected. This assignment provided us with valuable insights into structured testing methodologies, their differences, and their practical implications.

# High-level description of the exploratory testing plan

The exploratory testing approach focused on analyzing how users interact with an ATM system, identifying edge cases, and verifying system behavior under various conditions. Each of us tested both the versins following these key principles in our testing approach: Simulating typical user transactions at an ATM, including balance inquiries, cash deposits, withdrawals, and fund transfers. Exploring possible incorrect user actions, such as pressing invalid buttons or attempting operations with insufficient funds. Checking account balances and system logs after each transaction to verify accuracy. Validating outputs to ensure they correctly reflect the transactions performed.

# Comparison of exploratory and manual functional testing

We found more defects through exploratory testing than through scrpted testing. We found hidden defects, that would not be detected through a systemtic testing of function. We found small errors that would not be classified as system bugs in most cases, for example spelling mistakes. This was primarily because exploratory testing allowed us to approach the system in creative and unpredictable ways, uncovering issues beyond the 40 pre-defined scripted test cases.

Exploratory testing encourages testers to think beyond predefined scenarios, increasing the likelihood of discovering hidden defects. The unrestricted testing approach allows for a wider coverage of potential issues. However, there is the lack of structured documentation, and there is the chance of defects being missed out.

Scripted testing provides a structured and repeatable process, ensuring that all expected features are covered. This allows for clear documentation of test execution and defect tracking and ensures that all testers follow the same process, maintaining consistency across multiple testing rounds. However, the test is limited to predefined cases, restricting hidden defects to be discovered.

Both approaches have their strengths, and an optimal testing strategy would involve a combination of exploratory and scripted testing to achieve maximum coverage.

- All the defects found through the exploratory testing have been tracked and reported in [Exploratory Defect Report.xlsx](https://github.com/seng637-winter2025/a1-ExGranite/blob/main/Bug%20Reports/Exploratory%20Defect%20Report.xlsx).


- All the defects found through the scripted testing have been tracked and reported in [Scripted Defect Report.xlsx](https://github.com/seng637-winter2025/a1-ExGranite/blob/main/Bug%20Reports/Scripted%20Defect%20Report.xlsx).

# Notes and discussion of the peer reviews of defect reports

Text…

# How the pair testing was managed and team work/effort was divided 

Text…

# Difficulties encountered, challenges overcome, and lessons learned

Text…

# Comments/feedback on the lab and lab document itself

Text…
