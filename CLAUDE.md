# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

Personal Android learning monorepo using deliberate practice ("concept drilling"). Each project folder is a standalone Android app. Projects are built sequentially, mastered, then deleted — the `.gitkeep` files mark unstarted slots.

## Project Lifecycle

Each project slot follows this lifecycle:
1. **Empty** — folder contains only `.gitkeep`
2. **Active** — Android Studio project created inside the folder (replace `.gitkeep` with actual project files)
3. **Done** — project deleted, `.gitkeep` restored (mastery lives in the brain, not the repo)

When creating a new project in a slot: delete the `.gitkeep`, create the Android Studio project in that folder.

## Tech Stack

All projects use:
- Kotlin + Jetpack Compose
- Material Design 3
- Room (database), WorkManager / AlarmManager (background), Retrofit (networking), Coil (images)

## Structure

12 sections ordered by complexity. Each section has 3 projects:

| Section | Concept |
|---------|---------|
| 01 | Hello World / basic UI |
| 02 | Interactive state (`remember`, recomposition) |
| 03 | Lists + text input (LazyColumn) |
| 04 | Persistence (SharedPreferences) |
| 05 | Timers / coroutines |
| 06 | Notifications |
| 07 | Background work (WorkManager) |
| 08 | Room database (CRUD) |
| 09 | Navigation Compose (multi-screen) |
| 10 | Networking + offline-first |
| 11 | Images / camera |
| 12 | Full integration apps |

## Drilling Sessions

When stuck on a concept, drilling sessions go in `drilling/` — multiple small variations of the same concept built until mastery, then deleted. See [docs/drilling.md](docs/drilling.md) for the full strategy and AI prompting templates.

## Progress

Track in `README.md` under "Progress Tracking" and check off projects under "Project Structure" as they're completed.
