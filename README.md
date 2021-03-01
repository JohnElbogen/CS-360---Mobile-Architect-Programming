# CS-360
Mobile Architect &amp; Programming

**Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?**

The goals of the inventory app were to allow users to manage inventory of items.  Some needs which the design addressed were, the ability to add/edit/delete entries from their inventory.  The ability to log in/create an account.  Lastly, the ability for the user to have their data stored locally in a SQL database. (authentication info and inventory info)

**What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?**

Only two screens were necessary, a log in screen, and the main inventory screen.  The UI kept users in mind by allowing users to quickly and easily edit/view their inventory.  All design concepts successfully accomplished this by being built in a way that users can access all functions without much effort.  For example, a scroll view allowed users to add any amount of inventory while still being able to view their inventory options such as add alert/save/or add new item.

**How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?**

My approach for coding the application was to focus on each feature individually.  For example, I would create all necessary files for the "log in" button functionality.  This included, the ability to check username/passwords versus the database, the log in database itself, etc.  By working like this, I was able to focus on each features functionality as it was created to ensure it worked as intended, before testing its functionality with other parts.  This strategy can be applied in any other program I work on.

**How did you test to ensure your code was functional? Why is this process important and what did it reveal?**

I tested the code by creating test cases which the user would use.  For example, I tested each scenario: a user enters a username and clicks log in, a user enters a password and clicks log in, a user enters an existing username/password.  Each of these situations should have a corresponding result.  This process was important, because I utilized it while developing.  For each piece I developed, I tested its functionality to ensure it worked as intended.

**Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?**

The biggest challenge came from my own design choice.  I chose to use Dynamically Created EditText/Button layoutview, to allow the user to have an easy way to edit any of the information.  This was difficult, because I needed to somehow keep track of each of the created layouts that were inserted into a scrollview.  At first I was not sure of the best approach to track each feature.  This also created another issue.  When pulling the data base on loading the screen, I needed a way to display the data within the EditText + delete button format...  My solution was create lines using my existing add button function, but then adding the SQL data to the editText.  This approach worked well for my design, but in a larger inventory with one million entries, this could be inefficient.

**In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?**

I believe the way I approached how the inventory was displayed shows my success.  While the intention was more complicated to code, the result was a clean and comfortable user experience (in the context of my application solution/purpose).  It showed my ability to be a bit creative on my approach, while maintaining the level of structure needed for functioning code.
