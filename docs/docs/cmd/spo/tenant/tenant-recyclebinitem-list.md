# spo tenant recyclebinitem list

Returns all modern and classic site collections in the tenant scoped recycle bin

## Usage

```sh
m365 spo tenant recyclebinitem list [options]
```

## Options

`-h, --help`
: output usage information

`--query [query]`
: JMESPath query string. See [http://jmespath.org/](http://jmespath.org/) for more information and examples

`-o, --output [output]`
: Output type. `json,text`. Default `text`

`--verbose`
: Runs command with verbose logging

`--debug`
: Runs command with debug logging

!!! important
    To use this command you have to have permissions to access the tenant admin site.

## Examples

Returns all modern and classic site collections in the tenant scoped recycle bin

```sh
m365 spo tenant recyclebinitem list
```
