# Nutrivita Fit 🌿

**AI-Powered Corporate Wellness & Fitness Tracking Platform**

A modern, mobile-first health and wellness app designed for corporate teams to track fitness, wellness activities, and compete on leaderboards.

## ✨ Features

- **🏃 Activity Tracking** - AI auto-detects 18+ sport types
- **📊 Real-time Stats** - Heart rate, calories, distance, wellness scores
- **🧘 Wellness Dashboard** - Track meditation, sleep, nutrition, mental health
- **🤖 AI Coach** - Personalized wellness recommendations
- **🏆 Leaderboards** - Team challenges and competitions
- **📱 PWA Ready** - Install as app on any device
- **🔒 100% Offline** - Works without internet connection
- **⚡ No Backend** - All data stored locally in browser

## 🚀 Quick Start

### Option 1: Open in Browser
1. Download `nutrivita-fit.html`
2. Open in any modern web browser
3. Start tracking!

### Option 2: Install as App (Recommended)

**Android:**
1. Open in Chrome
2. Tap menu (⋮) → "Add to Home Screen"
3. App icon appears on home screen

**iPhone/iPad:**
1. Open in Safari
2. Tap share (↗️) → "Add to Home Screen"
3. App icon appears on home screen

## 📋 System Requirements

- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Mobile: iOS 12+ or Android 5+
- ~10MB storage for app
- No internet required after first load

## 🎮 How to Use

### Home Dashboard
- View daily activity rings (Move, Exercise, Stand)
- Check real-time metrics (heart rate, calories, distance, wellness score)
- See recent activities
- Weekly step chart

### Activity Tracking
- Select sport type or let AI auto-detect
- Click "Start Session" to begin
- Real-time duration, distance, heart rate display
- Click "Stop Session" when done

### Wellness Activities
- Log 9+ wellness activities:
  - Mindfulness: Meditation, Breathwork
  - Recovery: Sleep, Stretching
  - Nutrition: Hydration, Meals
  - Mental Health: Mood, Gratitude
- Earn wellness points for each activity
- Build daily streaks

### Team Leaderboard
- Register to join leaderboard
- Compete with colleagues
- 4 ranking categories: Overall, Fitness, Wellness, Department
- Monthly challenges

### AI Coach
- Ask NutriCoach anything
- Get personalized wellness tips
- Receive activity recommendations
- Training plans and nutrition advice

## 🛠️ Technical Stack

- **Frontend**: Vanilla HTML5, CSS3, JavaScript (no frameworks)
- **Icons**: Tabler Icons (CDN)
- **Fonts**: Google Fonts (Syne, DM Mono)
- **Storage**: Browser localStorage
- **PWA**: Service Worker for offline support
- **Size**: ~48KB (single HTML file)

## 📦 File Structure

```
nutrivita-fit/
├── nutrivita-fit.html      # Main app (all-in-one)
├── download.html           # Download portal
├── index.html              # Landing page
├── manifest.json           # PWA manifest
├── service-worker.js       # Offline support
├── package.json            # Project metadata
├── README.md               # Documentation
└── .gitignore             # Git configuration
```

## 💾 Data Privacy

✅ **Your data stays on your device**
- All data stored in browser localStorage
- No server uploads
- No account creation needed
- No tracking or analytics
- 100% private

## ⚙️ Customization

### Change Colors
Edit CSS variables in `nutrivita-fit.html`:
```css
:root {
  --g1: #1DB954;        /* Primary green */
  --bg: #0A0F0D;        /* Background */
  --text: #EEF5EE;      /* Text color */
}
```

### Modify Data
Edit JavaScript constants:
```javascript
const LB_DATA = { /* Leaderboard data */ };
const SNAMES = { /* Activity names */ };
const COACH_R = { /* AI Coach responses */ };
```

## 🐛 Troubleshooting

**App won't load?**
- Clear browser cache (Settings → Storage → Clear Cache)
- Try a different browser
- Check internet connection

**Data not saving?**
- Check if localStorage is enabled
- Not all browsers support localStorage in private mode

**App crashes?**
- Refresh the page
- Try on a different device
- Check browser console for errors

## 📱 Browser Compatibility

| Browser | Desktop | Mobile |
|---------|---------|--------|
| Chrome  | ✅      | ✅     |
| Firefox | ✅      | ✅     |
| Safari  | ✅      | ✅     |
| Edge    | ✅      | ✅     |
| Opera   | ✅      | ✅     |

## 🚀 Deployment

### Self-Hosted
1. Download `nutrivita-fit.html`
2. Upload to your web server
3. Users access via URL

### GitHub Pages
1. Repository is ready for GitHub Pages
2. Enable in Settings → Pages
3. Access via `https://HISMA1.github.io/nutrivitafit`

## 📄 License

MIT License - Free to use and modify

## 👥 Contributing

This is a corporate wellness project. For improvements:
1. Test thoroughly before deployment
2. Maintain data privacy
3. Keep app lightweight
4. Document changes

## 📞 Support

- **Issues?** Check browser console (F12)
- **Feature requests?** Customize the code
- **Questions?** Review the source code documentation

---

**Built with ❤️ for corporate wellness**

*Version 1.0 | Production Ready | Offline-First*
