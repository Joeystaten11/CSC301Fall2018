# Day 1 Lab
## Purpose
Get familiar with PhpMyAdmin, create a simple table, insert some data, make changes to the table and the data inside the table. Apply concepts from Unit 1.

## What to do

### 1. Log into the server 
I've set each of you up with a user account on the [CS database server](https://grid8.cs.elon.edu/phpmyadmin). Log in.

### 2. Find your database schema
On the left-hand pane, choose the database schema named after yourself. This is where you will do your work.

### 3. Create a new table 
* Assume you are a veterinarian. Using PhpMyAdmin in a browser, you need to ```CREATE``` a table to help keep track of your animal patients. 
* The table should have the following characteristics:
  * PetID: this is a special number that refers to the pet individually (set this to be the Primary Key - DO NOT SKIP THIS STEP - choose "primary" from the "index" dropdown, accept all defaults - we will talk more about primary keys later in the class) 
  * PetName: this is the pet's name, for example Fifi or Snuffles, 
  * Birthdate (month, day, and year), 
  * PetType (the only available choices are cat, dog, bird, fish, reptile, chicken), 
  * Owner's first and last name, 
  * Sex (for a dog or cat this can be 'm' or 'f', but what do we do about fish - it might be hard to tell! Should we have an "unknown" column?), 
  * The date of the pet's last visit, and 
  * A 'notes' field.
  * Decide which columns you will allow to be 'nullable'. For any columns that are *not* required, click the "null" checkbox.
* Once you are happy with the table design, use the "Preview SQL" button to get a copy of the ```CREATE``` statement that was generated. Copy this into the Moodle answer window for today's lab.
* Run the SQL you generated to ```CREATE``` the table.

#### Troubleshooting Step 3: 
* If you forget to hit "Preview", you can get the ```CREATE``` statements back by going to "Export", then "custom", then "view as text" and press "Go". You'll see your SQL ```CREATE``` statement there. 
* If you forget to make a Primary Key, hopefully you will notice this before you add a bunch of rows. You can go to the "Structure" of the table and hit the "Primary" icon to make an existing column primary.
 
### 4. INSERT  data
* Now we need to add pets to the table.
* Use the PhpMyAdmin ```INSERT``` tab to insert 10 pets (10 rows of data) to your table.

### 5. UPDATE data
* Oh no, the chicken just revealed itself to be a rooster. Use the "Edit" button to construct an ```UPDATE``` statement to change that chicken's sex from 'unknown' to 'm', and update it so that today's date is the last visit. 
* If available, copy this ```UPDATE``` statement to your text file. (Sometimes you won't actually get to see the UPDATE statement that was written for you; that's ok, just move to the next question)

### 6. Modify your table. 
* Tragedy strikes: One of the pets died. What is the best way to reflect its untimely demise in the database? (Assume that you want to keep a record that the pet was once a patient, so you don't want to DELETE it entirely.) 
  * On the 'Structure' tab, add a new column to your table that indicates whether the pet is "deceased" or not. There are a few different ways to reflect this information. 
  * Copy the ```ALTER``` statement that PhpMyAdmin constructed for you into your text file. 
* Now ```UPDATE``` that pet's record to show the fact that it died. 
  * Copy the ```UPDATE``` statement(s) to your text file (if possible).
## What to turn in
Paste in your SQL statements into the Moodle ```day1``` assignment box (save the file somewhere too, if you like). If you didn't finish today, keep working on these on your own time so you won't be behind for future classes.
