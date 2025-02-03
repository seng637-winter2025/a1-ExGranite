>   **SENG 637 - Software Testing, Reliability, and Quality**<br>
>   Assignment \#1 – Introduction to Testing and Defect Tracking


| Group: Group Number      |
|-----------------|
| Ahmad Al Asad                |   
| Saad Zafar Khan              |
<!-- | [Ahmad Al Asad](https://github.com/ExGranite)                |   
| [Saad Zafar Khan](https://github.com/saadz-khan)              |    -->

**Table of Contents**

1. [Introduction](#intro)
2. [Test Plan](#plan)
    - Test Types(#planA)
    - Scope of Testing(#planB)
    - Test Logistics(#planC)
3. [High-level description of the exploratory testing plan](#desc)
4. [Comparison of exploratory and manual functional testing](#comp)
5. [Notes and discussion of the peer reviews of defect reports](#notes)
6. [How the pair testing was managed and team work/effort was divided](#work)
7. [Difficulties encountered, challenges overcome, and lessons learned](#diff)
8. [Comments/feedback on the lab and lab document itself](#comm)

# <a name = "intro"></a>Introduction

This assignment involved testing an **ATM simulation system** ([ATM System - Lab 1 Version 1.0.jar](https://github.com/seng637-winter2025/a1-ExGranite/blob/main/Assignment%201%20-%20artifacts/ATM%20System%20-%20Lab%201%20Version%201.0.jar)) for defects and writing a defect report based on our findings. We conducted two types of testing:
	- **Exploratory Testing**: Unscripted testing to discover unexpected behaviors.
	- **Scripted Testing**: Following predefined test cases to systematically verify system functionality.

We used [Atlassian Jira](https://www.atlassian.com/software/jira) as our bug-tracking tool to log defects and collaborate efficiently as a team. Following the identification of defects, we performed regression testing on the updated version of the system, [ATM System - Lab 1 Version 1.1.jar](https://github.com/seng637-winter2025/a1-ExGranite/blob/main/Assignment%201%20-%20artifacts/ATM%20System%20-%20Lab%201%20Version%201.1.jar), and updated the reported issues accordingly.

Prior to this assignment, our knowledge of exploratory and scripted testing was minimal. Our experience was limited to non-structured testing, where we simply checked whether our programs worked as expected. This assignment provided us with valuable insights into structured testing methodologies, their differences, and their practical implications.

# <a name = "plan"></a>Test Plan
## <a name = "planA"></a>Test Types

We performed the following types of testing:
	- Exploratory Testing: Independant testing to uncover unanticipated bugs.
	- Scripted Testing: Systematic testing based on the pre-defined test cases.
	- Regression Testing: Verification of defect fixes in Version 1.1 after identifying issues in Version 1.0.

## <a name = "planB"></a>Scope of Testing

The ATM system was tested for Viewing account balances, epositing cash, withdrawing cash, transferring funds, verifying transaction logs, system behavior under incorrect inputs (e.g., entering invalid PINs, exceeding balance limits, pressing non-existent buttons) etc.

## <a name = "planC"></a>Test Logistics

The testing workload was distributed as follows:
	- Exploratory Testing: Each team member independently explored the system for defects.
	- Scripted Testing: Conducted as a pair
	- Regression Testing: Conducted as a team by re-executing identified defects on Version 1.1.

# <a name = "desc"></a>High-level description of the exploratory testing plan

Our exploratory testing approach aimed to analyze how users interact with the ATM system, identify edge cases, and verify system behavior under various conditions. Each of us tested both the versins following these key principles in our testing approach: Simulating typical user transactions at an ATM, including balance inquiries, cash deposits, withdrawals, and fund transfers. Exploring possible incorrect user actions, such as pressing invalid buttons or attempting operations with insufficient funds. Checking account balances and system logs after each transaction to verify accuracy. Validating outputs to ensure they correctly reflect the transactions performed.

# <a name = "comp"></a>Comparison of exploratory and manual functional testing

We found more defects through exploratory testing than through scrpted testing. We found hidden defects, that would not be detected through a systemtic testing of function. We found small errors that would not be classified as system bugs in most cases, for example spelling mistakes. This was primarily because exploratory testing allowed us to approach the system in creative and unpredictable ways, uncovering issues beyond the 40 pre-defined scripted test cases.

Exploratory testing encourages testers to think beyond predefined scenarios, increasing the likelihood of discovering hidden defects. The unrestricted testing approach allows for a wider coverage of potential issues. However, there is the lack of structured documentation, and there is the chance of defects being missed out.

Scripted testing provides a structured and repeatable process, ensuring that all expected features are covered. This allows for clear documentation of test execution and defect tracking and ensures that all testers follow the same process, maintaining consistency across multiple testing rounds. However, the test is limited to predefined cases, restricting hidden defects to be discovered.

Both approaches have their strengths, and an optimal testing strategy would involve a combination of exploratory and scripted testing to achieve maximum coverage.

- All the defects found through the **Exploratory Testing** have been tracked and reported in [Exploratory Defect Report.xlsx](https://github.com/seng637-winter2025/a1-ExGranite/blob/main/Bug%20Reports/Exploratory%20Defect%20Report.xlsx).
- All the defects found through the **Scripted Testing** have been tracked and reported in [Scripted Defect Report.xlsx](https://github.com/seng637-winter2025/a1-ExGranite/blob/main/Bug%20Reports/Scripted%20Defect%20Report.xlsx).

# <a name = "notes"></a>Notes and discussion of the peer reviews of defect reports

Due to our team only having two members, our peer review process first involved each of us performing exploratory testing on both the versions 1.0 and 1.1. The reports were combined to get a sum total of the number of defect reported. Then, we worked as a pair to perform the scripted testing on the 40 funcitonalities on both the versions and report their outcomes.

We discovered that each member had a unique way of interacting wit the system, which resulted in the significantly higher number of defects reported through exploratory testing. There were quite a number of differences between the two of our tests. For example, running the system through the terminal gives the output from the exceptions thrown in the terminal. This was found due to the pair testing method.

# <a name = "work"></a>How the pair testing was managed and team work/effort was divided 

We followed a structured approach in our testing.

- **Exploratory Tesing:** Each of use took 1 day to test and explore both the versions and recording any defects. We first tested version 1.0 and recorded the defects. Then we checked them on the updated version. The total defects were then compiled, retested as a pair, and documented.
- **Scripted Testing:** The 40 scripted test cases were tested on version 1.0 and the outcomes were documented as a pair. One member executed the test, while the other documented. We then conducted the regression testing on version 1.1 using the similar approach and documented the defects.

# <a name = "diff"></a>Difficulties encountered, challenges overcome, and lessons learned

The challenges faced during the testing were mostly on duplicate bug reports. Some defects were found multiple times from different methods, and they had to be combined. Another thing was that some tests could not be reproduced without closing and restarting the system.

To solve these, we conducted regular team discussions on the virtual platform Zoom to compile, refine and complete the defect report and lab report. We implemented a consistent bug report template to ensure the completeness of the defect tracking.

We learned that teamwork is crucial and working as a pair significantly improves workflow and time utilization. Using a structured testing method makes defect traking more organized and reproducible.

# <a name = "comm"></a>Comments/feedback on the lab and lab document itself

Overall, this lab provided an insightful hands-on experience with exploratory, scripted, and regression testing. It allowed us to gain practical exposure to structured testing methodologies and collaborative defect tracking, which will be valuable in future software projects.

The ATM Simulation program was a simple enough system to use and contained enough defects to make the testing process more engaging. It demonstrated the strengths and limitationas of both exploratory and scripted testing.

JIRA was used as our issue tracking tool, and it proved to be highly effective for managing and documenting defects. JIRA’s workflow tracking, issue categorization, and reporting features streamlined our bug-tracking process and enhanced team collaboration.

The assignment instructions and deliverables description was clear, well-structured and easy to follow. The instructions provided a good foundation for conducting both exploratory and scripted testing, ensuring our understanding of the topics.

This assignment significantly improved our understanding of structured testing, issue tracking, and defect management. It provided us with real-world skills that are directly applicable to software testing in professional environments.
