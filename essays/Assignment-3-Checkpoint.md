---
layout: essay
type: essay
title: "Assignment 3 Checkpoint"
# All dates must be YYYY-MM-DD format!
date: 2022-11-30
published: true
labels:
  - ITM 352
  - Checkpoint
---

Screencast link: [https://youtu.be/dwRhORAtOkY](https://youtu.be/dwRhORAtOkY)

**1. Show what each page will look like. The pages do not have to be “functional” but the design should be clear.**

Discussed in the screencast.

**2. Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.**

Our site’s shopping cart will be a separate page that users can view and edit. I mention the shopping cart briefly in the screencast, but once the user wants to checkout, they can click on the shopping cart. In the shopping cart, the user will have the option to completely remove the item from the cart or adjust quantities. When they are satisfied with the items in their cart, they can click checkout. If the user is logged in, then clicking checkout will lead them to the invoice confirmation page. If the user isn’t logged in, then clicking checkout will lead to the login page. Once the user is successfully logged in, they will be led back to the shopping cart page.


**3. Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.**
 
Sessions will be used to manage our shopping cart through storing product information under a person’s username (username, product, quantity, and series). A sample of the code is as follows:
"username":[ { "name": "iPhone 14 Pro", "price": 999, “series”: “iPhone” }, { "name": "iPad Pro (11-inch)", "price": 799,  “series”: “iPad”}, { "name": "Macbook Pro (14-inch)", "price": 1999, “series”:”Mac”} ]
This information can then be easily called based on the person’s username until the cookie expires/session ends.

 
**4. How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?**
 
I will put something along the lines of “loginstatus = true” in the cookie once someone logs in/registers. Without this cookie, I will make the other pages inaccessible. This will solve the security risk of someone being able to access the site without first logging in. Upon logging out or after the cookie expiration time, the user will be automatically logged out.
 
**5. Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)**
 
Currently, upon a successful login, personalization in the UI is provided by addressing customers by their name, showing their login status, last time logged in, and how many times they’ve logged in total. As for additional personalization that I want to add, I plan on adding an indicator that shows how many items are in the cart and possibly a popup cart that shows up every time an item is added into the cart.
 
**6. If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?**

Discussed in screencast.

**7. How are you approaching Assignment 3 differently than Assignment 2?**

Since Assignment 3 utilizes cookies and sessions, a lot of the code that was used in Assignment 2 will need quite a bit of modification. I am planning to approach Assignment 3 differently by approaching things step by step and in a meticulous fashion so I don’t skip a step. This will require an even greater degree of communication between my partner and I as well, in comparison to Assignment 2.

