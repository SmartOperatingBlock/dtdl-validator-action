# Dtdl Validator action
![Test and Release](https://github.com/smartoperatingblock/dtdl-validator-action/actions/workflows/test-and-release.yml/badge.svg)

A simple GitHub Action that validate Microsoft DTDL files based on the [Microsoft DTDL Validator project](https://github.com/Azure-Samples/DTDL-Validator).

## Usage
``` yaml

- uses: SmartOperatingBlock/dtdl-validator-action@<latest-version>
  with:
    # The folder in whitch the dtdl files are stored
    # Default: '.'
    folder: ''

    # If it is set to true then it will perform a recursive search starting from the
    # provided folder
    # Default: false
    recursive: true/false

```

# License
The scripts in this project are released under the [MIT License](LICENSE)