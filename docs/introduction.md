![](../assets/images/popetyio-logo.jpeg)

# Intro

**POPETY.IO** is a Real Estate Technology providing Location Intelligence through digital tools for Real Estate professionals. 

> The Popety.io third party API is currently in beta version.

# Getting started

## Authentication

Popety.io used API Key Authentication. 

`X-API-KEY` custom header needed to be set for passing your API key.

`
GET / HTTP/1.1
Host: example.com
X-API-KEY:  [YOUR_API_KEY]
`

> Send an email to Popety.io support to obtain your token access.

## Generate Reports

The /reports endpoint allow to generate Popety.io reports.

Reports are generated asynchronously and can take up to 5 minutes to be available to download. Method is available to check the status of report generation.

