# task_cruncher.html
A feature-rich TODO-list in a single html-file. It will run in a browser window using "local storage" for data persistence.

## Getting Started

Just copy the file <b>task_cruncher.html</b> to your local disk. Just one file, nothing more.  
Then start a browser and open the file. (Don't forget to bookmark it. You will use it alot)

### Prerequisites

A browser that can handle "local storage". Chrome and Mozilla works well, while IE and Edge doesn't.
And you need an Internet connection as well. Because the html-page is using well-known javascript libraries which are downloaded from CDNs.


## Built With

* [Vue.js](https://vuejs.org/) - A framework for reactive single page web applications
* [Bootstrap.js](https://getbootstrap.com/) - Responsive grid system, extensive prebuilt components, and powerful plugins built on jQuery.
* [jQuery](https://jquery.com/) - For HTML document traversal and manipulation, event handling, animation, and Ajax
* [Font Awsome Icons](https://fontawesome.com/) - Icons for a modern looking UI

## Using Task Cruncher

The application is mostly self-explanatory. And you can use it in the way that suits you.
Here are some tips to get you starting.

### Tasks

Add a task using the green button. Write a subject and click <b>Save</b>. It's that simple.
Click on the Edit icon (or on the subject text) to edit it.
You can change the category for the task, or the priority if you want it higher up in the list.
Tasks that belongs together can be tagged with a group-tag which will be visible as a badge.
Use the Comment field for a more detailed description, and the Log field to keep a track on what has already been done.
Click <b>Today</b> (the calendar icon on the far left) if you want it on the <i>Today list</i>.

And when you have executed a task, tick the circle in the <i>Done column</i>.
When the taske is marked as <i>Done</i> It will appear as crossed out. If you don't want it on your list you can archive it.
An archived task can be restored by clicking <b>Undo</b>, or permanently deleted by clicking <b>Delete</b>.

Through the task's lifetime dates are added. They are color-coded and begin with a letter.  
<b>C</b> - Created  
<b>D</b> - Done  
<b>A</b> - Archived  

### Views and Categories

The first five buttons are <i>Views</i>.
* <b>All</b> - Shows all tasks that aren't archived. The one with highest priority is at the top.
* <b>Done</b> - Shows all done tasks. The most recent done task at the top. Even archived tasks are shown here.
* <b>Archive</b> - The archive shows all archived tasks.
* <b>Tagged</b> - Shows all tagged tasks grouped by tag name.
* <b>Today</b> - The most important helper category. Shows all tasks that you want to see today.

There are a few default categories present the first time you start the application.
You can add, delete or edit the categories to your own liking.
On the far right in the Category button list there is one with a cogwheel. Click on it if you want to change the categories.
You can only delete a category if no task is using it (even archived tasks).

### Import and Export

Use <b>Export</b> frequently to save your task database to a JSON-formatted file. Local storage normally takes care of persistance. But if it should fail the Exported file could be used to restore the data using <b>Import</b>.
You can also use Export and Import if you want to use another browser. Or if you want to move the task database to another computer.

