<h1 align="center">jsoncli</h1>

<h3 align="center">
  🗷 A command line utility for manipulating JSON files 
</h3>

<div align="center">

[![PyPI version](https://badge.fury.io/py/jsoncli.svg)](https://badge.fury.io/py/jsoncli)
[![Downloads](https://static.pepy.tech/personalized-badge/jsoncli?period=total&units=international_system&left_color=grey&right_color=orange&left_text=Downloads)](https://pepy.tech/project/jsoncli)
[![Package Status](https://img.shields.io/static/v1?label=status&message=stable&color=brightgreen)](https://pypi.org/project/jsoncli/)
  
</div>

## Installation

jsoncli can be installed via pip through PyPi

```
pip install jsoncli
```

## Usage

Once jsoncli is installed, you can use the following command to interact with the cli

```
jsoncli COMMAND [FILE] [PATH] [VALUE] [--ARGS]
```
<table>
  <tr>
    <td>COMMAND</td>
     <td>Command to run</td>
  </tr>
  <tr>
    <td>FILE</td>
     <td>Path to JSON file</td>
  </tr>
  <tr>
    <td>PATH</td>
     <td>Key name or path (dot notation or slash notation)</td>
  </tr>
  <tr>
    <td>VALUE</td>
     <td>The new value for `set` command</td>
  </tr>
   <tr>
    <td>ARGS</td>
     <td>Optional arguments to pass. Check below</td>
  </tr>