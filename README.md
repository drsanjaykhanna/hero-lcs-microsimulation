# hero-lcs-microsimulation

Individual-level microsimulation and cost-utility model for **HERO**: an early health economic evaluation of large language model (LLM) patient engagement in the NHS England Lung Cancer Screening Programme.

## About the study

The model asks whether an LLM that handles the booking contact for lung cancer screening is worth developing and testing in the NHS. It compares three strategies:

1. **Standard care**: current invitation and human telephone booking.
2. **AI + human fallback**: an LLM handles booking, with escalation to a person when needed.
3. **AI only**: an LLM handles booking without human fallback.

The analysis follows the NICE reference case (NHS and Personal Social Services perspective, lifetime horizon, 3.5% discounting) and includes:

- probabilistic sensitivity analysis and a fully incremental analysis of the three strategies;
- value of information analysis;
- distributional cost-effectiveness analysis by deprivation quintile;
- workforce, pathway and budget impact.

## Status

The manuscript is in preparation for submission. **The full model code, parameter files, saved outputs and reproduction scripts will be released in this repository at submission**, with an archived, citable version (DOI) for the paper's code availability statement.

## Planned contents

```
hero-lcs-microsimulation/
├── src/            model (population, natural history, screening, costs, QALYs)
├── config/         parameters and scenario definitions
├── scripts/        entry points
├── v3/tools/       one script per analysis, table and figure
├── new_analyses/   saved outputs, including every probabilistic draw
└── tests/          automated checks (python -m pytest tests -q)
```

## Citation

Please cite the paper once published. Citation details will be added here.

## Licence

MIT. See [LICENSE](LICENSE).

## Contact

Sanjay Khanna · [sanjaykhannamd.com](https://sanjaykhannamd.com)
