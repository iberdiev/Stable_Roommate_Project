<h1> Stable Roommate Matching Algorithm using Python. </h1>
1. This algorithm is a project work for completing Computer Science course at University of Central Asia (Naryn). https://www.ucentralasia.org/
2. Algorithm takes data from the xlsx file, where each person has corresponded values. (e.g. we can make a survey, so they will answer for the questions by numbers).
3. In order to apply Irving's Algorithm, you need to create a preference list for each individual, so it estimates sum of absolutes values of differences between each person, and then sorts the lists. Bigger this sum, roommates are more distinct, consequently less preferance of each other.
4. Countries are also considered - students should live with someone from different country (formality of our university), so preferred roommate from the same country goes to the end of the list.
5. Finally, launching python file creates results.xlsx with the best roommates matching scenario, so everyone will be happy.
(In case of odd number of people, automatically one person will be added to the list, so algorithm is flexible to number of people)
