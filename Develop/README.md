For this assignment, the goal was to create a functional daily planner on our website.

The first thing I did was write out my html code for this website beyond the header that was given. This included all the coding done within the container div. The website was broken into 9 row divs, each row representing a different hour between 9am-5pm. Within each row were three column divs: One to display the hour, one to be the text input spot, and one to be a submit button that would save the inputs to local storage. There was one textarea created within the text input div, that would allow the user to edit the text within that div.

After creating the basics for the HTML, jQuery was used to animate the website.

Using jQuery, a real time clock was added to display in the header of the planner to inform the user of today's date.

Each time block is supposed to be colour coded according to real time, so that the user can easily identify which appointments for the day have already passed, which ones should be occuring presently, and which ones have yet to happen. As it turns out in the code, this is one point I struggled with. Around lines 110-118, you can see my attempted code to create parameters. The goal was to create an array where I could change the attribute of the time-block to add the classes past, present, and future that were sitting in the CSS file..

While that part wasn't completed, the user can still click the time block and edit the text there. Additionally, by clicking the submit button, that data will be saved in local storage. However, I struggled to get the data to display after refreshing the page.
