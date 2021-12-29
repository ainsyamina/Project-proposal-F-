# Project-proposal-F-
Group Member Details (Name & Matric No).
1. Muhammad Afiq Bin Munir (1818931) - LEADER
2. Nurul Jannah Binti Hussain (1811252)
3. Nur Ain Binti Ishak (1810052) 
4. Nurul Ain Syamina binti Noorafandi (1814584)
5. Iman Nurzawani Binti Osman (1814246)

b) Title: I Scream Ice Cream.

c) Introduction

For this group project we have chosen to create a mobile application store to sell ice cream Malaysia called ‘I Scream Ice Cream’. The mobile application platform 'I Scream Ice Cream' specializes in selling traditional Malaysian ice cream made and handled by IIUM students. The purpose of the project is to enhance the customer experience in buying ice cream Malaysia through mobile application. The user should be able to register and login to use this mobile application. There’s 5 flavours to choose from in the application. The ice cream can be ordered from wherever customers are, but only within IIUM. The order will be delivered once payment has been completed.

d) Objective of the proposed mobile application.
- Opportunities for students to generate income by doing part time jobs.
- Promote Malaysia product to International student
- Re-introduce Malaysia ice cream that nearly extinct 
- To provide the customers an easy format of ordering their desired deserts in an easy manner.
- To provide the easy billing and order format to the customers and workers in the store.

e) Features and functionalities of the proposed mobile application.
- Signup
- Login
- Ice Cream Menu
- Add to Cart page
- Payment page
- Delivery Location page
- Logout button
- Map API

f) Properly define the screen navigation (routing) and components (presentational and
container) implementation with a diagram.

![WhatsApp Image 2021-12-29 at 7 58 28 PM](https://user-images.githubusercontent.com/55817657/147659901-0e3a8c91-1773-4cbf-8bf7-4a7a2bff3f3c.jpeg)

Customer: use One-to-Many relationship. The relationship is between customer and order attributes. A customer can places many order for the ice cream

Order: use One-to-Many relationship. The relationship is between order and product attributes. One ice cream product can be ordered many times as the customer wants.

g) A sequence diagram to represent the interaction of the proposed mobile application.
1. Signup 

![signup](https://user-images.githubusercontent.com/55817657/147641606-1455cb11-26ff-4da9-a2e1-fc73d3c8b60c.png)

Figure 1: Sign Up Sequence Diagram

The user clicks the Sign Up button and is required to fill in their details. After the user fills in their details they must click the Submit button. After the user enters the information, the system will verify it and create an account for them. They will then be redirected to their account login page. 

2. Login 

![login](https://user-images.githubusercontent.com/55817657/147641686-70bb8a1a-8d6d-4aaf-b8f5-5fa99bca3089.png)

Figure 2: Login Sequence Diagram

After clicking the login button, the password and username will be validated through the database system. Once the database system finds the matching username and password,it will be verified. Login successful message will appear.

3. Add to cart 

![add to cart](https://user-images.githubusercontent.com/55817657/147641735-01c7612c-739a-4c26-b418-fd3ceaf8248d.png)

Figure 3 : Add to Cart Sequence Diagram

Users can select the ice cream flavor that they want and add their ice cream to cart. At the cart the user can select the quantity that they want then can go to the payment page. Users also can cancel their order in the add to cart page.

4. Delivery location 

![delivery location](https://user-images.githubusercontent.com/55817657/147641899-da1f2213-56b1-4f29-998d-76d0a1601ecf.png)

Figure 4: Delivery location sequence diagram

In the application, after the user selecting their favorite ice cream, users are prompted to enter their location for delivery. The system will then request the user's location from the database, and the database will provide it to the system to display to the user.

5. Payment 

![payment](https://user-images.githubusercontent.com/55817657/147641818-d96e0b01-55e8-4249-bfb6-43ffc8f9bcb7.png)

Figure 5: Payment Sequence Diagram

After users add their ice cream into the cart, users will go to the payment page and choose payment option either they will pay online or cash of delivery. For cash delivery, users will pay when we deliver their orders to their home. Meanwhile, for the online payment, users will enter the card details and the bank will verify their account. After the confirmation, users successfully pay for their order and wait untils it is delivered to their home.
