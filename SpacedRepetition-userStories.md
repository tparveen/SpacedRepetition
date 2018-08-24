#### User Stories and Acceptance Criteria
#### ======================================

User Story: As an user, I want to know the name and the purpose of the spaced repetition application, so that I can decide whether I want to continue interacting with it.

    Acceptance Criteria:
        When I visit the the spaced repetition site, I see the name of the learning app, and a  brief description 
        of what the app does.

----

User Story: As an user, I want to create an account so that I can use the app.

    Acceptance Criteria:
        When I visit the the spaced repetition site for the first time, I should be directed to a registration page
        On that page, I can enter my name, username, and password 
        My password should be at least 10 characters long
        If all information is correct, upon clicking the submit button, I should be taken to a login page
        If the information is incorrect, I should be given proper error messages and option to enter the 
        correct information
     
---

User Story: As a registered user, I should be able to log into my account, so that I can use the app

    Acceptance criteria:
        When I visit the the spaced repetition site, I should be able to go to a login page
        I can enter my username and password
        If my username and password is correct then the app should accept them and greet me with a message 
        "Hello MY_NAME"
        If my username and password is incorrect then the app should reject my information and the give me meaningful 
        message so I can try to log in again

---

User Story: As a logged in user, I am presented with a word so that I can learn the meaning of the word

    Acceptance criteria:
        When I log into my spaced repetition app, I am presented with a word that I want to learn
        I am given an input box to type the meaning of the word
        I am given a submit button to submit my answer  

---

User Story: As a user, I am given feedback to my answer so that I learn the word 

    Acceptance criteria:
        When I click on the submit button, I should get a response for correct answer
        If the answer is wrong, I should get a feedback as well as the correct answer so I can learn 
        the correct answer and get it right the next time.
      
---

User Story: As a user, when I am using the app, I should be able to move to the next word so I can learn more words 

    Acceptance criteria:
        When I learn a word, I should see a next button to move to the next word
      
---

User Story: As a user, when I am using the app, my progress should be recorded so I know which questions I got correct or wrong

    Acceptance criteria:
        When I get a word correct, I should get a score if I get that word correct
        When I get the word wrong, my score for that word should be deducted

---

User Story: As a user, I should see the words based on the spaced repetition algorithm, so that I can learn by frequently seeing the word that I have hard time remembering

    Acceptance criteria:
        When I get a word correct, I should see that word at a later time
        When I get the word wrong, I should see the word more frequently
      
---

User Story: As a user, I should be able to move through the words for as long as I want so that I can learn for as long as I want

    Acceptance criteria:
        Once I log in and start learning, I should be able to see the words based on the spaced repetition algorithm
        I can click the finish or reset button to finish any time
        Otherwise, unless I hit finish, I should be able to move through the words without any ending
      
---

User Story: As a user, I should be able to see my overall progress so that I know which words I need to learn more

    Acceptance criteria:
        When I log into my account, I should be able to click a progress button and see my overall progress
        As I am learning, I should be able to click on the progress button and see my overall progress updated 
        to reflect my current progress 
      
---

User Story: As a user, I should be able to successfully log out of the spaced repetition app so that I can rest my brain

    Acceptance criteria:
        When I click on the logout button, all my session data should be removed from the UI and I should 
        see a message that I have successfully logged out
      