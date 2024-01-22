- **Purpose**: Dedicated to explaining the metrics used in the field.

# Natural Language Generation Metrics
## Bilingual Evaluation Understudy (BLEU)

## Metric for Evaluation of Translation with Explicit Ordering (METEOR)

## Consensus-based Image Description Evaluation (CIDEr)

## Recall-Oriented Understudy for Gisting Evaluation (ROUGE)


# Clinical Efficacy (CE) Metrics
In the evaluation of chest radiology report generation systems, Clinical Efficacy (CE) metrics play a crucial role. These metrics help in quantitatively assessing how well the generated reports match the expected medical standards and diagnoses. For this purpose, labels from reference (standard) and generated reports are compared using tools like CheXpert and CheXbert, which are automated labelers designed to annotate radiology reports with clinical observations. The four key metrics used in this evaluation are Accuracy, Precision, Recall, and F1 Score, each providing unique insights into the model's performance.

## Background
Confusion Matrix:
- WIP
True Positives (TP): WIP
- WIP
True Negatives (TN)
- WIP
False Postivies (FP)
- WIP
False Negatives (FN)
- WIP
## Accuracy
Accuracy = $\frac{TP + TN}{TP + TN + FP + FN}$
## Precision
Precision (P) = $\frac{TP}{TP + FP}$
## Recall
Recall (R) = $\frac{TP}{TP + FN}$
## F1 Score
F1 Score = $\frac{2 * P * R}{ P + R}$

## Example:
Reference:
- Report:
	WIP
- Labels:
	WIP

Generated:
- Report:
	WIP
- Labels:
	WIP

Confusion Matrix:
- WIP
Accuracy = WIP
Precision = WIP
Recall = WIP
F1 Score = WIP


#task :
- Explain why CE metrics are needed in addition to NLG metrics.
	- Briefly explain TP, TN, FP, FN?
	- Contextualize importance of TP, TN, FP, FN? and CE metrics?
	- Include confusion matrix example?
	- Go over limitations of CE metrics?
	- Question for myself. Why is F1 score used over 0.5 R + 0.5 P?