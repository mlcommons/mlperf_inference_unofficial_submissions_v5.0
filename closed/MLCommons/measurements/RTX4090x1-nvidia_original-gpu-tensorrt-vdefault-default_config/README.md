| Model     | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   |
|-----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|
| retinanet | server       |     37.353 |      637.176 | -                 |                                   | passed   |
| retinanet | multistream  |     37.344 |      730.06  | 10.958            |                                   | passed   |
| retinanet | offline      |     37.335 |      862.711 | -                 |                                   | passed   |
| retinanet | singlestream |     37.33  |      572.738 | 1.746             |                                   | passed   |