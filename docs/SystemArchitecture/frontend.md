---
icon: octicons/device-mobile-24
# hide:
#    - toc
---
# Frontend: UI/UX and Features

## Overview

The OuSpark frontend is a cross-platform mobile and desktop application built using **Flutter and Dart**, designed to provide a rich and seamless user experience.

## Design Philosophy

- **Uniform Experience**: Consistent UI and UX across Android, macOS, and Windows
- **Performance**: Near-native performance with smooth animations
- **Responsiveness**: Adaptable to different screen sizes and device types

## UI/UX Design Process

- Created wireframes and prototypes using **Figma**
- Incorporated engaging animations using **Lottie** and **Rive**
- Developed reusable widgets for charts: Bar Chart, Pie Chart, Gauge, Line Chart
- Ensured color schemes and branding were consistent with the project identity

![figma ui](../assets/images/figma_ui.svg)

---

## Core Features 
### for Students

- **Personalized Dashboard** showing student profile and semester-wise results
- **Notification Banners** for timely updates
- **Tools Section** including SGPA & CGPA calculators, and search results
- **Advanced Analytics** such as college, department, and student rankings
- **Demographics Analytics** with gender ratio insights

### for Faculty and Administrators

- Access to detailed analytics for departments and batches
- Comparative performance dashboards across colleges and semesters
- Notification system for important announcements
- Resource links and strategic planning tools

## Technical Details

| **Feature** | **Implementation Details** |
|---------|------------------------|
| **Network Calls** | Supabase SDK and custom HTTP clients |
| **Animations** | Integrated with Rive and Lottie JSON animations |



!!!success "*This architecture supports rapid feature development and a maintainable codebase across multiple platforms*"
