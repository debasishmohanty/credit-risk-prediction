# Final Notebook Audit — Applied Changes

- Notebook 01: retained as the data-understanding foundation; clarified that later direct model comparisons use the matched text cohort from Notebook 03.
- Notebook 02: documented the rationale for resolving the 15 reviewed variables to removal; removed stray Notebook 03 cells.
- Notebook 03: corrected the contradictory export description so it matches the actual persisted sparse matrices and targets.
- Notebook 04: changed the structured-model selection narrative to validation-only selection, with 2018 used only for final out-of-time evaluation.
- Notebook 05: broadened the objective to include TF-IDF and BERT; added an explicit validation-based hybrid comparison; persisted validation targets and deterministic SHAP matrix samples; expanded handoff artifact validation.
- Notebook 06: changed final hybrid selection to 2013-validation-only; moved the recalibration decision to validation; retained 2014 for final calibration reporting; added SHAP global explainability for the selected Structured + TF-IDF model; updated final handoff and reproducibility checks.

Important execution note:
Notebook 05 must be run through the new final persistence cells once before Notebook 06, because Notebook 06 now expects the new validation-comparison, validation-target, and SHAP-sample artifacts.
