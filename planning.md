<header>

# STUDENT BUDGETING AI 

</header>

This ai will take in a student's major (maybe schedule also?) and show what classes they MUST take

This will be done using a dataset that will compile a list of UIUC grainger engineering school's majors and their corresponding prerequisites

- Will be for incoming freshmen as they all need the same general education requirements
- Will omit classes that are completely useless to the major - thus saving the student money
- Cost per class will be calculated, maybe credit hour options can be shown?

the AI will intake school name and gives back a list of opportunities for the user in saving money to pay for their tuition 

the dataset we create will then include name of the school, and the name of opporunity in each category (scholarship, grant, jobs, paid internships)

- MEETING WITH MS BELLITO on what students have the most questions about related to college financing

Paying each credit hour: https://www.bestcolleges.com/research/college-cost-per-credit-hour/#faq 

PROBLEM STATEMENT:

Students have issues paying for college due to:

1. Insufficient information on student loan debt
https://www.bestcolleges.com/resources/college-loans/

https://www.consumerfinance.gov/paying-for-college/repay-student-debt/

LOAN SIMULATOR (can utilize within website for those trying to calculate their initial costs) https://studentaid.gov/loan-simulator/


LOAN CALCULATOR https://smartasset.com/student-loans/student-loan-calculator

3. Taking unneccesary classes
Some type of schedule checker to create the most efficent way to graduate for the user

4. Paying off loans while in college:
https://www.nerdwallet.com/article/loans/student-loans/3-ways-to-reduce-student-loan-debt

5. Work experiences on campus, finding on-site payable opportunities for the user (who inputs their college)
6. Scholarships (a highly tailored scholarship search) - emphasis put on scholarships that are ATTAINABLE

7. Applying for student loan forgiveness
https://studentaid.gov/manage-loans/forgiveness-cancellation

8. DAY TO DAY EXPENSES: college students may need a tracker to see how much they are paying food,supplies, etc

Use of AI in college campuses: https://edtechmagazine.com/higher/article/2019/07/ai-has-potential-ease-campus-budget-burdens

 AI-powered budgeting app https://web.meetcleo.com/budget 


![image](https://github.com/bistii1/StudentBudgetingAI/assets/142824913/e547a634-8083-4e26-b837-372dbb353d39)

College budgeting template: https://www.notion.so/templates/college-budgeting-template

Minimizing student loan debt through smart spending: https://www.usnews.com/education/best-colleges/paying-for-college/slideshows/10-steps-to-minimize-student-loan-debt

<header>
 
 # More than 3 of 4 Americans believe paying for college is a challenge 
 77% of US adults say a college degree is unattainable due to the price
 
</header>

people think college is a waste of money: https://www.intelligent.com/1-in-3-recent-high-school-grads-skipping-college-because-its-a-waste-of-money/#:~:text=As%20college%20costs%20continue%20to,they%20can't%20afford%20it. 

solutions: increasing access to resources for education (online college, ways to get grants, less competitive scholarshps) 
PATHWAYS algorithim?
User starts on a screen and taps multiple aspects of their financial situation, which will result in a tailored end-screen on the resources that would help their specific situation.

AI Implementation would come in by training an LLM on the text the user inputs (through typing) and picking up on themes that will result in a more helpful end result 

working spreadsheet: https://docs.google.com/spreadsheets/d/1Vqpb1UCgND79CX3bfYcb5UugXMH6p40w2lFxcr_gnG0/edit#gid=0 


1. **Project Overview:**
    - Can you provide a brief overview of your project and its objectives?
    
  Our projects helps prospective college students in saving money and lessening their risk of falling into debt as they pay for college

 2. - What problem does your project aim to solve, and why is it important?
   
     Our project aims to solve the problem of students overpaying for college and falling into student loan debt that is most often crippling to many families - it is an issue such a widespread group of people experience as college education keeps getting more and more expensive. Everyone needs increased exposure to resources available to alleviate the consequences of student loan debt 

3. **MVP Definition:**
    - What features or functionalities have you identified as essential for the minimum viable product (MVP)?
    - 
      A website with updating information on the MVP
      Finding a small-scale hugging face model to train to be knowledgable on processes college payment    
   We need to train a chatbot that is equipped with answering questions on the college application process as it pertains to paying for college.

    - How did you decide on these specific features for the MVP?
  
 Website: this will serve as our base for the chatbot, and serve as a place for kids to recieve more information on their personal college situation.
   We know we need heightened resources for kids wanting to pay for college, and not everyone can afford a personal college counselor, so the chatbot built into the website will offer 24/7 personalized help with college finances to those who need it.

4. **Progress and Development:**
    - What progress have you made so far in developing the MVP?

I have tried to run 3 separate models for the chatbot, but I need to look at more models that are small enough to run in a replit environment 

Looked at llama-chat-gpt-neo3 model, beluga-3 model, llama-chat-gpt-neo

    - Can you show me the components or prototypes you've developed for the MVP?


Problem: Many college students face significant financial challenges that impact their ability to afford higher education and maintain academic performance due to a lack of financial understanding and awareness of resources available to them.

Affordability Gap: Roughly two-thirds of undergraduates are paying more for college than is recommended by a common benchmark for affordability, indicating a financial burden on students.
Decrease in Merit Financial Aid: The top method of paying for college, merit financial aid (scholarships and grants), decreased from 64% in 2019 to 51% in 2022, indicating a potential decrease in financial support for students.

Financial Challenges: College students face various financial challenges, including tuition fees, living expenses, textbooks, and unexpected costs, which can lead to financial stress.

Food and Housing Insecurity: A significant percentage of college students experience food insecurity (48%) and housing insecurity (41%), further exacerbating their financial difficulties.

Impact on Academic Performance: Financial stress has been linked to lower GPAs and higher dropout rates, indicating that financial challenges affect students' academic performance.

Lack of Financial Literacy: Many college students lack basic financial literacy skills, making it difficult for them to manage their finances effectively.

Missed Financial Aid Opportunities: Students may not be fully aware of available financial aid opportunities, leading to missed opportunities for financial support.

Underutilized Federal Work-Study Program: A significant number of eligible students do not take advantage of the Federal Work-Study program, missing out on potential income opportunities.

Low Financial Literacy Among Millennials: Only 24% of millennials demonstrated basic financial literacy, highlighting a lack of financial education among young adults.

<header>
# Solution: Implement AI-driven chat bot that will help students find resources on campus that wil help them save, earn, and budget their money
</header>

Personalized Budgeting Apps: AI-powered budgeting apps can help students track expenses, create budgets, and set savings goals, offering personalized financial advice.

Financial Aid Optimization: AI can assist students in identifying available financial aid options, including scholarships, grants, and work-study opportunities, ensuring they access all available resources.

Predictive Analytics for Financial Health: AI can analyze students' financial data to predict potential challenges and provide alerts and recommendations to avoid financial crises.

Student Debt Management: AI-driven platforms can help students manage student loan repayment plans efficiently, optimizing repayment options based on their financial situation.

Financial Education and Resources: AI chatbots can provide students with 24/7 access to financial information, budgeting tips, and direct them to relevant financial literacy resources.

Early Warning Systems: AI can identify early signs of financial distress by analyzing students' spending and academic performance, allowing institutions to intervene with support services.

Behavioral Nudges: AI can send personalized reminders and nudges to encourage responsible financial behavior, promoting savings and responsible spending.

Raise Awareness of Financial Aid Opportunities: Use AI-driven campaigns to inform students about available financial aid options, ensuring they do not miss potential sources of support.

Promote Federal Work-Study Program: AI can be used to match eligible students with suitable work-study opportunities, increasing their utilization of the program.
Enhance Financial Literacy: Implement AI-based educational tools to improve financial literacy among college students, addressing the lack of financial knowledge.
College counselor chatbot:


  
