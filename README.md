# 💎 Patreon Premium Creator & Posts Scraper

### [Try it today for free with our 3-day free trial! ](https://apify.com/radeance/patreon-scraper)

![Patreon Scraper Cover Image](https://i.imgur.com/T0VDZgm.png)
| Try our other scrapers ► | [Social Blade Scraper](https://apify.com/radeance/socialblade-api) | [Similarweb Scraper](https://apify.com/radeance/similarweb-scraper)| [TikTok Video Scraper](https://apify.com/radeance/tiktok-video-scraper-premium)
|----------------------------|-----------------------------|-----------------------------|-----------------------------|

Welcome to this **Premium Patreon Creator Scraper** on Apify!

This blazing-fast, feature-rich actor is designed to extract detailed creator and content data from Patreon like a pro — whether you're a **creator**, **market researcher**, **content analyst**, **competitive intelligence professional**, or **media strategist**. It effortlessly scrapes public Patreon **creator profiles**, providing extensive metadata including **engagement stats**, **earnings estimates**, **membership tiers**, **all posts**, and comprehensive **creator insights** from **Graphtreon**.

This scraper is **built for large-scale data collection** and **precision** — capable of scraping hundreds of creator profiles with **thousands of data points in minutes**

### [Try it today for free with our 3-day free trial! ](https://apify.com/radeance/patreon-scraper)

## ✨ Key Features

-   **✅ Comprehensive Creator Profile Scraping:**

    -   Scrapes creators by creator name or profile URL (bulk URLs supported)
    -   Extracts key creator details: creator ID, name, creation date, category, rankings,description and SEO data
    -   Captures profile images, background posters, and branding elements
    -   Retrieves social media links (YouTube, Instagram, Twitter, TikTok, Facebook, Twitch)

-   **✅ Advanced Financial & Performance Analytics:**

    -   Membership statistics: total members, paid members, patron counts
    -   Revenue insights: estimated monthly earnings (min/max ranges), earnings currency
    -   Platform performance: category rankings, overall Patreon rankings
    -   Growth metrics and engagement tracking

-   **✅ Detailed Membership Tier Analysis:**

    -   Complete tier structure with pricing, features, and post availability
    -   Tier-specific benefits and exclusive content access levels
    -   Member distribution across different subscription levels

-   **✅ Content & Engagement Intelligence:**

    -   Recent posts data: titles, types (video, podcast, text), publication dates
    -   Engagement metrics: likes, comments, commenter counts for each post
    -   Post thumbnails and preview URLs
    -   Perfect for content categorization and posting frequency analysis

-   **✅ Creator Insights & Audience Data:**

    -   NSFW content flags and content category classification
    -   Free trial availability and monetization strategies
    -   Creator descriptions and value propositions

-   **✅ High-Speed Performance:**

    -   Scrapes hundreds of creator profiles in minutes with parallel processing
    -   Smart rate limiting and request optimization for reliable data collection

-   **✅ Flexible Output Formats:**
    -   Exports results in multiple formats: JSON, CSV, XLSX, JSONL
    -   Clean, structured data ready for analytics, business intelligence, or competitive analysis
    -   Comprehensive dataset perfect for market research and creator economy insights

### [Try it today for free with our 3-day free trial! ](https://apify.com/radeance/patreon-scraper)

## ✨ Output Sample

```json
{
    "creator_id": "105636",
    "created_at": "2014-07-29T21:36:03.000+00:00",
    "profile_url": "https://www.patreon.com/watchwhatcrappens",
    "profile_image_url": "https://c7.patreon.com/https%3A%2F%2Fwww.patreon.com%2F%2Fcard-teaser-image%2Fcreator%2F105636%3Fc=449906604437864095/selector/%23creator-teaser%2C.png",
    "creator_name": "Watch What Crappens",
    "seo_description": null,
    "seo_keywords": null,
    "description": "Hey everybody! It's Ben and Ronnie! Typing. AT THIS VERY MOMENT. We're the hosts of Watch What Crappens, a podcast about all the crap on Bravo we love to watch. We love podcasting, and we love you, and we love money. Specifically, in reverse order. Thank you for making our podcast the huge success that it is. We hope to get bigger and better, and that's where this page comes into play. On Patreon, we offer a weekly bonus episode at the $7 level and you can watch our recaps on video at the $11 level! You can add the bonus feed address from your settings into your favorite podcast app and the episodes will appear in your podcast app as they are published as long as your membership is current. At the $7 level, you'll get weekly bonus episodes and access to our exclusive Discord community.At the $11 level, you'll have instant and early access to all of our Crappens On Demand recaps (which go public a week later) plus everything included in the $7 level. The $50 and $85 levels are for our Premium Sponsor shoutouts plus everything included in the lower levels. Thanks everyone! We're so excited you're here! Ben and Ronnie",
    "shows_earnings": false,
    "shows_patron_count": true,
    "shows_free_trial": true,
    "is_nsfw": false,
    "category": "Podcasts",
    "category_rank": 35,
    "patreon_rank": 105,
    "total_members": 16775,
    "paid_members": 9262,
    "monthly_earnings": null,
    "estimated_avg_monthly_earnings": 45000.0,
    "min_estimate_monthly_earnings": 25000.0,
    "max_estimate_monthly_earnings": 65000.0,
    "earnings_currency": "USD",
    "declined_patron_count": null,
    "tiers": [
        {
            "id": "10311998",
            "created_at": null,
            "published_at": null,
            "edited_at": null,
            "title": "Free",
            "price": null,
            "currency": "USD",
            "available_posts": 20,
            "features": []
        },
        {
            "id": "24269557",
            "created_at": null,
            "published_at": null,
            "edited_at": null,
            "title": "Weekly Bonus Episodes",
            "price": 7.0,
            "currency": "USD",
            "available_posts": 404,
            "features": ["Bonus Episode", "Discord Community"]
        },
        {
            "id": "24269567",
            "created_at": null,
            "published_at": null,
            "edited_at": null,
            "title": "Crappens on Demand",
            "price": 11.0,
            "currency": "USD",
            "available_posts": 996,
            "features": [
                "Crappens On Demand Elite",
                "Bonus Episode",
                "Discord Community",
                "Crappens On Demand Classic"
            ]
        },
        {
            "id": "24269578",
            "created_at": null,
            "published_at": null,
            "edited_at": null,
            "title": "Premium Sponsor!",
            "price": 50.0,
            "currency": "USD",
            "available_posts": 350,
            "features": [
                "Shout Out",
                "Bonus Episode",
                "Discord Community",
                "Crappens On Demand Elite",
                "Crappens On Demand Classic"
            ]
        },
        {
            "id": "24269585",
            "created_at": null,
            "published_at": null,
            "edited_at": null,
            "title": "SUPER PREMIUM SPONSOR!",
            "price": 85.0,
            "currency": "USD",
            "available_posts": 299,
            "features": [
                "Shout Out",
                "Bonus Episode",
                "Discord Community",
                "Crappens On Demand Elite",
                "Crappens On Demand Classic"
            ]
        }
    ],
    "total_posts": 4447,
    "posts": [
        {
            "id": "131287148",
            "created_at": "2025-06-12T06:43:54Z",
            "published_at": "2025-06-12T16:23:59Z",
            "post_type": "video_embed",
            "title": "Crappens on Demand: Next Gen NYC S1E2: War of the Nepo Babies",
            "comments": 16,
            "commenter_count": 13,
            "likes": 50,
            "description": null,
            "duration": null,
            "duration_formatted": null,
            "post_url": "https://www.patreon.com/posts/crappens-on-next-131287148",
            "pledge_url": "/bePatron?c=105636",
            "thumbnail_url": null,
            "video_preview_url": null,
            "video_preview_duration": null
        },
        {
            "id": "131261855",
            "created_at": "2025-06-11T22:05:54Z",
            "published_at": "2025-06-11T22:07:54Z",
            "post_type": "video_embed",
            "title": "Crappens on Demand: The Valley S2E09 No Time to ReJax",
            "comments": 23,
            "commenter_count": 16,
            "likes": 69,
            "description": null,
            "duration": null,
            "duration_formatted": null,
            "post_url": "https://www.patreon.com/posts/crappens-on-no-131261855",
            "pledge_url": "/bePatron?c=105636",
            "thumbnail_url": null,
            "video_preview_url": null,
            "video_preview_duration": null
        },
        {
            "id": "131247149",
            "created_at": "2025-06-11T18:12:10Z",
            "published_at": "2025-06-11T18:19:25Z",
            "post_type": "podcast",
            "title": "BONUS EP #565:  Love Island USA S7E8: Pie in the Ace",
            "comments": 7,
            "commenter_count": 7,
            "likes": 56,
            "description": null,
            "duration": null,
            "duration_formatted": null,
            "post_url": "https://www.patreon.com/posts/bonus-ep-565-usa-131247149",
            "pledge_url": "/bePatron?c=105636",
            "thumbnail_url": "https://c10.patreonusercontent.com/4/patreon-media/p/post/131247149/7151c2b422cb4a1882a3823fe77356aa/eyJoIjo1MTgsInciOjkyMH0%3D/1.png?token-hash=AEeB6ZMLHtO1xKdf6ZyL0Mtrx5b1q1pOpmbLwFw0uNg%3D&token-time=1751328000",
            "video_preview_url": null,
            "video_preview_duration": null
        },
        ...
    ],
    "thumbnail_url": "https://c10.patreonusercontent.com/4/patreon-media/p/campaign/105636/89e9d27b5caf4c5e8f80a26ad78ac2f9/eyJoIjozNjAsInciOjM2MH0%3D/1.jpeg?token-hash=zc8LfVWzBOeN8UDwNWyFDj0XVCr4i1p4z0bYMLTT_i4%3D&token-time=1751328000",
    "background_poster_url": "https://c10.patreonusercontent.com/4/patreon-media/p/campaign/105636/89e9d27b5caf4c5e8f80a26ad78ac2f9/eyJ3Ijo2MjB9/1.jpeg?token-hash=3DgV5dQRwm9V9PHIkZpMIe-MZPjGhIwmIOcHlILsya8%3D&token-time=1751328000",
    "primary_theme_color": "#008aa2",
    "youtube": "https://youtube.com/channel/UCGst9wCLerp9yCPZWbgPHLw",
    "instagram": "https://www.instagram.com/watchwhatcrappens",
    "twitter": "https://twitter.com/WhatCrappens",
    "facebook": null,
    "twitch": null,
    "tiktok": "https://tiktok.com/%40watchwhatcrappens"
}
```

## Use Cases

-   **Marketing Teams & Agencies:** Analyze creator monetization strategies, identify potential brand partnerships, and benchmark competitor creator programs across industries
-   **Business Intelligence & Strategy:** Extract creator economy insights, revenue modeling data, and membership tier optimization strategies for subscription-based businesses
-   **Data Scientists & Analysts:** Collect comprehensive Patreon datasets to model creator success factors, subscription trends, and content monetization patterns
-   **Content Creators & Coaches:** Research successful creators in your niche, analyze pricing strategies, membership tiers, and content delivery methods
-   **Investment & Market Research:** Study the creator economy landscape, evaluate platform growth trends, and assess creator business sustainability for investment decisions

## 📌 Input

![Scraper Sample Input](https://i.imgur.com/Hqb7DxB.png)

**- `creator`**: **(Required) (String)**
Enter the Patreon creator's username to scrape their profile data. This will be used to search for the creator's page if no direct URLs are provided in the bulk URL section.

**- `include_posts`**: **(Optional) (Boolean) (Default: true)**
Enable to include detailed posts data from the creator's Patreon page when available. This includes post titles, engagement metrics, content types, and publication dates.

**- `include_graphtreon`**: **(Optional) (Boolean) (Default: true)**
Enable to enhance results with additional analytics data from Graphtreon.com when available. This provides supplementary insights and historical data for deeper creator analysis.

**- `max_posts`**: **(Optional) (Integer) (Default: 20)**
Set the maximum number of recent posts to scrape per creator. Range: 1-10,000 posts. Set to higher values for comprehensive content analysis or lower values for faster processing.

<br>
<br>

### 🎛️ Advanced Options

![Scraper Sample Advanced Options Input](https://i.imgur.com/cLHST54.png)

**- `creator_urls`**: **(Optional) (Array) (Default: empty)**
Enter Patreon creator page URLs to scrape in bulk. You can specify multiple URLs by clicking on the Add button or in bulk by clicking on the Bulk edit button. If provided, this will override the single creator parameter above.

**- `proxySettings`**: **(Optional) (Object) (Default: Apify Residential US)**
Configure proxy settings for reliable scraping. Default uses Apify's residential proxy network with US geolocation for optimal performance and access to Patreon's content.

#### Supported Patreon Creator Page URL Formats

| Link                                                                                       | Supported |
| ------------------------------------------------------------------------------------------ | --------- |
| [https://www.patreon.com/johnwatsonrooney](https://www.patreon.com/johnwatsonrooney)       | ✅        |
| [https://www.patreon.com/cw/johnwatsonrooney](https://www.patreon.com/cw/johnwatsonrooney) | ✅        |

|

### ✏️ JSON Input

Sample JSON input if you use the apify api via CURL, Python, JS etc.

```
{
    "creator": "johnwatsonrooney", # For one creator only
    "creator_urls": [ # For multiple creators
        "https://www.patreon.com/johnwatsonrooney"
    ],
    "include_graphtreon": true,
    "include_posts": true,
    "proxySettings": {
        "useApifyProxy": true,
        "apifyProxyGroups": [
            "RESIDENTIAL"
        ],
        "apifyProxyCountry": "US"
    }
}
```

## 📎 Detailed Output Information

### Creator Profile Data

Includes comprehensive metadata for each Patreon creator, such as:

-   `creator_id` - Unique Patreon creator identifier
-   `creator_name` - Display name of the creator
-   `created_at` - Account creation timestamp
-   `profile_url` - Direct link to the creator's Patreon page
-   `profile_image_url` - Creator's profile picture URL
-   `description` - Creator's bio and value proposition text
-   `category` - Content category (e.g., "Podcasts", "Art", "Gaming") (via Graphetreon)
-   `is_nsfw` - Boolean flag indicating adult content

### Performance & Analytics

Provides detailed performance metrics and rankings:

-   `total_members` - Total number of patrons/subscribers
-   `paid_members` - Number of paying subscribers
-   `category_rank` - Ranking within their content category (via Graphetreon)
-   `patreon_rank` - Overall platform ranking (via Graphetreon)
-   `monthly_earnings` - Monthly earnings (via Patreon if visible)
-   `estimated_avg_monthly_earnings` - Average estimated monthly revenue (via Graphtreon)
-   `min_estimate_monthly_earnings` - Minimum estimated earnings range (via Graphtreon)
-   `max_estimate_monthly_earnings` - Maximum estimated earnings range (via Graphtreon)
-   `earnings_currency` - Currency for earnings (typically USD)

### Membership Tier Structure

Comprehensive breakdown of subscription offerings:

-   `tiers` - Array of all membership tiers with detailed information
-   `id` - Unique tier identifier
-   `title` - Tier name/title
-   `price` - Monthly subscription cost
-   `currency` - Pricing currency
-   `available_posts` - Number of posts accessible at this tier
-   `features` - Array of tier-specific benefits and perks

### Content & Engagement Data

Recent posts and engagement metrics:

-   `total_posts` - Total number of posts published
-   `posts` - Array of recent posts with detailed metadata
-   `post_type` - Content type (video_embed, podcast, text, etc.)
-   `title` - Post title
-   `comments` - Number of comments on the post
-   `commenter_count` - Unique number of commenters
-   `likes` - Post like count
-   `published_at` - Post publication timestamp
-   `post_url` - Direct link to the post

### Social Media & Branding

Creator's external presence and visual branding:

-   `youtube` - YouTube channel URL
-   `instagram` - Instagram profile URL
-   `twitter` - Twitter/X profile URL
-   `tiktok` - TikTok profile URL
-   `facebook` - Facebook page URL
-   `twitch` - Twitch channel URL
-   `thumbnail_url` - Main profile thumbnail image
-   `background_poster_url` - Background/banner image URL
-   `primary_theme_color` - Brand color in hex format

### Platform Features

Patreon-specific functionality indicators:

-   `shows_earnings` - Whether earnings are publicly displayed
-   `shows_patron_count` - Whether patron count is visible
-   `shows_free_trial` - Whether free trials are offered
-   `seo_description` - SEO meta description
-   `seo_keywords` - SEO keywords for discoverability

### Export Formats

-   Data can be exported in CSV, XLSX, JSON, JSONL, XML, and RSS formats for seamless integration into your data pipeline or analytics workflow.

## ⚙️ While the scraper is running

During the run, the actor will output log messages letting you know what is going on at any point. Each message always contains specific information about the process including which url / page the actor is working on.

If you provide invalid inputs to the actor, it will immediately stop with a failure state and output log messages explaining what is wrong. If you are unsure what went wrong feel free to open up an issue in the issue tab.

## 🔗 Legality of web scraping and scraping of job listings

The **Patreon Premium Creator & Posts Scraper** is designed to ethically extract **only publicly available data**, and it **does not** scrape private user data such as personal email addresses or personal identifiers.

Our scrapers are ethical and do not extract any private user data, such as email addresses, gender, or location. They only extract what the user has chosen to share publicly. We therefore believe that our scrapers, when used for ethical purposes by Apify users, are safe. However, you should be aware that your results could contain personal data. Personal data is protected by the GDPR in the European Union and by other regulations around the world. You should not scrape personal data unless you have a legitimate reason to do so. If you're unsure whether your reason is legitimate, consult your lawyers. You can also read our [blog post](https://blog.apify.com/is-web-scraping-legal/) on the legality of web scraping

## 💬 Feedback and Support

**Your satisfaction** is **important** to us! Therefore we are constantly striving to enhance the performance of our Actors.

If you have any technical feedback or encounter any bugs with the **Patreon Premium Creator & Posts Scraper**, please create an issue in the Actor’s Issues tab on the Apify Console.

You can also contact us directly for custom integrations or project use cases at business@radeance.com.

```

```
### [Try it today for free with our 3-day free trial! ](https://apify.com/radeance/patreon-scraper)