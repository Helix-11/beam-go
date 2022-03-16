beam-wordcount-go
Example from https://github.com/apache/beam/blob/master/sdks/go/examples/wordcount/wordcount.go

Read More
Apache Beam Go SDK Quickstart
Windows Tools
PowerShell (cross-platform)
Git
Chocolatey (Windows Package Manager)
Install Go
choco install golang -y
refreshenv
choco list --local-only 
Verify
go version
Review the installed files at C:\Program Files\Go.

Get Beam Go SDK
go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
Run WordCount Example
go install github.com/apache/beam/sdks/v2/go/examples/wordcount@latest
wordcount --input <PATH_TO_INPUT_FILE> --output counts
Examples:

wordcount --input 'C:\Users\dcase\Documents\44-517\beam-wordcount-go\data.txt' --output counts
wordcount --input data.txt --output counts.yaml
Review the local dependencies at C:\Users<username>\AppData\Local\go-build.

About Go
go get - updates dependencies/versions listed in go.mod and updates local cache
go run - comples and runs the file
[go install] is used to build and install the provided source file
go.mod can be found at $GOPATH/misc