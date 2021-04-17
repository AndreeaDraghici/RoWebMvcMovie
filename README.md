# RoWeb_MvcMovie
 .NET-Roweb 2021 (.NET Internship Tester-Roweb 2021)



The test consists of completing the first 5 steps (get started, add controller, add view, add model, work with a database) in the following tutorial: https://docs.microsoft.com/ro-ro/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-5.0&tabs=visual-studio

TASK 1:

Similar to what is described in the tutorial, add the necessary elements for a movie collection.


TASK 2:

We want to bring new implementations, within the application, as follows:


1) To add pagination (see the tutorial below).

In order to prove that the tutorial has been understood, the pagination will NOT be done with the previous & next button, but all the pages will be listed under the table and depending on the number of the selected page, the corresponding data will be brought.

https://docs.microsoft.com/en-us/aspnet/core/data/ef-mvc/sort-filter-page?view=aspnetcore-5.0


2) To add the possibility to insert reviews / reviews.

In the details view, immediately below the properties of a movie, a table with user reviews (username, date of completion and the actual review) will be implemented and under the table, 3 new elements will be added to add a review:

- an input where the name of the person doing the review will be filled in;

- an input where the actual review will be completed;

- a button to insert it.

As soon as the insert is made, the review table must be updated and display the new inserted record.
