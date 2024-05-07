[![Build and Test](../../actions/workflows/build_and_test.yml/badge.svg)](../../actions/workflows/build_and_test.yml)

# Welcome to Microsoft Build DEM747

In this demo we are going to build a deploy a website to Azure using GitHub Actions.

Azure resources and authentication has been pre configuered in the interest of time.

## Pre created Resources

### Azure Resources

Static Web Apps (one for each environment) and a Managed identity for deployment

![Azure Resources](azure-resources.png)

### GitHub Actions Variables

![Actions Variables](gh-actions-vars.png)

## Content

This repository hosts a basic [Next.js](https://nextjs.org/) application that can consume the
[GitHub Octodex](https://octodex.github.com/) RSS feed and then render the extracted feed
items into a web page so the Octocats can be viewed in all their glory and it also contains an API backend.

![Octodex app](octodex.png)

## Building

This is a standard Next.js application that uses the `next` framework to develop and build the application.

To run the application locally, use `npm run dev` from the checked out source code (after installing the dependencies of course using `npm install`). The application will start up and bind to port `3000` making the server available from http://localhost:3000

