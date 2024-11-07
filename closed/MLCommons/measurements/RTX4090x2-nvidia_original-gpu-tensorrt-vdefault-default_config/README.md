| Model    | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST05   | TEST04   |
|----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|----------|
| resnet50 | server       |     76.078 |     73743.9  | -                 |                                   | passed   | passed   | passed   |
| resnet50 | offline      |     76.078 |     87803.5  | -                 |                                   | passed   | passed   | passed   |
| resnet50 | multistream  |     76.064 |      7858.55 | 1.018             |                                   | passed   | passed   | passed   |
| resnet50 | singlestream |     76.064 |      3086.42 | 0.324             |                                   | passed   | passed   | passed   |