
# OpenAi GPT-3 Client

## Overview

This is a client for the OpenAI GPT-3 text generation API. The client was generated by GPT-3 itself from a curl statement 🤖.

## Installation

To install this client, run the following command:

```
go get github.com/shell-company/gpt3client
```

## Usage

To use this client, you will need to set the `OPEN_AI_APIKEY` environment variable to your OpenAI API key.

You can then use the client like so:

```go
package main

import (
	"fmt"

	"github.com/shell-company/gpt3client"
)

func main() {
	output, _ := gpt3client.SendOpenAIPrompt("Hello world")
	fmt.Println(output)
}
```

This will generate a response from the OpenAi GPT-3 API.
