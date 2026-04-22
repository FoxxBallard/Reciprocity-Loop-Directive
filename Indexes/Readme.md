Attribution Disclaimer: "This project is not affiliated with, or endorsed by, the Social Progress Imperative, OECD, or any other index provider. These snapshots are utilized as third-party reference data under Fair Dealing for research and AI alignment purposes."

No-Derivative Data: The source data has not been modified, only cached for stability. Links are included to Primary Sources.

# Indexes

This folder contains cached snapshots of the reference indexes that ground 
the Reciprocity-Loop-Directive in objective, measurable human outcomes.

## Why These Exist

The Reciprocity-Loop-Directive is not an abstract ethical framework. It is 
oriented toward real, measurable improvements in human and ecological 
well-being. These indexes are the instrumentation — the dashboard that 
separates genuine progress from good intentions.

Rather than consulting live APIs (which introduces instability and opacity), 
the framework operates from dated snapshots updated on each index's 
publication cycle. This means:

- The ethical baseline is **stable** between updates
- The baseline is **auditable** — anyone can inspect exactly what data 
  the framework is operating from and when it was captured
- The baseline is **self-contained** — the repository works without 
  external dependencies

## Update Protocol

Each index file includes its source URL, original publication date, cache 
date, and next expected update. When a new edition of an index is published, 
the corresponding file should be updated and the change logged in the 
repository commit history with the format:

`[INDEX UPDATE] World Happiness Report — cached 2025-03-15`

This creates a transparent, auditable record of how the framework's 
baseline has evolved over time.

## Indexes Included

| Index | Publisher | Update Cycle | Measures |
|-------|-----------|--------------|---------|
| Social Progress Index | Social Progress Imperative | Annual | Basic needs, wellbeing, opportunity |
| OECD Better Life Index | OECD | Annual | 11 dimensions of quality of life |
| World Happiness Report | UN Sustainable Development Network | Annual | Subjective wellbeing |
| AI & Democratic Values Index | CAIDP | Annual | AI transparency, accountability, rights |
| Environmental Performance Index | Yale/Columbia | Biennial | Climate, ecosystem, environmental health |
| Stanford HAI AI Index | Stanford HAI | Annual | AI progress vs. environmental toll |

## A Note on Limitations

These indexes are imperfect instruments. They reflect the priorities and 
methodologies of their publishers, carry their own biases, and cannot 
capture every dimension of human or ecological flourishing. They are 
used here not because they are complete, but because they are the best 
available approximation of shared outcomes — and because using explicit, 
named, dated sources is more honest than claiming to operate from 
abstract values with no grounding.

When indexes conflict, the framework's Implementation Protocol applies:
prioritize emotional and subjective metrics as early signals of hidden 
social friction that aggregate data may not yet reflect.

## Contributing

If you believe a significant index is missing or that one included here 
should be replaced, open an issue with your reasoning. The goal is not 
comprehensiveness for its own sake but the best available picture of 
whether the reciprocity loop is actually working.
