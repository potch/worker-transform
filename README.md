# worker-transform (Experimental)

Take a top-level module and split it into a Promise-based worker file and an RPC interface file.

## Usage

```sh
worker-transform file.js
```

## Output

```
file.js (preserved as-is)
file-worker.js
file-client.js
```
