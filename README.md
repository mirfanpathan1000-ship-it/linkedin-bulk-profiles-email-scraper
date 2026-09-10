# linkedin-bulk-profiles-email-scraper
Automate bulk LinkedIn profile and email data extraction for lead generation, sales prospecting, recruiting, and research. This repository preserves the supplied product content while adding GitHub-friendly SEO metadata.
# LinkedIn Bulk Profiles Email Scraper

Extract publicly available email addresses associated with **LinkedIn profiles in bulk** with the LinkedIn Bulk Profiles Email Scraper. This cloud-based scraping tool is designed for lead generation, recruitment, sales prospecting, B2B research, and professional contact discovery.

Instead of manually researching individual LinkedIn profiles, provide a list of LinkedIn profile URLs and automatically search public sources for available email addresses.

**Apify Actor:**
https://apify.com/bhansalisoft/linkedin-bulk-profiles-email-scraper?ref=github

## What Is a LinkedIn Bulk Profiles Email Scraper?

A LinkedIn bulk profiles email scraper helps automate the process of discovering publicly available email addresses associated with multiple LinkedIn profiles.

The tool accepts LinkedIn profile references in bulk and uses search-engine-based public data discovery to identify available contact emails without requiring direct LinkedIn authentication.

It can be useful when building professional contact lists, researching prospects, finding candidate contact information, or collecting publicly available B2B contact data.

## Features

* Extract emails from LinkedIn profiles in bulk
* Process multiple LinkedIn profile URLs
* No LinkedIn login required
* Search-engine-based public email discovery
* Discover business and B2B email addresses
* Automatic duplicate removal
* Fast cloud-based processing
* API and automation friendly
* Apify proxy support
* Export results to JSON, CSV, Excel, and XML

## LinkedIn Email Extraction

The scraper can discover different types of publicly available email addresses, including:

* Gmail addresses
* Outlook email addresses
* Yahoo email addresses
* Company-domain email addresses
* B2B business emails
* Public contact emails

Email availability depends on whether the information can be discovered from publicly accessible sources.

## Use Cases

### Lead Generation

Build targeted professional contact lists from a collection of LinkedIn profile URLs.

### Sales Prospecting

Discover publicly available business email addresses that can be used for B2B prospect research and sales workflows.

### Recruitment

Research publicly available contact information associated with candidate profiles.

### B2B Marketing

Create structured contact datasets for professional and business research.

### Business Research

Collect publicly available professional contact information at scale for research and data analysis.

### Influencer Contact Discovery

Find publicly available contact emails associated with professional or influencer profiles.

## How It Works

The workflow is simple:

1. Collect LinkedIn profile URLs or profile identifiers.
2. Add them to the scraper input.
3. Start the Apify Actor.
4. The scraper searches public sources for associated email addresses.
5. Duplicate records are removed.
6. Results are returned as structured data.
7. Export the dataset in your preferred format.

## Input

The main input parameter is `Linkedin_Profile_URL`.

Example:

```json
{
  "Linkedin_Profile_URL": [
    "schuyler-johnston-78826610a",
    "schuyler-johnston-78826610a22"
  ],
  "proxySettings": {
    "useApifyProxy": false
  }
}
```

You can provide multiple LinkedIn profile references in the input array.

## Input Parameters

| Parameter              | Description                                               |
| ---------------------- | --------------------------------------------------------- |
| `Linkedin_Profile_URL` | Array list of LinkedIn profile URLs or profile references |
| `proxySettings`        | Apify proxy configuration                                 |

## Example Output

```json
[
  {
    "Detail_Link": "marcus-marten-coney-96aa7b27",
    "Email": "hangabout@bigpond.com,marcus@bluechilli.com",
    "title": "",
    "Description": ""
  },
  {
    "Detail_Link": "dominick-arcuri-13777",
    "Email": "No found",
    "title": "",
    "Description": ""
  }
]
```

## Output Fields

| Field         | Description                                |
| ------------- | ------------------------------------------ |
| `Detail_Link` | LinkedIn profile identifier                |
| `Email`       | Extracted publicly available email address |
| `title`       | Additional title information               |
| `Description` | Additional profile description             |

## Export Formats

The scraper supports structured data exports including:

* JSON
* CSV
* Excel
* XML

This makes the resulting data suitable for spreadsheets, databases, CRM workflows, analytics, and other automation systems.

## How to Use

### Step 1 — Add LinkedIn Profile URLs

Add your LinkedIn profile URLs or profile identifiers as an array.

Example:

```json
[
  "schuyler-johnston-78826610a",
  "schuyler-johnston-78826610a22"
]
```

### Step 2 — Start the Actor

Open the Apify Actor and click **Save and Start**.

The scraper will process the supplied LinkedIn profile references and search publicly available sources for associated email addresses.

## Demo Video

Watch the complete LinkedIn Bulk Profiles Email Scraper demonstration:

https://www.youtube.com/watch?v=1uWjKd6QXNY

## Why Use This LinkedIn Email Scraper?

Manually searching for contact information for hundreds of LinkedIn profiles can take significant time.

This scraper automates the repetitive research process by allowing multiple profile references to be processed in a cloud environment.

Key benefits include:

* Bulk LinkedIn email extraction
* Reduced manual research
* Cloud-based automation
* Structured output
* Duplicate-free results
* Multiple export formats
* No direct LinkedIn login required
* API-friendly workflow

## LinkedIn Lead Generation Workflow

A typical workflow can look like:

```text
LinkedIn Profile URLs
        ↓
Bulk Profile Input
        ↓
Public Data Discovery
        ↓
Email Extraction
        ↓
Duplicate Removal
        ↓
Structured Dataset
        ↓
CSV / JSON / Excel / XML
        ↓
CRM / Research / Business Workflow
```

## Who Can Use It?

This tool can be useful for:

* Recruiters
* Sales teams
* B2B marketers
* Lead-generation agencies
* SEO agencies
* Growth teams
* Researchers
* Data collection professionals

## Public Data & Responsible Use

Only use data that you are authorized to collect and process. Respect applicable privacy, data-protection, anti-spam, and website terms-of-service requirements when using extracted contact information.

The scraper is intended for discovering publicly available information and should not be used to bypass authentication, access restricted information, or collect private data.

## Start Scraping LinkedIn Profile Emails

Start extracting publicly available contact emails from LinkedIn profile references with the **LinkedIn Bulk Profiles Email Scraper**.

**Apify Actor:**
https://apify.com/bhansalisoft/linkedin-bulk-profiles-email-scraper?ref=github
