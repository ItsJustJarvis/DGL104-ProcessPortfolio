# DGL104 - Process Portfolio

<br/>

## Author: Reeve Jarvis

<br/>

---

### **Week 1 Activities:**

---

<br/>

#### **Activity 0101**:

> **Question:** Consider a recent programming project (perhaps from last semester) in which you either didn't know the answer to a problem, or you couldn't figure out how to solve a development issue you were facing. Revisit that code now, with fresh eyes, and reconsider the problem: Can you articulate exactly why this was a problem before? Is the solution any more evident? Use your README.md file to explain what the problem was and describe the strategies and resources you could use to solve it.

<br/>

Towards the end of last semester we began to discuss recursion and implementing recursive solutions to problems we had previously approached in an iterative way. I found these recursive problems to be much more difficult to comprehend. One programming problem that stumped me was regarding a recursive method that conducts a binary search, but the method was limited to only two parameters: a String target, and an array of Strings. I struggled to find a solution that would return the intended results.

My primary issue was with properly adjusting the range of values I would be searching within, as after each binary search half of the possibilities are removed. Some thorough research on Stack Overflow and additional online resources led me to some possible solutions, however all of them used more parameters (representing the boundaries of the search) than the amount I was restricted to for my solution. I declared min, max, and mid variables to establish the boundaries of the search, however I was unable to figure out how to adjust these values appropriatly after each attempted search and maintain the integrity of my code. Due to time constraints and other course responsibilities I was unable to come to a successful solution.

Looking back now I feel that if I were to use Indirect Recursion, and write additional methods to establish the boundaries of the search that in turn call the initial method I may have been more successful. Though I was unable to complete this problem, I know that with some more research of code examples and time to explore this issue further I would come to a viable solution. I intend to explore recursion further, when time permits, to increase my understanding as I know it is an important aspect of programming.

---

<br/>

#### **Activity 0102**:

<br/>

> **Question:** Consider a recent programming project (perhaps from last semester). Open up the code and examine it for readability (as defined in the reading from Seriously Good Software). Use your README.md file to describe at least three potential areas of improvement, as per the reading from Serious Good Software.

<br/>

Examining my code from last semester, there are definitely some areas for improvement when it comes to Readability.

**1. Commenting:**

In CPS100 we were constantly reminded to comment our intentions before we begin coding. This is something that I struggled to follow, and led to comments being added after I had finished coding. The resulting comments were far too descriptive and word-heavy, impeding the readability of my programs and causes unnecessary clutter. Updating my code would also require more work to update the comments accordingly. As described in the reading, it is best to be generous with documentation comments and stingy with implementation comments. I intend to work on following this guideline in the future, and keep the implementation comments to a minimum while addressing my intentions prior to coding.

**2. Loops:**

Another area of improvement I can extract from the reading, is in using the most appropriate loop for the situation. We worked on various dice games for one of our assignments, and in particular my solution for a game called Pig had a complicated series of nested loops. At the time I was more concerned with functionality rather than readability. I feel that with some further refactoring I could simplify my solution, reduce the amount of loops involved and improve the users understanding.

**3. Naming:**

Lastly, I could improve upon naming my variables. The above mentioned Pig game relied upon multiple variables to track data values between the player and computer. The names of some of these variables got a bit lengthy, and in some cases resulted in redundancies. With some refactoring, and simplifying my class down into more methods I could have avoided these redundancies and in turn improved readability by providing simplified names for the variables to be shared across both player and computer.

<br/>

---

### **Week 2 Activities**

---

<br/>

#### **Activity 0201:**

<br/>

> **Question:** Consider the apps that you use regularly. Choose one app to asses based on the reading Usability Matters Ch. 2. Identify the values inherent to the app that might help to identify the target user base (a list is fine, but be descriptive). Briefly describe the target user base. Do your goals in using the app match those of the target user base?

<br/>

One application I use frequently is Splitwise. The applications main function is to provide a conveinent way to track financial interactions and distribute costs between those involved. It is a free to download app, that provides extra features for an additional premium. With the premium version you can scan receipts, work with various currency conversions, and track the data in graphs.

Values inherant to the app include:

- Providing a simplified, modern way to track purchases and financials
- Ensuring accountability between those involved in financial interactions (making sure you are paid)
- Increasing overall organization and budgetting skills
- Saving users money by keeping up to date on finances
- Keeping you informed of your current costs to guide future spending habits

From the outlined values above it is apparent that this was an excellent app idea that serves a significant purpose. It provides a valuable service to its users and replaces a flawed alternative used in the past (IOU notes). The use cases vary accross many different subsets of people. The application can be used to track money you have lent a family member, those drinks you purchased for your friend because they forgot their wallet, or even your business expenses. In a way, the target user base can be considered as any adult with income. Personally, I use this application with my significant other to keep track of purchases we have been making and ensure we are each contributing a fair amount to our costs. I beleive that my goals in using the app match those of the intended user. As an adult, keeping track of your finances can be tough and I am using the app combat that.

---

<br/>

#### **Activity 0203:**

<br/>

> **Question:** Visit CodeWars.com and create a new account (if you don't already have one). Consider using a non-identifiable email address for privacy purposes. Choose Java as your default language and choose to either 'Train' on Java, or go to the Kata menu and choose an 8 kyu exercise from the list of exercises. Give your kata of choice a try (don't spend overlong on it, if you get stuck). Take a screenshot of your code when you are done (whether you've finished the kata or not) and post it to your Process Portfolio. Briefly describe whether or not you found the kata challenging, and what stopped you if you got stuck.

<br/>

First of all, thank you for directing us towards codewars, I have had some fun figuring out problems and it is already increasing my understanding. After signing up I chose to train my Java skills and attempted an 8 kyu exercise.

| The Exercise:                            |
| ---------------------------------------- |
| ![8KyuExercise](photos/WhichQuarter.PNG) |

| My Solution: |
| ------------ |

|![8Kyu Solution](photos/WhichQuarterSolution.PNG)

I was able to complete this solution within a couple minutes, and passed the tests. Upon submitting my successful solution I was presented with alternate solutions following best practises as voted on by others. I immediately realized that there are much more elegant ways to complete the problem that would be less redundant. My solution may not have used the best practises, but I am still very new to programming and I was happy with how fast I was able to accomplish the task presented to me. I did not find it nearly as challenging as I expected it to be going in. Overall, I am still learning about the options available to me in Java when attempting to solve problems (all I will say is CPS100 left a lot to be desired). I expect that most 8Kyu challenges are of a higher difficulty, and I plan to find out.

<br/>

---

### **Week 3 Activities**

---

<br/>

#### **Activity 0301:**

<br/>

> **Question:** Choose a relatively popular app that you use regularly. Try to find [ideally] a video (or screenshots) of the app operating on a different platform than the one you typically use (i.e. if you use iOS, look for the Android version). If you have access to two devices with different platforms, even better - install the app on each platform and try it out. Alternatively, if your chosen app has a progressive web version that you can install on the same device with the native app, try that out instead. What differences do you note between platforms? Pay attention in particular to navigation and button placement. Write down your findings on your Process Portfolio.

<br/>

**App in Focus:** Facebook

| Facebook iOS                            | Facebook Android                                |
| --------------------------------------- | ----------------------------------------------- |
| ![Facebook iOS](photos/facebookiOS.jpg) | ![Facebook Android](photos/facebookAndroid.jpg) |

Examining the differences between the facebook application yields some expected results. Due to the different functionalities of the devices, they are presented with slightly different layouts.

The primary difference is in terms of navigation layout. As android devices have the 3 platform specific buttons integrated into the bottom of the screen, the in-app navigation has been relocated to the top of the activity screen. I beleive the reasoning behind this is to eliminate the possibility of accidentally hitting the android buttons while browsing between activities in the app itself. Additionally these buttons provide some in app functionality as well, such as using the back button to navigate to a previous activity screen within the app. The iOS version, due to not having these buttons has opted to place the navigation bar at the bottom of the screen. In app navigations can be done with a swipe gesture instead.

I can see benefits to either side. Having the ability to use the integrated back button on android is conveinent, though the iOS version does provide a nice "contained" look by bordering the bottom of the screen to avoid the run-off appearance present in the android version.

Either way, in my personal opinion, Android is king.

---

<br/>

#### **Activity 0302:**

<br/>

> **Question:** Visit either Android Developer Guides or Apple Developer Technologies. Scroll through to look for an article/documentation section that interests you. Read through any overview content and scan through some of the related content. Pay attention to the structure of the documentation (i.e. how the documentation is laid out, how the information is presented, etc.) Write a short summary of the section you looked at on your Process Portfolio and breifly describe what you learned about the documentation structure.

| Link To Documentation Reviewed: https://developer.android.com/training/animation/overview?hl=en |
| ----------------------------------------------------------------------------------------------- |
| ![Animations Doc](photos/androidAnimations.PNG)                                                 |

While browsing the Android Developer Guides I was drawn to an article regarding animations. You can see the layout of this article in the photo above. The page is presented with an easily navigated menu along the left side of the screen detailing all of the possible articles to explore. On the right hand side of the screen, there is a table of contents pertaining to the information contained within the current article you are viewing. Additionally, throughout the page there are embedded links which reference other materials that may be of interest to you or provide additional context. It is also helpful that they provide visual aids to increase understanding of the content.

This documentation provided some interesting information regarding the use of animations in your application design. It outlined some use cases for animations in your application, and important considerations to take when creating them. When it comes to animations the document covers four main topics:

1. Animate bitmaps - This section provides suggestions for the proper animation of a bitmap graphic using drawable animation APIs.

2. Animate UI visibility and motion - This section indicates the importance of using subtle animations to help users understand UI changes and make the experience less jarring using physics based motion.

3. Animate layout changes - This section details using transition frameworks to animate layout changes within the current activity, such as a tap event on an item for more information.

4. Animate between activities - Lastly this section discusses using animations to transition between activity screens within your application.

---

### **Week 4 Activities**

---

<br/>

#### **Activity 0401:**

<br/>

> **Question:** Scroll through either pttrns.com or mobile-patterns.com (watch out for ads) and pick a pattern that is of interest to you (it can be one you’ve used before, or not). Consider the when and how the pattern should be used and write a short summary (a paragraph) that outlines why you think the pattern is valuable (similar to - but shorter than - the introductory summaries for each of the patterns presented in UX Design Patterns for Mobile Apps: Which and Why.

| Pattern                                      |
| -------------------------------------------- |
| ![Youtube Navigation](photos/youtubeNav.PNG) |

The above pattern presents a navigation menu that is much more usable for the mobile platform than standard nav bars. By hiding the navigation behind a navicon, you save space in your design and contain the navigation elements in an attractive list that can be hidden or revealed at will. This is a valuable tool when designing with usability in mind on the mobile platform. We learned about implementing this design in our HTML and CSS course when discussing responsive design. This can be implemented with media queries, only activating when viewing on certain screen sizes. It allows a website/webapp to be responsive to their users devices. Overall, it is a great design choice that should always be implemented into the mobile version of websites or in webapps that require a long navigation list.

---

<br/>

#### **Activity 0403:**

<br/>

> **Question:** Visit CodeWars.com and attempt at least two katas. Ideally you should finish both - so choose something that is within your level of programming expertise.

**Kata #1:**

| Description:                                         |
| ---------------------------------------------------- |
| ![Kata 1 Description](photos/MaskifyDescription.PNG) |

| Solution: |
| --------- |

|![Kata 1 Solution](photos/MaskifySolution.PNG)

**Kata #2:**

| Description:                                         |
| ---------------------------------------------------- |
| ![Kata 2 Description](photos/SquaredDescription.PNG) |

| Solution:                                      |
| ---------------------------------------------- |
| ![Kata 2 Solution](photos/SquaredSolution.PNG) |
