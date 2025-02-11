# **Game and User Behavior Analysis in AI Editing Platform**

## **Analysis Type**  
**Diagnostic Analysis** – Investigating the underlying reasons for differences in user behavior, premium conversions, and game engagement patterns.

## **Tools Used**
- Python (Pandas, Matplotlib)
- SQL

## **Completion Date**
November 18, 2024

## **Company Industry**
Gaming & AI-based Content Creation

## **Company Name**
Eklipse

---

## **Overview Headline**
**Understanding User Behavior and Optimizing Premium Conversions Through Data-Driven Diagnostics**

## **Overview**
This project analyzes **why** Free and Premium users behave differently on **Eklipse**, a platform that allows users to upload game sessions, generate and edit clips, and access premium features. The goal is to diagnose the causes behind user engagement trends, identify factors affecting premium conversions, and determine the impact of specific games on user activity.


## **Data Details**
The analysis used multiple datasets, including:
1. **Clips Dataset** – Information on automatically generated and manually edited clips.
2. **Downloaded Clips Dataset** – Tracking of user downloads.
3. **Gamesession Dataset** – Details on uploaded game sessions.
4. **Premium Users Dataset** – Identifying users with active subscriptions.
5. **Shared Clips Dataset** – Data on shared clips.

Key Variables:
- `user_id`, `gamesession_Id`, `clip_type_id`, `duration`, `event_name`, `game_name`
- Timestamps (`created_at`, `join_at`)


## **Problem Statement**
**Why do Free users engage differently than Premium users, and what factors influence conversion to Premium?**  

Key questions addressed:
1. **Why** do Free users have higher session durations but lower engagement with advanced features?
2. **Why** do certain games drive higher engagement and monetization?
3. **Why** do users choose to upgrade (or not upgrade) to Premium?


## **Solution**
### **User Behavior Diagnostics**
- Analyzed **session duration, clip downloads, shares, and clip creation frequency** across Free and Premium users.
- Diagnosed **why Free users generate more clips but engage less with premium features**.
- Identified **patterns in sharing behavior** and how Premium users leverage AI-powered editing tools.

### **Conversion Diagnostics**
- Determined **why Free users hesitate to upgrade**, focusing on limitations such as download restrictions and AI editing access.
- Segmented users based on engagement patterns to identify **which behaviors predict conversion**.

### **Game Engagement Diagnostics**
- Investigated **which games drive the most engagement** and why some are more attractive to Premium users.
- Diagnosed the impact of **AI-generated highlight clips and TikTok-format clips** on game-specific engagement.
- Analyzed why **games like COD: Warzone, Fortnite, and Valorant** had the highest monetization potential.


## **Insights**
1. **High-Engagement Free Users Are an Untapped Premium Opportunity**  
   - Free users have **6,132 hours of gameplay** vs. **2,851 hours for Premium users**, but downloads are restricted.
   - Free users create **significantly more clips**, indicating that they depend on the platform but lack incentives to upgrade.

2. **Premium Users Leverage Advanced Features for Efficiency**  
   - **Shorter session durations** but **higher-quality output** due to AI-driven editing and multi-platform sharing.

3. **Game-Specific Behavior Trends Affect Monetization**  
   - **COD: Warzone & Fortnite** lead in **downloads and clip creation**.
   - **Valorant & Overwatch 2** are emerging as strong contenders for premium engagement.

4. **"Unknown" and "Other Games" Categories Distort Analytics**  
   - A significant number of clips are categorized under **Unknown**, which could affect marketing strategies.


## **Recommendations**
1. **Increase Free-to-Premium Conversions**
   - Implement **personalized upgrade offers** for high-engagement Free users.
   - Offer **limited-time Premium trials** for users reaching download limits.
   - Introduce **gamified incentives** (e.g., “Earn a 3-day Premium trial after 10 shares”).

2. **Game-Specific Premium Marketing**
   - **COD & Fortnite:** Market **AI-powered highlight clips** and **exclusive templates** to increase subscriptions.
   - **Valorant & Overwatch 2:** **Target premium engagement** by showcasing advanced editing tools.

3. **Improve Monetization Through AI Editing**
   - Introduce **tiered subscriptions** (e.g., a low-cost AI Editing Pass).
   - Enable **microtransactions for individual clip enhancements**.

4. **Refine Data Classification for Better Insights**
   - Implement **automated tagging** to track **"Unknown"** game engagement more accurately.

5. **Leverage Gamification**
   - Introduce **sharing challenges** (e.g., "Top 10 Fortnite clips get a free Premium trial").
   - **Reward active Free users** with **temporary Premium perks**.


## **Presentation**
[Canva](https://www.canva.com/design/DAGWt1t4Jh8/YycVuUB2fEH8zDUhjUvklw/view?utm_content=DAGWt1t4Jh8&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hd3ce5cdd3b)
