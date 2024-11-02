| Model   | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST05   |
|---------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|
| bert-99 | server       |    90.259  |        0.889 | -                 |                                   | passed   | passed   |
| bert-99 | offline      |    90.1567 |     8237.63  | -                 |                                   | passed   | passed   |
| bert-99 | singlestream |    90.2668 |      954.198 | 1.048             |                                   | passed   | passed   |