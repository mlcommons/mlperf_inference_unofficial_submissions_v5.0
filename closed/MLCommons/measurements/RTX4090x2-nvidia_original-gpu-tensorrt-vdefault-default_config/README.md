| Model   | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST05   |
|---------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|
| bert-99 | server       |    90.259  |     6061.44  | -                 |                                   | passed   | passed   |
| bert-99 | offline      |    90.1567 |     8219.2   | -                 |                                   | passed   | passed   |
| bert-99 | singlestream |    90.2668 |      956.938 | 1.045             |                                   | passed   | passed   |