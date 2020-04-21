# Interview Process
* Evaluation
* Structure

# Applying
* Experience
* Resume

# Soft Skills
* Preparation
* Interview

# Tech Skills
* Preparation
* Interview

## Evaluation <Coding, testing aptitude, not knowledge>
* Intelligence 50%
* Coding Skills 30%
* Experience 15%
* Personality 05%

## PMs (Microsoft) && APMs (Google)
* Communication Skills
* User-Focused Thinking
* Passion for Technology
* Analytical Skills
* Technical Skills (position dependent)

## How You Are Judged
* How did you do RELATIVE to other candidates on the SAME question?
* It's not about how quickly you solved the problem...it's about how quickly you solved it relative to other candidates.

## Resumes & Application Process
* How to Get an Interview
** Build something! <Don't waste your summers!>
** Make a kick-ass resume <It's really not that hard.>
* How We Review Resumes <Glanced at, not read. 15 - 30 seconds>
** 1. Pull resume out of giant stack
** 2. Spot-check: company names, positions, projects, schools.
** 3. Skim bullets to see if you've written real code.
** 4. Reject or Interview.
** 5. Go to next resume & whine about how many more you have left.
* How CS Resume Should Look
** One Page Only! Unless > 10 years exp
** A Real Resume Format with organized columns
** Short (1 - 2 line bullets)
** Focus on Accomplishments not responsibilities
** GPA if at least 3.0 max (in-major, overall)
** 3 - 4 Projects, Courses & independent Finished or unfinished
** List of Technical Skills Short! Cut the "fluff."
** No Objective! Objectives / Summaries are almost always useless.

## Behavioral Questions
* Communication Tips
** Goals:
*** Answer the question.
*** Deliver a *good* answer.
*** Communicate well.
** Stratigies:
*** Nugget First
**** Lead with your "thesis" / nugget
***** Grabs the listener's attention
***** Gives them context for where you're going
****** Q: What accomplishment are you most proud of?
****** A: I'm most proud of the way I re-architected	the ...
*** S.A.R.: Situation, Action, Result
**** Situation: What was the issue?
**** Action: What did you do about it?
**** Result: What was the impact?
* Preparing for Behavioral Qs
** Create Preparation Grid for Projects
*** <Enjoyed, Hated, Most Challenging, Hardest Bug> <OS Project> <Amazon Intern.>

## Technical Skills Interview Prep
* How to study
** Study the basics
*** Complex algorithms generally unnecessary.
** Practice solving questions
*** Don't memorize!
*** See: CtCI & CareerCup.com
** Push yourself!
** Write code on paper
** Data Structures
*** How to implement
*** When to use (pros / cons)
*** Linked Lists, Stacks, Queues, Trees, Tries, Graphs, Vectors, Heaps, "Hashtables"
** Algorithms
*** Implementation
*** Space vs. Time Complexity
*** Quick Sort, Merge Sort, "Tree Insert / Find", Binary Search, Breadth-First Search, "Depth-First Search"
** Concepts
*** Not just a concept - know how to code!
*** Threading, "System Design & Scalability", Memory Management, "Recursion", Probability + Combinatorics, "Bit Manipulation"

## Technical Skills Mastering the Interview
* Types of "Serious" Questions
** 1. Product Design Questions
*** How would you design an calculator for the blind?
*** Design an elevator for a building.
*** Pick a Google product. How would you improve it?
*** Why?
**** Communication & Structured Thinking
**** Ability to understand the user
**** Creative
**** Business instincts / skills
*** Qs Approach
**** 1. Ask questions to resolve ambiguity
**** 2. Understand the user
**** 3. Structure the problem
**** 4. Solve piece by piece
**** How would you design a calculator for the blind?
***** Step 1: Ask Questions
****** Adults? Children? Professionals?
****** Where are they using it? School, work, etc.
**** Step 2: Understand the User
***** What's important to a blind child?
****** Keeping up with the rest of the class
****** Not feeling "different"
****** Efficient input / output
***** What about teachers, parents, classmates, etc.?
**** Step 3: Structure
***** Find a structure
****** Otherwise, you're just blabbering
***** One approach:
****** 1. Make list of functions necessary
****** 2. Discuss how to do input / output
****** 3. Usability for non-blind
****** 4. Summary
**** Step 4: Solve!
** 2. Estimation Questions
*** How many tennis balls can fit in an SUV?
*** How much money does Gmail make from ads every day?
*** How much do New Yorkers spend on electricity each year?
*** Estimation Qs: Why?
**** Problem Solving
**** Basic Quantitative Skills
*** Estimation Qs: How to Approach
**** 1. Ask questions to resolve ambiguity
***** Don't make assumptions (yet)
**** 2. Outline / Structure Your Approach
**** 3. Break down the components
***** Assume numbers when necessary
***** State assumptions explicitly
***** Round numbers to make your math easier
**** 4. Sanity Check
***** Do your numbers make sense?
*** How much money does Gmail make from ads every year?
**** Step 1: Ambiguous Information
***** Profit or revenue?
***** Past year? Or average over history?
***** Gmail only? Or include Google Apps?
**** Step 2: Outline Your Approach
***** (# of users) * (# of clicks / year) * ($ / click)
**** Step 3: Break down components
***** Estimate # of Gmail users in the US
****** 1. Assume 300 million people in the US.
******* Exclude 0 - 12 years old and 65 - 75 years old
******* -> ~ 200 million
****** 2. Assume 80% of people use email
****** 3. 80% of those have non-work account
****** ... and so on ...
**** Step 4: Validate Numbers
***** Could revenue be $5 billion?
***** No, because...
****** Google's annual revenue is ~ $40 billion
****** $16 / US citizen (not just Gmail users)
** 3. Software Engineering Questions
*** Coding & Algorithms
*** Object Oriented Design
*** Scalability

## Technical Questions
* 1. Ask Questions!
** Questions are more ambiguous than they appear
* 2. Talk out loud
** Show us how you think
* 3. Think critically
** Does your algorithm really work? What's the space and time complexity?
* 4. Code slowly and methodically
** It's not a race
* 5. Test your code
** And make CAREFUL fixes

## What does a "good coder" do?
* Be methodical. Don't try to rush
* Reasonably Bug Free
** Throughout testing (and careful fixing)
** Check for error conditions
* Clean coding
** Use other functions
** Good use of data structures (define own if useful)
** Concise and readable

## Types of Interview Questions
* Coding & Algorithms
** Pattern Matching <Compare to similar problems.>
*** Q: Write code to reverse the order of words in a sentence.
**** "dogs are cute"
**** "cute are dogs"
**** Similar to: reverse characters in a string.
**** "dogs are cute"
**** "etuc era sgod"
**** A: Reverse full string, then reverse each word.
** Simplify & Generalize <Solve first for a simplified / tweaked problem.>
*** Q: Design algorithm to figure out if you can build a ransom note (array of strings) from a magazine (array of strings).
**** Simlify: what if we used characters instead of strings?
**** Build array of character frequencies.
**** Generalize: how we can extend answer to words?
**** A: Build hashtable from word to frequency.
** Base Case & Build <Solve for n = 1, and build solution for n = 2.>
*** Q: Design algorithm to print subsets of set.
**** {a, b, c} => {}, {a}, {b}, {c}, {a, b}, {a, c}, {b, c}, {a, b, c}
**** S({}) => {}
**** S({a}) => {}, {a}
**** S({a, b}) => {}, {a}, {a, b}
**** S({a, b, c}) => ?
**** A: Build S(n) by cloning S(n-1) and adding n to the cloned sets.
** Data Structure Brainstorm <Try to apply data structure to solve problem.>
*** Q: There are 10^10 possible phone #s. Explain how you could effeciently implement assignSpecificNum(num) and assignAnyAvailableNum().
**** Array (sorted)? Too slow to remove num.
**** Linked list? Too slow to find specific num.
**** Hash table? Can't iterate through free nums.
**** Tree? Ah-ha!
**** A: Store free #s in BST. Remove when taken.
** Example: Reverse a Linked List
* Object Oriented Design
** Handle Ambiguity <What about the question is ambiguous?>
** Design the Core Objects <What are the main objects in the system?>
** Analyze Relationships <How are the objects related to each other?>
** Investigate Actions <What are the main operations?>
** Q: How would you design the data structure and objects for a resturant?
*** Handle Ambiguity <Is it a single resturant, or part of a chain?>
*** Design the Core Objects <Guest, Party, Table, Server, Host, ...>
*** Analyze Relationships <Server and Host are both Employees...>
*** Investigate Actions <A Party is seated at a Table by a Host...>
** Example:  Design a Parking Lot
* System Design
** Handle Ambiguity <What about the question is ambiguous?>
** Make Believe <Pretend there wasn't so much data & solve>
** Get Real <Go back to the real problem. What breaks?>
** Solve Problems <Solve the issues you just found.>
** Q: Given millions of documents, find all documents which contain a list of words.
*** Handle Ambiguity <Do the words need to be in a specific order?>
*** Make Believe <Assume everything can fit on one machine.>
*** Get Real <Must split up data across machines.>
*** Solve Problems <Divide hash table by file or by keyword?>
** Examlpe: Design a Web Crawler

## <Gulp> This is a lot of stuff. Do I need to get everything right? </Gulp>
* Evaluation is RELATIVE, not absolute.
* It's not about how quickly you solved the problem...it's about how quickly you solved it relative to other candidates.
* SO RELAX. Interviews are supposed to be hard! Everyone makes mistakes. Everyone!

## Final Thoughts
* After Your Interview
** Follow-up with your recruiter
*** No response != rejection
** You have no idea how well/poorly you did.
*** Seriously. I know you think you do. But you don't.
** Lots of randomness.
*** So if you fail, get up and try again.
