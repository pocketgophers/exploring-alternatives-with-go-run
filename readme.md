This is the code and output associated with https://pocketgophers.com/exploring-alternatives-with-go-run/

It may not be the latest version. The latest version is in the branch with the most recent name.

The source for this tutorial is in the source branch.

Get the code with:

```
go get -d pocketgophers.com/exploring-alternatives-with-go-run
```

Run the examples with:

```
go run main.go messy.go |tee messy.txt
```

and

```
go run main.go clean.go |tee clean.txt
```

then compare the results with:

```
benchstat messy.txt clean.txt
```
