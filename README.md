# Android Learning Journey

Personal repository for learning Android native development through deliberate practice. Following the "concept drilling" approach - building multiple variations of the same concept until mastery.

## Learning Philosophy

- **No tutorials** - learn by building
- **Repetition over variety** - drill concepts until boring
- **Depth-first** - master one thing before moving on
- **Delete when done** - practice code, not portfolio

## Project Structure

### 01 - Hello World Variations
- [x] hello-world - Display text, change to name
- [ ] current-date - Show current date/time
- [ ] random-number - Generate random number on open

### 02 - Interactive State
- [ ] counter - Increment/decrement buttons
- [ ] toggle - Switch between two messages
- [ ] color-picker - Buttons change background color

### 03 - Lists and Input
- [ ] name-list - Add names via text field, click to delete
- [ ] todo-list - Add tasks, mark complete, delete
- [ ] shopping-list - Items with quantity counter

### 04 - Persistent Data
- [ ] persistent-counter - Counter survives app restart (SharedPreferences)
- [ ] note-saver - Save/load single note
- [ ] username-remember - Store and display user's name

### 05 - Timers and Async
- [ ] count-up-timer - Seconds counting, Start/Stop/Reset
- [ ] countdown-timer - Set seconds, counts to zero
- [ ] stopwatch-laps - Multiple timestamps

### 06 - Notifications
- [ ] timer-notification - 10-sec timer, notification when done
- [ ] instant-notification - Button sends notification with custom text
- [ ] daily-reminder - Scheduled notification at specific time

### 07 - Background Work
- [ ] periodic-notification - Repeat every 15 min, persist across reboot
- [ ] background-counter - Increment counter every hour
- [ ] custom-reminder - Periodic with custom message/interval

### 08 - Database Apps
- [ ] notes-app - Add/delete/edit notes with Room
- [ ] contacts-app - Store name + phone, search by name
- [ ] expense-tracker - Amount + category + date, show total

### 09 - Navigation & Multi-screen
- [ ] recipe-viewer - List → detail → edit screens
- [ ] contact-manager - List → detail → add/edit, dialogs
- [ ] note-categories - Three-level hierarchy

### 10 - Networking & Offline-first
- [ ] weather-cache - Fetch API, store in Room, pull-to-refresh
- [ ] rss-reader - Parse XML, store articles, WebView
- [ ] vps-sync-test - POST/GET to Hetzner VPS endpoint

### 11 - Images & Media
- [ ] photo-gallery - Pick image, display with Coil, grid layout
- [ ] profile-card - Pick photo, add text, export as image
- [ ] camera-notes - Take photo, add note, thumbnails

### 12 - Full Integration
- [ ] interval-alarm - Complete app: AlarmManager, notifications, Room, boot persistence
- [ ] medication-reminder - Multiple alarms, different intervals
- [ ] water-reminder - Repeating notifications, track completion

## Progress Tracking

**Current:** Section 1, Project 2

**Completed Sections:** 0/12

**Total Projects:** 1/36

## Drilling Sessions

(Created when stuck on specific concepts - multiple variations to master)

See [docs/drilling.md](docs/drilling.md) for the full strategy.

## Key Learnings

- Section 01: `Column`/`Box` for layout, `Modifier` chain order matters, `@Preview` is independent from the running app, `fillMaxSize()` needed for centering to work
- Section 02: [learning note]

## Tech Stack

- Kotlin
- Jetpack Compose
- Room Database
- WorkManager / AlarmManager
- Retrofit
- Coil
- Material Design 3

## Notes

This is practice code, not production. Projects get deleted after mastery. The learning is in the brain, not the repo.
