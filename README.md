# Awesome GPT Plugins

In additional to prompting GPTs can be extended through actions (HTTP APIs) or uploading files or binaries. This repo is a collection of useful actions or binaries that can be used to add functionality to your GPT in one step.

## Contents

- [Actions](#actions)
- [Binaries](#binaries)

## Actions

To add an action to your GPT, copy the YAML code into a new action. All of the examples below do not require authentication.

For more detailed instructions, see [How to Use GPT Actions](Actions.md).

| **Action**                                              | **Description**                                        |
| ------------------------------------------------------- | ------------------------------------------------------ |
| [aljazeera](actions/aljazeera.yaml)                     | Get news from the homepage.                            |
| [bbc](actions/bbc.yaml)                                 | Get news from the homepage.                            |
| [nytimes](actions/nytimes.yaml)                         | Get news from the homepage.                            |
| [poetrydb](actions/poetrydb.yaml)                       | Look up poems.                                         |
| [ip-whois](actions/ip-whois.yaml)                       | Look up the owner and location of an IP address.       |
| [random-dog](actions/random-dog.yaml)                   | Provide an image of a dog.                             |
| [coingecko](actions/coingecko.yaml)                     | Look up current crypto prices.                         |
| [gutenberg](actions/gutenberg.yaml)                     | Search books.                                          |
| [random-user](actions/random-user.yaml)                 | Provide fake user credentials.                         |
| [us-national-weather](actions/us-national-weather.yaml) | Get the current weather forecast for cities in the US. |
| [url-shortener](actions/url-shortener.yaml)             | Generate a short URL.                                  |
| [rust](actions/rust.yaml)                               | Compile and run a Rust program.                        |

## Binaries

The binaries below are able to be run by Code Interpreter.

For detailed instructions, see [How to Use Binaries in GPT](Binaries.md).

| Binary                                                       | Description                            |
| ------------------------------------------------------------ | -------------------------------------- |
| [deno-x86_64](https://github.com/denoland/deno/releases/download/v1.33.1/deno-x86_64-unknown-linux-gnu.zip) | Run JavaScript code to see the output. |
| [php](https://static.simonwillison.net/static/2023/php)      | Run PHP code to see the output.        |

These both come from a well written [blog post by Simon Willison](https://til.simonwillison.net/llms/code-interpreter-expansions).

Additionally, it is possible to ask Code Interpreter to compile a C binary, which you can then upload to a new GPT. Alternatively, you could upload a Python script or module.
