# Chess Captures Forced
This project is based on Alpaca (https://github.com/bbogdan95/alpaca.git), a full open-source chess engine. The original engine uses standard rules, while this project adds a new rule - captures are forced. 


## Build:

```
go build cmd/alpaca/main.go
```

## Changes:
Modified search.go and main.go to restrict moves to captures if there is one available.

## License/Credits:
This project is based on the open-source chess engine Alpaca (https://github.com/bbogdan95/alpaca.git), which is licensed under MIT. More is in the LICENSE file.