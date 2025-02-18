# SQL_Murder_Mys

Here are some of the crazy solutions for SQL-Murder-Mys game.
# It is so amazing to know that we can complete the learning while playing the game.

-- Here are some of my contributions to complete the game


Okay, I need to solve the SQL Murder Mystery problem. Let me start by recalling the scenario. There's been a murder in SQL City, and I need to find out who did it using SQL queries. The database has various tables like crime_scene_report, person, drivers_license, interview, etc.

First step is probably to check the crime scene report. The problem mentioned the crime happened on a specific date, maybe January 15th, 2018, in SQL City. Let me look up the crime_scene_report table for that date and city. The type would be 'murder'.

So I'll write a SELECT statement to get the description from crime_scene_report where date is 20180115, type is murder, and city is SQL City. That should give me details about the crime scene.

Once I get the description, it might mention witnesses. For example, maybe there are two witnesses: one lives on Northwestern Dr, and the other named Annabel lives somewhere on Franklin Ave. Then, I need to find those people in the person table.

Looking for the person on Northwestern Dr, the address would be something like '%Northwestern Dr%' and the name like 'Annabel%' on Franklin Ave. Once I find their IDs, I can check their interviews in the interview table.

The interviews might mention clues like the killer was seen at a gym, maybe a "Get Fit Now Gym" with a membership number starting with "48Z", and the person has a gold membership. Or perhaps the suspect drove a car with a specific license plate, like 'H42W'.

Then, using the drivers_license table to find people with that plate number or car details. Also, checking the gym membership table for people with those membership IDs.

Once I have a suspect from the gym and the license, I can cross-reference with the person table to get their details. Maybe the person's ID matches both the gym membership and the driver's license. Then, checking if they attended an event on a specific date or something else that confirms they're the killer.

Wait, let me structure this step by step. First, get the crime scene report. Then find the witnesses, get their interviews, extract clues, use those clues to query other tables like drivers_license, gym memberships, person, and then finally identify the killer.
