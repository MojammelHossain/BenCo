## Introduction

This folder contains appendices of its associated paper, including experimental results and visualization.

### Additional Results

Additional identification of mention results
|  category | model | parameters | pre. | rec. | f1 |
|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|
|                |  c2f+Fasttext  |s=30, a=250, CL=2|    98.52      |     66.00      |     79.05      |
|   Biography    |  c2f+Fasttext  |s=20, a=50, CL=3|    97.54      |     65.67      |     78.50      |
|                |  c2f+Fasttext  |s=10, a=50, CL=3|    92.54      |     59.67      |     75.50      |
| | | | | | |
|                |  c2f+Fasttext  |s=30, a=250, CL=2|    74.20      |     49.92      |     59.69      |
|       Story    |  c2f+Fasttext  |s=20, a=50, CL=3|    75.16      |     49.49      |     59.68      |
|                |  c2f+Fasttext  |s=10, a=50, CL=3|    76.52      |     46.77      |     58.05      |
| | | | | | |
|                |  c2f+Fasttext  |s=30, a=250, CL=2|    79.00      |     41.36      |     54.29      |
|       Novel    |  c2f+Fasttext  |s=20, a=50, CL=3|    90.12      |     38.21      |     53.67      |
|                |  c2f+Fasttext  |s=10, a=50, CL=3|    83.75      |     35.07      |     49.44      |
| | | | | | |
|                |  c2f+Fasttext  |s=30, a=250, CL=2|    74.03      |      26.55     |      39.08     |
|  Descriptive   |  c2f+Fasttext  |s=20, a=50, CL=3|    70.00      |     19.31      |     30.27      |
|                |  c2f+Fasttext  |s=10, a=50, CL=3|    68.88      |     21.37      |     32.63      |
| | | | | | |

Some additional results on the Model's performance.
| Category | | Parameters | Pre. | Rec. | F1 | Pre. | Rec. | F1 | Pre. | Rec. | F1 | Pre. | Rec. | F1 |
|:--------|:--------|:--------|:--------|:--------|:--------|:--------|:--------|:--------|:--------|:--------|:--------|:--------|:--------|:--------|
| | c2f + Fasttext | s=30, a=250, CL=2 | 93.43 | 45.94 | 61.59 | 97.88 | 65.83 | 78.72 | 65.62 | 41.76 | 51.04 | 85.64 | 51.18 | 63.78|
| Biography| c2f + Fasttext | s=20, a=50, CL=3 | 91.63 | 45.20 | 60.54 | 96.84 | 65.48 | 78.13 | 65.87 | 41.92 | 51.23 | 84.78 | 50.87 | 63.30|
| | c2f + Fasttext | s=10, a=50, CL=3 | 90.98 | 47.81 | 62.68 | 96.92 | 67.25 | 79.41 | 77.44 | 42.24 | 54.66 | 88.54 | 52.44 | 65.58|
| | | | | | | | | | | | | | | |
| | c2f + Fasttext | s=30, a=250, CL=2 | 48.07 | 22.95 | 31.07 | 65.78 | 38.81 | 48.82 | 21.98 | 33.73 | 26.62 | 45.28 | 31.83 | 35.50|
| Story| c2f + Fasttext | s=20, a=50, CL=3 | 53.08 | 21.70 | 30.81 | 67.02 | 38.50 | 48.91 | 22.17 | 34.02 | 26.84 | 47.42 | 31.41 | 35.52|
| | c2f + Fasttext | s=10, a=50, CL=3 | 53.82 | 19.35 | 28.47 | 66.76 | 34.62 | 45.60 | 21.92 | 34.77 | 26.89 | 47.50 | 29.58 | 33.65|
| | | | | | | | | | | | | | | |
| | c2f + Fasttext | s=30, a=250, CL=2 | 47.06 | 7.32 | 12.67 | 61.03 | 26.70 | 37.15 | 16.04 | 23.06 | 18.92 | 41.38 | 19.03 | 22.91|
| Novel| c2f + Fasttext | s=20, a=50, CL=3 | 65.10 | 8.54 | 15.10 | 71.42 | 25.56 | 37.65 | 24.96 | 28.08 | 26.42 | 53.83 | 20.73 | 26.39|
| | c2f + Fasttext | s=10, a=50, CL=3 | 57.71 | 5.82 | 10.57 | 63.79 | 21.02 | 31.62 | 17.03 | 23.42 | 19.72 | 46.18 | 16.75 | 20.64|
| | | | | | | | | | | | | | | |
| |  c2f + Fasttext | s=30, a=250, CL=2 | 56.43 | 9.88 | 16.82 | 61.84 | 18.28 | 28.22 | 25.72 | 20.01 | 22.51 | 48.00 | 16.06 | 22.52|
| Descriptive| c2f + Fasttext | s=20, a=50, CL=3 | 53.78 | 7.64 | 13.37 | 58.92 | 12.84 | 21.08 | 28.76 | 19.17 | 23.01 | 47.15 | 13.22 | 19.15|
| | c2f + Fasttext | s=10, a=50, CL=3 | 52.41 | 7.46 | 13.06 | 58.06 | 14.00 | 22.57 | 24.47 | 19.03 | 21.41 | 44.98 | 13.50 | 19.01|
| | | | | | | | | | | | | | | |

### Additional Visualizations
A screenshot (Left side) from [WebAnno](https://webanno.github.io/webanno/) during annotation phase. In this example, the highlighted words are marked as mentions and same color indicate the mentions belong to the same cluster. A colored line joins the highlighted words creating a chain forming a single cluster. The supplementary datafile (right side) index.csv contains an index to all the datapoints.

| WebAnno | IndexFile |
|:-----|:-------|
| ![Alternate text](/appendix/annotation_ss.PNG) | ![Alternate text](/appendix/details_description.PNG) |

An example taken from Biography test document.
| Ground Truth | Prediction (BERT-base) |
|:-----|:-------|
| ![Alternate text](/appendix/story_gold.PNG) | ![Alternate text](/appendix/story_pred.PNG) |
