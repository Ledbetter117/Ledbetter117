## Building LLM Evals for Emergency Care

**ED RN, Level 2 trauma center · Paramedic · TCCC instructor (DHA Tier 3) · daily clinical AI operator**

Clinical AI deployment hangs on one question: when the model gets it wrong, how wrong, and who gets hurt? The work on this page builds the evals that answer it.

### 🔍 On the bench now
**[ed-availability-intake-eval](https://github.com/Ledbetter117/ed-availability-intake-eval)** — can a vision LLM safely read the messy, hand-marked availability calendars ED staff turn in?
- 100% synthetic calendars with perfect ground truth. PHI can't exist here by design.
- 4 difficulty slices, from clean scans to pen-on-paper handwriting.
- Headline metric: the `UNAVAILABLE → available` flip. One wrong cell schedules a nurse who was never coming in.

### 🩺 Why a nurse writes evals
Clinical AI fails in ways you only recognize after enough night shifts. The value is translation: "the model misread a cell" becomes "there is no night-shift RN on the 14th." Then building the harness that measures for it.

### ⚕️ Up next
Training-support AI for Tactical Combat Casualty Care / Prolonged Casualty Care. Public Joint Trauma System doctrine only.

### Connect
[LinkedIn](https://www.linkedin.com/in/galen-coulter-ledbetter-964a2043)
