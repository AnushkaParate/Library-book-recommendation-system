# 📚 Library Book Recommendation System

A web application that helps users discover books through a simple, account-based interface — with sign-up/sign-in, a book recommendation page, and about/contact pages.

## Features

- **User Authentication** – Sign up and sign in (data handled via `users.json` / server)
- **Book Recommendations** – Browse books listed in `books.json`
- **About Page** – Learn more about the project
- **Contact Page** – Get in touch

## Tech Stack

- HTML5, CSS3, JavaScript
- Node.js (`server.js`)
- JSON for data storage (`books.json`, `users.json`)

## Project Structure
├── 0_login3.html / .css / .js   # Login/Sign-up page (entry point)
├── 1_index.html / 1_script.js / 1_style.css   # Home page
├── 2_aboutus.html / .css         # About page
├── 3_contact.html / .css         # Contact page
├── 4_books.html                  # Book recommendations page
├── books.json                    # Book data
├── users.json                    # User data
├── server.js                     # Backend server
├── package.json / package-lock.json
├── image.png

## Getting Started

1. Clone the repository:
```bash
   git clone https://github.com/AnushkaParate/Library-book-recommendation-system.git
   cd Library-book-recommendation-system
```
2. Install dependencies:
```bash
   npm install
```
3. Start the server:
```bash
   node server.js
```
4. Open `0_login3.html` in your browser (or the port shown by the server, if it serves the frontend too).

## How It Works

1. Users sign up or sign in from `0_login3.html`.
2. On successful login, users are redirected to the book recommendation page.
3. Book data from `books.json` is displayed for browsing.
