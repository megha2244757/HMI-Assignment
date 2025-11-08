# HMI Widget Assignment - Mobile App Widgets

A Human-Machine Interface (HMI) assignment project showcasing mobile app widgets with interactive usability testing and feedback collection.

## 📱 Project Overview

This project demonstrates 4 mobile app widgets designed with platform-specific design principles:

### Spotify Widgets (Android Material UI)
1. **Music Player Controls** - Full playback controls with album art, song info, and progress bar
2. **Now Playing Summary** - Compact widget showing currently playing track

### Apple Weather Widgets (iOS Flat Design)
1. **Current Weather Card** - Temperature, condition, and weather icon display
2. **3-Day Forecast Card** - Weather predictions for the next three days

## 🛠 Technologies Used

- **Frontend Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS with shadcn/ui components
- **Icons**: Lucide React
- **Routing**: Wouter
- **State Management**: React Hooks
- **Form Handling**: React Hook Form with Zod validation
- **Build Tool**: Vite
- **Backend**: Express.js (Node.js)

## 🚀 Getting Started

### Prerequisites
- Node.js 20 or higher
- npm or yarn package manager

### Installation & Running

1. The project is already set up and configured in Replit
2. Click the **Run** button or execute:
   ```bash
   npm run dev
   ```
3. The application will start on port 5000
4. Access the live preview at the generated Replit URL

### Sharing the Project

The Replit deployment automatically generates a public URL that can be accessed from any browser:
- Share the URL with your lecturer or testers
- No installation required for viewers
- Works on desktop and mobile browsers

## 📦 Widget Descriptions

### 1. Spotify Music Player Controls
**Design Style**: Android Material UI
- **Features**:
  - Large album artwork (80x80px)
  - Song title and artist information
  - Play/Pause toggle button with icon animation
  - Previous and Next track buttons
  - Progress bar with time indicators
  - Spotify green accent color (#1DB954)
  - Elevated card with shadow (Material Design elevation)

### 2. Spotify Now Playing Summary
**Design Style**: Android Material UI
- **Features**:
  - Prominent album artwork (120x120px)
  - "NOW PLAYING" label
  - Song and artist details
  - Playing indicator icon
  - Compact horizontal layout
  - Spotify green accent

### 3. Apple Weather Current Card
**Design Style**: iOS Flat Design
- **Features**:
  - Large temperature display (72° font size)
  - Weather condition icon (96x96px)
  - Location name
  - High/Low temperature indicators
  - iOS blue accent color (#007AFF)
  - Minimal shadows and flat appearance
  - Clean, centered layout

### 4. Apple Weather Forecast Card
**Design Style**: iOS Flat Design
- **Features**:
  - 3-column grid layout
  - Day abbreviations (Mon, Tue, Wed)
  - Weather icons per day (48x48px)
  - High and low temperatures
  - Vertical dividers between days
  - iOS blue accent color
  - Flat design with subtle borders

## 🧪 Usability Testing & Feedback

### Interactive Feedback System
The project includes a built-in feedback collection system where testers can:
- Select which widget to review
- Provide a 1-5 star rating
- Write detailed comments about:
  - Ease of use
  - Visual clarity
  - Design appeal
  - User experience

### Sample Feedback Summary

**Spotify Music Player Controls** (Avg: 5/5 stars)
- ✅ Intuitive control layout
- ✅ Responsive interactions
- ✅ Clear visual hierarchy
- ✅ Smooth animations

**Spotify Now Playing Summary** (Avg: 5/5 stars)
- ✅ Perfect at-a-glance information
- ✅ Prominent album artwork
- ✅ Minimal and clean design

**Apple Weather Current** (Avg: 4/5 stars)
- ✅ Clear temperature display
- ✅ Recognizable weather icons
- ✅ Clean iOS-style design
- 💡 Could add more detailed info (humidity, wind)

**Apple Weather Forecast** (Avg: 4/5 stars)
- ✅ Well-organized 3-day layout
- ✅ Easy to scan information
- ✅ Clear iconography
- ✅ Proper use of iOS design principles

## 🎨 Design Principles Applied

### Android Material UI (Spotify)
- Elevation and shadows for depth
- Rounded corners (border-radius: 8-12px)
- Material Design color system
- Touch target sizes (44x44px minimum)
- Responsive hover states

### iOS Flat Design (Weather)
- Minimal shadows and borders
- Clean typography hierarchy
- Flat, simple iconography
- Precise spacing and alignment
- iOS system colors

## 📂 Project Structure

```
├── client/
│   ├── src/
│   │   ├── components/
│   │   │   ├── SpotifyMusicPlayer.tsx
│   │   │   ├── SpotifyNowPlaying.tsx
│   │   │   ├── WeatherCurrent.tsx
│   │   │   ├── WeatherForecast.tsx
│   │   │   ├── FeedbackForm.tsx
│   │   │   └── FeedbackList.tsx
│   │   ├── pages/
│   │   │   └── Home.tsx
│   │   └── App.tsx
├── server/
│   └── routes.ts
└── shared/
    └── schema.ts
```

## ✅ Assignment Requirements Checklist

- [x] 2 mobile apps selected (Spotify - Android, Apple Weather - iOS)
- [x] 2 widgets per app (4 total widgets)
- [x] Android Material UI design for Spotify
- [x] iOS flat design for Apple Weather
- [x] Built with React + Tailwind CSS
- [x] Mobile-first responsive layout
- [x] Public web link for sharing
- [x] Interactive usability testing section
- [x] Real-time feedback collection and display
- [x] Clean, modern, and minimal design
- [x] Comprehensive README.md documentation

## 🔗 Testing Instructions for Reviewers

1. Visit the shared Replit URL
2. Review each of the 4 widgets
3. Test interactive features:
   - Click Play/Pause on Spotify player
   - Try Previous/Next buttons
   - Hover over interactive elements
4. Submit feedback using the form:
   - Enter your name
   - Select a widget from the dropdown
   - Rate it 1-5 stars
   - Write your feedback
   - Click "Submit Feedback"
5. View all submitted feedback below the form

## 📝 Conclusion

This HMI assignment successfully demonstrates:
- Platform-specific design implementation (Android Material UI vs iOS Flat Design)
- Interactive widget prototypes with realistic functionality
- User feedback collection system for usability testing
- Clean, maintainable code structure
- Responsive mobile-first design approach
- Professional documentation and presentation

The project showcases the importance of adhering to platform-specific design guidelines while creating intuitive and visually appealing user interfaces. The integrated feedback system allows for continuous improvement based on real user testing.

## 👨‍💻 Author

Created as an HMI assignment project demonstrating mobile widget design and usability testing principles.

---

**Note**: This is a prototype demonstration using mock data. For a production application, the widgets would connect to real APIs (Spotify API, Weather API) for live data.
