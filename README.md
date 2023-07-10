# python-bsdl-parser

This is a [TatSu][TatSu]-based parser for IEEE 1149.1 Boundary-Scan Description
Language (BSDL) files.

## Requirements

* Python 3
* [TatSu][TatSu]

## Usage

First, install the TatSu command from [here][TatSu]. Then you can run `make` to
generate the actual parser module (`bsdl.py`).

After generating the parser module, run
`./bsdl2json.py bsdl_file.bsd > json_file.json` to convert your BSDL file to
JSON.


[TatSu]: https://pypi.python.org/pypi/tatsu
