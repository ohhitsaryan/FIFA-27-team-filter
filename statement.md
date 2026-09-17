# Project Statement: FIFA 27 Team Picker AR Filter

## Problem Statement
Traditional random selection tools or manual selection methods for casual football gaming matches lack engagement and immersive context. Players often struggle with unbiased, interactive ways to pick teams for matchups, leading to repetitive choices or tedious decision-making processes.

## Scope of the Project
This project is a real-time, browser-based Augmented Reality (AR) computer vision web application. It utilizes MediaPipe BlazeFace to track player faces through a live webcam feed and executes a weighted probability roulette algorithm to dynamically assign authentic football club crests directly above the users' heads.

## Target Users
* Casual and competitive gamers playing FIFA 27 matchday challenges.
* Content creators and streamers looking for interactive overlay tools for audience engagement.

## High-Level Features
* **Real-Time Multi-Face AR Tracking:** Detects 1 to 2 faces simultaneously and overlays high-tech UI brackets and team crests dynamically.
* **Weighted Probability Roulette:** Implements smooth `easeOutQuint` animation curves and weighted randomization across major football leagues and clubs.
* **Interactive Filtering System:** Swipeable league and nation filter chips allowing users to restrict randomization pools instantly.
* **Cross-Platform Accessibility:** Client-side execution running smoothly on desktop and mobile browsers via Vite and HTTPS (Vercel).