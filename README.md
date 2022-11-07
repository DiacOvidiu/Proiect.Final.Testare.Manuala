# DiacOvidiu


**DemoBlaze** - https://demoblaze.com/

For the testing process I chose the website DemoBlaze. I covered a set of nine requirements that will be detailed below:

Project Requirements

 - The user should be able to register
 - The user should be able to login using a registered account
 - The user should be able to browse the store
 - The user should be able to add a product to the cart
 - The user should be able to customise the cart (add, update, delete)
 - The user should be able to search
 - The user should be able to reset their password via email
 - The user should be able to change password or email
 - The user should be able to user the application on mobile also (mobile friendly)

**Project Roles/Needs**

 - 1 Lead developer
 - 1 senior developer
 - 2 mid/junior developers
 - 1 QA Lead
 - 1 senior QA
 - 2 mid/junior QA
 - 1 Project Manager

**Entry Criteria**
1. Complete or partially testable code is available.
2. Requirements are defined and approved.
3. The project must be completed in 8 months.

**Exit Criteria**
1. Deadlines met or budget depleted.
2. Execution of all test cases.
3. Availability of sufficient and desired test data.
4. Test environment has been set-up and all other necessary resources such as tools and devices are available.
5. Desired and sufficient coverage of the requirements and functionalities under test.
6. All the identified defects are corrected and closed.
7. No high priority or severity or critical bug has been left out.

**Risks**
 - the amount of man power might not be enough
 - the time needed in order to complete the project might extend
 - financial risks is the possibility of losing money in a business venture or investment. There are several types of financial risks, such as credit risk, liquidity risk, and operational risk.
 - the need of additional maintenance needed


**Test case design** (based on Project stories)

**Project Epic**
 - [**Project Epic - Requirements**](https://github.com/DiacOvidiu/Proiect_final/blob/main/Epic.JPG)


**Project Stories**
 - [**The user should be able to register**](https://github.com/DiacOvidiu/Proiect_final/blob/main/story_sign.up.JPG) 
 - [**The user should be able to login using a registered account**](https://github.com/DiacOvidiu/Proiect_final/blob/main/story_sign.up.JPG)
 - [**The user should be able to add a product to the cart**](https://github.com/DiacOvidiu/Proiect_final/blob/main/story_add.product.JPG)
 - [**The user should be able to see information about the company**](https://github.com/DiacOvidiu/Proiect_final/blob/main/story_about.us.JPG)
 - [**The user should be able to contact the company**](https://github.com/DiacOvidiu/Proiect_final/blob/main/story_contact.JPG)
 - [**The user should be able to select the category of a product**](https://github.com/DiacOvidiu/Proiect_final/blob/main/story_categories.products.JPG)
 - [**The user should be able to see information about the products added to the cart**](https://github.com/DiacOvidiu/Proiect_final/blob/main/story_cart.JPG)
 - [**The user should be able to change his account password**](https://github.com/DiacOvidiu/Proiect_final/blob/main/story_reset.pass.JPG)
 - [**The user should be able to user the application on mobile also (mobile friendly)**](https://github.com/DiacOvidiu/Proiect_final/blob/main/story_mob.comp.JPG)

**Project Test Cases**
 - [***Search product: Check that the previous and next buttons are not accessbile when we are accessing the last product in the category***](https://github.com/DiacOvidiu/Proiect_final/blob/main/search%20product.jpg)
 - [***User registration with number data at username***](https://github.com/DiacOvidiu/Proiect_final/blob/main/test_signup.jpg)
 - [***Checking the connection of an account that has the wrong password***](https://github.com/DiacOvidiu/Proiect_final/blob/main/test_login_w.pass.JPG)
 - [***Check the functionality to add a product***](https://github.com/DiacOvidiu/Proiect_final/blob/main/test_add.prod.jpg)
 - [***Check the functionality of placing an order***](https://github.com/DiacOvidiu/Proiect_final/blob/main/test_place.ord.jpg)
 
 Out of all the stories in scope, the following test cases have been created and executed, covering 9 stories, as you can see in the traceability matrix below.

**Test Execution**
 - [**TestCycle1**](https://github.com/DiacOvidiu/Proiect_final/blob/main/test%20cycle.JPG)
 - [**TestCycle2**](https://github.com/DiacOvidiu/Proiect_final/blob/main/Test%20Execution%20by%20cycle.jpg)

**Project Issues**
 - [**Placing an order without having a product in the shopping cart**](https://github.com/DiacOvidiu/Proiect_final/blob/main/bug_order.without.product.JPG)

   https://github.com/DiacOvidiu/Proiect_final/blob/main/Bug%20Place%20Order.JPG
   
 - [**Categories Products issue**](https://github.com/DiacOvidiu/Proiect_final/blob/main/bug_categories.product.JPG)

   https://github.com/DiacOvidiu/Proiect_final/blob/main/Categories%20Products%20bug.mp4



**Traceability Matrix**
 - [**TracebilityMatrix**](https://github.com/DiacOvidiu/Proiect_final/blob/main/Traceability%20Matrix.JPG)


After testing, two bugs were reported to the development team: one of high severity and high priority (the user can place without having products in the cart), and one of low severity and medium priority (the "next" button " and the "previous" button in filtering by category and activated even when there are no more products in that category
