# Inference parameters

### GECToR Large models with a vocabulary size of 5K.
| Model | AC | MEP | TP | FP | FN | Prec | Rec | F0.5 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RoBERTa | 0.05 | 0.6 | 2526 | 1315 | 4935 | 0.6576 | 0.3386 | 0.5533 |
| DeBERTa | 0.4 | 0.55 | 2445 | 1240 | 5016 | 0.6635 | 0.3277 | 0.5507 |
| XLNet | 0.3 | 0.6 | 2624 | 1459 | 4837 | 0.6427 | 0.3517 | 0.5514 |
| BERT | 0.0 | 0.55 | 2332 | 1480 | 5129 | 0.6118 | 0.3126 | 0.5135 |

To reproduce results, please use `--special_tokens_fix 1` for all models along with the specified `--additional_confidence` (AC) and `--min_error_probability` (MEP) parameters.
