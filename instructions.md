<h1>Machine Learning Engineer Assignment</h1>

We're excited about your interest in SimPPL! This assignment is designed to give you a taste of the kind of data engineering challenges we tackle.  You'll build a system for collecting and analyzing social media data, with a focus on scalability and robust design. You will need to build a basic data collection platform to collect data from some fringe social networks within platform terms of service, in order to answer the question

<h2>Platform Choices </h2>h2
Some examples that may guide you in learning more about smaller platforms including some so-called fringe platforms (since there are existing data collection tools for these platforms already), in order of priority for the kinds of platforms we’d like to see you analyze. 

Note: Pick one or two platforms at max.

1. Gab

2. Threads (Meta)

3. ShareChat

4. Koo

5. 4chan

6. Telegram

7. Bitchute

8. Rumble

9. Moj

10. Mastodon

11. VK

<h2>Why do we care about this? </h2>

We have tools for curating and analyzing data from Reddit and Twitter and we built https://parrot.report (see this video in case the site is under maintenance—which it is right now) to study the sharing of news from certain unreliable Russian media providers. To ramp you up towards understanding how to go about this, and to expand your understanding of the broader social media ecosystem, we would like to extend our analysis to other publicly available platforms listed above to get a broader range of viewpoints from different (apolitical/politically biased) groups. In the long run, this research intends to accomplish the following objectives:

1. Track different popular trends to understand how public content spreads on different social media platforms.
   
2. Identify posts containing misinformation with the use of fact-checking mechanisms.
   
3. Analyze the trends across lots of accounts over time and report on how information spreads.

<h2>Task Objectives</h2>

1. Data Collection: Develop a scraper to collect data from a social media platform of your choice (see the list below). Your scraper should collect post content, engagement metrics (likes, shares, etc.), user information, and timestamps.
   
2. System Design: Create a system design (in words and with a diagram) that explains how your data collection solution could be scaled to handle a large volume of data and potentially multiple social media platforms. Consider cloud infrastructure, data storage, processing pipelines, and any APIs or services you would use.

3. Dashboard Development: Build a basic dashboard to visualize some of the collected data. This dashboard should demonstrate your ability to present data in a clear and informative way.

<h2>Rubric for Evaluation</h2>

1. Functionality: Does the scraper work reliably and collect the required data?

2. Scalability: Is the system design well-thought-out and scalable? Does it address potential challenges of handling large datasets and multiple platforms?

3. Documentation: Is the code and system design well-documented and easy to understand?

4. Dashboard: Is the dashboard functional and does it present data effectively?

5. Diagram: Is the system diagram clear, well-labeled, and informative? Does it effectively explain the proposed architecture?

Bonus Points:

Cloud Infrastructure: Demonstrate knowledge of cloud platforms (AWS, GCP, Azure) in your system design.
Data Processing: Incorporate data processing techniques (e.g., cleaning, transformation) into your pipeline.
Efficient Storage: Show an understanding of efficient data storage solutions (databases, data lakes).

<h2>Instruction for the submission</h2>
These instructions outline how to use GitHub for this assignment.  Please follow them carefully to ensure your work is properly submitted.

1. Fork the Repository:
   
  a. Go to the assignment repository provided by the instructor: [Insert Repository Link Here] 
  
  b. Click the "Fork" button in the top right corner of the page. This creates a copy of the repository in your GitHub account. 
  
2. Clone Your Fork:
   
  a. Go to your forked repository (it will be in your GitHub account).
  
  b. Click the "Code" button (the green one) and copy the URL. This will be a git URL (ending in .git).
  
  c. Open a terminal or Git Bash on your local machine.
  
  d. Navigate to the directory where you want to work on the assignment using the cd command. For example: cd /path/to/your/projects.
  
  e. Clone your forked repository using the following command: git clone <your_forked_repository_url> (Replace <your_forked_repository_url> with the URL you copied).
  
This will download the repository to your local machine.

4. Develop Your Solution

Work on your assignment within the cloned repository. Create your code files, visualizations, and any other required deliverables. Make sure to save your work regularly.

6. Commit Your Changes
   
  a. After making changes, you need to "stage" them for commit. This tells Git which changes you want to include in the next snapshot.
  
  b. Use the following command to stage all changes in the current directory: 
    i. To add all the files - git add. <br>
    ii. Or, if you want to stage-specific files - git add <file1> <file2> ...
  c. Now, commit your staged changes with a descriptive message- git commit -m "Your commit message here" (Replace "Your commit message here" with a brief1 description of the changes you made.2 Be clear and concise!)  <br>  
  d. push your commits back to your forked repository on GitHub- git push origin main (Or, if you're working on a branch other than main, replace main with your branch name. origin refers to the remote repository you cloned from). 
  
8. Please notify us of your submission by emailing simppl.collabs@gmail.com with the subject line "Applicant for SimPPL".

<h2>Things to keep in mind while submitting your assignment</h2>
Please ensure you include:
1. A detailed README file (with screenshots).

2. A detailed script for us to understand your code and thought process. 

3. A link to a documentation or (system design if you have created one). 

4. Both of these make it easier for us to run your code and evaluate the assignment.

<h3>Note</h3>

Focus on quality over quantity. A well-designed and scalable system is more important than a complex one.
Presentation matters! Make sure your submission is easy to understand.
Why We Care About This:

We're building tools to analyze how information spreads on social media, especially from unreliable sources. Your work will help us understand how to scale our analysis to a wider range of platforms and handle larger datasets. This is crucial for tracking trends, identifying misinformation, and understanding how narratives spread online.

We're excited to see your solution!

