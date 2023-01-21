# go-bench-sample

## bench
```bash
go test -bench .
```

## bench with cpu profiling
```bash

go tool pprof --text ./pprof/test.bin ./pprof/cpu.out

go test -bench . -o ./pprof/test.bin  -cpuprofile ./pprof/cpu.out
```