name: java Workflow Demo

on: [push]

jobs:
  Execute:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: java Version
        run: java -version
      - name: Identifying the Folder
        run: pwd
      - name: List the files in current directory
        run: ls ${{github.workspace}}
      - name: Run java File
        run: javac ../devsecops-cgi/hello.java
