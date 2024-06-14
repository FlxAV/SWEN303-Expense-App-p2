# Usability Test Results

## Table of Contents
- [SEQ Scores](#seq-scores)
- [SUS Scores](#sus-scores)
- [Identified Issues](#identified-issues)
- [Gitlab Issues](#gitlab-issues)

### SEQ Results

| User | User 1  | User 2 | User 3 | User 4 | User 5 | Task Avg |
| ----------- | ----------- | ----------- | ----------- | ----------- |----------- | ----------- |
| Task 1 | 5 | 6 | 7 | 6 | 6 | 6.00 |
| Task 2 | 4 | 7 | 6 | 6 | 5 | 5.60 |
| Task 3 | 6 | 6 | 7 | 7 | 7 | 6.60 |
| Task 4 | 6 | 6 | 7 | 5 | 6 | 6.00 |
| Task 5 | 7 | 7 | 5 | 7 | 7 | 6.60 |
| Task 6 | 6 | 6 | 7 | 4 | 6 | 5.80 |
| User avg | 5.67 | 6.33 | 6.50 | 5.83 | 6.17 |      |

Below are the calculations used to determine the overall SEQ score of our prototype after user testing.

(5 + 4 + 6 + 6 + 7 + 6) / 6 = 5.67

(6 + 7 + 6 + 6 + 7 + 6) / 6 = 6.33

(7 + 6 + 7 + 7 + 5 + 7) / 6 = 6.50

(6 + 6 + 7 + 5 + 7 + 4) / 6 = 5.83

(6 + 5 + 7 + 6 + 7 + 6) / 6 = 6.17

Overall average SEQ score: 6.10

We achieved a final SEQ score of 6.1, significantly surpassing both our goal of 5.3 and the industry average of 5.3-5.6 outlined in our usability goals. While not a perfect score, this is an excellent result from our testing, with no significant weaknesses identified in any of our six tasks. The lowest score among these tasks was a 5.6 out of 7.0.

#### Task 1 Comments:

- Groups highlight is not clear enough for people with limited vision. Use of a different colour or making the tab more obvious is needed. I thought I was on the friends tab at first because it looks white underneath it.
Done callout isn't large enough and is a struggle to reach. If intentional to deter from accidentally creating groups this is good but you can do this by a confirmation dialogue instead. I'd put the done dialogue near the bottom so users are encouraged to scroll if needed and then confirm once having read everything.
Overall very easy process just some misplaced elements.

- Nice looking UI, like the option to sign up with google/apple. Creating groups is intuitive while offering all features you would need.

#### Task 2 Comments:

- Process is clear; any trouble only comes from clumsiness of figma and isn't related to groups work. Well laid out. Confirmation is inconsistent with adding groups but this is the style that should be used.

- Again intuitive and professional looking user flow, with plenty of options without bloating. I think the only thing missing is there's no "back" option once you click add expense, which could be annoying if you miss click the group. Other then that looks really good!

#### Task 3 Comments:

- Activity icon should have a notification telling how many expenses you have yet to be resolved.
Overall incredibly good workflow though for this. Obvious and the information density is good. Text for dates and money is a bit small though. I'd play with sizes a bit in each item.

#### Task 4 Comments:

- Easy to find once you're used to how the app lays things out.

    Initial though process is based on previous app usage. This would be easily conveyed through prompt-based tutorial on first launching the app or using a feature.

    1) Add group
    2) In group management click + near friends
    3) Select friend
    4) Confirm

    Use of confirmation dialogues and callouts really good.

- Adding was very easy, but scrolling to manage deleted my group. Just a figma thing the actual action was very intuitive.

- In this example the group wasn't saved, but assuming it did save it was easy to understand, and would be familiar to most users.

#### Task 5 Comments:

- Very straight forward and inline with modern workflows.

    1) Profile
    2) Tap email
    3) Edit and confirm

- i had a liitle difficulty with this one but easy and intuitive once done

- Went to profile and found email. Was very easy.

#### Task 6 Comments:

- 1) Group
    2) Expense
    3) Shows expense stats here

    Overall easy to find; any trouble due to figma resetting prototype when regoing to manage page.

    Nesting expenses under so many taps is only downside. I should have a way to see this with one tap given it's a feature users would use incredibly often.

- I can see that Elliot, Dillon, and felix owe me 16.64 each. On the manage tab. Clicking on the expense and navigating to the specifics of the most recent expense I can see Felix has settled the debt. This process took me a minute to realise that the info provided on the manage tab was the not the intented information for this task.


### SUS Results

| User | User 1  | User 2 | User 3 | User 4 | User 5 | 
| ----------- | ----------- | ----------- | ----------- | ----------- |----------- | 
| SUS Q1 | 3 | 3 | 5 | 5 | 5 |  
| SUS Q2 | 4 | 1 | 1 | 1 | 4 |  
| SUS Q3 | 4 | 4 | 5 | 5 | 4 |  
| SUS Q4 | 1 | 3 | 4 | 1 | 1 |  
| SUS Q5 | 4 | 5 | 5 | 5 | 3 |  
| SUS Q6 | 3 | 2 | 1 | 1 | 1 |  
| SUS Q7 | 4 | 4 | 5 | 4 | 4 |  
| SUS Q8 | 2 | 2 | 2 | 1 | 1 |  
| SUS Q9 | 4 | 5 | 5 | 4 | 4 |  
| SUS Q10 | 1 | 2 | 1 | 5 | 1 |  

Below are the calculations used to determine the overall SUS score of our prototype after user testing.

(2 + 1 + 3 + 4 + 3 + 2 + 3 + 3 + 3 + 4 ) * 2.5 = 70.0


(2 + 4 + 3 + 2 + 4 + 3 + 3 + 3 + 4 + 3 ) * 2.5 = 77.5


(4 + 4 + 4 + 1 + 4 + 4 + 4 + 3 + 4 + 4 ) * 2.5 = 90.0


(4 + 4 + 4 + 4 + 4 + 4 + 4 + 4 + 3 + 1) * 2.5 = 90.0


(4 + 1 + 3 + 4 + 2 + 4 + 3 + 4 + 3 + 4) * 2.5 = 80.0


Overall average SUS score: 81.50


We achieved an overall SUS score of 81.5 out of 100, once again significantly surpassing our goal of 70 and the industry standard of 68 outlined in our usability goals. This result highlights another excellent outcome from our user testing.


### Answers to Specific Questions

| User | User 1  | User 2 | User 3 | User 4 | User 5 | 
| ----------- | ----------- | ----------- | ----------- | ----------- |----------- | 
| Can you describe which task you found to be the hardest to complete and why?| No, everything is easy | Viewing expenses; this is purely related to quirks of figma.| I found updating email address a littles hard as i could not see the option to update but it was still intuitive| Task 6. Every task was easy, but task 6 I thought I had the correct information before I went digging further.| All of the tasks were relatively easy as someone who has used apps like this in the past, but I would say the hardest of the tasks was finding who had settled their payments, as I wasn't sure if it was meant to be in the "Manage" section or the "Analysis" section.|  
|Can you describe which task you found to be the easiest to complete and why?| task 1 is most easiest.| Editting email. This is exactly the workflow used in most apps so it doesn't require any thought to do.| creating a group and adding friends was simple because i did not have to search around the screen as everything was properly labeled and clearly visible| 1. This task is incredibly streamlined. You create a user and they are immediately prompted to create a group.| To me the best was the resolve payments task was the easiest, as it is clearly shows you what you need to pay and what you have already payed, with great use of colours.|  
| Were you stuck or lost at any point in this test? If so, what were you trying to do? | trying to press another buttom or ask for helpl| Was never stuck.| i got a bit lost trying to change the email but i just went back and redid it, it was still very simple| No| As I said previously, I wasn't sure if I was meant to go to Analysis or the Manage section for seeing who had settled their debts, as they both have similar information.|  
| Any further criticisms / notes you might have. (Optional)| | Sizing could be a bit better. As someone with eyesight issues, the small text really is difficult . Money amounts should be big and visible. Dates should be big and visible. Eye candy like users icons and layout are nice but can sometimes make app harder to use for people with visual or motor-function (can't remember the exact term) issues.| great app, nice and simple. one thing i liked is that its not overwhelming with features and buttons but noce and easy to get used to without effort|  | I think the "Activity" bar should be something different, as when I see the bell icon I would assume it to be notifications e.g. spam and promotions and think that maybe something like "payments" with a different icon would be more intuitive, especially for older users. I think you could possible try organise the different payments in a way that will make it easier when you have a lot of payments due. Maybe adding a resolve all button could do the same thing? or a resolve all in X group.|  

## Identified Issues
| Task | Severity  | Issue | 
| ----------- | ----------- | ---------------------- | 
| Task 1 | Moderate  | -  Groups highlight is not clear enough for people with limited vision.  |
| Task 1 | Major  | -  Done callout isn't large enough and is a struggle to reach.  |  
| Task 2 | Moderate  | - No "back" option once you click add expense.  | 
| Task 3 | Minor  | - No notification telling how many expenses you have yet to be resolved.  | 
| Task 3 | Minor  | - Text for dates and money is too small.  | 
| Task 4 | Major  | - Initial thought process is based on previous app usage.  |  
| Task 5 |    |    |  
| Task 6 | Major  | - Nesting expenses under too many tabs. |

## Gitlab Issues
Links to corresponding issues created in Gitlab for tracking:
- Issue 1: [Link](#)
- Issue 2: [Link](#)
- Issue 3: [Link](#)