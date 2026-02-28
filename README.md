
# YouTube Ad Strategist (AI + n8n)

An automated YouTube Ads strategy system built using **n8n automation** that discovers trending videos, analyzes engagement metrics, extracts marketing signals, and generates insights for building high-performing YouTube advertising campaigns.

The system collects data from **YouTube APIs, Google Search insights, and keyword discovery** to recommend campaign ideas, placements, and targeting strategies.

---

# Features

• Automated YouTube keyword discovery  
• Trending video analysis  
• Engagement and velocity scoring  
• Keyword relevance detection  
• Google search intent discovery  
• Campaign strategy insights generation  
• Google Sheets reporting dashboard  
• Placement targeting research for YouTube Ads  

---

# How the System Works

The workflow automatically performs the following steps:

1. Accept campaign inputs (keywords, region, audience).
2. Query the **YouTube API** for videos related to the keywords.
3. Collect **trending videos** in the selected region.
4. Fetch video metadata including:
   - views
   - likes
   - comments
   - publish date
5. Calculate performance metrics such as:
   - views per day
   - engagement rate
   - trend score
6. Detect keyword relevance in titles, descriptions, and tags.
7. Normalize and score each video using custom formulas.
8. Extract search insights from **Google Search data**.
9. Store results in **Google Sheets dashboards**.
10. Generate strategic datasets for planning YouTube ad campaigns.

---

# Architecture

### Data Sources

• YouTube Data API  
• Google Search (SERP API)

### Processing

• n8n automation workflows  
• JavaScript scoring logic

### Storage

• Google Sheets

### Output

• Campaign strategy insights  
• Trending video placements  
• Keyword intelligence for YouTube Ads  

---

# Video Scoring Model

Videos are evaluated using multiple signals:

Additional weighting is applied for:

• keyword relevance  
• freshness  
• engagement velocity  

This allows identifying videos suitable for:

• YouTube Ads placements  
• creative inspiration  
• competitor analysis  

---

# Example Output Data

The workflow generates structured data including:

• Video title  
• Channel name  
• Views  
• Views per day  
• Engagement rate  
• Trend score  
• Matched keywords  
• Content freshness score  

This helps marketers quickly identify **high-performing YouTube content for advertising strategy.**

---

# Requirements

To run this system you need:

• n8n installed  
• YouTube Data API key  
• SERP API key  
• Google Sheets API access  

---

# Setup Guide

### 1. Install n8n
### 2. import workflow into n8n

### 3. Add API Credentials

Configure:

• YouTube API key  
• SERP API key  
• Google Sheets credentials  

### 4. Configure Campaign Inputs

Define:

• keywords  
• region  
• campaign goal  
• target audience  

### 5. Run the Workflow

The automation will:

• fetch YouTube data  
• score videos  
• store insights in Google Sheets  

