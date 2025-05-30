# 📰 HCN DISPATCH REPORTER GUIDE - SIMPLIFIED WORKFLOW
## 🚀 ULTRA-SIMPLE DAILY PROCESS
### Your Only Task - Upload One File Daily
1.	Go to - https://github.com/selco13/hcn-news-data
2.	Click - "Add file" → "Create new file"
3.	Filename - 2025-05-24.json (today's date)
4.	Copy & paste the template below
5.	Fill in your news
6.	Click "Commit new file"
**That's it!** The system automatically discovers your file and adds it to the news rotation.
---
## 📝 DAILY NEWS TEMPLATE
**Copy this entire template and fill in your news**
```
{
  "breaking": {
    "active": false,
    "text": "",
    "mainStoryIsBreaking": false
  },
  "mainStory": {
    "category": "EXPLORATION",
    "title": "New Mining Operation Approved in Nyx System",
    "subtitle": "Corporate consortium receives UEE approval for asteroid mining in previously restricted zone",
    "author": "Your Name, Correspondent",
    "date": "Star Date: 2954.05.24",
    "content": "<p>Write your main story here. Each paragraph should be wrapped in paragraph tags like this.</p><p>Add more paragraphs as needed. Remember to include quotes and details that make the story interesting.</p><p>Always end with a strong concluding paragraph that ties everything together.</p>"
  },
  "quickUpdates": [
    {
      "title": "Traffic Advisory Issued",
      "summary": "Heavy congestion expected around major jump points this week."
    },
    {
      "title": "New Trade Route Opens",
      "summary": "Commercial vessels gain access to Hadrian system shipping lanes."
    },
    {
      "title": "Weather Alert Active",
      "summary": "Ion storms detected in outer Stanton system - pilots advised caution."
    }
  ],
  "marketWatch": [
    {
      "title": "UEC Exchange Rate",
      "summary": "1 UEC = 1.00 UEC (Stable)"
    },
    {
      "title": "Mining Equipment",
      "summary": "↑ 6.8% - New operations drive equipment demand"
    },
    {
      "title": "Quantum Fuel",
      "summary": "↓ 2.1% - Supply chains stabilize after recent shortages"
    }
  ],
  "secondaryStories": [
    {
      "category": "BUSINESS",
      "title": "Corporate Merger Creates Mining Giant",
      "subtitle": "Two major asteroid mining companies announce historic partnership",
      "author": "Business Reporter Name",
      "date": "2954.05.24",
      "content": "<p>Write your secondary story content here. This can be shorter than the main story but should still be informative and engaging.</p>"
    },
    {
      "category": "TECHNOLOGY",
      "title": "New Scanner Technology Improves Asteroid Detection",
      "subtitle": "Advanced sensors can identify valuable minerals from greater distances",
      "author": "Tech Reporter Name",
      "date": "2954.05.24",
      "content": "<p>Another secondary story goes here. You can have 2-3 secondary stories per day.</p>"
    }
  ]
}
```
---
## 🚨 FOR BREAKING NEWS
If you have breaking news, change the top section to
```
"breaking": {
  "active": true,
  "text": "BREAKING: Your urgent headline here - this will scroll across the screen",
  "mainStoryIsBreaking": true
},
```
---
## 🎯 APPROVED CATEGORIES
**Choose from these for your stories**
* **BREAKING** - Urgent News
* **EXPLORATION** - New Discoveries, Jump Points
* **MILITARY** - UEE Forces, Fleet Week
* **POLITICS** - Senate, Government
* **SECURITY** - Piracy, Law Enforcement
* **TECHNOLOGY** - Ship Tech, Advances
* **BUSINESS** - Corporate News, Economics
* **COMMUNITY** - Events, Culture
* **SCIENCE** - Research, Discoveries
---
## ✍️ WRITING GUIDELINES
### Star Citizen Style
* **Government** - UEE (United Empire of Earth)
* **Military** - UEE Navy, UEE Advocacy
* **Currency** - UEC (United Earth Credits)
* **Date** - Always "Star Date: YYYY.MM.DD"
* **Media** - Holofeed not Broadcast :bangbang:
### HTML Formatting
* Wrap paragraphs in `<p></p>` tags
* For quotes - `<p>"Quote here," said Name.</p>`
* For emphasis - `<strong>important text</strong>`
### Market Watch Symbols
* Use `↑` for price increase
* Use `↓` for price decrease
* Use `↗` for upward trend
* Use `↘` for downward trend
* Include percentage change
---
## 📅 STREAMLINED DAILY WORKFLOW
**Every Day**
1.	**Check what happened yesterday** for context
2.	Open GitHub repository
3.	Click "Add file" → "Create new file"
4.	Name file - YYYY-MM-DD.json **(today's date)**
5.	Copy template above
6.	Fill in all sections with today's news
7.	Commit new file
8.	**Done!** The system automatically finds your file!
**No more index file management!**
he system automatically discovers your daily files and adds them to the news rotation.
---
## 🔍 QUALITY CHECKLIST
Before committing your file
* [ ] File named with today's date (`2024-05-24.json`)
* [ ] All categories from approved list
* [ ] Dates in Star Citizen format (Star Date: YYYY+930.MM.DD)
* [ ] Paragraphs wrapped in `<p></p>` tags
* [ ] No missing commas in JSON
* [ ] Quotes use proper quotation marks
* [ ] Content fits Star Citizen Universe
---
# 🔧 HOW THE AUTO-DISCOVERY WORKS
**Behind the scenes, the system**
1.	**Tries to load** an index file if it exists (for faster loading)
2.	**If no index exists** - Automatically checks the last 60 days for news files
3.	**Builds the edition list** dynamically based on files it finds
4.	**Updates automatically** whenever you add new files
**This means**
* ✅ **Zero maintenance** - Just upload daily files
* ✅ **No coordination needed** - Multiple reporters can work independently
* ✅ **Automatic updates** - New files appear immediately
* ✅ **Error-proof** - No chance of forgetting to update index files
---
# 📰 HCN DISPATCH REPORTER GUIDE - MULTI-REPORTER WORKFLOW
## 🚀 MULTIPLE REPORTERS? NO PROBLEM!
The system now supports **multiple reporters working on the same day** without conflicts. Each reporter can upload their own file using different naming conventions.
## Your File Naming Options
### Option 1: Simple Daily File
* `2024-05-24.json` - Use if you're the only reporter for the day
### Option 2: Reporter-Specific Files
* `2024-05-24-sarah.json` - Include your name
* `2024-05-24-marcus.json` - Each reporter gets their own file
* `2024-05-24-elena.json` - No conflicts possible
### Option 3: Edition-Type Files
* `2024-05-24-main.json` - Main daily edition
* `2024-05-24-breaking.json` - Breaking news updates
* `2024-05-24-morning.json` - Morning edition
* `2024-05-24-evening.json` - Evening update
* `2024-05-24-update.json` - General updates
## How Multi-File Merging Works
✅ **Automatic Combination** - System merges all files for the same date
✅ **Smart Prioritization** - Breaking news takes precedence
✅ **No Duplicates** - Duplicate stories/updates are filtered out
✅ **Latest Wins** - If same content from multiple reporters, latest version is used
---
# 📅 DAILY WORKFLOW OPTIONS
## Solo Reporter Workflow
1.	**Upload** - `2024-05-24.json` (complete daily edition)
2.	**Done!**
## Multi-Reporter Workflow
1.	**Sarah uploads** - `2024-05-24-sarah.json` (her stories)
2.	**Marcus uploads** - `2024-05-24-marcus.json` (his stories)
3.	**Elena uploads** - `2024-05-24-breaking.json` (breaking news)
4.	**System automatically merges** all three into one daily edition
## Breaking News Updates
1.	**Morning** - Upload `2024-05-24-main.json` (daily edition)
2.	**Afternoon** - Upload `2024-05-24-breaking.json` (breaking news)
3.	**Evening** - Upload `2024-05-24-update.json` (final updates)
4.	**Readers see** - Combined edition with all content
---
# 📝 FILE TEMPLATES
## Full Daily Edition Template
```
{
  "breaking": {
    "active": false,
    "text": "",
    "mainStoryIsBreaking": false
  },
  "mainStory": {
    "category": "EXPLORATION",
    "title": "Your Main Headline Here",
    "subtitle": "Brief description under the headline",
    "author": "Your Name, Correspondent",
    "date": "Star Date: 2954.05.24",
    "content": "<p>Your main story content here.</p><p>Multiple paragraphs as needed.</p>"
  },
  "quickUpdates": [
    {
      "title": "Quick Update 1",
      "summary": "Brief summary of this update."
    },
    {
      "title": "Quick Update 2",
      "summary": "Another brief summary."
    }
  ],
  "marketWatch": [
    {
      "title": "UEC Exchange Rate",
      "summary": "1 UEC = 1.00 UEC (Stable)"
    },
    {
      "title": "Your Market Item",
      "summary": "↑ X.X% - Brief explanation"
    }
  ],
  "secondaryStories": [
    {
      "category": "BUSINESS",
      "title": "Secondary Story Headline",
      "subtitle": "Brief description",
      "author": "Your Name",
      "date": "2954.05.24",
      "content": "<p>Secondary story content here.</p>"
    }
  ]
}
```
## Breaking News Only Template
```
{
  "breaking": {
    "active": true,
    "text": "BREAKING: Your urgent headline that scrolls across screen",
    "mainStoryIsBreaking": true
  },
  "mainStory": {
    "category": "BREAKING",
    "title": "Breaking News Headline",
    "subtitle": "What happened briefly",
    "author": "Your Name, Breaking News",
    "date": "Star Date: 2954.05.24",
    "content": "<p>Breaking news story details here.</p>"
  },
  "quickUpdates": [],
  "marketWatch": [],
  "secondaryStories": []
}
```
## Updates Only Template
```
{
  "breaking": {
    "active": false,
    "text": "",
    "mainStoryIsBreaking": false
  },
  "mainStory": null,
  "quickUpdates": [
    {
      "title": "Traffic Update",
      "summary": "Current situation at major ports."
    },
    {
      "title": "Weather Alert",
      "summary": "Storm warning for outer systems."
    }
  ],
  "marketWatch": [
    {
      "title": "Fuel Prices",
      "summary": "↑ 3.2% - High demand from increased traffic"
    }
  ],
  "secondaryStories": [
    {
      "category": "COMMUNITY",
      "title": "Local Event Coverage",
      "subtitle": "Community gathering draws crowds",
      "author": "Your Name",
      "date": "2954.05.24",
      "content": "<p>Event coverage here.</p>"
    }
  ]
}
```
---
# 🔄 SMART MERGING RULES
## Priority Order
1.	**Breaking news files** (`-breaking.json`) [Highest Priority]
2.	**Main edition files** (`-main.json` or just `YYYY-MM-DD.json`)
3.	**Timed editions** (`-morning.json`, `-evening.json`)
4.	**Reporter files** (`-sarah.json`, `-marcus.json`)
5.	**Update files** (`-update.json`)
## Merge Logic
* **Breaking News** - Latest active breaking news wins
* **Main Story** - Priority by file type, or latest if same type
* **Quick Updates** - All merged, duplicates removed by title
* **Market Watch** - All merged, latest wins for same items
* **Secondary Stories** - All merged, duplicates removed by title
## Content Limits :bangbang:
* **Quick Updates** - Max 5 items (most recent)
* **Market Watch** - Max 5 items (most recent)
* **Secondary Stories** - Max 6 stories (most recent)
---
# 💼 NEWSROOM ORGANIZATION EXAMPLES
## Example 1 - Beat Reporters
* **Sarah (Politics)** - 2024-05-24-sarah.json - Government stories
* **Marcus (Military)** - 2024-05-24-marcus.json - Defense coverage
* **Elena (Business)** - 2024-05-24-elena.json - Economic news
* **Result** - Combined edition with all beat coverage
## Example 2 - Edition Schedule
* **6 AM** - 2024-05-24-morning.json - Morning briefing
* **12 PM** - 2024-05-24-breaking.json - Breaking news
* **6 PM** - 2024-05-24-evening.json - Evening wrap-up
* **Result** - Comprehensive daily edition with all updates
## Example 3 - News Desk
* **Editor** - 2024-05-24-main.json - Main daily stories
* **Breaking News Desk** - 2024-05-24-breaking.json - Live updates
* **Wire Service** - 2024-05-24-update.json - Market/quick updates
* **Result** - Professional multi-source daily edition
---
# ✅ QUALITY CONTROL
## File Naming Rules
* ✅ Always start with date - `YYYY-MM-DD`
* ✅ Use hyphens for separators - `-sarah` not `_sarah`
* ✅ Keep names short and clear - `-main`, `-breaking`, `-update`
* ✅ Avoid spaces and special characters
## Content Guidelines
* ✅ Include your byline in author fields
* ✅ Use Star Citizen universe terminology
* ✅ Check JSON syntax before uploading
* ✅ Don't duplicate content between files
## Coordination Tips
* 📢 **Communicate** - Let other reporters know what you're covering
* 🕐 **Timing** - Breaking news should be uploaded ASAP
* 📝 **Clear Authorship** - Include your name in author fields
* 🔄 **Updates** - Use update files for corrections/additions
---
# 🆘 TROUBLESHOOTING
## JSON Error
* Check for missing commas between sections
* Make sure all quotes are double quotes "
* Use jsonlint.com to check syntax
## File Not Showing
* Wait 2-3 minutes for auto-discovery to run
* Check file name uses exact date format (YYYY-MM-DD)
* Verify repository is Public, not Private
## Can't Edit Files
* Make sure you're logged into GitHub
* Check you're in the right repository
* Try refreshing the page
## Multiple Files Not Merging
* Check all files use same date format (YYYY-MM-DD)
* Verify all files are valid JSON
* Wait 2-3 minutes for system to discover files
* Check console for merge messages
## Content Missing
* Ensure unique titles (duplicates are filtered)
* Check file naming follows patterns above
* Verify content structure matches templates
* Look for JSON syntax errors
## Breaking News Not Showing
* Make sure "active" - true in breaking section
* Use -breaking.json filename for priority
* Check breaking text is under 200 characters
* Verify breaking news uploaded after other files
---
# 📞 SUPPORT
**Pro Tip:** The system checks for new files every few minutes, so your news will appear automatically without any extra steps. Just focus on writing great content!

This streamlined workflow eliminates all the technical maintenance tasks and lets reporters focus on what they do best - creating compelling news content for the Star Citizen universe.