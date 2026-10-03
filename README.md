# Comprehensive Date Decrement & Subtraction Suite (C++) 🗓️⏳

A modular and clean C++ algorithmic engine engineered to handle reverse calendar arithmetic across every temporal magnitude (days, weeks, months, years, decades, centuries, and millennia).

---

## 🌟 Implemented Utilities (Problems 33 to 46)
- **Granular Days & Weeks Subtraction:** Atomic decrements via `DecreaseDateByOneDay`, `DecreaseDateByXDays`, `DecreaseDateByOneWeek`, and `DecreaseDateByXWeeks`.
- **Month Boundaries & Negative Overflow:** Dynamically adjusts year bounds when wrapping past January (`Month 1 -> Month 12`, `Year--`) and intelligently clamps invalid day offsets (e.g., subtracting a month from March 31 clamps to February 28/29).
- **Macro Decrements (Years, Decades, Centuries, Millennia):** Implemented both iterative approaches and direct $O(1)$ scalar subtraction (`Faster` variants) to avoid processing overhead.

---

## 💻 Sample Terminal Output
```text
Please enter a Day? 1
Please enter a Month? 1
Please enter a Year? 2026

Date After: 

01-Subtracting one day is: 31/12/2025
02-Subtracting 10 days is: 21/12/2025
03-Subtracting one week is: 14/12/2025
04-Subtracting 10 weeks is: 5/10/2025
...
13-Subtracting One Century is: 5/5/1705
14-Subtracting One Millennium is: 5/5/705
