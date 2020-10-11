# Report

## Data

```yaml
investigations:
  - investigation:
    travel_variant: "direct"
    experiments:
      - experiment:
          number: 1
          input_data:
            buffer_size: "1mb"
          results:
            duration: "415602ns"
      - experiment:
          number: 2
          input_data:
            buffer_size: "2mb"
          results:
            duration: "652681ns"
      - experiment:
          number: 3
          input_data:
            buffer_size: "4mb"
          results:
            duration: "1264153ns"
      - experiment:
          number: 4
          input_data:
            buffer_size: "8mb"
          results:
            duration: "2536603ns"
      - experiment:
          number: 5
          input_data:
            buffer_size: "12mb"
          results:
            duration: "3824627ns"
  - investigation:
    travel_variant: "reverse"
    experiments:
      - experiment:
          number: 1
          input_data:
            buffer_size: "1mb"
          results:
            duration: "325475ns"
      - experiment:
          number: 2
          input_data:
            buffer_size: "2mb"
          results:
            duration: "630165ns"
      - experiment:
          number: 3
          input_data:
            buffer_size: "4mb"
          results:
            duration: "1263117ns"
      - experiment:
          number: 4
          input_data:
            buffer_size: "8mb"
          results:
            duration: "2536645ns"
      - experiment:
          number: 5
          input_data:
            buffer_size: "12mb"
          results:
            duration: "3833844ns"
  - investigation:
    travel_variant: "random"
    experiments:
      - experiment:
          number: 1
          input_data:
            buffer_size: "1mb"
          results:
            duration: "1701197ns"
      - experiment:
          number: 2
          input_data:
            buffer_size: "2mb"
          results:
            duration: "3738903ns"
      - experiment:
          number: 3
          input_data:
            buffer_size: "4mb"
          results:
            duration: "8261037ns"
      - experiment:
          number: 4
          input_data:
            buffer_size: "8mb"
          results:
            duration: "24523367ns"
      - experiment:
          number: 5
          input_data:
            buffer_size: "12mb"
          results:
            duration: "61152243ns"
```

## Chart

[![Chart](https://i.ibb.co/2NZSt1r/processor-data-access-chart.png)](https://live.amcharts.com/jZGU4/)