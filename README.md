# Toolskit Packages

A simple example of how to upload a files and manipulate JSON in **Golang**.

The included tools are:

- [X] Read JSON
- [X] Write JSON
- [X] Produce a JSON encoded error response
- [X] Upload a file to a specified directory
- [X] Download a static file
- [X] Get a random string of length n
- [X] Post JSON to a remote service 
- [X] Create a directory, including all parent directories, if it does not already exist
- [X] Create a URL safe slug from a string

## Installation

`go get -u github.com/JuniorPaula/toolskit`

## Tests
```golang 
go test -v .
```

```golang
=== RUN   TestTools_PushJSONToRemote
--- PASS: TestTools_PushJSONToRemote (0.00s)
=== RUN   TestTools_RandomString
--- PASS: TestTools_RandomString (0.00s)
=== RUN   TestTools_UploadFiles
--- PASS: TestTools_UploadFiles (0.37s)
=== RUN   TestTools_UploadOneFile
--- PASS: TestTools_UploadOneFile (0.15s)
=== RUN   TestTools_CreateDirIfNotExist
--- PASS: TestTools_CreateDirIfNotExist (0.00s)
=== RUN   TestTools_Slugify
--- PASS: TestTools_Slugify (0.00s)
=== RUN   TestTools_DownloadStaticfile
--- PASS: TestTools_DownloadStaticfile (0.01s)
=== RUN   TestTools_ReadJSON
--- PASS: TestTools_ReadJSON (0.00s)
=== RUN   TestTools_WriteJSON
--- PASS: TestTools_WriteJSON (0.00s)
=== RUN   TestTools_ErrorJSON
--- PASS: TestTools_ErrorJSON (0.00s)
PASS
```