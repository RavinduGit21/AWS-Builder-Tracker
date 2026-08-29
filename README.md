# ☁️ AWS Builder Rewards Tracker

An intuitive, local-first web dashboard designed for community builders to log daily engagement, maintain activity streaks, track badge progress, and reach AWS reward milestones across a 90-day program.

---

## 🌟 Features

- 📅 **90-Day Interactive Calendar Tracker**
  - Track daily Builder Center activities: **Visit**, **Like**, **Comment**, **Wish Vote**, and **Article Publishing**.
  - Interactive grid with visual status cues for completed tasks and past/future dates.

- 🔥 **Automated Streak Engine**
  - Instant calculation of consecutive activity streaks for visits, likes, and comments.
  - Monitors progress toward crucial **7-day**, **30-day**, and **90-day** streak milestones.

- 🏆 **21 Badge Progress Management**
  - Complete list of all 21 AWS Builder Center badges (manual check-ins and numeric goal counters).
  - Dynamic visual progress bars calculating overall completion percentage.

- 🎁 **Reward & Milestone Tracker**
  - Real-time indicator for unlocked rewards and next targets:
    - **7 Badges**: $10 / $20 AWS Credits
    - **14 Badges**: $100 AWS Credit Milestone
    - **21 Badges**: AWS Certification Voucher Milestone

- 📝 **Daily Notes & Reference Journal**
  - Dedicated notes section to stash links to published articles, comment threads, Wish votes, and community interactions.

- 🔒 **Local-First & Privacy-Focused**
  - Runs entirely in the browser using `localStorage`. No user accounts, registration, backend servers, or tracking cookies required.
  - Includes **Export Data** functionality to backup your progress state into JSON format.

---

## 🎯 Badges & Milestone Matrix

| Badge ID | Badge Name | Requirement / Target | Tracking Type |
| :--- | :--- | :--- | :--- |
| `b1` | **Knowledge Seeker** | Complete Builder Center activity | Manual Checkbox |
| `b2` | **Hello, World!** | Complete profile onboarding | Manual Checkbox |
| `b3` | **Photo Finisher** | Add a profile photo | Manual Checkbox |
| `b4` | **Discussion Debut** | Create first discussion/post | Manual Checkbox |
| `b5` | **First Wish** | Create first Wish | Manual Checkbox |
| `b6` | **First Article** | Publish first article | Manual Checkbox |
| `b7`–`b9` | **7-Day Streaks** | 7 consecutive days of Visit / Like / Comment | Automated Streak |
| `b10` | **4-Week Wish Vote Streak** | Vote on Wishes weekly for 4 consecutive weeks | Counter |
| `b11` | **4-Week Article Streak** | Publish an article weekly for 4 consecutive weeks | Counter |
| `b12`–`b14`| **30-Day Streaks** | 30 consecutive days of Visit / Like / Comment | Automated Streak |
| `b15` | **Conversation Starter** | Get replies on 10 of your comments | Counter |
| `b16` | **Meaningful Contributor** | Get 10 likes on each of 5 comments | Counter |
| `b17` | **Valued Creator** | Get 10 likes on each of 5 articles | Counter |
| `b18` | **Idea Influencer** | Get 10 votes on your Wishes | Counter |
| `b19`–`b21`| **90-Day Streaks** | 90 consecutive days of Visit / Like / Comment | Automated Streak |

---

## 🛠️ Technology Stack

- **Frontend**: Standard HTML5 & Vanilla JavaScript (ES6+)
- **Styling**: Modern Vanilla CSS3 with CSS Custom Properties, Flexbox, and CSS Grid
- **Persistence**: Browser `localStorage` (Key: `awsBuilderRewardsTracker_v1`)
- **Dependencies**: Zero external libraries or frameworks (100% lightweight & offline-capable)

---

## 🚀 Getting Started

### Option 1: Direct File Launch
Simply open `index.html` directly in any modern web browser (Chrome, Firefox, Edge, Safari):

```bash
# On Windows PowerShell
Invoke-Item index.html
```

### Option 2: Local HTTP Server
Serve using any simple static file server, for example:

```bash
# Using Python
python -m http.server 8000

# Using Node npx
npx serve .
```

Then open `http://localhost:8000` in your web browser.

---

## 💾 Data Backup & Reset

- **Export Data**: Click the **Export Data** button in the header to download a timestamped JSON backup file containing your task records, custom counters, manual check-ins, and notes.
- **Reset All**: Use the **Reset All** button to clear browser storage and start fresh.

---

## 📄 License

Distributed under the MIT License. Feel free to customize and modify for your personal AWS tracking goals!
