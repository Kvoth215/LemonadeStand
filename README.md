# 🍋 Lemonade Stand Pro
### A Business Simulation Game for Middle School BCIT Classes
**Built for:** BCIT Business Simulation · Located in Langhorne PA  
**Designed by:** A BCIT teacher in collaboration with Claude AI  
**Plays on:** Any browser — phones, tablets, PCs, laptops  

---

## What Is This?

**Lemonade Stand Pro** is a fully self-contained business simulation game that runs entirely in a single HTML file — no app store, no login, no subscription, no internet connection required after loading. Students run a lemonade stand for 7, 14, or 21 days, making real business decisions every single day and living with the consequences.

It was built from scratch by a BCIT teacher who wanted something that actually *teaches* business concepts rather than just describing them. Every mechanic in the game is grounded in a real business principle.

---

## Why This Works in a Classroom

### Students make decisions with real stakes
Every day students choose how many cups to produce, what price to charge, how much to spend on advertising, and whether to take risks. Bad decisions cost real (simulated) money. Good decisions compound. There is no "undo."

### The math is always visible
Revenue, costs, profit, break-even, ROI — the numbers are right there on screen, recalculated in real time as students plan their day. Students aren't told what these terms mean — they *experience* them.

### It catches teachable moments automatically
- **Demand exceeds supply?** The game immediately shows a callout: how many customers were turned away, how much revenue was lost, and what "opportunity cost" means — using the student's own numbers.
- **Inventory waste?** Unsold cups are flagged with their exact dollar cost.
- **End of day quiz?** A multiple choice question appears. Students must answer it to unlock the next day. After they answer, a full explanation of the correct answer appears — right or wrong.

### 40+ random events keep every playthrough different
Bee swarms, rival stands opening, going viral on social media, a TV news crew showing up, a dog drinking your entire lemonade supply, Chick-fil-A opening next door — every event connects to a real business concept and forces a decision with trade-offs.

### Three difficulty levels grow with your students
| Mode | Days | Features | Best For |
|------|------|----------|----------|
| **Easy** | 7 | No overhead, stable prices | First exposure, younger students |
| **Standard** | 14 | $1/day overhead, reputation system, full events | Core BCIT unit |
| **Hard (MBA)** | 21 | Startup loans, spoilage, price volatility, full chaos | Advanced students, extra credit |

---

## Business Concepts Covered

The game teaches **21 named business concepts**, one per day, with a rotating library so longer playthroughs cover more ground:

- Revenue, Cost & Profit
- Supply & Demand / Law of Demand
- Price Elasticity of Demand
- Inventory Management & Waste
- Break-Even Analysis
- Overhead & Fixed Costs
- Variable Costs
- Marketing ROI (Return on Investment)
- Opportunity Cost
- Reputation Capital & Brand Trust
- Competition Strategy & Differentiation
- Loans, Interest & Capital
- Supply Chain Risk Management
- Ethical Decision Making in Business
- Risk vs. Reward & Expected Value
- Capital Investment & ROI
- Customer Lifetime Value
- Market Positioning
- Cash Flow Management
- Economies of Scale
- Business Strategy & Adaptation

---

## Game Features At a Glance

| Feature | Details |
|---------|---------|
| 🎨 **B&W Illustrations** | 20+ hand-drawn SVG scenes that change with weather and events |
| 🔊 **Sound Effects** | Thunder, rain, wind, cash register, sad trombone, crowd cheer, bee buzz, fanfare — all synthesized in-browser, no audio files |
| 📈 **Profit History Chart** | Bar chart of every day's profit/loss appears after Day 2 |
| 🧠 **Quiz System** | One question per day, must answer to advance, full explanation shown after answering |
| 🏆 **Class Leaderboard** | Stores top 20 scores per browser, filterable by class period |
| 📄 **Printable Worksheet** | 12-question reflection worksheet auto-fills with student's actual game data and prints clean |
| 🎓 **Final Grade** | A+ through F based on net profit, with Zesty the lemon mascot delivering the verdict |
| 💬 **Ask Claude** | Button at game end that pre-writes a detailed prompt to Claude.ai for deeper concept exploration |

---

## How to Deploy Updates

This entire game lives in **one file: `index.html`**. To update anything:

1. Request a change (new event, bigger font, different text, new concept, bug fix)
2. Receive the updated `index.html`
3. Go to your GitHub repository
4. Click `index.html` → click the pencil icon (Edit) → paste the new content → click **Commit changes**
5. Your live link updates in about 60 seconds

That's it. No build process, no dependencies, no terminal commands needed.

---

## Hosting Setup (First Time)

### GitHub Pages
1. Create a free account at [github.com](https://github.com)
2. Click **New repository** → name it `lemonade-stand-pro` → set to **Public**
3. Upload `index.html` and `README.md`
4. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
5. Your game is live at: `https://YOUR-USERNAME.github.io/lemonade-stand-pro`

### Netlify (recommended if Chromebooks block GitHub Pages)
1. Create a free account at [netlify.com](https://netlify.com)
2. Drag and drop the `index.html` file onto the Netlify dashboard
3. Your game is live instantly at a URL like `https://lemonade-stand-pro.netlify.app`
4. To update: drag and drop the new file onto the same site in Netlify

---

## Sharing With Students

Once hosted, share the link via:
- **Google Classroom** — post as a link in the assignment
- **Email** — one clean URL, no attachment problems
- **QR Code** — generate at [qr.io](https://qr.io) or any QR generator, print and post in class
- **Classroom projector** — display the URL and have students type it in

Students need no account, no download, and no installation. They open the link, enter their name and class period, and play.

---

## The Leaderboard

The leaderboard stores scores in the browser's **local storage** — meaning:
- Scores from the same computer accumulate over time ✅
- Scores from different computers or devices do not sync ❌

For a cross-class leaderboard, use the **printed reflection worksheet** (auto-generated at game end) to collect student results and post a manual leaderboard on the board.

A "Teacher Reset" button in the leaderboard screen clears all scores from that machine.

---

## The Reflection Worksheet

At the end of every game, students can print a 12-question reflection worksheet that automatically fills in:
- Their name, class, stand name, difficulty, net profit, and final grade
- Spaces for written answers to 12 business concept questions including:
  - Break-even calculation using their actual numbers
  - Marketing ROI calculation from a real advertising day they played
  - Law of Demand proof with their actual price/customer data
  - Three real-world business applications of concepts they practiced
  - Their single most important learning from the simulation

This bridges the simulation to written assessment without any extra prep work.

---

## Credits

**Game design & business curriculum:** BCIT Teacher, Langhorne PA  
**Development:** Built with Claude AI (Anthropic)  
**Sound engine:** Web Audio API — no external files  
**Graphics:** Inline SVG — no external images  
**Dependencies:** Zero. One file. That's it.

---

## Future Updates Planned

- [ ] Student-chosen game name (class vote in progress!)
- [ ] Additional events suggested by students
- [ ] Week-by-week performance breakdown on final screen
- [ ] Option to export results as CSV for gradebook

---

*"The best way to learn business is to run one — even a pretend one with catastrophic bee swarms."*  
— Zesty 🍋
