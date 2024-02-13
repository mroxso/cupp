### Bulding the application
```bash
docker build -t cupp:local .
```

### Running the application
```bash
docker run --rm -i --name cupp cupp:local python3 cupp.py -i
```