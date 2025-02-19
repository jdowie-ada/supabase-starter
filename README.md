# Supabase Starter Guide (with Codespaces Tips)

This guide helps you get started with Supabase, especially if you're using GitHub Codespaces. We'll cover setting up a simple database, creating an HTML/JavaScript frontend, and writing and deploying serverless functions.

## 1. Project Setup

* **Create a Supabase Project:**
    * Go to [Supabase](https://supabase.com/) and sign up/log in.
    * Create a new project. Choose a name and region.

* **Database Schema:**
    * In the Supabase dashboard, go to "Table Editor."
    * Create a table (e.g., "messages") with relevant columns (e.g., `id`, `message`, `created_at`).

* **GitHub Codespace:**
    * Create a new Codespace or open an existing one.

## 2. Frontend (HTML and JavaScript)

* **HTML (`index.html`)**

```html
<!DOCTYPE html>
<html>
<head>
<title>Simple Supabase App</title>
</head>
<body>
  <input type="text" id="messageInput" placeholder="Enter your message">
  <button id="sendButton">Send</button>

  <div id="messagesContainer"></div>

  <script type="module" src="script.js"></script>
</body>
</html>
