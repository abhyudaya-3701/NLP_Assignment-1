
# NLP Assignment 1

This repository contains the code and related files for the first assignment of the NLP (Natural Language Processing) course. The focus of this assignment is to work on NLP tasks such as text processing, corpus creation, and basic language modeling.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [License](#license)

## Overview

In this assignment, various tasks related to natural language processing are covered, including:
- Downloading and curating datasets for English, ensuring that only publicly accessible and non-copyrighted data is used.
- Creating a list of dataset source names, their volumes in GBs, and the total number of articles for each source.
- Preparing one text file (.txt) per article/page.
- Compiling a list of bad-word dictionaries specific to the English language, which includes both existing and custom dictionaries.
- Cleaning the dataset by removing articles that contain bad words, pornographic content, hate speech, and abuse, using appropriate tools.
- Preparing statistics tables showing the total number of articles and GBs before and after cleaning the dataset.
- Deduplicating the dataset to remove duplicate articles with the help of provided codebase, while applying robust techniques for deduplication (bonus points for additional techniques).
- Preparing additional statistics tables that reflect the total number of articles and GBs before and after deduplication.

## Dataset

The dataset used for this assignment is custom-made, focusing on English language text data. The corpus creation process involves scraping, cleaning, and structuring the raw data into a usable format for NLP tasks.

## Requirements

To run the code, you need the following Python packages:

- `numpy`
- `pandas`
- `bs4` (Beautiful Soup)
- `requests`
- `selenium`
- `datasets`
- `pdfplumber`

Make sure to manually install these dependencies as needed.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/abhyudaya-3701/NLP_Assignment-1.git
   ```

2. Navigate into the repository directory:
   ```bash
   cd NLP_Assignment-1
   ```

## Usage

To run the notebooks and scripts:
1. Open the Jupyter notebooks in the `Scraping Notebooks` folder to review or run the code for scraping and data preprocessing tasks.
2. Review and modify the data preprocessing scripts in the `Data Pre-processing` folder for handling the scraped text data.

## Folder Structure

```
NLP_Assignment-1/
├── Scraping Notebooks/      # Contains Jupyter notebooks for web scraping and data collection
├── Data Pre-processing/     # Scripts for cleaning and preprocessing the scraped text data
├── README.md                # Project documentation
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
