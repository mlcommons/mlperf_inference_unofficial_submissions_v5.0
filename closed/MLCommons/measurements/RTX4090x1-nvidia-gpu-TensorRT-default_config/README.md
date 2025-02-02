| Model    | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST04   |
|----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|
| resnet50 | offline      |     76.078 |     44259.5  | -                 |                                   | passed   | passed   |
| resnet50 | singlestream |     76.064 |      3521.13 | 0.284             |                                   | passed   | passed   |
| resnet50 | server       |     76.078 |     35342.5  | -                 |                                   | passed   | passed   |
| resnet50 | multistream  |     76.064 |     15841.6  | 0.505             |                                   | passed   | passed   |