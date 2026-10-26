# Cinema ticket booking (2018)

A university web project: browse cinemas and movies, pick a showtime and seats, pay, and see your watch history.

**Stack:** Node.js, Express, MongoDB (Mongoose), server-rendered HTML views, SCSS. It was deployed to Heroku (`Procfile`).

## Structure

- `app_server/controllers`: cinema list, movie list, seat selection, payment and summary, user and watch history
- `app_server/models`: users, showtimes, payments, history (Mongoose)
- `app_server/views`: page templates
- `public`: styles, fonts, images

## Run locally

```bash
npm install
# set your MongoDB connection string in app_server/models/db.js
npm start
```
