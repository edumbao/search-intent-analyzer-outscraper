# Search Intent Analyzer

Version: 1.3.0 - Outscraper Version

This is a local Search Intent Analyzer built with Python and Streamlit.

The original project used Firecrawl. This version was modified to use Outscraper's Google Search API for SERP-based search intent analysis.

## What It Does

The app accepts a keyword, pulls Google search results, and helps estimate the likely search intent behind the keyword.

It can help classify intent types such as:

- Informational
- Commercial investigation
- Transactional
- Navigational

The goal is not to replace manual SEO judgment. The goal is to make SERP review faster and easier for content planning.

## Current Features

- Streamlit interface
- Keyword input
- Country and location settings
- Result limit setting
- Outscraper Google Search API integration
- SERP/title/snippet-based intent scoring
- Result table
- Export options

## Setup

Install the required packages:

```bash
pip install -r requirements.txt
