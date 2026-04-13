# Data

This directory is intentionally empty. Benchmark data is **not** checked into the repository — please download it before running the pipeline.

## LoCoMo-10

HyperMem's evaluation uses the LoCoMo benchmark (10 long-horizon conversations). The same file ships with EverMemOS, so you can copy it directly:

```bash
# From the repository root
cp methods/evermemos/data/locomo10.json methods/hypermem/data/
```

## Expected layout

After downloading:

```
data/
└── locomo10.json
```

## Auxiliary benchmarks

Additional benchmarks (LongMemEval, PersonaMem, etc.) can be placed under the same directory and referenced via the experiment config. See [`hypermem/config.py`](../hypermem/config.py).
