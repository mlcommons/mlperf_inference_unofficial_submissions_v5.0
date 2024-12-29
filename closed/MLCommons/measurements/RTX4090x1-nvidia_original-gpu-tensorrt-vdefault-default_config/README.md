| Model     | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   |
|-----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|
| retinanet | server       |     37.334 |      637.174 | -                 |                                   | passed   |
| retinanet | multistream  |     37.349 |      734.012 | 10.899            |                                   | passed   |
| retinanet | offline      |     37.349 |      861.556 | -                 |                                   | passed   |
| retinanet | singlestream |     37.306 |      570.776 | 1.752             |                                   | passed   |