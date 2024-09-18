---
difficulty: 1
training: true
chapter: "Chapter 5: Best Practices"
tags: vue
---

# Fix the URL Injection Vulnerability

In this challenge, we've created a menu of links.
For the sake of the challenge, pretend they were provided by a user,
saved to, and retrieved from a database.

One user has provided an unsafe link that executes arbitrary JavaScript.

Ideally, you should sanitize this data before it enters the DB on your backend.

Since we don't have a backend for the exercise, make it safe by sanitizing it
before displaying the links to the page.

> 💡 HINT: We have pre-installed [@braintree/sanitize-url](https://www.npmjs.com/package/@braintree/sanitize-url) to the project

## Requirements

1. Sanitize the "user provided" URLs to prevent an attack via link injection

## Screenshot of the Link Injection Attack

![Screenshot of the xss attack](https://images.certificates.dev/csvd-training-code-challenge-19-before.gif)

## Screenshot of the Solution

![Screenshot of the solution](https://images.certificates.dev/csvd-training-code-challenge-19.gif)
