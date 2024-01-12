# SWE101: Programming Fundamentals

## Assessment 01 HTML Fundamentals

### Case Background

As part of the digital transformation initiative at a leading finance technology solutions provider, there's a strategic push towards educating the masses about personal finance. The company's vision revolves around empowering individuals to take charge of their finances through a blend of technological aid and knowledge dissemination.

As a data analyst, your primary job role requires you to analyze large datasets, derive insights, and aid the decision-making process, the current task is unique. The company believes that an analyst's precision and attention to detail are invaluable in constructing a user-centric platform. Your current assignment is to lay the groundwork for a new website segment dedicated to personal finance advice. This portal is envisioned as a valuable resource for beginners, aiming to simplify complex financial jargon and present actionable financial strategies.

Using the knowledge of data representation and understanding of user behavior you've amassed over the years, your challenge is to structure the website in a way that's intuitive, engaging, and most importantly, informative. Remember, while the company has web developers and designers to add the bells and whistles, they are counting on your expertise to ensure the content's logic, flow, and structure are spot on. Your proposed structure will serve as the blueprint upon which the entire portal will be built.

### Objective

As a data analyst, you've been entrusted with the foundational task of this project, a testament to the significance of clear data communication in decision-making. This assignment isn't just about coding a webpage, but weaving a digital narrative that aligns with the company's vision. Your goal is to craft an intuitive and comprehensive webpage layout that displays crucial financial indicators and advice. By marrying your analytical skills with a user-centric approach, you are set to create a platform that demystifies finance, making it accessible and engaging for all. Remember, it's not just about presenting data but enlightening individuals to make informed financial choices, shaping their futures.

### Section 1: Basic HTML Structure (10 points)

#### Task 1.1

Create an HTML file named index.html. Inside this file, establish the basic HTML structure. This includes the DOCTYPE declaration, the opening and closing HTML tags, the HEAD and BODY sections. (2 points)

#### Task 1.2

Within the HEAD section, add a TITLE tag that reads "Personal Finance Advice". (2 points)

#### Task 1.3

Within the BODY section, add a HEADER with an H1 tag that reads "Welcome to Personal Finance 101". (3 points)

#### Task 1.4

Create a MAIN section right after the HEADER, this section will house the content of the webpage. (3 points)

### Section 2: Text Formatting, Anchor Links, and Lists (20 points)

#### Task 2.1

Inside the HEADER, create a NAV section below the h1 with anchor links to "#Budgeting" with the text "Budgeting Basics", "#Savings" with the text "Savings Strategies", and "#Debt" with the text "Debt Management". (5 points)

#### Task 2.2

Inside the MAIN section, create an article with an H2 tag that reads "Budgeting Basics", and an id of "Budgeting". This id be associated with the anchor tag "#Budgeting". Format two paragraphs below the heading explaining the importance of budgeting. (5 points)

#### Task 2.3

Within the MAIN section, create a new article with an H2 tag that reads "Savings Strategies", and an id of "Savings". This id be associated with the anchor tag "#Savings". Below the heading, create a list of three strategies for saving money. (5 points)

#### Task 2.4

Repeat the same for "Debt Management". (5 points)

### Section 3: Images (15 points)

#### Task 3.1

Find suitable images for "Budgeting Basics", "Savings Strategies", and "Debt Management" articles and embed them just below the respective headings. (15 points)

(Repeat for other articles)

### Section 4: Form, Input, and Button (30 points)

#### Task 4.1

Create a SECTION at the end of the MAIN section. This will include a form for users to subscribe to a financial advice newsletter. (10 points)

#### Task 4.2

Within the form, include an input field for the user's email, a checkbox asking if they'd like to receive weekly updates, and a submit button. (20 points)

### Section 5: Footer (15 points)

#### Task 5.1

Create a FOOTER section that includes the copyright notice and the current year. (5 points)

#### Task 5.2

Add a "Contact Us" link and a "Terms of Service" link in the footer. (5 points)

#### Task 5.3

Add a small description about the webpage or any other additional relevant information in the footer. (5 points)

---

Expected outcome (without red marking)
![](./resources/swe_101_assignment_01_img.png)

---

## CHALLENGE

Create 3 different page for each category: Budgeting Basic, Savings Strategies, and Debt Management.

- **/** should link to the Budgeting Basic page
- **/saving** should link to the Savings Strategies page
- **/debt** should link to the Debt Management page
Expected outcome (without red marking)
<div style="display: flex;">
<img src="./resources/swe_budgeting_example.png" alt="budget" width="250" />
<img src="./resources/swe_saving_example.png" alt="saving" width="250" />
<img src="./resources/swe_debt_example.png" alt="debt" width="250" />
</div>

### Challenge Guide

1. Duplicate the main file twice (3 .html file in total)
2. Rename one file to `saving.html` and another to `debt.html`
3. Delete the Saving and Debt article from the original file.
4. Do the same for `saving.html` (removing Budgeting, and Debt article) and `debt.html`
5. Update the `<a>` href link to the corresponding page. `./` points to the current folder. `./debt.html` would point to the `debt.html` in the current folder.
6. Once completed, git add, commit, and push it to github repository.

### GitHub Guide

1. `$ git add .` this add all updated files to staging
2. `$ git commit -m "a random message"` this shift the staged updates to local repository.
3. `$ git push` this push the updated local repository to github repository.
