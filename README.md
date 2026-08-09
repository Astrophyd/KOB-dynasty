# 🏀 KOB Dynasty

A browser-based street basketball management simulator where you build and lead your neighborhood crew through an epic tournament circuit.

## 🎮 Play Now

**[▶️ PLAY KOB DYNASTY](https://astrophyd.github.io/KOB-dynasty/)**

---

## 📖 How to Play

### Main Hub
From the main screen, navigate to:
- **Play Match** - Start the next game in the tournament circuit
- **The Squad** - Manage your roster and train players
- **Rookie Draft** - Scout and sign new players across 3 draft rounds
- **Circuit Map** - View your tournament schedule and opponents
- **The Block** - Upgrade court equipment for permanent bonuses
- **The Hustle** - Sign sponsors, place wagers, and drop viral mixtapes

### Match Simulator
During a match, you alternate between **Offense** and **Defense** for up to 10 possessions:

**Offense Plays:**
- 🤝 **Pass** (High safety, 2 pts, 75% success)
- 🏃‍♂️ **Drive & Layup** (Solid 2-pointer, 68% success)
- 🎯 **Contested 3** (High risk/reward, 3 pts, 38% success)
- ⚡ **Ankle Breaker** (Flashy 3-pointer, 45% success)

**Defense Plays:**
- 🔒 **Lockdown** (Clamp defense, stop offense)
- ⚡ **Try to Steal** (Aggressive, risk layup)
- 🥋 **Slick Foul** (Stop fast break)
- 🗣️ **Trash Talk** (Get in their head)

**Win conditions:**
- Win the match (higher score) to advance to next opponent
- Win all 4 opponents to complete the season and unlock harder seasons
- Build rep, cash, and an elite squad

### Squad Management
- Train starters to boost their shot % and defense rating
- Higher stat players → better offensive/defensive success rates
- Combine trained players with court upgrades for maximum synergy

### Rookie Draft
Three rounds of prospects:
- **1st Round (Elite):** High-tier players, $600-$750
- **2nd Round (Solid):** Mid-tier players, $380-$450
- **3rd Round (Value):** Development prospects, $170-$220

Draft strategically to fill roster gaps!

### Court Upgrades (The Block)
Invest in permanent court improvements:
- 🏀 **Leather Balls** (+5% shooting precision, $200)
- 🏋️ **Training Gear** (+5 defense rating, $300)
- 🏀 **Breakaway Rims** (+10% offense success, $400)
- 💡 **Floodlights & Neon** (+30 rep per win, $350)
- 🏗️ **Resurfaced Court** (+$200 cash bonus + injury prevention, $600)

Each upgrade can be purchased multiple times for cumulative bonuses!

### Revenue Streams (The Hustle)
**Sponsors:**
- Sign brand deals for passive income
- Higher rep requirement = higher payout

**Wagers:**
- Place bets on match outcomes
- Win-multiplier based (1.5x to 4.0x your stake)

**Mixtapes:**
- Drop viral highlight reels
- Instant cash and rep boost

## 🎯 Core Mechanics

### Difficulty Scaling
- Each season you complete increases opponent difficulty by **25%**
- Difficulty affects opponent stat bonuses and success rates
- Earn more cash/rep from harder opponents

### Player Stats
- **Shot Rating:** Affects offense play success rates
- **Defense Rating:** Affects defense play success rates
- Both are boosted by training and court upgrades

### State Persistence
Your entire Dynasty state saves automatically to browser localStorage:
- Dynasty name & avatar
- Cash and rep
- Win/loss record
- Squad roster
- Draft pool progress
- Court upgrades
- Match progress

Close and reopen anytime—your game picks up exactly where you left off!

## 🕹️ Controls

- **Touch/Click:** All buttons are touch-friendly
- **Tab switching:** Toggle between offense/defense plays during matches
- **Music toggle:** 🎵 button mutes/unmutes background music
- **SFX toggle:** 🔊 button controls sound effects

## 📱 Platform

- **Browser-based:** Works on desktop, tablet, and mobile
- **No installation:** Just open the HTML file in a modern browser
- **Offline-ready:** Download and play anywhere

## 🏆 Progression

1. **Start:** Build your Dynasty name and crew
2. **Season 1-N:** Win tournaments at increasing difficulty
3. **Seasons Won:** Track championships across multiple seasons
4. **Meta:** Unlock harder, more rewarding tournaments as you scale

## 🎨 Features

- **Dynamic Commentary Feed:** Live play-by-play analysis
- **Tactical Playbook:** 8 unique plays (4 offense, 4 defense)
- **Chance-Based Engine:** Outcomes influenced by stats, upgrades, and RNG
- **Sound Design:** Web Audio API for interactive SFX and music toggles
- **Ambient UI:** Glowing effects and smooth transitions

## 🛠️ Technical Stack

- **HTML5:** Semantic structure
- **Tailwind CSS:** Utility-first responsive design
- **Vanilla JavaScript:** No dependencies required
- **LocalStorage:** Save/load game state
- **Web Audio API:** Sound effects

## 📄 Credits

**Made by Astrophyd** 🏀

---

**Tip:** Save your Dynasty regularly by playing matches! Auto-save happens after every action. You can export your save data by opening browser DevTools and checking `localStorage.underdog_dynasty_save`.

Enjoy building your Dynasty! 👑
