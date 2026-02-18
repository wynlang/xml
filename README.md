# xml — Official Wyn Package

Simple XML tag extraction. Pure Wyn.

## Install

```bash
wyn pkg install github.com/wynlang/xml
```

## Usage

```wyn
var value = xml_get_tag("<root><name>Alice</name></root>", "name")  // "Alice"
```
