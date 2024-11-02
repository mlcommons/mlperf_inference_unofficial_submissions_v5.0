| Model    | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST05   | TEST04   |
|----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|----------|
| resnet50 | server       |     76.078 |     73744    | -                 |                                   | passed   | passed   | passed   |
| resnet50 | offline      |     76.078 |     87917    | -                 |                                   | passed   | passed   | passed   |
| resnet50 | multistream  |     76.064 |      7699.71 | 1.039             |                                   | passed   | passed   | passed   |
| resnet50 | singlestream |     76.064 |      1639.34 | 0.61              |                                   | passed   | passed   | passed   |