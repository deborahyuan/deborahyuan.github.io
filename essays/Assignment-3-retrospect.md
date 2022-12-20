---
layout: essay
type: essay
title: "Reflecting on Assignment 3"
# All dates must be YYYY-MM-DD format!
date: 2022-12-18
published: true
labels:
  - ITM 352
  - Learnings
---

1. Briefly describe your system (e.g. A store selling Pokemon game cards)

Our store is a Walmart replica of Apple’s website.  On the website we sell 6 different models of iPhones, iPads, and Macs, referred to on our website as “Series.” We have different types of accounts, like regular accounts and admin accounts. In addition, customers can’t check out if they aren’t logged in.

2. Any notable shortcomings, bugs, problems, or additional features not implemented?

One notable shortcoming is that I was really struggling with the decrypt function on the admin page. For whatever reason, the decryption package that we were using wasn’t working, so we couldn’t decrypt users’ passwords on the admin page. As a result, to bypass this issue, we just had to abandon using decrypt, so edited passwords on the admin page are not encrypted. However, new user accounts that are created will still be encrypted. In addition, another issue with our admin page is that none of the inputted edits will be checked for validation, as I was running short on time; the idea was that the admin should be able to override any restrictions as an admin. I also discovered a bug with the cart that causes the webpage to crash, but it only occurs in a very specific scenario. There are other smaller bugs, like the fact that Evon and my users are still considered “signed in,” as we didn’t remove our accounts from the active account object.

3. Describe what you are most proud of about your system:

I don’t have anything that I am particularly proud of, now that I think about it. If anything, I would say that the managing products page is quite nice and clean. I also think that our website looks visually cohesive and nice. 

4. Describe what you are least happy with your system:

I am unhappy with the admin functionalities, particularly the managing users page. I also think that given more time, I would have been able to add more fancy UI features.

5. How was developing this assignment different than assignment #2?


Everything was so different – cookies and sessions were a real game changer. In addition, having objects in objects with us having 3 different types of product offerings made the process a lot more confusing, especially when it came to grabbing information submitted in forms.

6. When you ran into a problem, what did you do to address it?

When running into a problem, we would first try to look at the console on both the server and the client. Next, we would try to figure out what went wrong and do trial and error until the problem is fixed. In general, this was a very long and grueling process.

7. Describe what worked well in doing this assignment?

What worked really well was the way Evon and I divided our work in the very beginning of starting on this project. The things Evon was tasked with were ordered in a way that she could get things done without my parts being finished yet. This proved to be very good, as I caught COVID during this time and I was unable to work on the project for a while. During Assignment 2, I think we worked out a good system on incorporating her code with mine, so we followed that same method with Assignment 3 and it worked perfectly.

8. Describe what did not work well in doing this assignment?

TIme management was not very good during this assignment. I think it was largely due to the fact that this project coincided with the end of the semester, so all the other projects from other classes were also due. The problem was that the other classes’ presentation or project timelines were only a week or two weeks. Due to the greater urgency of finishing those projects, Assignment 3 had to be left for later.

9. What did you learn from doing this assignment?

I learned that communication and understanding is so important. Making sure that both you and your partner understand the project is crucial to coding in collaboration. I also learned that cookies and sessions are everywhere on websites due to their usefulness; I learned about their usefulness firsthand.

10. If you could go back in time and do things differently, what would you change?

If I could go back in time and do things differently, I would definitely start earlier. I also think that if I had started off on the assignment having more knowledge on submitting forms and grabbing information, cookies, and sessions, the project would have been a lot easier. I think that just shows that I was lacking knowledge in those areas. If I could go back in time, I would try to brush up on those areas. 

11. Estimate the % of time you spent (a) thinking about how to do something, (b) writing code (but do not include testing, (c) testing and debugging
A: 5% B: 10% C: 85%

12. Assign an estimated percentage on the amount each team member contributed to the assignment (including yourself) and explain briefly your rationale for the percentage breakdown. Be sure to include an overview of what specifically you and your partners contributed (e.g. “I worked on the security and my partner 1 worked on personalization”)

Evon: 50%
Worked on sending the invoice, password encryption, cart counter visuals, and IR1.

Myself: 50%
Worked on setting up cookies and sessions, changing the website to account for the new products, admin functionality, editing cart quantities, IR 5, customizing interface if user is logged in.
