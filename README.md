# Snippetbox

This repository contains the sample web application built while following the "Let's Go" book by Alex Edwards (https://lets-go.alexedwards.net/). The application is a simple snippet-sharing service written in Go, demonstrating many of the techniques used to build real-world web applications with the Go programming language.

## Features

- User signup and authentication
- Create and view text snippets
- Form validation and user-friendly error handling
- MySQL database integration
- Clean project structure following Go idioms
- Templates for rendering HTML responses
- Middleware for logging, recovery, and authentication
- Unit tests for handlers, middleware, and models

## Project Layout

The code is organized using conventions described in the book:

```
cmd/web/          # entry point for the web server
internal/         # application-specific packages
  assert/         # test helpers for assertions
  models/         # data models and database access
  validator/      # custom form validation logic
ui/               # user interface files
  html/           # HTML templates
  static/         # static assets (CSS, JS, images)
```
