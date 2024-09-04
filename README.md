# Auto-Email

## Overview

Auto-Email is a tool designed to generate cold emails automatically based on job postings scraped from websites. The application utilizes a combination of language models and web scraping to streamline the process of creating personalized emails for job applications or business inquiries.

## Features

- **Cold Mail Generation:** Create tailored cold emails using job descriptions and relevant portfolio links.
- **Web Scraping:** Extract job postings from URLs provided by the user.
- **Portfolio Integration:** Query a portfolio of previous projects or relevant links to include in the email.
- **Streamlit Interface:** A user-friendly web interface for interacting with the application.

 (Recording shows how the system works: https://github.com/mohamedAtoui/Auto-Email/blob/main/Recording.mp4)

 ## Image of Business E-mail Generator: 
 ![Example Image](https://github.com/mohamedAtoui/Auto-Email/blob/main/Cold-Email.png)

## Set-up:
 1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside app/.env update the value of GROQ_API_KEY with the API_KEY you created.
 2. Run the streamlit app:
 ```bash
    streamlit run app/main.py
