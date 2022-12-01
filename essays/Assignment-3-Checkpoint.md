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
 
Shopping cart data stored in sessions will be – USER : Product, Quantity, Series
"username":[ { "name": "iPhone 14 Pro", "price": 999, “series”: “iPhone” }, { "name": "iPad Pro (11-inch)", "price": 799,  “series”: “iPad”}, { "name": "Macbook Pro (14-inch)", "price": 1999, “series”:”Mac”} ]
 
**4. How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?**
 
**5. Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)**
 
**6. If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?**

Discussed in screencast.

**7. How are you approaching Assignment 3 differently than Assignment 2?**

