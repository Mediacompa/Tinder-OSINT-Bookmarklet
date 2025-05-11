# Tinder-OSINT-Bookmarklet
Get extra info about a tinder profile, birthdate, userid, pictures, work ...

# Tinder Profile JSON Extractor Bookmarklet

## 📌 Description (English)

This is a bookmarklet that extracts and displays the `webProfile` JSON object from the Tinder website's JavaScript data (`window.__data.webProfile`). It opens the information in a clean, formatted window for easy viewing and copying.

### ✅ Features

- Extracts only the `webProfile` section from the page
- Displays formatted JSON in a new window
- Lightweight and easy to use
- No external dependencies

### 🚀 Installation

1. Create a new bookmark in your browser.
2. Copy and paste the code from [`bookmarklet.js`](./bookmarklet.js) as the URL.
3. While viewing a Tinder profile page, click the bookmarklet to see the data.

### 🛠 Example Output

```json
{
  "username": "user",
  "user": {
      "birth_date": "1980-05-14T07:12:30.234Z",
      "_id": "560...",
      "badges": [
        {
          "type": "selfie_verified"
        }
      ],
  "name": "User B.",
  "photos": [...],
  "bio": "Just a chill person who loves dogs."
  "jobs": [],
    "schools": [
      {
        "name": "University of... "
      }
    ]
}
