# AI Quest Support

AI Quest is a free, offline-first iPhone app for learning the vocabulary of artificial intelligence and AI-assisted coding through short 3–5 minute quests. This public repository contains support information. The app's source code is private.

## Get help

[Open a support request](https://github.com/weskcode/aiquest-support/issues/new/choose) or browse [existing requests](https://github.com/weskcode/aiquest-support/issues).

Include:

- Your AI Quest version (found in **Settings → About AI Quest**)
- Your iOS version and iPhone model
- What you expected, what happened, and the steps to reproduce the issue
- Screenshots (optional — please remove any personal or identifying information first)

GitHub issues are public and visible to everyone. Do not include personal contact details, private files, or exported progress files unless you are comfortable making them public.

To ask privately, email [weskcode@duck.com](mailto:weskcode@duck.com).

## Getting started

Complete the short welcome screens, choose a daily goal (**5**, **10**, or **15 minutes**), and optionally enable a daily reminder. AI Quest requires no account, no sign-in, and no internet connection.

- **Home**: Shows your streak, today's goal ring, your next recommended concept, and your learning paths.
- **Learn**: Browse all 7 learning paths and 63 concepts. Every concept includes a plain-language definition, why it matters, an analogy, an in-practice example, a common misconception, and related concepts.
- **Quests**: Tap **Start quest** or **Practice** to read the short card and answer 5 questions with immediate explanations on every answer.
- **Review**: Collects concepts due for spaced-repetition review (1, 3, 7, and 14 days out) as they move from **New** → **Learning** → **Familiar** → **Mastered**.
- **Progress**: Tracks your XP, level, current and longest streak, weekly activity, badges, and path completion.

## Reminders

Reminders are optional local notifications scheduled directly on your iPhone — AI Quest does not use a remote push server.

- Turn **Daily reminder** on or off and pick your preferred time in **Settings → Notifications**.
- When reviews are due tomorrow, AI Quest also schedules a single gentle refresher 30 minutes after your daily reminder time.
- If reminders aren't arriving, confirm that **Daily reminder** is enabled in AI Quest **Settings** and that notifications are allowed for AI Quest in **iOS Settings → Notifications → AI Quest**.

## Home Screen widget

Add the **AI Quest Progress** widget from the iOS widget gallery to see your streak, daily goal progress, and due reviews at a glance. Tapping the widget opens directly into AI Quest.

Widget snapshots update automatically as you complete quests or change settings. iOS controls widget refresh timing, so opening the app is the quickest way to refresh the widget if it appears stale.

## Backup, transfer, and resetting progress

AI Quest stores all progress locally on your iPhone and does not use iCloud sync or a cloud server.

- **Export Progress** (**Settings → Your data → Export Progress**): Saves a JSON backup (`AIQuestProgress.json`) to Files or any location you choose. Use this before deleting the app or switching iPhones.
- **Import Progress** (**Settings → Your data → Import Progress**): Restores a previously exported JSON file. You will be asked to confirm before your current progress is replaced.
- **Reset Progress** (**Settings → Your data → Reset Progress**): Clears your XP, streak, mastery, daily activity, and earned badges after confirmation. The built-in curriculum stays on your device.

Install app updates directly over your existing installation. Deleting the app removes local SwiftData storage from your iPhone, so export a backup first if you want to keep your progress.

## Accessibility and comfort

- Toggle **Haptics** in **Settings → Haptics**.
- AI Quest follows your system **Light / Dark Appearance**, **Dynamic Type** text sizes, **Reduce Motion**, and **VoiceOver** settings.
- There are no lives, energy limits, countdown timers, ads, or in-app purchases.

## Privacy

Read the [AI Quest Privacy Notice](https://github.com/weskcode/aiquest-privacy).
