# nbs2ctx


<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

## Usage

nbs2ctx is a minimal CLI for turning a directory of notebooks (e.g. an
NBDev project) into context for an LLM. For example, from the root dir
of this github repo we could run:

`nbs_to_ctx nbs ctx.xml`

This will create a file ctx.xml with the contents of all the notebooks
in the nbs folder.

    <documents>
    <document index="1">
    <source>00_core.ipynb</source>
    <document_content>
    # nbs_to_ctx

    &gt; Turning Jupyter notebooks into LLM-ready context

    ```python
    #| default_exp core
    ... and so on, with the full contents of the notebook

### Installation

Install latest from the GitHub
[repository](https://github.com/AnswerDotAI/nbs2ctx):

``` sh
$ pip install git+https://github.com/AnswerDotAI/nbs2ctx.git
```

or from [pypi](https://pypi.org/project/nbs2ctx/)

``` sh
$ pip install nbs2ctx
```
