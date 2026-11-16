# Resta con fichas

Bilingual (ES/EN) practice for two-digit subtraction with a place value chart, based on Eureka Math Grade 2, Module 4, Lesson 13.
Mateo taps a ten to change it for 10 ones when needed, crosses out ones and tens, and writes the answer in the vertical subtraction.

Served at https://jonomf.github.io/resta-fichas/ and listed in the hub (`jonomf/teo-hub`, id `resta-fichas`).
Plain static files, no build step. Follows the "Mateo Learning Games" `hub-conventions.md`.

## Storage
- `rf_state`: language, stars, which homework problems are solved
- `rf_streak`: days-in-a-row counter
- `hub:app:resta-fichas`: progress summary for the hub tile
- Reads `hub:theme` for the theme (dark by default)
