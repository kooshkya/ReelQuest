# Reel Quest Web Client Interface Documentation
This documentation is supposed to outline the general UI design of the website. I will not include any technical or implementation details here. Each "view" of the website will be explained separately.

## Login Page:
This is where the root directory of the website will redirect the user if they are not already logged in.
Items that should be included in this view:
- A form where the user can enter their username and password, and be logged in.
- A link to the signup page.

## Singup Page:
The purpose of this view is quite self-evident. The items it needs to contain are such:
- A form where the user can fill out their information. A first name, a last name, a unique username, a password, a password verification, and a submit button. If a user is successfully signed-up, they will be redirected to the login page.
- A link to the login page.

## Index (Main) Page:
This is the home page of each user. It will be extensively expanded and improved in the future, but for now, these are the requirements:
- A header displaying site title, username, etc.
- links to the user's watched, watching, and to-watch lists.
- A link to a search page where the user can look up movies and shows.
- A logout button, which logs the user out and redirects to the login page.

## Watched, Watching, and To-Watch pages:
These three are similar in that they are all lists of titles. The required items are such:
- A list of the relevant titles. Each list item should at least contain the title and a small thumbnail.
- Users should be directed to the movie/show's info page when they click on them in the list.
- A search bar that allows searching among the titles listed.
- Filters to allow the user to filter through titles based on movies/shows, release/start year, etc.
- Buttons on each title to move them to another list, or just delete them from the current list (only shows should movable to the "watching" list).
- Each list item should contain the user's rating on the "watched" list.
- A link back to the main page.

## The Search Page:
This page should allow the user to search for a specific movie/show based on its title. The user should also be able to filter the search results based on movie/show, release/start year, etc.
Additional features include:
- By clicking on any title, the user should be moved to its info page.
- There should also be a link back to the main page.

## The Info Page:
This page should display detailed information about a movie/show. 
- It should contain a poster, a short description, a cast list, release/start year, etc.
- If the movie/show is on one of the user's lists, it should be signified on this page. The user should also be able to add or move the title to any of their lists. (Only shows should be moved to the "watching" list.)
- The user should be able to rate the show/movie. If they rate a show/movie, it is marked as "watched". If they move the title from the "watched" list, the rating is deleted. 
- The user should be able to see their rating of movies/shows.
- There should also be a link back to the index page.


## Additional Features For Later Versions:
- A user settings page where the user can edit their info.
- Captcha validation on signup and login pages.
- Accounts can be locked for a duration on repeated failed login attempts.