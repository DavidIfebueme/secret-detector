# CLI Usage

## Basic Scan
```bash
secret-detector scan ./src
```

## Scan with Output File
```bash
secret-detector scan ./src -o results.json
```

## Exclude Paths
```bash
secret-detector scan ./src --exclude vendor,node_modules
```
