# Google Summer Of Code 2024 Report: Incrementally Improve Auto-Completion Feature
Final report about the project "Incrementally improve the auto-complete feature" in Purr Data.

## Project Overview

This project was aimed at incrementally improve the existing Auto-Completion feature in Purr Data with a series of bug fixes and enhancements to better its UX. The project was successfully completed with all the milestones achieved except a few.

***
The first phase of the project was majorly focused on fixing the existing bugs in the Auto-Completion feature and enhancing the UX of the feature. The following milestones were achieved in the first phase:

- Addition of Scroll bar to the completion drop-down list 

The drop-down list for auto-completion had a fixed size of 8 items which was not enough to display all the items in the list. This was fixed by adding a scroll bar to the drop-down list so that the user can scroll through the list to view all the items.

Also the functionality of navigating through the list using the arrow keys was added.

| Before the fix | After the fix |
|:--------------:|:-------------:|
| ![Before the fix](image.png) | ![After the fix](image-1.png) |


- Addition of text highlighting to the completion drop-down list 
The completion drop-down list was enhanced by adding text highlighting to the items in the list. This was done to make it easier for the user to identify the matching items in the list and to make the suggestions stand out.

![alt text](image-2.png)

- Addition of tooltip to the completion drop-down list 
A tooltip was added to the completion drop-down list suggestions to display the desscription of the item when the user hovers over an item in the list. This was done to make it easier for the new users to better use the objects in the list.

![alt text](image-3.png)

- Addition of fuzzy matching to the autocompletion feature 
A fuzzy search option was added to the autocomplete feature, allowing users to find approximate matches rather than exact ones for their search queries. Additionally, results are displayed even if caps lock is on or words are capitalized. The fuzzy search functions with the autocompletion prefix, whether it's enabled (matching objects by the prefix entered in the search box) or disabled. Additionally a checkbox was added in GUI tab in the preference dialog to enable and disable fuzzy matching.

![alt text](image4.png)
![alt text](image5.png)
![alt text](image6.png)

- Addition of checkbox for clearing and resseting the help/autocompletion index 
A checkbox has been introduced, providing users with the option to clear and reset the help/autocompletion index. This feature enhances the user experience by offering a straightforward way to refresh or restart the index, instead of having to do it manually by searching the necessary files and deleting them. Users can choose to reset index along with clearing 

![alt text](image7.png)

- Addition of issue/feedback tab to preference dialog 
A new "Issue" tab has been added to the existing four tabs in the preferences dialog, allowing users to submit issues or feedback directly to the Purr Data GitHub repository. Users must be logged into GitHub to use this feature. When the submit button is clicked, the issue creation page for Purr Data opens in the user's default browser with all relevant fields pre-filled.

![alt text](image9.png)
![alt text](image8.png)


- Addition of error detection for incorrect object queries in the autocompletion search box

A feature has been implemented to detect errors when users enter incorrect object queries in the autocompletion search box. When a wrong query is detected, it is highlighted with a squiggly red underline, enabling users to quickly identify and correct the mistake, thereby enhancing the overall search experience.

![alt text](image10.png)



## Pull request and commit of all the changes made 
State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment
Show your appreciation to those who have contributed to the project.



