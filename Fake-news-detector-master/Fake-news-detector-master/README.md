# Fake-news-detector
Fake News Detector
This project implements a fake news detection system using a series of Python scripts designed to analyze web content for credibility.

How It Works
Scraper Module
The scraper script extracts URLs, domain names, and hyperlinked texts from the user-supplied webpage.

Verification Against Database
Extracted links are then cross-checked against a static database of known fake news websites. This database is stored in a CSV (comma-separated values) format.

Database Source
The fake news sites database was originally sourced from OpenSources.co and has been extended to include additional websites, with a focus on Indian news sites.

User Interface
The entire workflow is controlled via a Python-based GUI built with Tkinter, providing an easy-to-use interface for users.


