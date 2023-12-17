# Vertex AI Acronym Expansion

This repository contains Google Colab notebooks that demonstrate a workflow of uploading a file via Google Colab, processing the file content with Vertex AI, and saving the result to Google BigQuery.

## Table of contents

1. [Overview](#overview)
2. [Setup](#setup)
3. [Notebooks](#notebooks)
4. [Cleaning up](#cleaning-up)
5. [License](#license)

## Overview

This workflow aims to expand acronyms found in a CSV file using a pre-trained model from Vertex AI and save the expanded acronyms to Google BigQuery. Users can interact with the notebooks to understand and execute the process step-by-step.

## Setup

### Requirements

- A Google Cloud Project.
- Billing enabled on your project.
- [Google Cloud SDK](https://cloud.google.com/sdk) installed locally or Cloud Shell.
- Necessary permissions for Vertex AI and BigQuery.

### Installation

Install the necessary library for interacting with BigQuery in your Google Colab environment:

```bash
!pip install pandas-gbq
```

## Authentication

Authenticate with Google Colab using your user account:

```python
from google.colab import auth as google_auth
```

## Notebook

[Acronym Expansion Notebook]:
This notebook walks you through the process of uploading a file, expanding acronyms using Vertex AI, and saving the result to BigQuery.


