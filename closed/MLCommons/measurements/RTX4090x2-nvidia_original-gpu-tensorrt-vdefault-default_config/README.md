| Model    | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST05   | TEST04   |
|----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|----------|
| resnet50 | server       |     76.078 |     73744    | -                 |                                   | passed   | passed   | passed   |
| resnet50 | offline      |     76.078 |     87929.2  | -                 |                                   | passed   | passed   | passed   |
| resnet50 | multistream  |     76.064 |      7905.14 | 1.012             |                                   | passed   | passed   | passed   |
| resnet50 | singlestream |     76.064 |      3225.81 | 0.31              |                                   | passed   | passed   | passed   |