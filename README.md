# 🎵 Melody Insights: Music Streaming Analytics Dashboard 🎵

**Global Streaming Performance + User Behavior Analysis**  
**Built with Tableau** | 1,000 Songs / Streams Dataset | Interactive Music Analytics Project

![](https://media.istockphoto.com/id/1297013252/photo/music-player-on-mobile-phone-with-earphones.jpg?s=612x612&w=0&k=20&c=Y56aq0uvPe8UTYtnMzjHBNQY2WjGERO5iYta1-WwQU8=)

## Project Overview

**Project Name:** Melody Insights – Global Music Streaming & User Behavior Dashboard

**Domain:** Music Industry Analytics
**Tools Used:** Tableau

**Dataset Summary**  
- 1,000 stream/song records  
- Total Streams: 255,072  
- Total Unique Songs: 1,000  
- Total Unique Users: 1,000  
- Key dimensions: Artist, Genre (Pop, Rock, Hip-Hop, Electronic, Classical, Jazz, Indie), Subscription (Free/Premium), Device (Mobile/Desktop/Tablet), Stream Date, Avg Duration (~4 min)

**Main Goals**  
- Reveal top-performing artists and genres globally  
- Compare Free vs Premium user behavior  
- Understand device preferences and streaming patterns over time  
- Deliver actionable insights for music platforms, labels, and marketers

## Dashboard 1: Global Music Streaming Performance

![](https://github.com/Shital9090/Music_Streaming_Analysis/blob/main/Global%20Music%20Streaming%20Performance.png)

**Purpose**  
Shows overall platform performance, top artists, genre distribution, and temporal streaming trends.

**Key Metrics (Cards)**  
- Total Streams: 255,072  
- Total Songs: 1,000  
- Average Song Duration: ~4.039 minutes  
- Total Unique Users: 1,000

**Main Visuals & Explanations**

1. **Top 10 Artists by Streams (Horizontal Bar Chart)**  
   - Artists ranked by total stream count  
   - Top performers: Taylor Swift (highest), Imagine Dragons, Arijit Singh, Adele, Ed Sheeran, BTS, Bad Bunny  
   - **Takeaway:** Pop/global superstars dominate; Indian & K-pop artists (Arijit Singh, BTS) show strong international reach

2. **Genre Popularity Distribution (Donut Chart)**  
   - Almost even split across genres  
   - Rock (~30.32%), Pop (~29.40%), Electronic (~28.70%), Classical (~28.70%), Jazz (~28.47%), Indie & Hip-Hop (~27.55%)  
   - **Takeaway:** Highly diverse catalog — no single genre dominates → platform appeals to wide audience

3. **Streams Over Time (Line Chart)**  
   - Monthly stream count from Jan to Dec  
   - Fluctuates between ~15K–22K streams/month with small peaks in March, May–June, November  
   - **Takeaway:** Consistent year-round engagement with mild seasonal boosts (possibly spring/summer & year-end)

4. **Top N Parameter Slicer**  
   - Dynamic control to show Top 5, 10, 15 artists  
   - **Use:** Helps zoom into highest-impact creators

**Core Insights from Dashboard 1**  
- Taylor Swift leads globally — strong candidate for playlist/promotion priority  
- Balanced genre mix → opportunity to cross-promote between genres  
- Stable monthly streams → loyal recurring listeners

## Dashboard 2: User Behavior & Subscription Insights

![](https://github.com/Shital9090/Music_Streaming_Analysis/blob/main/User%20Behavior%20%26%20Subscription%20Insights.png)

**Purpose**  
Analyzes how subscription type (Free vs Premium) and device usage influence streaming behavior.

**Key Metrics (Cards)**  
- Free Users: 518  
- Premium Users: 482  
- Free Streams: ~120K+ (slightly higher volume)  
- Premium Streams: ~120K+

**Main Visuals & Explanations**

1. **Free vs Premium Streaming (Clustered Column Chart)**  
   - Free users generate marginally higher total stream volume  
   - **Takeaway:** Free tier drives discovery & high volume; Premium provides steady revenue

2. **Users Split (Card + implicit comparison)**  
   - 518 Free | 482 Premium → near 50/50 split  
   - **Takeaway:** Large free user base = conversion opportunity

3. **Device Usage Distribution (Pie Chart)**  
   - Tablet: 35.3%  
   - Desktop: 32.9%  
   - Mobile: 31.8%  
   - **Takeaway:** Surprisingly tablet-strong usage (possibly longer sessions); Mobile still very significant

4. **Average Streams by Genre & Subscription Type (Clustered Bar Chart)**  
   - Premium users stream more per genre in most cases (especially Classical, Pop, Rock)  
   - Free users higher in Electronic & Hip-Hop  
   - **Takeaway:** Premium subscribers show deeper/more diverse listening; Free users lean toward high-energy genres

**Core Insights from Dashboard 2**  
- Premium users engage more deeply → focus on retention & upselling premium features  
- Mobile + Tablet = ~67% of streams → mobile-first + tablet-optimized UX is critical  
- Genre preferences vary by subscription → targeted campaigns (e.g., Electronic/Hip-Hop for Free users)

## Interactivity & Features
- Genre, Subscription Type, Device Type slicers available on both pages  
- Cross-filtering enabled (click artist → see genre/device impact)  
- Tooltips show exact values & context

## How to Use
1. Open the `.pbix` file in Power BI Desktop  
2. Use slicers to filter by genre, subscription, device, artist top-N, month  
3. Click visuals to cross-highlight related data  
4. Hover for detailed tooltips

## Files in Repository
- `Melody_Insights_Dashboard.pbix` (combined or separate pages)  
- `data/music_streaming_sample.csv` (if included)  
- `README.md`  
- `/images/` folder with screenshots (recommended)

## Future Ideas
- Add listener retention/churn metrics  
- Song-level popularity & repeat streams  
- Country/region analysis (if data added)  
- Artist collaboration network  
- Publish to Power BI Service + embed

⭐ If this project inspires you — feel free to fork or contribute!

Made with passion for music & data in Sholapur, Maharashtra 🎧📈  
Shital | Data Analytics Enthusiast
