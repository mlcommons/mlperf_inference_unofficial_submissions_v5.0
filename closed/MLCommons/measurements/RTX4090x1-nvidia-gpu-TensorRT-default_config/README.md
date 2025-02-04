| Model    | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST04   |
|----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|
| resnet50 | offline      |     76.078 |      44390.5 | -                 |                                   | passed   | passed   |
| resnet50 | singlestream |     76.064 |       3546.1 | 0.282             |                                   | passed   | passed   |
| resnet50 | server       |     76.078 |      35342.5 | -                 |                                   | passed   | passed   |
| resnet50 | multistream  |     76.064 |      17621.1 | 0.454             |                                   | passed   | passed   |