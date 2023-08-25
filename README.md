# WebShop_TestCase

## User Story
| User Story  | Description | Acceptance Criteria | Preconditions |
|-------------|-------------|--------------------|----------------|
| US_01 | Create User Account | As a user, I should be able to register to our web store, so I can shop and access other features. | - I should be able to click the "Register" button on the homepage. <br> - After entering my personal information, I should be able to register successfully by clicking the "Register" button. <br> - I should be able to confirm that the registration process is successful. | - The browser (Chrome, Safari, or Firefox) where the test scenario will be run must be installed and started. <br> - Internet access should be provided in the test environment. <br> - The current password should be at least 6 characters long. |
| US_02 | Negative | Create User Account | As a user, I would like to see what kind of error I received when I try to register with the same e-mail address while registering to our web store. So I can give users a better shopping experience. | - I should be able to click the "Register" button on the homepage. <br> - When I try to register with the same e-mail address, I should be able to view the message "The Specified Email Already Exists". | - The browser (Chrome, Safari, or Firefox) where the test scenario will be run must be installed and started. <br> - Internet access should be provided in the test environment. |
| US_03 | Logout | As a user, I should be able to exit my account from my web store. So my shopping becomes safer. | - The user should be able to exit the account. <br> - When the user successfully closes the session, it must be directed to the login page. | - The user must have logged in to the website. |
| US_04 | Login | As a user, I should be able to log in to our web store, so that I can manage my account information, shop, and access other features. | - I should be able to click the "Login" button on the homepage. <br> - After entering the valid e-mail and password information, I should be able to log in successfully by clicking the "Login" button. <br> - I should be able to confirm that the login is successful. | - The user's account (user's e-mail address and user's password) must be successfully created and verified. |
| US_05 | Negative | Login | As a user, I want to test various negative scenarios when logging in to our web store, so I can be sure that there is a safe entry mechanism. | - I should be able to click the "Login" button on the homepage. <br> - When I try to log in by leaving the e-mail and password part empty, I should be able to view the message "Login Was UNSuccessful". <br> - When I try to log in with a valid e-mail and an empty password, I should be able to view the message "Login Was UNSuccessful". <br> - When I try to log in with an empty e-mail and a valid password, I should be able to view the message "Login Was UNSuccessful". <br> - When I try to log in with invalid e-mail or password information, I should be able to view the message "Login Was UNSuccessful". | N/A |
| US_06 | Ordering | As a user, I should be able to order products from our web store, so I can buy and pay for the products I want. | - I should be able to select a product from the product list on the homepage. <br> - I should be able to successfully add the product to the basket by clicking the "Add To Cart" button for the product I have selected. <br> - I should go to the basket page and confirm that the product I selected is displayed in my basket. <br> - For cargo information, I should be able to select the appropriate options from "Select Country" and "Select State" fields. <br> - I should be able to mark the "Agree" confirmation box to accept conditions. <br> - I should be able to start payment by clicking the "Checkout" button. <br> - By following the steps below, I should be able to complete the order: <br> &emsp;a) I should be able to enter the invoice address and continue. <br> &emsp;b) I should be able to select the "In-Store Pickup" option and confirm that the shipping address is lost, then continue. <br> &emsp;c) I should be able to choose the payment method and continue. <br> &emsp;d) I should be able to verify the payment method in the "Payment Information" section and continue. <br> &emsp;e) I should be able to verify that the total price of the product matches the calculated sum. <br> - I should be able to confirm the order by entering the payment information. <br> - By viewing the message "Your Order Has Been Successfully Processed!", I should be able to confirm that the order is successfully completed. | - The browser (Chrome, Safari, or Firefox) where the test scenario will be run must be installed and started. <br> - Internet access should be provided in the test environment. <br> - It should be confirmed that the products and prices are correctly displayed. <br> - The user's account (user's e-mail address and user's password) must be successfully created and verified. <br> - To order, the system must be logged in. |
| US_07 | Survey Response | As a user, I should be able to answer surveys like "Community" on our web store. There should be a "Submit" button to send the response. After sending my response, I should be able to view the message "Only Registered Users Can Vote" (if I am not logged in). After logging in, I should be able to view a result page displaying the responses. This way, customers who share their opinions can strengthen their connection with the web store. | - I have to see the survey "Community Pool" on the homepage. <br> - To answer the survey, I should be able to choose one of the options: "excellent," "good," "poor," or "very bad." <br> - There should be a "Submit" button to send the response. <br> - After sending my response, I should be able to view the survey results. <br> - The results should display the number of votes for each option. | - The browser (Chrome, Safari, or Firefox) where the test scenario will be run must be installed and started. <br> - Internet access should be provided in the test environment. <br> - If user login is required, I should be able to log in with a valid username and password. |
| US_07 | Negative | Using Coupons and Gift Cards | As a user, I should be able to use coupon codes while shopping from our web store and add gift cards. This helps me save money and earn rewards during my shopping experience

. | - I should be able to select a product from the "Computers" category on the homepage. <br> - I should be able to add the selected product to the basket by clicking the "Add To Cart" button. <br> - By going to my basket, I should be able to confirm that the selected product is displayed. <br> - I should be able to add a coupon code for the product in my basket by clicking the "Apply Coupon" button. <br> - After adding the coupon code, I should be able to confirm that the coupon is successfully applied. <br> - I should be able to add a gift card by clicking the "Add Gift Card" button. <br> - After adding a gift card, I should be able to confirm that the card is successfully added. <br> - I should be able to start payment by clicking the "Checkout" button. <br> - By entering the payment information, I should be able to confirm the order. <br> - By viewing the message "Your Order Has Been Successfully Processed!", I should be able to confirm that the order is successfully completed. | - The browser (Chrome, Safari, or Firefox) where the test scenario will be run must be installed and started. <br> - Internet access should be provided in the test environment. <br> - Coupon codes and gift cards must be applied accurately to the user's account. |
| US_08 | Download Order History | As a user, I want to see the history of the orders I've placed on our web store and be able to download the invoice of any order. This allows me to keep track of my past purchases and obtain order documents. | - I should be able to access my account by logging in on the homepage. <br> - On my account page, I should see a link such as "My Account (your email address)" and be able to view my account information by clicking this link. <br> - On the account information page, I should see a link called "Orders" or "Siparişler" and be able to view my order history by clicking this link. <br> - On the order history page, I should see the most recent order and other past orders. <br> - To access the details of an order, I should be able to click on the relevant order number. <br> - On the Order Details page, I should be able to download the invoice for the order. | - The browser (Chrome, Safari, or Firefox) where the test scenario will be run must be installed and started. <br> - Internet access should be provided in the test environment. <br> - The user's account information and order history data must be presented accurately. |

Lütfen yukarıdaki tabloyu kopyalayıp Github README.md dosyanıza yapıştırabilirsiniz.