# overview

Software Requirements Specification(SRS), describes the requirements and the nature of the application or the software that is to be developed. The main purpose of this software is to build systems, this document illustrates the functional and non-functional requirements of our website.

# Functional Requirements

### 1)Login:

FR1: The user shall register into their own account with their user details.
FR2: The user shall log in to their respective account.
FR3: contact details of the customer, such as email and phone number, are to be collected and stored in the database.
FR4: Forgot password button present under the login/sign-in plot is very necessary.
FR5: Functionality of all buttons present on the login page is mandatory.

### 2)Homepage:

FR6: The website will be launched, and the items will be shown.
FR7: On the website, the products that will be sold will be shown.
FR8: The website should show all the products that match the search.
FR9: Functionality of the search function is essential.
FR10: availability of the products should be shown.

### 3)Customer:

FR11: Users can select the category, sell, buy, or donate. Items will be shown according to the selected criteria.
FR12: The user can search for information about items and see all relevant information about them.
FR13: The user can get discounts on some things they buy.
FR14: The website notifies the user when a matched product is located.
FR15: Customers can manage the product quantity they want to order

### 4)Cart: 

FR16: The user can choose items and put them in the shopping cart.
FR17: The pricing will automatically update after the buyer has added all necessary products to their shopping basket.
FR18: The price increase respectively as the customer keeps adding items to the cart.
FR19: Items in the cart can be removed if the user decides to drop the item.
FR20: Total price of the order will be displayed at the bottom of the page.


### 5)Payment:

FR21: We can move forward with the payment based on the payment.
FR22: The website will take the customer to how they can pay.
FR23: The buyer must visit the payment page to place an order.
FR24: The check-in page should show the total bill, and the taxes applied.
FR25: All the payment gateways should work for a successful transaction.



# Non-Functional Requirements

### 1)Login: 

NFR1: Theme of the login page 
NFR2: The use of fonts on the login page is not mandatory.
NFR3: Number of characters for a password is not mandatory
NFR4: Password can be any characters like numbers, alphabets, etc
NFR5: Pictures present on the login page are not that important 


### 2)Homepage:

NFR6: When a customer is connected to the server, any changes made to the website will be shown to them.
NFR7: Additional deals and discounts must be provided on the order page.
NFR8: The website shall be flexible enough to make changes depending on customer feedback.
NFR9: The user details and interests shall be saved automatically by user selection.
NFR10: Waiting time for the display of the items while loading
NFR11: Theme of the first page of the website
NFR12: Alignment of the items on the homepage of the website


### 3)Customer:

NFR13: Customers can add the desired products to the wishlist.
NFR14: Customers can change their details in their profiles.
NFR15: Customer details besides username, password, contact, location, and email are not that useful
NFR16: customer can view the number of people who liked the similar products
NFR17: Customers can view their favorites and wishlists anytime they want.


### 4)Cart:

NFR18: The products shall be wishlisted or added to the favorites per the customer's interests.
NFR19: Products that are out of stock and added to the wishlist will be notified to the customer when they become available.
NFR20: The website shall allow the customer to enter their feedback and reviews about the website's service.
NFR21: The offers on a product shall be displayed when a customer views a product.
NFR22: The customer's rating will be shown in the space below the product.
 


### 5)Payment:

NFR22: If the user has any promo codes, we can use them. The promo codes are located on the payment pages.
NFR23: After completion of the payment, a pop-up box is displayed 
NFR24: Sometimes, we get suggested products while proceeding to payment.
NFR25: In some cases, tipping the delivery person is expected.
NFR26: The payment page occasionally displays a few ads.



### How will you train people to use it?
 
A)   It makes use of the Salesforce application. It makes use of the Salesforce application. Our website is a standard e-commerce website where customers can search for, see information about, and place orders for the products they choose from anywhere in the world. Our website is designed to be incredibly user-friendly for our customers. The following is an overview of the directions for navigating our website:
Customers can log in or register on the website. Look for the things they require and add them to the shopping cart; after doing so, the payment page is presented; once the transaction is complete, it takes the user back to the site. If visitors to our website have any questions or concerns, they may speak with a member of our customer service staff, and interested visitors can even contribute their items.

### How will you ensure it integrates within their ecosystem / software?
 A) Im taking  a segment of our project to answer this question
shopping cart: Customers put items in an online shopping basket or cart  Nearly many carts enable two or three selections for each product, such as an extra-large green flannel shirt.   Some carts enable fractional sales of cloth.
Each page of a growing number of store-building systems displays the products currently in the shopping cart in addition to a running total. Customers are able to more easily recall their current position in the ordering process as a result of this.
Based on customers feedback our website has been running without any obstacle.



### How will you ensure that it any discovered issues are resolved?

 A) They'll be simpler to detect and solve because you'll learn how to make your code more modular, how to test it, and how to organize it to fail quickly and near the source of the issue rather than somewhere random. With asserts, it's easy to check the inputs to all functions with non-trivial preconditions. This is a useful feature that doesn't require a lot of infrastructure. This has rescued me countless times when I would otherwise have had strange segfaults and unpredictable behavior that would have been almost impossible to debug. We also got some syntax help from Google.

## Traceability

## use case Diagram 
 
| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
|    Id1     | Products      |     FR7,FR8,FR10,FR17  |
|    Id2     | View Items    |     FR6, FR11,FR12     |
|    Id3     | Add To Cart   |     FR16,FR18,FR19  |

## Activity Diagram

| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
|    Id4     | User|     FR,1,FR2,FR11,FR12,FR13    |
|    Id5     | sign up    |     FR1     |
|    Id6     | Payment page    |     FR21,FR23,FR24,FR25     |

## Class Diagram

| Artifact Name   | Requirement ID |
| :----------:    | :----------: |
| Class User      |     FR1,FR2,FR11,FR12,FR13   |
| Class Products     |      FR7,FR8,FR10,FR17     |
| Class Admin      |    TBH    |
| Class Cart      |     FR16,FR18,FR19    |
| Class Cart Items      |     FR18,FR19,FR20  |
| Class Orders      |     FR20    |
| Class Order Items      |     FR23     |

### Artifacts



*[Activity Diagram.pdf](https://github.com/YesaswiniVellaboina/GVSU-CIS641-ONETEAMONEGOAL/blob/master/docs/Activity%20Diagram.pdf)


*[Class Diagram.pdf](https://github.com/YesaswiniVellaboina/GVSU-CIS641-ONETEAMONEGOAL/blob/master/docs/Class%20Diagram.pdf)

*[Object Diagram.pdf](https://github.com/YesaswiniVellaboina/GVSU-CIS641-ONETEAMONEGOAL/blob/master/docs/Object%20Diagram.pdf)

*[sequence diagram and state machine diagram.pdf](https://github.com/YesaswiniVellaboina/GVSU-CIS641-ONETEAMONEGOAL/blob/master/docs/sequence%20diagram%20and%20state%20machine%20diagram.pdf)

*[use case diagram.PDF](https://github.com/YesaswiniVellaboina/GVSU-CIS641-ONETEAMONEGOAL/blob/master/docs/Use%20case%20diagram.pdf)


### Installation

- We have utilized the Salesforce tool and the coding languages of Javascript, HTML, and CSS; lightning web components; aura components; and Apex, which is used for Salesforce flow controllers.
- To complete the installation, all that is required of you is to run the code in Visual Studio while the Salesforce tool is open.
- we used
	salesforce is the connecting point between the cloud and the customers
	javascript to construct the more complicated aspects of our website
	HTML code is used to describe how webpages are organized.
	Use CSS for both layout and style.



