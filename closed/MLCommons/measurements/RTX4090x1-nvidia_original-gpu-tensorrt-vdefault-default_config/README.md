| Model     | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   |
|-----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|
| retinanet | server       |     37.355 |      637.174 | -                 |                                   | passed   |
| retinanet | multistream  |     37.341 |      735.903 | 10.871            |                                   | passed   |
| retinanet | offline      |     37.376 |      863.003 | -                 |                                   | passed   |
| retinanet | singlestream |     37.331 |      571.102 | 1.751             |                                   | passed   |