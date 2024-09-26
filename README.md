# Mailer.AI: AI-Powered Cold Email Automation for Service Companies

**Mailer.AI** is an AI-driven tool designed to assist service-based companies in generating personalized cold emails by analyzing and tailoring the content to the job descriptions (JDs) of potential clients. This solution helps companies enhance their outreach efforts by automating email creation, allowing them to quickly and efficiently contact numerous prospects.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Tech Stack](#tech-stack)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Outreach for service-based companies often involves manually crafting emails tailored to each potential client's needs. **Mailer.AI** automates this process by extracting job descriptions from company websites or job portals, analyzing them for key roles and technologies, and generating personalized email pitches that match the specific needs of product-based companies.

With **Mailer.AI**, companies can:
- Automatically extract job descriptions from URLs.
- Use AI to generate customized emails that address the requirements of each potential client's job openings.
- Scale their outreach efforts while maintaining a personal touch in their communication.

## Features

- **Automated JD Extraction**: Extract job descriptions from URLs using a web scraper.
- **Cleaned Data**: Process and clean extracted job descriptions by removing unnecessary content like HTML tags and special characters.
- **Portfolio Integration**: Integrate a predefined portfolio of skills to personalize emails.
- **AI Email Generation**: Automatically generate personalized cold emails based on job descriptions and portfolio data.
- **Streamlit Interface**: Provides a user-friendly web interface for job description extraction and email generation.

## Project Structure

```bash
Mailer.AI/
│
├── main.py                # Main Streamlit app for extracting JDs and generating emails
├── portfolio.py           # Manages portfolio of skills for personalized emails
├── utils.py               # Utility functions for text cleaning and processing
├── app/
│   └── resource/
│       ├── my_portfolio.csv    # Portfolio CSV containing skills and relevant links
│       └── gmail.png           # Image asset for the Streamlit app
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation








