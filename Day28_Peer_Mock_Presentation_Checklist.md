# Day 28 — Peer Mock Presentation Checklist

Use this during the individual presentation to other interns. Do not mark items complete until performed.

## Suggested 7-minute run
1. Problem, objective and scope — 45 sec
2. Dataset and synthetic timestamp caveat — 60 sec
3. Methodology and chronological split — 75 sec
4. Results versus constant-mean baseline — 75 sec
5. Reproducible software demo — 90 sec
6. Limitations and failure conditions — 60 sec
7. Future scope and questions — 35 sec

## Questions to practise
- Why was Linear Regression selected over the constant-mean baseline?
- Why is the split chronological rather than random?
- What does “next-row pH” mean, and why is it not genuine future forecasting here?
- Why are dissolved oxygen and pressure not included?
- Why can anomaly precision/recall/F1 not be reported?
- How can another person reproduce inference from the repository?

## Rehearsal record
- Date/time:
- Presenter:
- Peer reviewers:
- Actual duration:
- Questions asked:
- Points that were unclear:
- Technical corrections:
- Actions completed:

## Final verification checklist
- [ ] GitHub repository opens without access errors.
- [ ] README setup and inference commands are followed from a clean environment.
- [ ] Required Python packages install from requirements.
- [ ] Model file and input CSV are present and referenced by the scripts.
- [ ] Example input produces an output with the documented schema.
- [ ] Report metrics match the evaluation CSV and notebook.
- [ ] Synthetic timestamp caveat is visible in report and slides.
- [ ] No unverified peer feedback or mentor approval is claimed.
