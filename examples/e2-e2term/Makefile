all: e2_term e2

e2_term: e2_term.go conn.go
	go build -o $@

e2: e2.go conn.go
	go build -o $@ -tags $@

clean:
	rm e2 e2_term