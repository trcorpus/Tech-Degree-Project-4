# Tech-Degree-Project-4

In this project, I have created a work log program that saves information to a database using SQLite. The instructions for this project are as follows:

- The CSV timesheets were a huge success but some more features are needed, including the ability for other developers to use the data without worrying about file locking or availability. The managers have also asked for a way to view time entries for each employee. Seems like a database would be a better solution than a CSV file!

- Create a command line application that will allow employees to enter their name, time worked, task worked on, and general notes about the task into a database. There should be a way to add a new entry, list all entries for a particular employee, and list all entries that match a date or search term. Print a report of this information to the screen, including the date, title of task, time spent, employee, and general notes.

Additionally, I have added the following features:
- Menu has a “quit” option to exit the program.
- Records can be deleted and edited, letting user change the date, task name, time spent, and/or notes.
- Can find entries based on a ranges of dates. For example between 01/01/2016 and 12/31/2016.
- If multiple employees share a name (e.g. multiple people with the first name Beth), a list of possible matches is given.
- Records are displayed one at a time with the ability to page through records (previous/next/back).
- Test coverage for at least 85% of the code. (Saved in file "worklogdbtests.py").
