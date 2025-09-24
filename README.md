# Hello World GitHub Action

A simple GitHub Action that prints "Hello <name>".

## 🚀 Usage

Add this to your workflow:

```yaml
name: Example Workflow

on: [push]

jobs:
  hello:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Run Hello World Action
        uses: johnkravin9-design/my-first-action@v1
        with:
          name: "John"
