| Model    | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST04   |
|----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|
| resnet50 | multistream  |     76.064 |     15841.6  | 0.505             |                                   | passed   | passed   |
| resnet50 | singlestream |     76.064 |      3278.69 | 0.305             |                                   | passed   | passed   |
| resnet50 | server       |     76.078 |     73725.3  | -                 |                                   | passed   | passed   |
| resnet50 | offline      |     76.078 |     87960    | -                 |                                   | passed   | passed   |