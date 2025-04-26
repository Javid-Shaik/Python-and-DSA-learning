# Python Day 1 - Final Project: The Magical Cafe Order System

## Story:  
Imagine you are the **owner of a magical cafe** in a fantasy world.  
Your task is to create a simple system that will handle customers' **orders** and **payments**. Sounds fun, right? 🎉

### The **Mission**:  
Build a **Magic Cafe Order System** that handles customers, gives them their order, calculates the total, and thanks them for visiting.

---

### Your Adventure Begins:

1. **Welcome the Customer**:  
   Greet the customer with a **magical** welcome message:  
   `"Welcome to The Magic Cafe, where every cup is enchanted!"`

2. **Ask for Their Name**:  
   Use `input()` to get their **name**.  
   If the name starts with **"M"** or **"m"**, give them a special **"Magical Discount"** of 20%.

3. **Show the Menu**:  
   Display a small **menu** of items with prices:
   - **Latte**: $5
   - **Cappuccino**: $4.5
   - **Espresso**: $3
   - **Hot Chocolate**: $2.5

   Offer them the chance to choose **one** drink from the menu.

4. **Calculate the Order**:  
   If they choose **Latte**, the price is $5.  
   If they choose **Cappuccino**, it’s $4.5, and so on.  
   - Calculate their **total** (add taxes — let's make it a **10% tax**).

5. **Apply Special Discount** (if applicable):  
   - If their name starts with **"M"** or **"m"**, apply a **20% discount** to the total price.

6. **Payment Time**:  
   Ask the customer how much they want to pay.  
   - If the amount is **less than the total**, print: `"Sorry, that's not enough. Please pay the full amount."`
   - If the amount is **more than the total**, print: `"Thank you! Here's your change of $X."`

7. **Thank the Customer**:  
   After the payment is done, **thank the customer** by printing:  
   `"Thank you for visiting The Magic Cafe, [name]! We hope to see you again soon!"`

---

### Special Bonus Curiosity Twists:

- **Multiple Orders**:  
   Add a **loop** that asks for **multiple customers' orders** until the user types **"exit"**. Each time, the system should reset and handle a new customer.
   
- **Handle Invalid Input**:  
   If they enter something other than a valid menu item, print:  
   `"Oops! We don't have that item. Please choose from the menu."`

- **Create a Fun "Mystery Drink"**:  
   If the customer chooses **Espresso** and their name starts with **"E"**, print:  
   `"You've unlocked the Mystery Drink! Enjoy a free bonus item!"`

---

### Example Run:
 Welcome to The Magic Cafe, where every cup is enchanted!
 
 What's your name? Mary
 
 Hello Mary! You get a 20% discount!
 
 Please choose an item from the menu:
   1. Latte - $5
   2. Cappuccino - $4.5
   3. Espresso - $3
   4. Hot Chocolate - $2.5

Your choice: Latte

The price is $5.

After taxes: $5.50

After your magical discount: $4.40

How much would you like to pay? 5

Thank you! Here's your change of $0.60.

Thank you for visiting The Magic Cafe, Mary! We hope to see you again soon!

**What You’ll Learn**:

- **Variables**: You’ll use variables to store customer info, prices, and total.

- **Conditions**: You’ll check if the name starts with M, handle invalid input, and calculate discounts.

- **Loops**: You’ll repeat this for multiple customers until they decide to exit.

- **Data Handling**: Handle numbers (prices, payments) and strings (names).

# Final Tips:
- Take it one step at a time. Start with the basics (welcome message, input) and build from there.

- If you're unsure about anything, check the docs and experiment. Coding is like solving puzzles — enjoy every small win!

**Mission Complete**:
 
 Once you finish this, you’ll have built a real-world project that could easily be a small coffee shop or cafe order system. Now, you're ready for bigger adventures!
 
# Summary:
  1. Variables: `"Store and manipulate customer data."`
  2. Conditions: `"Offer discounts, handle invalid input."`
  3. Loops: `"Handle multiple customers."`
  4. Real-world thinking: `"Imagine you're designing a system that would actually work in a cafe or shop!"`

That’s it for your Day 1 final project!
Time to build magic, one line of code at a time! 🌟
