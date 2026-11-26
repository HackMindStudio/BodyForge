# BodyForge — Module Responsibilities & System Connections

> Status: Planning documentation. The responsibilities below describe intended scope; they do not confirm implementation.

## 1. Core Systems

### 1.1 User Authentication & Account Management
**Responsibility:** Handle user authentication and account management.

### 1.2 User Profile & Preferences
**Responsibility:** Maintain the user's profile and preferences.

### 1.3 Fitness Engine
**Responsibility:** Provide the fitness functionality within BodyForge.

### 1.4 Forge AI — Multilingual AI Assistant
**Responsibility:** Provide multilingual AI assistance. Personalization is based on the user's goals, experience, selected martial arts, learning path and progress.

### 1.5 XP, Levels, Streaks & Achievements
**Responsibility:** Provide the gamified progression system through XP, levels, streaks and achievements.

## 2. Martial Arts Academy

**Responsibility:** Provide an academy supporting 350–400+ martial arts styles.

Its stated capabilities are:
- Learn All Martial Arts option
- Specific Martial Arts selection
- Custom Learning Path
- Martial Arts Search & Filtering
- Beginner, Intermediate and Advanced learning

## 3. Martial Arts Learning System

**Responsibility:** Organize learning content for each martial art.

Its stated learning areas are:
- Stance & Footwork
- Attacks & Defense
- Counters & Combinations
- Grappling & Ground Fighting
- Throws, Takedowns & Submissions
- Solo & Partner Drills
- Weekly & Monthly Plans
- Quizzes, Challenges & Progress Tracking
- Injury Prevention & Recovery

## 4. Physical Development

**Responsibility:** Provide optional physical training alongside Martial Arts.

Its stated areas are:
- Strength
- Explosive Power
- Speed
- Endurance
- Agility
- Balance
- Coordination
- Mobility & Flexibility
- Recovery

## 5. Visual Learning System

**Responsibility:** Explain techniques visually.

Its stated formats are:
- 2D Stickman Diagrams
- SVG Animations
- Frame-by-Frame Motion
- Slow Motion
- Front, Side and Angle Views

## 6. Forge AI Personalization

**Responsibility:** Understand the following context to provide personalized assistance:
- User goals
- User experience
- Selected martial arts
- Learning path
- User progress

## 7. Technology & Architecture

The project overview identifies:
- Next.js / React
- TypeScript
- Prisma
- Existing database architecture
- Secure authentication
- User Isolation
- Ownership Validation
- Scalable architecture

## 8. Stated System Connections

The following connections are directly supported by the project overview:

1. **User context → Forge AI:** Forge AI uses goals, experience, selected martial arts, learning path and progress for personalized assistance.
2. **Martial Arts Academy → Martial Arts Learning System:** Users explore or select martial arts, and each martial art has structured learning areas.
3. **Martial Arts Learning System → Visual Learning System:** Visual formats are intended to explain techniques.
4. **Martial Arts → Physical Development:** Physical training is described as optional and alongside Martial Arts.
5. **Learning → Progress Tracking:** Quizzes, challenges and progress tracking are included in the Martial Arts Learning System.
6. **Gamified progression:** XP, levels, streaks and achievements are listed as a Core System.

## 9. Relationship Boundaries Not Yet Specified

The project overview does not yet define:
- Detailed data flow between every module
- Exact database entities, tables or relationships
- API contracts between modules
- Internal service boundaries
- Which module owns each progress record
- Exact implementation sequence

These details are intentionally left unspecified rather than guessed.

---

**Scope rule:** This document only organizes the responsibilities and connections stated in the supplied BodyForge overview. It does not add features, technical choices or implementation claims.
