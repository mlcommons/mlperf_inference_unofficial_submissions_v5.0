| Model     | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   |
|-----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|
| retinanet | multistream  |     37.33  |     1421.97  | 5.626             |                                   | passed   |
| retinanet | singlestream |     37.352 |      580.046 | 1.724             |                                   | passed   |
| retinanet | server       |     37.336 |     1414.96  | -                 |                                   | passed   |
| retinanet | offline      |     37.356 |     1734.74  | -                 |                                   | passed   |