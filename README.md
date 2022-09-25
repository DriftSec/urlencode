# urlencode
(en|de)code urls from the CLI

# Installation

```
go get github.com/DriftSec/urlencode
```

# Usage

Pipe into the tool with no options to encode, for decoding, add `-d`.

```
~$ echo "test!" | urlencode
test%21
~$ echo "test%21" | urlencode -d
test!
```
