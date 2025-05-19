# Fake News Schulprojekt - Article Website

This project is a static website designed to display a single article, with a simple web-based administration interface to edit the article's content.

The article content, including text, metadata, and images (stored as base64 strings), is saved to and loaded from a `article.json` file hosted on GitHub.

The admin interface allows users to log in with a password, modify various aspects of the article (title, date, content, tags, images), and save the changes directly back to the `article.json` file in the repository.

The main page fetches and renders the latest article content from the `article.json` file using client-side JavaScript.

This project was created by Finn Pfeifer. 