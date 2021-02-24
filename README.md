# FamPass

## Summary

FamPass allows users to share accounts from a centralized website without exposing their real passwords.

## Getting Started
1) Load the google chrome extension and connect to a postgreSQL DB model.
2) Start the server and create a user. 
3) Create a family or join a family by inputting the family’s unique name and password. 
4) Add families and share services as needed.

## Tech Stack

Front-end technologies:

1) React, react-router, react Hooks
2) Bootstrap
3) Axios

Back-end technologies:

1) SQL
2) Express
3) Authentication: encoding, b-crypt

Chrome extension: popup, background, content


## Bugs to fix/Future optimizations

Back-end approach
1) Edit back-end queries to filter through data more specifically before passing to front-end, via POST requests rather than GET requests
2) Add route to permit addition of members to families of which user is already a member without providing family passwords

FamilyPage
1) Add drop down menu for adding/deleting members within each family
2) Sidebar component: track and render profile icons for all users in one user account
3) Modify UX to allow real-time updating of information displayed through the use of websockets, so that users can go from page-to-page without the need to refresh after each CRUD operation

ServicesPage
1) Add/delete service based on which user is sharing said service


## Stretch goals
1) Session storage to allow the user to remain logged for an extended period of time
2) App will be able to access more service providers beyond Netflix, such as Hulu, Spotify, etc.
3) Add the ability to control how many users are using each service at a time to stop owner from being unable to use their own service




