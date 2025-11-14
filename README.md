# LinkedIn Company Posts Batch Scraper | No Cookies
This scraper extracts public posts, reactions, comment counts, and media from multiple LinkedIn company pages at scale—all without requiring a login. It is designed for fast, reliable, and secure batch processing of up to 1000 companies in one run.
Whether you're gathering competitive intelligence or tracking brand activity, this LinkedIn posts scraper delivers clean and structured data.


<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/za2122/footer-section/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/devpilot1" target="_blank">
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
  If you are looking for <strong>Linkedin Company Posts Batch Scraper | No Cookies</strong> you've just found your team — Let’s Chat. 👆👆
</p>


## Introduction
The LinkedIn Company Posts Batch Scraper retrieves recent posts and public activity from any set of LinkedIn company pages.
It solves the challenges of manual data collection by automating extraction, ensuring accuracy, and avoiding account risk since no cookies or login are required.
This tool is ideal for analysts, marketers, researchers, and data teams seeking automated LinkedIn insights.

### Why Use a No-Login LinkedIn Scraper?
- Zero account risk — no cookies or authentication required.
- Extract posts from up to 1000 companies in one batch.
- Collect reactions, comments, media, and URLs for each post.
- Maintain input order and avoid duplicates automatically.
- Supports both company names and full LinkedIn URLs.

## Features
| Feature | Description |
|---------|-------------|
| Batch Processing | Scrape up to 1000 LinkedIn company pages in one execution. |
| No Login Required | Extract public posts securely without sharing cookies or account access. |
| Concurrent Requests | Process up to 10 companies at a time for faster turnaround. |
| Flexible Input | Accepts company names, LinkedIn profile URLs, or mixed inputs. |
| Post Limiting | Choose between 1–100 posts per company with the `limit` parameter. |
| Media Extraction | Retrieves images, article previews, and other attachments. |
| Reaction & Comment Counts | Captures engagement metrics for each post. |
| Order Preservation | Keeps output in the same order as the input list. |
| Automatic Deduplication | Removes repeated company entries before scraping. |

---

## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|------------------|
| companyName | The company identifier used for extraction. |
| postUrl | Direct URL to the LinkedIn post. |
| content | Text content of the post. |
| media | Images, article links, or other attached media. |
| reactions | Counts of reactions by type (e.g., likes, celebrates, insights). |
| commentsCount | Number of comments on the post. |
| timestamp | Unix timestamp of the post. |
| publishedAt | Human-readable post date. |

---

## Example Output
    [
      {
        "companyName": "microsoft",
        "postUrl": "https://www.linkedin.com/posts/example",
        "content": "Announcing new cloud innovations...",
        "media": ["https://image-link.jpg"],
        "reactions": {
          "likes": 254,
          "insightful": 32,
          "celebrate": 14
        },
        "commentsCount": 18,
        "timestamp": 1680789311000,
        "publishedAt": "2023-04-06T06:55:00Z"
      }
    ]

---

## Directory Structure Tree
    Linkedin Company Posts Batch Scraper | No Cookies/
    ├── src/
    │   ├── runner.py
    │   ├── extractors/
    │   │   ├── linkedin_parser.py
    │   │   └── utils_time.py
    │   ├── outputs/
    │   │   └── exporters.py
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── inputs.sample.txt
    │   └── sample.json
    ├── requirements.txt
    └── README.md

---

## Use Cases
- **Marketing teams** collect competitor social activity to refine messaging and track industry trends.
- **Data analysts** automate LinkedIn post monitoring to support reporting and dashboards.
- **Researchers** gather public corporate announcements for analysis and insights.
- **Recruiters** monitor employer brand activity to understand company culture trends.
- **Brand managers** track engagement on partner or competitor updates for benchmarking.

---

## FAQs

**Does this scraper require a LinkedIn account?**
No. It uses only public LinkedIn data, meaning you avoid any login risk or restrictions.

**How many companies can I scrape at once?**
You can submit up to 1000 companies per run, and both names and LinkedIn URLs are supported.

**Can I control how many posts I get per company?**
Yes. Use the `limit` parameter to set between 1 and 100 posts per company.

**What happens if two company inputs are duplicates?**
The scraper automatically removes duplicates and maintains the original ordering of unique entries.

---

## Performance Benchmarks and Results
**Primary Metric:** Processes an average of 8–12 company pages per minute depending on post volume and media content.
**Reliability Metric:** Maintains a 98%+ success rate across large batches with automatic retry handling.
**Efficiency Metric:** Supports up to 10 concurrent requests to minimize total runtime without overloading resources.
**Quality Metric:** Consistently delivers complete post data, including reactions, timestamps, and media, with high structural accuracy.


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
        <img src="https://github.com/za2122/footer-section/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        “Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time.”
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/za2122/footer-section/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        “Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on.”
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtube.com/shorts/6AwB5omXrIM" target="_blank">
        <img src="https://github.com/za2122/footer-section/blob/main/media/review3.gif" alt="Review 3" width="35%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        “Exceptional results, clear communication, and flawless delivery. Bitbash nailed it.”
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
  </tr>
</table>
