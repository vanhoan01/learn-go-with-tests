# test
cd path
go test -v

# Build and run server
go build
.\folder-name.exe

Add new tab pwsh
# test application
# http server
// Score the win
curl -X POST http://localhost:5000/players/Hoan
// Check scores
curl http://localhost:5000/players/Hoan

# json
// Score the win
curl -X POST http://localhost:5000/players/Hoan
curl -X POST http://localhost:5000/players/Alice
curl -X POST http://localhost:5000/players/Bob
// Check league information
curl http://localhost:5000/league

# io
// Score the win
curl -X POST http://localhost:5000/players/Alice
curl -X POST http://localhost:5000/players/Hoan
curl -X POST http://localhost:5000/players/Hoan
curl -X POST http://localhost:5000/players/Hoan
curl -X POST http://localhost:5000/players/Himmel
curl -X POST http://localhost:5000/players/Himmel
// check the players sorted by their scores, from highest to lowest
curl http://localhost:5000/league

# command-line (Command line & package structure)
go get github.com/quii/learn-go-with-tests/command-line/v3
    github.com/vanhoan01/learn-go-with-tests/command-line
go test

cd .\cmd\webserver\
go run main.go

Visit http://localhost:5000/league

Add new tab
cd .\command-line\

// Score the win
curl -X POST http://localhost:5000/players/Alice
curl -X POST http://localhost:5000/players/Hoan
curl -X POST http://localhost:5000/players/Hoan
curl -X POST http://localhost:5000/players/Hoan
curl -X POST http://localhost:5000/players/Himmel
curl -X POST http://localhost:5000/players/Himmel
// check the players sorted by their scores, from highest to lowest
curl http://localhost:5000/league

Visit http://localhost:5000/league
and file game.db.json
# more info
https://pkg.go.dev/fmt
pwsh> $env:CGO_ENABLED=1; go test -race
godoc -http=:5000