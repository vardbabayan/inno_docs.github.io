# API Documentation

## IU Alumni project provides diverse API options to communicate with different components of the project.

## Here are the main API in the project:
* Donation API 
* Elective courses API
* Request Pass API
* User API

Let's review each one by one:

## Donation API
Donation API is used to manage donations:
* create donations 
* see all available donations 
* provide ability to manage donations from admin side.

```js
router = APIRouter(tags=["Manage Donations"], prefix="/donation")
```
Requests are sent via `/donation` route 
GET and POST requests are available for admin and from user sides.

---

## Elective courses API
Elective courses API is made for users to provide opportunity:
* see all available electives
* create new elective courses
* request a particular elective course
* update elective course
* delete elective course
```js
router = APIRouter(tags=["Elective Courses"], prefix="/elective_course")
```
Requests are sent via `/elective_course` route


---

## Request Pass API
Request Pass API is made to provide opportunity to manage user's passes
* order pass
* see your pass
* delete your pass

```js
router = APIRouter(tags=["Obtain Pass"], prefix="/request_pass")
```
Requests are sent via `/request_pass` route

---

## User API
User API is a core API in `IU Alumni` because the process the following operations:
* user's login
* user's account creation
* user's admin account creation
* user's account update
* user's password change
* see available registered users
* verify account through SSO 
```js
router = APIRouter(tags=["User Authentication"], prefix="/user")
```
Requests are sent via `/user` route