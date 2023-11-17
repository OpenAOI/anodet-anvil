# anodet-anvil
An Anvil + Flask webapp for for computer vision anomlay detection with [Anodet](https://github.com/OpenAOI/anodet) framework.

## Requirements
- Python 3.10
- mkdocs, mkdocstrings, mkdocs-material
- anvil, anvil-uplink
- mccp


## Installation

```
git clone https://github.com/OpenAOI/anodet-anvil.git
```

Clone the <a href="https://anvil.works/build#clone:JT6SCPFZFHLBPZ6K=SDLUIZFY3TF7DKYEMR2HJWDA|YZFAF3UQ2TEZDHTQ=DUSY6UWZ2WDCVXNUJYFEU6NW|5IMMJBKGCSO6YGHB=K2QYA32ANY6JM6L3SQVCNJWH">Anvil Works Project Source Code</a>

```bash
pip install mkdocs mkdocstrings mkdocs-material anvil anvil-uplink mccp
```

Clone Anodet into parent directory

```bash
git clone https://github.com/OpenAOI/anodet.git
```

## Starting the application

Simply run the client code from Anvil website and the server code in _run.py

## What about uplink key?

Head over to Anvil Works to get your uplink key. Create anvil_key.json and place the uplink key in you root dir like this:
```json
{
    "Server_Uplink_Key": "server_XXXXXXXXXXXXXXXXXXXXXXXX-xxxxxxxxxxxxxxxxx"
}
```

## For documentation

Run terminal command:

```bash
mkdocs serve
```
