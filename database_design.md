# Gamification Database Design

## Tables Needed

### WorkerXP

Stores worker XP progress.

Fields:

- workerId
- totalXp
- currentLevel
- lastUpdated

---

### BadgeEntity

Stores earned badges.

Fields:

- badgeId
- workerId
- badgeName
- unlockDate

---

### StreakEntity

Tracks daily streak.

Fields:

- workerId
- streakCount
- lastActiveDate

---

### EventLog

Stores trigger history.

Fields:

- eventId
- workerId
- eventType
- xpAwarded
- timestamp

## Benefits

- Offline persistence
- Easy sync
- Modular structure
- Analytics support
