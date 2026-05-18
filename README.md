# Grade Distribution Analyzer

A lightweight browser-based tool for analyzing student grade distributions from raw score data. Single HTML file, no backend setup required. 

## Usage

* Paste scores as comma-separated values or line-by-line input (copied from excel file)
* Define and edit custom grade cutoffs
* Interactive draggable grade boundary slider
* Multiple visualization modes:

  * Grade-wise distribution
  * Score histogram
  * Cumulative percentile plot
* Zoom and pan support in cumulative view
* Automatic grade statistics calculation
* Suggested cutoffs based on the largest score gaps
* GPA / grade point analysis

## Input Format

Accepted formats:

```text
95, 88, 76, 82, 91
```

or

```text
95
88
76
82
91
```

## Grade System

Default grading scheme included:

| Grade  | Points |
| ------ | ------ |
| A+ / A | 10     |
| A-     | 9.25   |
| B+     | 8.75   |
| B      | 8      |
| B-     | 7.25   |
| C+     | 6.75   |
| C      | 6      |
| C-     | 5.25   |
| D+     | 4.75   |
| D      | 4      |
| NC     | 0      |

All cutoffs are editable from the UI.
