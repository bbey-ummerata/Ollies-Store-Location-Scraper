# Ollies Store Location Scraper
>This scraper collects retail store location data from Ollie’s store locator and transforms it into a clean, structured dataset. It’s useful for building location-aware tools, mapping services, or store-level analytics for retail operations or market research.


<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Ollies Store Location Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
The Ollies Store Location Scraper accesses Ollie’s official store locator pages to gather comprehensive information about each store location. That includes address details, geographic coordinates, contact numbers, and store-specific metadata. Great for logistics planning, retail analysis, or building store-based services.

### Why It’s Useful
- Harvests store addresses and coordinates for mapping or geo-analysis  
- Collects store-level contact and metadata for outreach or customer support  
- Automates retrieval—no manual copy-paste from multiple pages  
- Produces structured JSON or CSV output ready for use in apps or dashboards

---
## Features
| Feature | Description |
|---------|-------------|
| Location Data Extraction | Retrieves address, city, state, ZIP/postal code, and full store address. |
| Geolocation | Pulls latitude and longitude if provided (coordinates) for mapping. |
| Contact Info | Extracts store phone numbers or store-specific contact details. |
| Store Metadata | Includes store ID, store name, hours if available, and store-specific notes. |
| Clean Output Formats | Results are returned as structured JSON or exportable CSV. |
| Scalable Crawling | Automatically iterates through all store listings without manual input. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|-------------------|
| storeId | Unique identifier for the store location. |
| storeName | Name of the store (as listed). |
| address | Full address line of the store. |
| city | City of the store location. |
| state | State or region. |
| postalCode | ZIP or postal code. |
| country | Country (typically USA in this context). |
| phone | Store phone number, if available. |
| latitude | Geographical latitude coordinate, if available. |
| longitude | Geographical longitude coordinate, if available. |

---
## Example Output
    
    [
      {
        "storeId": "O1234",
        "storeName": "Ollie's Bargain Outlet – Atlanta",
        "address": "123 Main St.",
        "city": "Atlanta",
        "state": "GA",
        "postalCode": "30303",
        "country": "USA",
        "phone": "(404) 555-0123",
        "latitude": 33.7490,
        "longitude": -84.3880
      }
    ]

---
## Directory Structure Tree
    
    ollies-store-location-scraper/
    ├── src/
    │   ├── main.js
    │   ├── scraper/
    │   │   ├── store_locator_parser.js
    │   │   └── request_handler.js
    │   ├── utils/
    │   │   ├── csv_exporter.js
    │   │   └── geo_parser.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_input.json
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **Retail analysts** build store-level datasets for coverage and demographic mapping.  
- **Logistics teams** plan delivery zones and store accessibility based on store addresses.  
- **Marketplace builders** enrich listings with nearby store information for customer convenience.  
- **Developers** power store finder features with clean, structured store data.  

---
## FAQs

**Does it collect coordinates (latitude/longitude)?**  
Yes, if provided by the store locator site — otherwise, those fields may remain empty.

**What output formats are supported?**  
Structured JSON by default; easily convertible to CSV using built-in export utility.

**Does it require manual input?**  
No — the scraper automatically iterates through all store listing entries available on Ollie’s site.

**Is phone/contact info always available?**  
Phone number is extracted if listed; availability depends on store listing completeness.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Collects full store location data (dozens of stores) in a few seconds per location.

**Reliability Metric:**  
Stable extraction even when some store entries have partial info, courtesy of fallback parsing logic.

**Efficiency Metric:**  
Minimized requests and optimized parsing speed allow rapid full-site scraping.

**Quality Metric:**  
Provides clean, normalized address and store data suitable for mapping, CRM ingestion, or analytics dashboards.


---


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>

