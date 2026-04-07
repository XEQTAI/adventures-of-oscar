# Oscar - The Mystery Cat Community

> A modern, sleek social platform for tracking Oscar's daily adventures through community sightings. Anonymous posts with beautiful feline avatars.

## ✨ Features

### Main Feed (index.html)
- **Modern Minimal Design** - Clean, professional interface inspired by contemporary social platforms
- **Anonymous Sightings** - No usernames, just pure community vibes
- **SVG Feline Avatars** - Each post gets a random beautiful avatar (Lion, Tiger, Leopard, Cheetah, Puma, Ocelot)
- **AI-Generated Images** - 5 stunning images of Oscar embedded in initial posts
- **One-Page Scrollable Feed** - Everything on one elegant, minimal page
- **Community Stats** - Real-time sighting counter
- **My Scanned Cats** - Track which cat profiles you've visited

### Individual Cat Profile (profile.html)
- **Social Media Profile** - Each cat gets their own beautiful profile page
- **Scan to Connect** - QR codes link directly to cat profiles
- **Add to Collection** - Build your list of scanned cats
- **Profile Stats** - Sightings, followers, posts at a glance
- **Recent Activity** - See what people have posted about this cat
- **Persistent Storage** - All data stored locally in browser

## 🎨 Design Highlights

### Typography & Layout
- Clean sans-serif fonts (Apple system fonts)
- Generous whitespace and minimal borders
- Three-column grid layout: sidebar, feed, stats
- Responsive design (adapts to tablets and mobile)

### Color Palette
- White backgrounds (#fff, #fafafa)
- Subtle grey tones for secondary text
- Vibrant gradient for avatars (#667eea to #764ba2)
- Light blue for interactive elements (#0a66c2)

### SVG Avatars
Each post gets a randomly assigned feline avatar:

- **Lion** 🦁 - Majestic with golden mane
- **Tiger** 🐯 - Bold orange with dark stripes
- **Leopard** 🐆 - Spotted golden beauty
- **Cheetah** 🐆 - Sleek with tear marks
- **Puma** 🐾 - Mountain cat elegance
- **Ocelot** 🐱 - Spotted wildcat charm

## 🚀 How It Works

### For Users

1. **Visit the Feed**
   - Go to `index.html`
   - See anonymous community sightings with beautiful avatars
   - Scroll through Oscar's adventures
   - View community stats on the right

2. **Scan a QR Code**
   - Point phone camera at any QR code (print them and put them on Oscar sighting locations)
   - Opens that cat's individual profile page (`profile.html?id=...`)
   - See stats, recent activity, and follow that cat
   - Add to your "My Scanned Cats" collection

3. **Build Your Collection**
   - Each QR code scan adds a cat to your list
   - See all your scanned cats in the right sidebar
   - Click to revisit any cat's profile

### For Deployment

**QR Code Setup**
- Each physical location where you place a QR code is essentially a "cat object"
- Print QR codes pointing to: `https://xeqtai.github.io/adventures-of-oscar/profile.html?id=location-name`
- Examples:
  - `?id=porch` - QR code on your porch
  - `?id=garden` - QR code in the garden
  - `?id=fence` - QR code on the fence

- Each gets a unique, consistent cat avatar based on the ID
- All share the same community feed data

## 📸 Images

All 5 AI-generated images of Oscar are embedded in the initial posts:

1. **Lounging** - Oscar in the garden (Lion avatar)
2. **Playing** - Oscar with toys (Tiger avatar)
3. **Window Watching** - Oscar looking at birds (Leopard avatar)
4. **Cozy Corner** - Oscar relaxed (Cheetah avatar)
5. **Action Shot** - Oscar running fast (Puma avatar)

## 💾 Data Storage

- All posts stored in browser's `localStorage`
- All scanned cats stored in `localStorage`
- Data persists between page visits
- Clear browser data to reset

## 📱 Responsive

- **Desktop**: Full 3-column layout
- **Tablet**: 2-column (feed + sidebar)
- **Mobile**: Single column feed

## 🔗 Files

- `index.html` - Main community feed
- `profile.html` - Individual cat social media profile
- `qr.html` - (Legacy) QR code generator page

## 🎯 Use Cases

1. **Print QR Codes** on items Oscar visits
2. **Place them strategically** (garden, porch, fence, etc)
3. **Community submits sightings** on main feed
4. **Visitors scan QR codes** to collect cats
5. **Build a network** of cat-tracking locations

## 🌐 Live

**Main Feed**: https://xeqtai.github.io/adventures-of-oscar/

**Cat Profiles**: https://xeqtai.github.io/adventures-of-oscar/profile.html?id=your-location-name

---

**Made with 💜 for Oscar and his mystery**