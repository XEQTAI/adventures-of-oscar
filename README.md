# Oscar - A Modern Social Feed Platform

**Live Site:** https://xeqtai.github.io/adventures-of-oscar/

## 🎯 Concept

Oscar is a modern, minimal social media feed where multiple cats (or any objects) can have their own community feed. Scan a QR code to add a cat to your collection and see all the sightings posted by the community.

### How It Works

1. **Scan a QR Code** - Each cat has a unique QR code
2. **Build Your Collection** - Scanning different QR codes adds them to your sidebar
3. **See the Feed** - Each cat shows all anonymous community posts
4. **Stay Private** - Posts are anonymous with fun feline avatars
5. **Share Moments** - Anyone can post a sighting with a photo

---

## ✨ Features

✅ **Modern Dark UI** - Sleek, minimal design inspired by current social platforms  
✅ **Anonymous Posts** - No usernames, just random feline emoji avatars  
✅ **Multiple Objects** - Add multiple cats to your collection via QR scanning  
✅ **Single Page Feed** - Minimal headers, just beautiful scrolling posts  
✅ **AI-Generated Images** - 5 stunning photos of white/grey spotted cats  
✅ **Smooth Interactions** - Hover effects, smooth scrolling, responsive design  
✅ **QR Code Modal** - Elegant modal for scanning or downloading QR codes  
✅ **Collection Management** - Left sidebar shows all discovered cats  
✅ **Real-time Stats** - Post count updates instantly  
✅ **Mobile Responsive** - Sidebar collapses on small screens  

---

## 🎨 Design Philosophy

**Modern UX Principles:**
- Minimal text, maximum visual
- Dark theme for modern aesthetic
- Smooth animations and transitions
- Clear visual hierarchy
- Micro-interactions on hover
- No clutter, no distraction
- Focus on content (posts and images)

**Color Palette:**
- Background: Deep black (#0f0f0f)
- Accents: Cyan (#00d4ff)
- Text: Clean white/grey
- Borders: Subtle dark grey

---

## 🐱 Feline Avatars

Posts use random feline emoji avatars:
- 🦁 Lion
- 🐯 Tiger
- 🐆 Leopard
- 🐱 Cat
- 🦅 Eagle (honorary)
- 🐅 Tiger (alternate)
- 🧏 Persona (honorary)
- 🤺 Fencer (honorary)
- 🐈 Black Cat

---

## 🎬 Screenshots (Conceptual)

### Main Feed View
```
┌─────────────────────────────────────────────┐
│ SIDEBAR      │  FEED                       │
│              │  Oscar (20 sightings)       │
│ 🦁 Oscar     │  ─────────────────────────  │
│ 🐯 Tiger     │  🐆 Spotted this beauty!    │
│ 🐆 Leo       │  [IMAGE: Cat lounging]      │
│              │  👁️ 42  💬 8  ❤️ 23        │
│ + Scan QR    │  ─────────────────────────  │
│              │  🦁 Oscar visited hours!    │
│              │  [IMAGE: Cat playing]       │
│              │  👁️ 56  💬 12  ❤️ 31       │
└─────────────────────────────────────────────┘
```

---

## 🔗 QR Code System

**How to Generate QR Codes:**

1. Open the app
2. Click "+ Scan QR" button
3. A modal appears with the current cat's QR code
4. Click "Download" to save as PNG
5. Print or share the QR code

**Each QR Code Links to:**
```
https://xeqtai.github.io/adventures-of-oscar/?cat=oscar-main
```

Scanning opens that specific cat's feed. If it's new, it adds to your collection!

---

## 📱 How to Use

### For Visitors
1. **Scan QR Code** with your phone camera
2. **Opens the app** with that cat's feed
3. **See all posts** about that cat
4. **Add more cats** by scanning different QR codes
5. **Post your own sighting** - Photos are pre-loaded in demo

### For Sharing
1. Print QR codes and attach to physical items
2. Share QR link on social media
3. Display in your window/yard
4. Anyone scanning builds their collection

---

## 💾 Data Storage

- **Browser LocalStorage** - All data stored locally
- **No Backend Required** - Completely client-side
- **Persists Forever** - Data survives page refreshes
- **Per-Device** - Each browser has its own collection

---

## 🎨 Initial Posts

The demo includes 5 beautiful AI-generated cat images:

1. **Garden Lounging** - Cozy white/grey cat relaxing
2. **Playtime** - Dynamic action shot with toys
3. **Window Watching** - Bird-gazing moment
4. **Armchair Comfort** - Sitting pose
5. **Playful Energy** - Running and jumping

Each post is attributed to an anonymous "Spotter" with a random feline avatar.

---

## 🚀 Technology Stack

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with CSS variables
- **Vanilla JavaScript** - No frameworks, pure functionality
- **QR Code Library** - QRCode.js for QR generation
- **GitHub Pages** - Free hosting
- **LocalStorage API** - Browser data persistence

---

## 📐 Responsive Design

**Desktop (>1024px):**
- 280px sidebar with labels
- Main feed takes up remaining space
- Optimal reading width

**Tablet (768px - 1024px):**
- 280px sidebar still visible
- Feed responsive
- Touch-friendly interaction zones

**Mobile (<768px):**
- Sidebar collapses to 70px (icons only)
- Full-width feed
- Optimized touch interactions

---

## 🎯 Use Cases

### For Pet Owners
- Track your visiting cat's journey
- Share sightings with the community
- Build a photo timeline

### For Communities
- Document local wildlife
- Build engagement around animals
- Create shared memories

### For Developers
- Clean code example
- Modern UI/UX patterns
- Collection-based social system

---

## 🔮 Future Enhancements

- User accounts (optional)
- Real-time sync across devices
- Image upload from device
- Comment threads
- Reactions/emojis
- Hashtag support
- Search functionality
- Map view of sightings
- Leaderboards
- Notifications

---

## 📝 Notes

- **Anonymous by Default** - Privacy-first design
- **No Moderation Needed** - Community can self-moderate
- **Lightweight** - Single HTML file, no dependencies except QR library
- **Fast** - Instant loading, smooth interactions
- **Accessible** - Semantic HTML, readable contrast

---

## 🏗️ Architecture

```
index.html (Single Page App)
├── UI Components
│   ├── Sidebar (Collections)
│   ├── Feed (Posts)
│   └── Modal (QR Code)
├── JavaScript
│   ├── Data Management (LocalStorage)
│   ├── UI Rendering
│   ├── QR Generation
│   └── Interactions
└── Styling
    ├── Dark Theme Variables
    ├── Responsive Grid
    └── Smooth Animations
```

---

**Made with ❤️ for Oscar and the community**

*Last updated: April 7, 2026*
