# ☁️ AWS Builder Rewards Tracker

An intuitive, modern, local-first web dashboard designed for AWS community builders to log daily engagement, maintain activity streaks, track badge progress, and reach AWS reward milestones across a 90-day program.

---

## 🌟 Features

- 🏆 **All 21 AWS Student Rewards Badges Table**
  - Structured full matrix table detailing all 21 AWS Builder Center badges.
  - Displays badge icons, precise requirement descriptions ("What you need to do"), and real-time status indicators (Unlocked ✅ / In Progress / Pending).
  - Includes interactive checkboxes for manual check-ins and numeric input fields for goal counters.

- 📊 **Practical Daily Task List**
  - **✅ One-Time Tasks**: Quick checklist for foundational onboarding badges (Knowledge Seeker, Hello World, Photo Finisher, Discussion Debut, First Wish, First Article).
  - **🔥 Everyday Core Habits**: Dedicated daily habit tracker for **Visit Builder Center**, **Like useful content**, and **Leave a meaningful comment** — the 3 daily habits that feed all 7-Day, 30-Day, and 90-Day streak badges.

- 🎁 **Visual Reward Milestones**
  - Dynamic milestone cards highlighting current reward achievements and next targets:
    - 🎯 **7 Badges**: $10 AWS Credits
    - 🎁 **14 Badges**: +$20 AWS Credits ($30 Total Credits)
    - 🏆 **21 Badges**: $100 AWS Foundational Certification Voucher

- 📅 **90-Day Interactive Calendar Matrix**
  - Full 90-day daily activity grid tracking Visit, Like, Comment, Wish Vote, and Article publishing tasks.
  - Visual cues highlighting today's date, past logs, and future days.

- 📝 **Quick Notes & Reference Journal**
  - Dedicated notes section to stash links to published articles, comment threads, Wish votes, and community interactions.

- 🔒 **Local-First & Data Portability**
  - Runs entirely in your browser using `localStorage`. No server, backend, account registration, or tracking.
  - **📥 Import JSON**: Restore or load tracker progress from a JSON file.
  - **📤 Export JSON**: Download timestamped JSON backups of your progress state.

---

## 🎯 All 21 AWS Badges & Requirements

| # | Badge Name | Requirement ("What you need to do") | Tracking Type |
| :-: | :--- | :--- | :--- |
| **1** | 🧠 **Knowledge Seeker** | Complete the required learning/exploration activity on Builder Center. | Manual Checkbox |
| **2** | 🌐 **Hello, World!** | Complete your Builder Center profile/onboarding. | Manual Checkbox |
| **3** | 📸 **Photo Finisher** | Add a profile photo to your Builder Center profile. | Manual Checkbox |
| **4** | 💬 **Discussion Debut** | Make your first discussion/post on Builder Center. | Manual Checkbox |
| **5** | 💡 **First Wish** | Create your first Wish in the AWS Builder Center Wishlist. | Manual Checkbox |
| **6** | 📝 **First Article** | Publish your first Builder Center article. | Manual Checkbox |
| **7** | 💻 **7-Day Visit Streak** | Visit Builder Center for 7 consecutive days. | Automated Streak |
| **8** | 💖 **7-Day Like Streak** | Like content for 7 consecutive days. | Automated Streak |
| **9** | 💬 **7-Day Comment Streak** | Comment for 7 consecutive days. | Automated Streak |
| **10** | 📋 **4-Week Wish Vote Streak** | Vote on Wishes once each week for 4 consecutive weeks. | Goal Counter |
| **11** | ✍️ **4-Week Article Streak** | Publish 1 article every week for 4 consecutive weeks. | Goal Counter |
| **12** | 💻 **30-Day Visit Streak** | Visit Builder Center for 30 consecutive days. | Automated Streak |
| **13** | 💖 **30-Day Like Streak** | Like content for 30 consecutive days. | Automated Streak |
| **14** | 💬 **30-Day Comment Streak** | Comment for 30 consecutive days. | Automated Streak |
| **15** | 🗣️ **Conversation Starter** | Get a reply on 10 of your comments. | Goal Counter |
| **16** | ⭐ **Meaningful Contributor** | Get 10 likes on each of 5 different comments. | Goal Counter |
| **17** | 🏆 **Valued Creator** | Get 10 likes on each of 5 different articles. | Goal Counter |
| **18** | 💡 **Idea Influencer** | Get 10 votes on your Wishes. | Goal Counter |
| **19** | 💻 **90-Day Visit Streak** | Visit Builder Center for 90 consecutive days. | Automated Streak |
| **20** | 💖 **90-Day Like Streak** | Like content for 90 consecutive days. | Automated Streak |
| **21** | 💬 **90-Day Comment Streak** | Comment for 90 consecutive days. | Automated Streak |

---

## 🎁 Reward Milestones Breakdown

- **7 Badges**: Unlocks **$10 AWS Credits**
- **14 Badges**: Unlocks an additional **$20 AWS Credits** (*$30 Total Credits earned*)
- **21 Badges**: Unlocks **$100 AWS Foundational Certification Voucher**

---

## 🛠️ Technology Stack

- **Frontend**: HTML5 & Modern Vanilla JavaScript (ES6+)
- **Styling**: Vanilla CSS3 with Custom Properties, Glassmorphism, Flexbox, and CSS Grid
- **Typography**: Google Fonts (*Outfit* & *Inter*)
- **Storage**: Browser `localStorage` (`awsBuilderRewardsTracker_v1`)
- **Dependencies**: 100% Zero external dependencies — runs completely offline.

---

## 🚀 Getting Started

### Launching directly in browser
Double click `index.html` or run in terminal:

```powershell
Invoke-Item index.html
```

---

## 💾 Data Backup & Restore

- **Export Data**: Click **Export Data** to save your progress state to a JSON backup file.
- **Import Data**: Click **Import JSON** to restore or load tracker progress from a JSON file.
- **Reset All**: Use **Reset** to restore default tracker state.

---

## 📄 License

Distributed under the MIT License. Feel free to modify and share!
