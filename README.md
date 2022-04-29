# 📓 Notion 

#### Create and Edit Notes like in Notion

This clone tries to replicate some of the great note-taking features Notion has. If you don't know [Notion.so](https://notion.so) yet, I highly recommend to check it out!



---

<img alt="notion clone screenshot" src="./screenshot.gif" width="480">

---

## Features

- **Slash Commands** (Type `/` to turn the block into different content types)
- **HTML Support** (Use regular HTML tags like `<a>` in text blocks)
- **Image Support** (Upload images by using the `/image` command)
- **Drag And Drop** (Reorder blocks easily by drag and drop)
- **Guest Editing** (Anyone can create public pages and share them via link)
- **User Management** (Create an account to create private pages)
- **Scheduled Jobs** (Delete inactive pages and accounts automatically)

## Tech Stack

The frontend is built with Next.js and fully server-side rendered. On the backend, a REST API handles saving user content and user management.

#### Frontend

Next.js · React.js · SCSS/SASS

#### Backend

Express.js · MongoDB with Mongoose · Nodemailer · JWT (Cookie-based)

### MongoDB Atlas

You have to create a new MongoDB cluster upfront. It will store all of your page and block data. You can create one for free on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

**Make sure**, you create the following collections:
* pages
* users

**Make sure**, you allow network access to everyone (due to Heroku).
