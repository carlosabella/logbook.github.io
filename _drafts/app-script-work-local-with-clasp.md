---
layout: post
title:  "Google App Script local development with Clasp "
date:   2022-01-29 22:01:43 +0530
categories: categories
author: "Carlos Abella"
---

# Requirements: 
### Local: 
Node.js >= v6.0.0
### Google: 
Enabling the Google Apps Script API
Before we install and use clasp, we need to enable the Google Apps Script API because that’s what clasp uses in the background. Navigate to the Apps Script Settings page, click on “Google Apps Script API” and toggle the switch to “on”.

# Installation
Install Clasp:
npm i @google/clasp -g

Install autocomplete (install in every GAS project): 
npm install --save @types/google-apps-script

Automatically VSCode will import the types in every project.



# Bibliography
Best manual to work with Clasp is this google codelab: https://codelabs.developers.google.com/codelabs/clasp#0 
In here you will find basic usage: clone, pull, push, versioning and deployment.

Command line guide: https://developers.google.com/apps-script/guides/clasp

Official repository: https://github.com/google/clasp

Samples: https://github.com/googleworkspace/apps-script-samples
