# Pizza-Database-to-Dashboard 
This project was made to test my SQL and PowerBI skills with data I created about a fictional pizza place. In this readme I will describe the steps I took to create the database and dashboard. The tables I created, SQL queries, and PowerBI dashboard are all in this repo.

### Step 1: Design

 There was two different designs I had to focus on from the moment I started this project, the first was of the tables themselves in the database and then the database itself. I decided that the fact table would be the orders tables and from there I opened excel and created necessary columns of information that would be collected by a pizza place. Once I created each column, I used QuickDBD (Linked [here](https://www.quickdatabasediagrams.com)) to visualize the table and make any tweaks I saw fit. Then I created three other tables named menu, customers, and addresses in excel and QuickDBD. Connecting the tables was a very easy process but to export and use the tables I had to set up the database first. As a side note I should add that I manually created all of the data in each table. I had insights in mind when I created this project and creating orders data while I randomized names (except for my own) everything else was manually created by myself.

### Step 2: Using MySQL and PopSQL

 Downloading and getting MySQL to run a database on my local machine was not a hard task. It was very easy to create the database and to configure it so that I could create the tables and eventually add the data using PopSQL. Like MySQL, PopSQL was not hard to learn and I was able to establish a link between the database I created and PopSQL very easily. 

### Step 3: Populating Data

 Populating the data did have some difficulties. At first I wanted to read the data in from the excel sheet I created but this did not end up working, I then used sqlizer.io (Linked [here](https://sqlizer.io/)) to convert my excel documents into excel insert statements on a large scale. Though I did not use the exact product I got from the website in my query. Just so that the data types were clearer when they eventually got imported to PowerBI I altered the insert statements. But once all errors or spelling issues were resolved the data entry was successful.

### Step 4: Creating the Dashboard

 Connecting to the MySQL database did give me trouble at first but once I was able to connect I began to create my dashboard. I urge that you dear reader pull up the dashboard now so that you can see each insight and page I am discussing. The key insights I wanted to show throughout the entire dashboard was the biggest customers and the most popular menu items. On the overview the first things I wanted to audience to see was the total order cost by customer - aka who was the biggest spender - and what percentage of the orders are delivery. If we take the perspective of a manager of the pizza place, we can see who the best customers are, and we can reward these customers with coupons or other incentives to keep on purchasing from the pizza shop. Being a manager and seeing the percentage of delivery orders could make the manager adjust how many delivery drivers there are on a shift. On the menu items I broke it down to the most popular categories, items, and item sizes. This could help a manager understand which ingredients are being used the most and how fast they should buy more ingredients. The delivery tab shows the most popular delivery orders over time and location, one thing to note is that I set the addresses to locations on my university campus so that I would not use any homes or business that did not want to be used. Then in the final page a manager could see which customers ordered delivery over the time period measured, this page also showed the customer's common order size and categories. All of this information could be used by a manager to streamline business decisions and how they order ingredients, organize the shifts, or what items to add, keep, or remove from the menu.

### Future Work

 Two tables I could have added was employees and ingredients. These tables could have been used by a fictional manager to understand how much they are spending per hour on employees or ingredients vs the money earned through the sales of the orders.

### Conclusion

 While more information could make this dashboard exponentially more useful for a fictional manager, it was a successful project. This project demonstrates my understanding of creating a SQL server and connecting it to PowerBI to make a end product which is useable and communicates key data to interested parties.
