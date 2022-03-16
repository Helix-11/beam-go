# beam-wordcount-go
# Logan Krohn

Example from https://github.com/apache/beam/blob/master/sdks/go/examples/wordcount/wordcount.go

## Read More

- [Apache Beam Go SDK Quickstart](https://beam.apache.org/get-started/quickstart-go/)

## Install Go

- [Go Download](https://go.dev/)


## Verify

```PowerShell
go version
```

Review the installed files at C:\Program Files\Go.

## Get Beam Go SDK

```PowerShell
go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
```

## Run WordCount Example

```PowerShell
go install github.com/apache/beam/sdks/v2/go/examples/wordcount@latest
wordcount --input <PATH_TO_INPUT_FILE> --output counts
```

Example: 

```PowerShell
wordcount --input data.txt --output counts.yaml
```

Review the local dependencies at C:\Users\<username>\AppData\Local\go-build.

## About Go

- [go get](cmd/go/internal/get) - updates dependencies/versions listed in go.mod and updates local cache
- [go run]() - comples and runs the file
- [go install] is used to build and install the provided source file
- go.mod can be found at $GOPATH/misc
