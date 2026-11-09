---
title: Privacy Policy
permalink: /privacy/
---

# GymTrainer — Privacy Policy

_Last updated: 9 November 2026_

GymTrainer ("the app", "we") is a personal gym, nutrition, and body-tracking app for iPhone and Apple Watch. We designed it to be private by default: your data stays on your device unless you explicitly use a feature that needs to send it somewhere. This policy explains what data the app handles and why.

## Summary

- **No account, no login.** We do not ask for your name, email, or any identifier.
- **Your data is stored on your device** (via Apple's on-device database) and, if you choose, in your own Apple Health.
- **We do not run ads, analytics, tracking, or third-party marketing SDKs.**
- **The data that leaves your device** goes only to Google's Gemini API, using an API key that you provide: (a) a meal photo and/or text you submit for nutrition analysis, and (b) — only when you tap "Get advice" in the AI Coach — a summary of the selected period, including the specific foods you logged (with their calories/macros), the exercises, sets, and weights you performed, calories in/out, body weight, and your goal.

## Data stored on your device

The app stores the following locally so it can work offline: workouts and sets, programs, exercise library, body measurements and weight, your profile (height, weight, age, gender, activity level, weight goal, target weight), and your food log. This data is not transmitted to us — we have no servers and never receive it.

You can export a backup file (JSON) and import it yourself. Those files are created and stored wherever you choose (e.g., Files app, iCloud Drive). We do not access them.

## Apple Health (HealthKit)

If you grant permission, the app:

- **Reads** heart rate, active energy, sleep, and body mass to analyze your workouts, recovery, and daily energy.
- **Writes** your body-weight entries, completed workouts (with estimated calories), and logged nutrition to Apple Health.

Health data is used **only** to provide in-app features. It is **never** used for advertising, marketing, or data mining, and is never shared with us or any third party. You can revoke access anytime in the Health app.

## Nutrition photo analysis (Google Gemini)

The meal-logging feature is optional. When you use it, the meal **photo and/or text description you provide** is sent over an encrypted (HTTPS) connection to Google's Gemini API to estimate calories and macros. 

- This request is made using **a Google Gemini API key that you obtain and enter yourself.** Your use of Google's API is governed by Google's terms and privacy policy.
- We do not store these photos or results on any server; the estimate is returned to your device and saved locally in your food log.
- Your API key is stored securely in the device Keychain and is never transmitted to us.

## AI Coach (Google Gemini)

The AI Coach is optional and manual. When you tap "Get advice", the app sends a **text summary of the
selected day/week/month** — the specific foods you logged (with calories/macros), the exercises, sets, and
weights you performed, calories in/out, body weight, and your goal — to Google's Gemini API using
**your own API key**, and shows the returned suggestions.
We store the generated text locally; we do not send it to any server of ours. No photos are sent by the Coach.

If you never use meal logging or the AI Coach, no data leaves your device.

## Notifications

The app schedules **local** notifications on your device (rest-timer alerts and an optional daily weigh-in reminder). These are generated on-device and are not sent through any server.

## Children

The app is not directed at children and does not knowingly collect data from anyone.

## Changes

We may update this policy; the "last updated" date will change accordingly.

## Contact

Questions about this policy: **mirzaumt@gmail.com**
