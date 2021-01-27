# DGL104 - Process Portfolio
## Author: Reeve Jarvis

---

### **Week 1 Activities:**

---

#### **Activity 0101**:

>**Question:** Consider a recent programming project (perhaps from last semester) in which you either didn't know the answer to a problem, or you couldn't figure out how to solve a development issue you were facing. Revisit that code now, with fresh eyes, and reconsider the problem: Can you articulate exactly why this was a problem before? Is the solution any more evident? Use your README.md file to explain what the problem was and describe the strategies and resources you could use to solve it.

Towards the end of last semester we began to discuss recursion and implementing recursive solutions to problems we had previously approached in an iterative way. I found these recursive problems to be much more difficult to comprehend. One programming problem that stumped me was regarding a recursive method that conducts a binary search, but the method was limited to only two parameters: a String target, and an array of Strings. I struggled to find a solution that would return the intended results. 

My primary issue was with properly adjusting the range of values I would be searching within, as after each binary search half of the possibilities are removed. Some thorough research on Stack Overflow and additional online resources led me to some possible solutions, however all of them used more parameters (representing the boundaries of the search) than the amount I was restricted to for my solution. I declared min, max, and mid variables to establish the boundaries of the search, however I was unable to figure out how to adjust these values appropriatly after each attempted search and maintain the integrity of my code. Due to time constraints and other course responsibilities I was unable to come to a successful solution. 

Looking back now I feel that if I were to use Indirect Recursion, and write additional methods to establish the boundaries of the search that in turn call the initial method I may have been more successful. Though I was unable to complete this problem, I know that with some more research of code examples and time to explore this issue further I would come to a viable solution. I intend to explore recursion further, when time permits, to increase my understanding as I know it is an important aspect of programming. 

---

#### **Activity 0102**:

>**Question:**Consider a recent programming project (perhaps from last semester). Open up the code and examine it for readability (as defined in the reading from Seriously Good Software). Use your README.md file to describe at least three potential areas of improvement, as per the reading from Serious Good Software.

Examining my code from last semester, there are definitely some areas for improvement when it comes to Readability. 

**1. Commenting:** 

In CPS100 we were constantly reminded to comment our intentions before we begin coding. This is something that I struggled to follow, and led to comments being added after I had finished coding. The resulting comments were far too descriptive and word-heavy, impeding the readability of my programs and causes unnecessary clutter. Updating my code would also require more work to update the comments accordingly. As described in the reading, it is best to be generous with documentation comments and stingy with implementation comments. I intend to work on following this guideline in the future, and keep the implementation comments to a minimum while addressing my intentions prior to coding. 

**2. Loops:** 

Another area of improvement I can extract from the reading, is in using the most appropriate loop for the situation. We worked on various dice games for one of our assignments, and in particular my solution for a game called Pig had a complicated series of nested loops. At the time I was more concerned with functionality rather than readability. I feel that with some further refactoring I could simplify my solution, reduce the amount of loops involved and improve the users understanding. 

**3. Naming:**

Lastly, I could improve upon naming my variables. The above mentioned Pig game relied upon multiple variables to track data values between the player and computer. The names of some of these variables got a bit lengthy, and in some cases resulted in redundancies. With some refactoring, and simplifying my class down into more methods I could have avoided these redundancies and in turn improved readability by providing simplified names for the variables to be shared across both player and computer. 

---

### **Week 2 Activities** 

---

#### **Activity 0201:**

>**Question:** Consider the apps that you use regularly. Choose one app to asses based on the reading Usability Matters Ch. 2. Identify the values inherent to the app that might help to identify the target user base (a list is fine, but be descriptive). Briefly describe the target user base. Do your goals in using the app match those of the target user base?

One application I use frequently is Splitwise. The applications main function is to provide a conveinent way to track financial interactions and distribute costs between those involved. It is a free to download app, that provides extra features for an additional premium. With the premium version you can scan receipts, work with various currency conversions, and track the data in graphs.

Values inherant to the app include:

* Providing a simplified, modern way to track purchases and financials
* Ensuring accountability between those involved in financial interactions (making sure you are paid)
* Increasing overall organization and budgetting skills
* Saving users money by keeping up to date on finances
* Keeping you informed of your current costs to guide future spending habits

From the outlined values above it is apparent that this was an excellent app idea that serves a significant purpose. It provides a valuable service to its users and replaces a flawed alternative used in the past (IOU notes). The use cases vary accross many different subsets of people. The application can be used to track money you have lent a family member, those drinks you purchased for your friend because they forgot their wallet, or even your business expenses.  In a way, the target user base can be considered as any adult with income. Personally, I use this application with my significant other to keep track of purchases we have been making and ensure we are each contributing a fair amount to our costs. I beleive that my goals in using the app match those of the intended user. As an adult, keeping track of your finances can be tough and I am using the app combat that. 

---

#### **Activity 0203:**

>**Question:** Visit CodeWars.com and create a new account (if you don't already have one). Consider using a non-identifiable email address for privacy purposes. Choose Java as your default language and choose to either 'Train' on Java, or go to the Kata menu and choose an 8 kyu exercise from the list of exercises. Give your kata of choice a try (don't spend overlong on it, if you get stuck). Take a screenshot of your code when you are done (whether you've finished the kata or not) and post it to your Process Portfolio. Briefly describe whether or not you found the kata challenging, and what stopped you if you got stuck.

First of all, thank you for directing us towards codewars, I have had some fun figuring out problems and it is already increasing my understanding. After signing up I chose to train my Java skills and attempted an 8 kyu exercise.

|The Exercise:|                           
|---|
|![8KyuExercise](photos/WhichQuarter.PNG)|
||

|**My Solution:**|
|---|
|![8Kyu Solution](photos/WhichQuarterSolution.PNG)
||

I was able to complete this solution within a couple minutes, and passed the tests. Upon submitting my successful solution I was presented with alternate solutions following best practises as voted on by others. I immediately realized that there are much more elegant ways to complete the problem that would be less redundant. My solution may not have used the best practises, but I am still very new to programming and I was happy with how fast I was able to accomplish the task presented to me. I did not find it nearly as challenging as I expected it to be going in. Overall, I am still learning about the options available to me in Java when attempting to solve problems (all I will say is CPS100 left a lot to be desired). I expect that most 8Kyu challenges are of a higher difficulty, and I plan to find out.

---





  
       




