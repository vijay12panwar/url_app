# URL Shortener App - Backend

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction

URL Shortener App is a backend application designed to shorten long URLs into more manageable and user-friendly links. This application provides a robust API for generating short URLs and redirecting users to the original long URLs.

## Features

- Shorten long URLs to a unique short code.
- Redirect users to the original URL when accessing the short link.
- Customizable short link structure.
- Analytics for tracking link usage and statistics.
- Secure and scalable architecture.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (version 14 or later)
- MongoDB (latest version)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/URL_Shortener_App.git
cd URL_Shortener_App
```
Install dependencies:
```
npm install
```
Set up environment variables:
Create a .env file in the root directory and configure the following:
```
PORT=3000
MONGODB_URI=mongodb://localhost:27017/url_shortener
SECRET_KEY=your_secret_key
```
Replace your_secret_key with a secure secret key for JWT authentication.

Start the application:
```
npm start
```
