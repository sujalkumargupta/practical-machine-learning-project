# Practical Machine Learning — Course Project

Predicting how well a barbell lift was performed (`classe` A–E) from wearable accelerometer data.

**View the report online:** https://sujalkumargupta.github.io/practical-machine-learning-project/

## Files

| File | What it is |
|------|------------|
| `index.Rmd` | R Markdown source of the analysis |
| `index.html` | Compiled HTML report (open in a browser) |
| `test_predictions.csv` | Predictions for the 20 test cases |

## Summary

* 52 sensor features after removing ID columns and mostly-empty summary columns.
* Compared a decision tree (~68 % accuracy) with a random forest, using 5-fold cross-validation plus a 30 % hold-out set.
* Random forest: **99.32 % validation accuracy**, expected out-of-sample error ≈ **0.7 %**.

## Data

Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. *Qualitative Activity Recognition of Weight Lifting Exercises.* Proceedings of Augmented Human '13. Stuttgart, Germany: ACM SIGCHI, 2013.
<http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har>
