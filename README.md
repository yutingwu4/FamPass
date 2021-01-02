FamPass

Summary
In this scratch-project, FamPass allows users to share accounts from a centralized website without exposing their real passwords.

How to use
1) Load the google chrome extension and connect to a postgreSQL DB model.
2) Start the server and create a user. 
3) Create a family or join a family by inputting the family’s unique name and password. 
4) Add families and share services as needed.

Learning Objectives
Front-end technologies:
React, react-router, react Hooks
Bootstrap
Axios
SQL
Express
Authentication: encoding, b-crypt
Chrome extension: popup, background, content


*Bugs to fix/Future optimizations*

Back-end approach
Edit back-end queries to filter through data more specifically before passing to front-end, via POST requests rather than GET requests
Add route to permit addition of members to families of which user is already a member without providing family password and modify frontend accordingly

FamilyPage
Drop down menu for adding/deleting members within each family
Sidebar component: track and render profile icons for all users in one user account
User to be able to go from page-to-page without needing to refresh after each CRUD operation by allowing for real time updating of information displayed through the use of websockets

ServicesPage
Add/delete service based on which user is sharing said service


*Stretch goals*
Session storage to allow the user to remain logged for an extended period of time
App will be able to access more service providers beyond Netflix, such as Hulu, Spotify, etc.
Add the ability to control how many users are using each service at a time to stop owner from being unable to use their own service




