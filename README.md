# Stable_Roommate_Project
Stable Roommate Matching Algorithm using Python
This algorithm is a project work for completing Computer Science course at University of Central Asia (Naryn). https://www.ucentralasia.org/
Algorithm takes data from the xlsx file, where each person has corresponded values. (e.g. we can make a survey, so they will answer for the questions by numbers).
In order to apply Irving's Algorithm, we need to create a preference list for each individual, so it estimates sum of absolutes values of differences between each person, and then sorts the lists. More bigger this sum, more distinct, consequently less preferable.
Countries of are also considered - students should prefer someone from different country (formality of our university), so preferred roommate from the same country goes to the end of the list.
Finally, launcing py file creates results.xlsx with the best roommates matching scenario, so everyone will be happy.
