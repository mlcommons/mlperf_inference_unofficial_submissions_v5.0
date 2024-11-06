| Model    | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST05   | TEST04   |
|----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|----------|
| resnet50 | server       |     76.078 |     73743.9  | -                 |                                   | passed   | passed   | passed   |
| resnet50 | offline      |     76.078 |     87844.7  | -                 |                                   | passed   | passed   | passed   |
| resnet50 | multistream  |     76.064 |      7797.27 | 1.026             |                                   | passed   | passed   | passed   |
| resnet50 | singlestream |     76.064 |      1315.79 | 0.76              |                                   | passed   | passed   | passed   |