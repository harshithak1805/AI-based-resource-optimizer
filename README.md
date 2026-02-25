# AI-based-resource-optimizer
#Overview
SmartSchool AI is a single-file HTML application built for KV Dwarka Sec-8 (easily customizable to any CBSE school). It provides every student with a personalized academic dashboard that is generated uniquely per login — no two accounts ever see the same data.

The entire application lives in one file: smartschool_complete.html. There is no server, no database, no API key, and no build step required.

#Features
🔐 Authentication
Student Sign In and Register flows
Persistent sessions via localStorage
Each registered account retains all data across browser sessions
🎓 Per-Student Dynamic Dashboard
Every login generates a deterministic unique academic profile seeded from the student's email + class:

Unique subject marks (class-appropriate subjects)
Unique overall average, attendance %, class rank, awards count
Unique monthly performance trend (11 months)
Unique attendance heatmap pattern
## 📊 My Profile Tab
Hero banner with name, class, rank, admission number
5 animated quick-stat cards (Overall %, Attendance, Rank, Subjects, Awards) — all dynamic
Performance Trend line chart (per-user 11-month trajectory)
Skills Radar chart (derived from subject marks)
Subject performance bars with CBSE grade labels (A1/A2/B1/B2)
Recent activity timeline
## 📈 Academics Tab
Score history line chart
Grade distribution doughnut chart
Full subject results table with FA1/FA2/SA1/FA3/FA4 breakdown
## 📅 Timetable Tab
Full weekly CBSE period-wise schedule grid
## ✅ Attendance Tab
Present/Absent/Leave cards with dynamic counts matching user's attendance %
Annual attendance heatmap (green = present, red = absent)
Status badge: WITHIN LIMIT / BORDERLINE / CRITICAL
## 📈 Resource Dashboard Tab
School efficiency score ring
Classroom / Lab / Teacher workload cards
Resource Radar + Weekly Hours bar charts
Interactive sliders to recalculate efficiency score in real time
## 🤖 AI Student Analyser Tab
Auto-fills with the logged-in student's data on load
## 🎲 Random Student generator for demo/testing
Live subject marks bar preview with color coding (green ≥85, amber 75–84, red <75)
Fully offline AI analysis engine — no API key needed:
Exam Readiness Score (0–100) with animated ring gauge
Academic Summary (4 sentences, unique per student)
Top 2 Strengths with CBSE grade context
Top 2 Improvement Areas with score gaps
3 Personalized Recommendations (attendance-aware, rank-aware, subject-specific)
School-level recommendations (workload, labs, timetable, infrastructure)
## ⚙️ Settings Tab
Full student profile editor (personal info, academic details, guardian contacts)
Avatar upload with crop-to-fit
Auto-save with 1.5s debounce
App preferences (notifications, privacy, display, data)
