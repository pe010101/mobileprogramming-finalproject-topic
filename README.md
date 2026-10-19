# SoundShades

An app where you draw pixel art about how a song makes you feel, and share it with others.

## Project Description
SoundShades is a mobile application where users can listen to a song, draw a pixel-art representation of how that song feels to them, and publish it to a public feed. Other users can browse the artwork, see what song inspired it, and interact with the posts.

## Technologies
- **Framework:** React Native with Expo (TypeScript)
- **Database & Authentication:** Firebase (Auth and Realtime Database)
- **Navigation:** React Navigation
- **Networking:** Axios
- **Device / Expo APIs:** Expo Haptics (vibration on touch), Expo Notifications, AsyncStorage (offline drafts)
- **UI Components:** React Native Paper

## Main Features
- **User Authentication:** Secure register and login using Firebase Auth.
- **Drawing Canvas:** A touch-based pixel grid where users can draw using a selected color palette.
- **Song Integration:** Users select a song (title/artist) to listen to while drawing, which is then attached to the artwork.
- **Pinterest-Style Feed:** A masonry grid displaying pixel art created by all users, showing the art, song title, and author.
- **Social Interactions:** Like and comment on other users' posts.
- **Profile Page:** A personal gallery showing the user's own published artwork.
- **Offline Drafts:** Ability to save unfinished artwork locally using AsyncStorage and publish it later.

## Mockups

1. **Home Feed:** A 2-column layout showing cards of pixel art with song titles.
2. **Drawing Screen:** A large pixel grid in the center, a color palette at the bottom, the currently playing song title at the top, and a "Publish" button.
3. **Post Details:** A large view of the artwork, the song details, and a comments section.

## Grade Aspiration: 5
This project targets Grade 5 by fulfilling all course requirements
