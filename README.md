# \<mah-date-formatter\>

An element for when you just want to databind some dates and not worry about the details.
Accepts javascript parsable dates and unix dates and outputs it as text in many different formats.

## Examples

### Basic Usage

    <mah-date-formatter input="[[now]]"></mah-date-formatter>

### Parsing Unix

    <mah-date-formatter input="[[nowUnix]]" input-format="unix"></mah-date-formatter>

### Overriding User Locale

    <mah-date-formatter input="[[now]]" locale="zh-CN"></mah-date-formatter>

### All output formats

| Format     | Example                                                     |
| ---------- | ----------------------------------------------------------- |
| date       | "Tue Jan 09 2018"                                           |
| time       | "09:50:59 GMT-0500 (Eastern Standard Time)"                 |
| string     | "Tue Jan 09 2018 09:50:59 GMT-0500 (Eastern Standard Time)" |
| gmt        | "Tue, 09 Jan 2018 14:50:59 GMT"                             |
| iso        | "2018-01-09T14:50:59.368Z"                                  |
| json       | "2018-01-09T14:50:59.368Z"                                  |
| utc        | "Tue, 09 Jan 2018 14:50:59 GMT"                             |
| localeDate | "1/9/2018"                                                  |
| localeTime | "9:50:59 AM"                                                |
| locale     | "1/9/2018, 9:50:59 AM"                                      |
| millis     | "1515509459368"                                             |
| unix       | "1515509459"                                                |

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
