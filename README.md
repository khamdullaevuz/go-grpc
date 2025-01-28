# gRPC example

This is a simple example of a gRPC server and client in Go.

## Running the example

1. Generate the gRPC code from the proto file:

```bash
make gen
```

2. Run the order service:

```bash
make run-orders
```

3. Run the kitchen service:

```bash
make run-kitchen
```