# Usability Test Plan

## Table of Contents
- [Introduction](#introduction)
- [Script](#script)
- [Metrics](#metrics)
- [Tasks](#tasks)
- [Roles](#roles)
- [Problem Severity](#problem-severity)

## Introduction
Brief overview of the usability testing plan.

## Methodology

#### Participants

Four participants from another group will act as test users for our usability testing. Participants were selected through email communication. Given their background, we assume their skill level with similar systems will be relatively high, which will be considered when reviewing test results.

#### Testing Overview

Testing will be conducted asynchronously to accommodate participants' busy schedules. Communication and coordination will occur through Discord, and a Google Form will guide participants through the tasks and collect their feedback.

#### Training

Participants will receive a brief overview of the app and the testing process through a description provided in the Google Form. This overview will not focus heavily on navigation to assess the intuitiveness of the app's layout.

#### Procedure

1- Setup:
- Participants were contacted via email and invited to a shared Discord server for easier communication.
- In Discord, both groups agreed to create Google Forms for the other group's members to fill out, allowing testing to be completed at their convenience.

2- Task Completion:
- Each participant will receive a Google Form containing detailed descriptions of six tasks to complete within the app.
- The tasks will include a mix of step-by-step instructions and tasks requiring independent navigation.
- As participants complete each task, they will answer questions in the form regarding their experience, focusing on usability, functionality, and any encountered issues.
- Metrics collected will include task completion time, ease of navigation, encountered errors, and user satisfaction.

3- Feedback Collection:
- After completing all tasks, participants will fill out a final section of the Google Form, providing overall feedback on their experience.
- This section will include specific questions about the app's functionality and usability, as well as an optional space for additional comments.

4- Data Analysis:
- Once all participants have completed the testing, the collected data will be analysed.
- The focus will be on identifying common issues, usability trends, and areas for improvement.


## Script
### Introduction

The purpose of our app is to help flat groups effectively track and manage their expenses.

To use the app, sign in or create an account. Once signed in, you can create a group in the Manage tab to share with other flat members. You can add, view, and manage expenses within your group. Members can be added or removed anytime. Expenses can be added through the Add tab, assigned to groups and members, and split three ways: Numeric, Percent, and Even. The Activity tab shows all expenses, and expenses can be marked as resolved. The Profile tab lets you personalise your account and change settings like your profile picture, email, or app appearance.

We appreciate your honest feedback. Your responses are completely anonymous, and no personal information will be recorded or displayed. Thank you for taking the time to review our product

### Your Tasks

During the testing process, you will complete six tasks within our Figma app. Three tasks will come with step-by-step instructions, while the other three are to be completed without guidance. This approach helps us understand both how you learn the app and how you navigate it independently. Don’t hesitate to make any comments if there are significant differences between the two methods. After each task, you will answer a single question about your experience. Once all tasks are complete, there will be a final questionnaire about your overall experience with the six tasks.  We have chosen to handle our questionnaires in this way so that we will have data to analyse for both the individual tasks and the overall experience with all tasks as a whole. Additionally, there will be a few specific questions and an optional section for any further comments and feedback.

As mentioned, for the first three tasks we will take you step by step until you have completed the task, feel free to voice any concerns or opinions while completing the task.


### Tasks

#### Task 1 - Create a Group

For this task we will get you to create a group from the Login page.

- Step 1 First of all click on “Sign up” and then click on “Continue”.
- Step 2 You are now in the Manage Tab by default, click on “Create Group”.
- Step 3 Here you would write down your desired information of said group, now click on “Done”.

You have successfully created a group.

#### Task 2 - Add an Expense to a group

For this task we will get you to add an Expense to the group you have created.

- Step 1 First of all make sure you are in the “Manage Tab”
- Step 2 Now click on the arrow that is on the group you have just created.
- Step 3 You are now inside the group with the information of said group.
- Step 4 Now click on “Add an Expense”.
- Step 5 You are now in the Add Expense Tab, here you would add information about your expense including: The group it belongs to, some information and the split amongst the members.
- Step 6 Scroll down and click on “Save Expense”, followed by “Confirm” when the pop up appears.

You have successfully added an Expense.

#### Task 3 - Resolve an expense from the Activity tab

For this task we will get you to Resolve an Expense from the Activity Tab.

- Step 1 Go to the bottom of the screen, on the hot bar click on the “Activity” icon.
- Step 2 Here you can scroll and would be able to Resolve any of these expenses. For this test however Resolve the first Expense by clicking on “Resolve”.
- Step 3 A pop up should appear, click on “Confirm”

You have successfully Resolved an Expense from the Activity Tab.

For these next three tasks we will no longer take you through step by step. Instead we will ask you to complete a task or obtain some information. We will describe the task we would like you to complete or the information we would like you to acquire, you will then commence completing said task. If you are willing, please explain your thought process as you are completing your task. If at any point during this task you are lost on the next step to complete the task please describe your issue. 

#### Task 4 - Add a member to a group from your Friends list

For this task we would like you to navigate back to the group you have created and add a member to the group that is currently in your friends list.

#### Task 5 - Update your Email address on your Profile

For this task we would like you to navigate to your profile page and update your email address.

#### Task 6 - Figure out who has settled their debt with you for an Expense (view Expense)

For this task we would like you to navigate to an Expense you have created in a group and tell us who has Settled their debt with you already..


## Metrics

After conducting research, we have chosen to use both the System Usability Scale (SUS) and the Single Ease Question (SEQ) testing methods to evaluate our prototype. By employing both methods, we aim to gain comprehensive insights into the overall usability of our prototype, as well as more precise feedback on each individual task. We believe these methods are suitable because they provide reliable results even with a small sample size, giving us a clear gauge of our app's usability.

## Usability Goal

Once we receive all the data and feedback from our questionnaire, we will calculate the average scores for each testing metric. 

The SEQ feedback will provide a rating on a scale from 1 to 7, where 1 indicates the task was very difficult and 7 indicates it was very easy. We will compile these ratings and compute the averages for each individual task, as well as the overall average for all six tasks combined. According to the following website (https://measuringu.com/seq10/), the average SEQ score typically falls between 5.3 and 5.6. To set a realistic goal for our prototype, we aim to achieve an average of at least 5.3 for each individual task and for the total average across all tasks.

The SUS feedback will provide a rating on a scale from 0 to 100, with a higher score indicating better usability. This score will be obtained through our questionnaire, which consists of the ten standard SUS questions, each answered on a scale from 1 (strongly disagree) to 5 (strongly agree). To calculate the final score, we will subtract 1 from the score of each odd-numbered question and subtract the value of each even-numbered question from 5. We will then sum these adjusted values and multiply the total by 2.5 to obtain a final usability score out of 100. After averaging the usability scores from all test subjects, we aim to achieve a score of at least 70. According to the following website (https://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/), a SUS score of 68 is considered the industry standard, so setting an average score of 70 as our goal is both realistic and indicative of above average usability for our prototype.


## Roles
### Facilitator
Responsibilities of the facilitator.
### Note Taker
Responsibilities of the note taker.
### Analyst
Responsibilities of the analyst.
### Test Subject
Responsibilities of the test subject.

## Problem Severity
Classification criteria for problem severity:
- Minor
- Moderate
- Major