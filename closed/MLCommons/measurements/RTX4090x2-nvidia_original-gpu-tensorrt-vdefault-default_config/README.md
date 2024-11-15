| Model   | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST05   |
|---------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|
| bert-99 | server       |    90.259  |     6061.5   | -                 |                                   | passed   | passed   |
| bert-99 | offline      |    90.1567 |     8219.33  | -                 |                                   | passed   | passed   |
| bert-99 | singlestream |    90.2668 |      961.538 | 1.04              |                                   | passed   | passed   |