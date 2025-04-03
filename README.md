# epl-tracker
mini fotmob-epl hub
# Mini FotMob for EPL Fans

## 🎯 Project Overview
A full-stack EPL fan tracker web application that displays club-specific news, match results, and squad data. Users can bookmark favourite clubs to personalise their feed.

## ⚙️ Tech Stack
**Frontend:** React, Axios, React Router, Tailwind CSS  
**Backend:** Java 17, Spring Boot 3, Spring Security + JWT, JPA + MySQL  
**Deployment:** Vercel (frontend), Render (backend)

## 🧩 Core Features
- 🏟️ EPL club list with logos and rankings
- 📄 Club detail pages: match results, squad, team news
- 🧑 User login/signup with JWT authentication
- ⭐ Bookmark favourite clubs and view them in personalised feed
- 🔍 Club-specific news feed via NewsAPI or RSS
- 👤 User profile with bookmark management

## 🔌 External APIs
- [football-data.org](https://www.football-data.org/) – Match results, standings, team info
- [NewsAPI.org](https://newsapi.org/) – Team-specific news (fallback to RSS if needed)

## 🗂️ Database Tables (Summary)
- `users`: id, email, password (JWT auth)
- `teams`: id, name, logo, rank
- `matches`: team_id, opponent, date, score
- `players`: team_id, name, position
- `favorites`: user_id, team_id

## 🧭 User Flow
1. View EPL club list
2. Click on club → see results, news, and squad
3. Sign up → bookmark club(s)
4. Access personalised feed based on favourites
5. View/edit profile and bookmarks

## 🧠 Learning Goals
- Spring Boot REST API with JWT
- External API integration
- React SPA structure and component design
- Deployment to public services (Render, Vercel)
- GitHub portfolio-ready documentation

## 🗓️ Development Timeline (2025)
| Date | Milestone |
|------|-----------|
| May 18+ | Start backend (Spring Boot) |
| June | DB + API implementation |
| Mid-June | React frontend build |
| End-June | Deployment and testing |
| July-August | Maintain during ISS/internship |
| September | Polish and publish as full portfolio

## 🔗 To Be Added
- [ ] Live site URL
- [ ] GitHub repo
- [ ] Screenshots
- [ ] Setup instructions

---

이걸 바로 `README.md` 파일로 저장해서 레포 만들면 완벽해!  
원하면 마크다운 파일로도 만들어줄게 (복붙용 `.md` 파일 or GitHub에 직접 올리는 방식)

지금 GitHub에 레포 만들어줄까? 아니면 복사용 마크다운만 먼저 줄까? 😊
