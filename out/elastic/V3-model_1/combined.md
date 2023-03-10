# Precision Scores

P@10 for 30 Topics. NeuralModels where trained on ```[1, 2, 4, 8, 9, 10, 15, 20, 21, 22, 27, 31, 33, 36, 37, 40, 43, 45, 47, 48]```, evaluated on all other Topics.

| StanceModel    | Topic-Relevance | Argumentativeness | Stance | Stance (Con) | Stance (Pro) |
|----------------|-----------------|-------------------|--------|--------------|--------------|
| Oracle         | 1.0             | 1.0               | 0.9    | 0.8          | 1.0          |
| Bert           | 0.88            | 0.793             | 0.473  | 0.233        | 0.713        |
| Neural V7      | 0.89            | 0.817             | 0.458  | 0.223        | 0.693        |
| Clip good/anti | 0.913           | 0.795             | 0.447  | 0.217        | 0.677        |
| Neural V6      | 0.902           | 0.817             | 0.445  | 0.213        | 0.677        |
| Formula        | 0.857           | 0.775             | 0.443  | 0.18         | 0.707        |
| Dummy          | 0.913           | 0.813             | 0.438  | 0.19         | 0.687        |
| NN 0.5:V6      | 0.878           | 0.78              | 0.42   | 0.22         | 0.62         |
| Random         | 0.89            | 0.807             | 0.413  | 0.16         | 0.667        |
| AFinn          | 0.848           | 0.765             | 0.398  | 0.193        | 0.603        |
| Google         | 0.772           | 0.697             | 0.387  | 0.15         | 0.623        |
| Neural V3      | 0.793           | 0.735             | 0.357  | 0.18         | 0.533        |
| Neural V9      | 0.692           | 0.618             | 0.337  | 0.133        | 0.54         |
| Neural V8      | 0.663           | 0.583             | 0.312  | 0.16         | 0.463        |

