# Precision Scores
| Topic   | Topic-Relevance | Argumentativeness | Stance | Stance (Con) | Stance (Pro) |
|---------|-----------------|-------------------|--------|--------------|--------------|
| Overall | 0.89            | 0.817             | 0.458  | 0.223        | 0.693        |
| 3       | 0.9             | 0.85              | 0.45   | 0.2          | 0.7          |
| 5       | 1.0             | 1.0               | 0.5    | 0.1          | 0.9          |
| 6       | 0.8             | 0.65              | 0.35   | 0.2          | 0.5          |
| 7       | 0.7             | 0.7               | 0.35   | 0            | 0.7          |
| 11      | 1.0             | 1.0               | 0.6    | 0.6          | 0.6          |
| 12      | 0.85            | 0.85              | 0.5    | 0.1          | 0.9          |
| 13      | 0.9             | 0.7               | 0.4    | 0.1          | 0.7          |
| 14      | 0.55            | 0.5               | 0.3    | 0.1          | 0.5          |
| 16      | 0.85            | 0.65              | 0.25   | 0.3          | 0.2          |
| 17      | 0.75            | 0.65              | 0.35   | 0.1          | 0.6          |
| 18      | 0.9             | 0.85              | 0.55   | 0.7          | 0.4          |
| 19      | 1.0             | 0.85              | 0.4    | 0.3          | 0.5          |
| 23      | 0.95            | 0.85              | 0.6    | 0.4          | 0.8          |
| 24      | 0.9             | 0.85              | 0.4    | 0            | 0.8          |
| 25      | 0.8             | 0.75              | 0.5    | 0.4          | 0.6          |
| 26      | 0.9             | 0.8               | 0.45   | 0.5          | 0.4          |
| 28      | 0.95            | 0.8               | 0.35   | 0.2          | 0.5          |
| 29      | 0.95            | 0.95              | 0.6    | 0.6          | 0.6          |
| 30      | 0.85            | 0.75              | 0.45   | 0.1          | 0.8          |
| 32      | 0.8             | 0.8               | 0.55   | 0.2          | 0.9          |
| 34      | 0.9             | 0.55              | 0.3    | 0.1          | 0.5          |
| 35      | 1.0             | 0.9               | 0.5    | 0.2          | 0.8          |
| 38      | 1.0             | 1.0               | 0.5    | 0            | 1.0          |
| 39      | 0.95            | 0.9               | 0.45   | 0.1          | 0.8          |
| 41      | 0.95            | 0.95              | 0.5    | 0.1          | 0.9          |
| 42      | 1.0             | 1.0               | 0.6    | 0.4          | 0.8          |
| 44      | 0.7             | 0.7               | 0.6    | 0.3          | 0.9          |
| 46      | 1.0             | 1.0               | 0.5    | 0            | 1.0          |
| 49      | 0.95            | 0.95              | 0.45   | 0.2          | 0.7          |
| 50      | 0.95            | 0.75              | 0.45   | 0.1          | 0.8          |

# Train History

## Con

| Epoch | loss   | accuracy | val_loss | val_accuracy | lr     |
|-------|--------|----------|----------|--------------|--------|
| 0     | 0.5365 | 0.8044   | 0.4837   | 0.8089       | 0.0001 |
| 1     | 0.4605 | 0.8110   | 0.4777   | 0.8065       | 0.0001 |
| 2     | 0.4136 | 0.8312   | 0.4759   | 0.8137       | 0.0001 |
| 3     | 0.3605 | 0.8511   | 0.4902   | 0.8032       | 0.0001 |
| 4     | 0.3187 | 0.8838   | 0.5153   | 0.7952       | 0.0001 |
| 5     | 0.2737 | 0.8999   | 0.6146   | 0.7476       | 0.0001 |

## Pro

| Epoch | loss   | accuracy | val_loss | val_accuracy | lr     |
|-------|--------|----------|----------|--------------|--------|
| 0     | 0.7251 | 0.6432   | 0.5758   | 0.7468       | 0.0001 |
| 1     | 0.6260 | 0.7309   | 0.6438   | 0.6129       | 0.0001 |
| 2     | 0.5417 | 0.7784   | 0.6625   | 0.7129       | 0.0001 |
| 3     | 0.4561 | 0.8183   | 0.6530   | 0.7048       | 0.0001 |
