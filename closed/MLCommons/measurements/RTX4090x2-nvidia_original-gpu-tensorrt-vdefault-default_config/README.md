| Model   | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST05   |
|---------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|
| bert-99 | server       |    90.259  |        0.889 | -                 |                                   | passed   | passed   |
| bert-99 | offline      |    90.1567 |     8232.03  | -                 |                                   | passed   | passed   |
| bert-99 | singlestream |    90.2668 |      968.992 | 1.032             |                                   | passed   | passed   |