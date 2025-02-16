# Project Title

Automatizing Part of Literature Search in Systematic Reviews

## Summary

This project automates the early stages of literature search in systematic reviews. The AI filters out articles that are clearly outside the research scope and extracts relevant metadata, such as abstracts, titles, and publication years, for researchers to review. 


## Background

Manually conducting systematic reviews is a time-consuming process that can take years. While human judgment is necessary for later stages, the initial filtering and extraction process can be automated. Currently, systematic reviews are done mostly manually, making this a widespread problem in academia.

This project aims to address the following issues:

The tedious and time-consuming nature of manual literature filtering
The inefficient use of academic professionals' time on repetitive tasks
The delay in publishing systematic reviews due to slow manual processes


## How is it used?

Researchers conducting systematic reviews can use this tool to automate the initial literature screening. The AI scans academic databases, removes irrelevant papers, and extracts key information from relevant ones.

Example workflow:

User inputs keywords and criteria
AI retrieves articles from sources like PubMed, Embase, and CINAHL
Irrelevant articles are filtered out using tf-idf and regex-based methods
Extracted metadata is presented in a structured format for review
Here’s an example of how the extracted data might look:
[
  {
    "title": "AI in Systematic Reviews",
    "authors": "Doe et al.",
    "year": 2023,
    "abstract": "This paper explores AI applications in systematic literature reviews."
  },
  ...
]

## Data sources and AI methods
The tool retrieves peer-reviewed articles from:

PubMed
Embase
CINAHL
AI methods include:

Term Frequency-Inverse Document Frequency (tf-idf) to determine article relevance
Regular expressions (regex) to extract structured information from articles
More on tf-idf

Technique	Purpose
tf-idf	Identifies relevant articles
Regex	Extracts metadata from text


## Challenges

This tool does not fully automate systematic reviews. The following limitations apply:

AI cannot make subjective research decisions
Some relevant articles may still be incorrectly filtered out
Ethical considerations: Avoiding bias in AI-driven literature filtering

## What next?

Future improvements include:

Enhancing AI’s accuracy in filtering articles
Extending support for more databases
Integrating a feedback mechanism for researchers to refine results


## Acknowledgments

Inspired by the need for efficiency in academic research
No external data, code, or images were used without permission(https://creativecommons.org/licenses/by/2.0)
* etc
