# Digital Clock

A simple and responsive Digital Clock built using HTML5, CSS3, and JavaScript.

## Project Overview

This project displays the current time in HH:MM:SS format and updates automatically every second.

## Features

- Displays current hours, minutes, and seconds
- Automatically updates every second
- Uses leading zeros for single-digit values
- Simple and responsive user interface
- Works directly in a web browser

## Technologies Used

- HTML5
- CSS3
- JavaScript

## How It Works

The JavaScript `Date` object is used to get the current system time.

The `setInterval()` function calls the clock update function every second. The `padStart()` method is used to add leading zeros when required.

## Deployment

The project is deployed using GitHub Pages through GitHub Actions.

Deployment configuration:

- Repository: Digital-Clock
- Branch: main
- Deployment source: GitHub Actions
- Workflow: Deploy static content to Pages
- Website: https://nighotrutuja31-dot.github.io/Digital-Clock/

## Rollback

The project uses Git for version control. Previous commits are preserved in the GitHub repository, allowing changes to be reviewed or reverted if required.

The GitHub Actions workflow provides deployment history under the Actions tab, which can be used to verify deployment status and previous deployments.

## Project Outcome

A functional live Digital Clock was successfully developed and deployed. The clock displays the current time and updates automatically every second.

## Author

Rutuja Nighot
