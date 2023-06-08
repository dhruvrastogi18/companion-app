# Companion App 

A smart journaling desktop application to help you track your mood and take better care of your mental health.  

It starts with a journalling app. Everyday, the user can write entries to their journal to put on paper their thoughts or feelings. He/She can also click on some activities (like playing sports, studying etc) to add them to their daily entry. Likewise, they can add the people they spent time with. The user is then asked to evaluate their mood/day with a slider (from worst to best day of their life). It is then possible for them to see the evolution of their mood in time.
This is for the regular journaling part.  

The specificity of the project is that the data that the user creates by writing the journal is analysed to find trends or patterns in their mood and give them some insights about them.  
The trends and patterns that it analyses can be numerous. For example, the app will be able to tell to the user that every Thursday of the mont month they are experiencing a decrease of mood. Many metrics can be tracked, as sleep or physical activity, and anomalies in these metrics can be detected and correlated to changes in mood. With this information, the user will then be able to figure out what is going wrong and causes them this stress.   


Thus CompanionApp helps you introspect to understand what makes you happy, stressed or depressed and keeps an eye on your mood and mental health.


As an extension, if we have the time, Companion App can even help you with other aspects of your life. We implemented a habit tracker in the app. The user could tell the app that they want to go to the gym every monday and the app would ask them if they did so every monday.

Based on the same model the user the personal journal to a project-oriented journal. The user would not track their mood anymore but rather their performance or the advancement of their project.  
  
  
Here is an example of the application's UI:
![exampleUI](https://user-images.githubusercontent.com/91381114/203642351-10ddf1b8-be66-4267-aefb-1da34732f860.jpg)


### Members (name surname, github username)

    - Dhruv Rastogi, dhruvrastogi18
    - Shubhangi Thakur
    - Shaurya Pratap Singh
    - Siddharth Joshi

#### Teams


##### Analysis team :
  - Dhruv (Data Collection & Data Analysis)
  - Shubhangi (TensorFlow & NLP)
  - Shaurya (NLP & Algorithm)

##### Frontend team :
  - Dhruv (Designing Specific components)
  - Siddharth (Organised Full Frontend and Glued Components together)
  
##### File processing :
Handles the saving, loading and encryption of files.
- Dhruv (Studied AES Encryption)
- Shaurya (File Handling)

##### Writing research Paper:
- Dhruv (Studied Previous Research)
- Shubhangi (Studied Previous Research & wrote current research)
- Siddharth (Wrote current research)




## How to test the app?

#### OS specificities
The app can run on all OS (Linux, Windows and MacOS)
It has been more tested on Windows. The NLP analysis of the text of the entry, which is an experimental feature that we still though relevant to show, **is only working on MacOS**

#### How to use the app?
- You can modify today's entry using the "modify" button of the example entry. Every day (you may change the date of you computer) you can create a new entry by clicking on the "today's entry button". The text editor allowes you to extensivelt style your writing. You can try putting the text as bold, italic, create lists, tables etc...

- You can create custom activities by clisking on the "All Activities" button. You can then add these activities to any entry by modifying the entry and ticking the corresponding activities in the upper part of the card.

- You can log your mood by using the slider at the top right corner of the entry card.

- You may use the "Test" button to generate a lot of sample entries. Use this button only once. **This button is only here to help you test the app and would not be here if you were a regular user and not a testor.** When you use it, a lot of entries are created. It will take some time. You may sort them to display only the last 30 using the filters. Notice that by default only the 30 first are shown but this is not the case after using the test button (again, it is not a regular button that would be in the app). Click on the menu with default value "mood" at the top of the entries to choose your filter, then click "add" to add the filter.) You may want to create first some custom activities to have them added to your sample generated entries.

- You may create habits using the all habits button

- Every Sunday, last day of month or of year, a weekly/montly/yearly recap is generated. You may want to set your PC's date to december 31st, 2023, and hit the test button, then write an entry. That way you can generate at the same time a weekly, montly and yearly recap to test them all.

- For testing purposes, you can delete entries and recaps by deleting the content of the folders "Entries" and "Entry_recaps" in the build folder.

- You can use the settings at the top left corner to prevent the creation of a recap.

#### App Screenshots
Main Screen:

![Main Screen](https://i.ibb.co/QH9jN9P/Screenshot-2023-04-19-at-10-19-04-PM.png)

Entering into Journal:

![Journal Screen](https://i.ibb.co/1shhtWW/Screenshot-2023-04-19-at-10-21-47-PM.png)

Charts:

![Charts](https://i.ibb.co/6NVk2R6/Screenshot-2023-04-19-at-10-24-20-PM.png)

Habits Tab:

![Habits Tab](https://i.ibb.co/yVcwGnK/Screenshot-2023-04-19-at-10-25-01-PM.png)

Friend (Foxy):

![Friend](https://i.ibb.co/J79yrRC/Screenshot-2023-04-19-at-10-25-46-PM.png)

