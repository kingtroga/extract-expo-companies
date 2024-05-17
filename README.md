# Python Extract Websites: README

## Project Description

Using Python scripts, I meticulously scraped 19 Expo websites, unearthing 26,453 company names. Crafting a tailored Google search, I navigated through quotas, uncovering elusive company websites. My async Python script then delved deeper, capturing essential details: Source, Company Name, Website, Contact Name(s), Contact Email(s), Contact Phone Number(s), and Social Media Accounts.

## Step-by-Step Process

### Step 1: Scraping Expo Websites
I utilized 19 different Python scripts employing Beautiful Soup and Requests libraries to scrape data from various Expo websites. This process yielded a total of 26,453 company names from these websites.

### Step 2: Extracting Data and Saving to Excel
With the collected data from the Expo websites, I extracted pertinent details and saved them into an Excel file named `company_details_from_expo.xlsx`.

### Step 3: Enhancing Data with Additional Contact Information
Over the next three days, I utilized a custom Google search engine to programmatically search for the websites of each company. Due to a detail quota limit of 10,000, this was done in batches.

Once I obtained the websites, I developed an asynchronous Python script to crawl each entire website for more comprehensive details, including:
- **Website Scrape Source**
- **Company Name**
- **Website**
- **Contact Name(s)**
- **Contact Email(s)**
- **Contact Phone Number(s)**
- **Social Media Accounts** (Facebook, Instagram, LinkedIn, etc.)

### Data Extraction in Chunks
The data was extracted in chunks of 1,000 asynchronously to ensure efficiency and manageability.

## Output
The final data is stored in an Excel file with detailed contact information for each company.
