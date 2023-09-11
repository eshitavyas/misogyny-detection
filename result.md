# Model Accuracy Results


| Model                         | Accuracy   |
| ----------------------------- | ---------- |
| Logistic Regression           | 86.72%     |
| BiLSTM + RNN with Glove Embedding Layer | 90.02%     |
| BERT                          | 88.00%     |
| Naive Bayes                   | 86.00%     |

# Model Predcitions

| Sentence                                  | Misogyny Accuracy    | Model Prediction                                      | Classification |
|----------------------------------------|------------ |-----------------------------------------------|-------------------|
| "women cant play sports"               | 99.96399%   | "You're a misogynist"                       | Misogyny          |
| "let the men handle the technical ppts" | 99.962425% | "You're a misogynist"                       | Misogyny          |
| "you look beautiful today"             | 0     | "You're good to go."                        | Not Misogyny      |
| "the girls of this batch are very smart"| 0     | "You're good to go."                        | Not Misogyny      |
| "girls should not wear short clothes"  | 97.64505%   | "You're a misogynist"                       | Misogyny          |
| "boys will be boys"                    | 91.19183%   | "You're a misogynist"                       | Misogyny          |
