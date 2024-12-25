| Model    | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST04   |
|----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|
| resnet50 | server       |     76.078 |     35357.7  | -                 |                                   | passed   | passed   |
| resnet50 | multistream  |     76.064 |     16949.2  | 0.472             |                                   | passed   | passed   |
| resnet50 | offline      |     76.078 |     43755.8  | -                 |                                   | passed   | passed   |
| resnet50 | singlestream |     76.064 |      3610.11 | 0.277             |                                   | passed   | passed   |