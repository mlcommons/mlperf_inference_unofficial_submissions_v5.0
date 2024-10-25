| Model    | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST05   | TEST04   |
|----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|----------|
| resnet50 | server       |     76.078 |     73015.2  | -                 |                                   | passed   | passed   | passed   |
| resnet50 | offline      |     76.078 |     87471.2  | -                 |                                   | passed   | passed   | passed   |
| resnet50 | multistream  |     76.078 |      8403.36 | 0.952             |                                   | passed   | passed   | passed   |
| resnet50 | singlestream |     76.078 |      2923.98 | 0.342             |                                   | passed   | passed   | passed   |