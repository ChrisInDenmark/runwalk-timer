# Run Trainer v0.9 Friend Test

Friend-test build based on v0.8.

Changes:
- Default workout renamed from "Return to Running" to "Easy Start".
- Halfway announcement is enabled by default on fresh installs.
- Goal Reached announcement is enabled by default on fresh installs.
- Existing user choices are preserved if they previously turned either announcement off.
- All other v0.8 behavior and layout remains unchanged.

Default workout progression:
1. Easy Start — Walk / Run
2. Steady Run — Continuous
3. Speed Session — Jog / Sprint

Storage:
- Workout/settings data: localStorage
- Saved activities: IndexedDB
