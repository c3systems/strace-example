# STRACE
The two trace files were run with `strace go run main.go 2>&1 | tee ./trace.txt`.

The two trace files named *_bin*.txt were run from a compiled version of the program `go build main.go && strace ./main 2>&1 | tee ./trace.txt`
