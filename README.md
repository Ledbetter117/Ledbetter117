## Clinical workflow evaluation and software

**Galen Coulter-Ledbetter — RN, Paramedic**

I build reproducible tools for questions that arise in emergency-care workflows: how to measure errors in extracted availability, and how to check a roster against explicit rules. The projects connect nursing experience with Python, data validation, software testing and transparent evaluation.

### Published projects

**[ED Availability Intake Evaluation](https://github.com/Ledbetter117/ed-availability-intake-eval)** now includes a completed paired simulation: 12 fictional calendars rendered in three conditions and 36 actual local vision-model observations. Strict exact recovery was 4/12 typed, 3/12 handwriting-font and 3/12 degraded calendars. The package includes frozen inputs, raw response text, a reproducible scorer and a written report. The earlier 40-calendar benchmark is preserved separately. Fonts are not human handwriting; real-photograph and human-intent evaluation remain future studies.

**[ED Roster Gap Lab](https://github.com/Ledbetter117/ed-roster-gap-lab)** now includes a completed simulation with 10 explicit hypothetical rules, 24 fictional rosters, 336 scored shift units and two local-model comparisons. A deterministic detector agreed with a separately implemented software reference on all 336 constructed units. The model results exposed contrasting failure modes: Bolt missed 45 of 46 gaps; Flint produced 219 false alarms among its valid labels and 71 invalid labels. The report separates model performance from software checks and preserves the earlier human-study protocol as future work.

Each repository includes methods, runnable checks, a technical report and explicit limits. These are research and software artifacts, not validated clinical systems or evidence of safe staffing.

### Approach

Start with a concrete workflow question. Define what counts as an error, make the checks reproducible, and preserve both favorable and unfavorable results. A useful evaluation makes its evidence and its limits easy to inspect.

### Connect
[LinkedIn](https://www.linkedin.com/in/galen-coulter-ledbetter-964a2043)
