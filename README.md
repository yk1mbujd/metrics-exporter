# metrics-exporter

A minimal metrics registry with counters, gauges and histograms.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

## Install

```bash
pip install metrics-exporter
```

## Usage

```python
from metrics_exporter import metricsExporter

result = metricsExporter("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
