changes I've made:
1. rename the input file from "intent_mod" to "intent_model"

---------------------------------------------------------------------

* AUC stands for Area Under the Curve, and it is a `measure of the performance of a binary classifier`. The ROC curve is a graphical representation of the AUC, and it plots the true positive rate (TPR) against the false positive rate (FPR) at different classification thresholds. A higher AUC indicates a better-performing classifier.

  * AUC: The AUC is a single number that summarizes the performance of a classifier across all possible classification thresholds. A perfect classifier will have an AUC of 1, while a random classifier will have an AUC of 0.5.

  * ROC curve: The ROC curve is a more detailed representation of the AUC. It shows how the TPR and FPR change as the classification threshold is varied.
AUC and ROC curves are both important metrics for evaluating the performance of binary classifiers. AUC is a single number that is easy to understand, while the ROC curve provides more detailed information about the performance of the classifier.
