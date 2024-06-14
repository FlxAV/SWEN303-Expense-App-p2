# Proposed Prototype Updates

## Table of Contents
- [Overview](#overview)
- [Justifications](#justifications)

## Overview
Summary of proposed updates based on test results.

## Justifications
|  Update        |  Severity  |  Justification        |
|  ------------- |  --------  |  -------------------  |
|  Highlighting text of group and friend page.  | Medium |  Currently the app has a thin slider underneath the selected page while in the "Manage" tab. This was implemented to enhance our minimilist design. However This can be improved upon without compromising the design. Adding an enlargen effect when a user taps on either the "Groups" or "Friends" buttons will increase the users actions visual cues, inturn helping user flow.  |
|  Moving "Done" button to the bottom of the page and adding a confrimation overlay  | Medium |  Currently the app has a "Done" button at the top right of the screen. However by adding the button to the bottom of the screen and creating a confirmation overlay this prevents the user from having to navigate back to the top of the screen once they've finished altering the group. By moving the button to the bottom this improves user flow as they are already scrolling down to view information. As well as this we are also improving user error mitigation by adding an extra step for confirmation in the form of an overlay.  |
|  Adding a return button to the "Add" tab.  | Medium |  If the user clicks the Add expense button from within a specific group then there will be a "Return" button at the top. This will increase user flow further by allowing an easy route back to the previous page they were on.  |
|  Adding an "Unresolved expenses" Icon above the search bar in the "Groups" page.  | Low |  This is a minor change that will help users drastically. By having a small icon at the top of the page using negative colors like red it will constantly act as a neural prompt to get them to resolve those expenses. Once the user has no expenses to resolve it will be green. This is a small feature implentation that will help with app purpose and user retention due to constantly wanting the icon to be green. |
|  Increasing subtext size.  | Low |  Small quality of life change. Increasing the size of the text will improve readability through out the app.   |
|  Upon first launch of the app show a short skipable tutorial of how to use it.   | High |  This allows the users freedom to dive straight into the app or watch a short video explaining the features of our app and how to use them. This will make the app more intuitive and less reliant on prior use.  |
|  Keeping indentation to a minimum. Removing additional page popups where applicable  | High |  This helps keep the architecture of the app simple. Preventing users from possibly getting lost. Primary functions and viewing data should be a simple task and should be shown to the user in an easy / readable / minimilist way to reduce clutter and user overstimulation.  |