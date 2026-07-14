# 💓 HEART-TRACK

A beautiful, privacy-first health & fitness app designed to help you manage cholesterol, track meals, log workouts, and monitor lab results—all while keeping your data 100% on your device.

## ✨ Features

- **Meal Logging** – Log what you eat and get AI-graded feedback on your LDL impact
- **Smart Grading** – Meals scored A+ to C- based on saturated fat, fiber, omega-3s, and your cholesterol goals
- **Fitness Tracking** – Log workouts (runs, rides, strength, walks, swims) with distance, time, and calories
- **Lab Results** – Track bloodwork (LDL, HDL, triglycerides, A1c, glucose, BP) and get a personalized action plan
- **Weekly Trends** – Visualize your progress with daily grade trends
- **Themes** – Choose between Sunset (default), Midnight, or Emerald
- **Offline-First** – All data stored locally on your device; no server, no account needed

## 🚀 Quick Start

1. **Visit the app**: https://dakrollins.github.io/HEART-TRACK/
2. **Set up your profile** – Enter your age, weight, height, activity level, and cholesterol goals (takes 2 min)
3. **Log a meal** – Tap "Log a meal", pick from common foods or type your own
4. **Check your grade** – See how each meal impacts your LDL goal
5. **Track fitness** – Add workouts to build your weekly trend
6. **Review labs** – Enter bloodwork and get an action plan

## 🔒 Privacy

**Your data never leaves your device.** All information is stored in your browser's local storage. No cloud sync, no tracking, no servers. When you clear your browser data, HEART-TRACK data is cleared. You own it all.

## 🍎 How Grading Works

Meals are scored based on:
- **Saturated fat** – Primary driver of LDL
- **Fiber** – Soluble fiber directly lowers cholesterol
- **Omega-3s** – Anti-inflammatory; salmon & chia seeds are stars
- **Sodium** – Monitored for blood pressure
- **Added sugars** – Raises triglycerides

**A+/A grades** have high fiber + lean protein + minimal sat fat
**B/B+ grades** are balanced; could use tweaks
**C grades** are occasional treats; heavy on sat fat, fried, or sugary

## 🍽️ Food Database

50+ foods curated with real nutrition data:
- **Proteins**: chicken breast, salmon, turkey, eggs, beans, lentils
- **Grains**: brown rice, oats, whole wheat pasta, sweet potato
- **Produce**: broccoli, spinach, avocado, berries, tomatoes
- **Brands**: PB2, Siete chips, Greek yogurt, oat milk

Add your own custom foods with full macros and heart-health flags.

## 📊 What You Can Track

| What | Details |
|------|---------|
| **Meals** | Name, portion, macro breakdown, grade, photo (optional) |
| **Workouts** | Type, distance, time, calories, Strava screenshot (optional) |
| **Labs** | LDL, HDL, triglycerides, A1c, glucose, BP systolic/diastolic + photo |
| **Profile** | Age, weight, height, sex, activity level, LDL goal |
| **Trends** | 7-day rolling average of daily grades |

## 🎨 Themes

- **Sunset** – Warm coral + gold (default)
- **Midnight** – Pure black + white
- **Emerald** – Green + lime (calming)

## 💾 Data Export

To back up or migrate your data:
1. Open browser DevTools (F12)
2. Go to **Application > Local Storage > https://dakrollins.github.io/HEART-TRACK/**
3. Copy the `heartTrackData` value to a text file

## 🛠️ Tech Stack

- **HTML/CSS/JS** – Vanilla JS, no frameworks
- **Icons** – Emoji (universal, always available)
- **Storage** – Browser LocalStorage API
- **Deployment** – GitHub Pages

## 🌐 Use As a Template

Want to fork and customize? Click **Use this template** to create your own version:
- Change colors, themes, or food database
- Modify grading logic
- Add more metrics or goals

## 📝 Notes

- Meal grades are estimates based on macronutrients; always follow your doctor's advice
- Lab interpretations are informational, not medical diagnoses
- This is a tracking tool, not a replacement for medical care

## 📧 Questions?

Open an issue or reach out. Happy to help you track your way to better cholesterol! 🚀

---

**Made with ❤️ for heart health**
