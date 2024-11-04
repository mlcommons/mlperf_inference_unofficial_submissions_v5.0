| Model   | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST05   |
|---------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|
| bert-99 | server       |    90.259  |     6061.48  | -                 |                                   | passed   | passed   |
| bert-99 | offline      |    90.1567 |     8228.93  | -                 |                                   | passed   | passed   |
| bert-99 | singlestream |    90.2668 |      961.538 | 1.04              |                                   | passed   | passed   |