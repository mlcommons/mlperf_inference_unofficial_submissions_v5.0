| Model     | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   |
|-----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|
| retinanet | server       |     37.362 |      637.176 | -                 |                                   | passed   |
| retinanet | multistream  |     37.325 |      733.205 | 10.911            |                                   | passed   |
| retinanet | offline      |     37.321 |      863.829 | -                 |                                   | passed   |
| retinanet | singlestream |     37.335 |      572.738 | 1.746             |                                   | passed   |