# Node-RED Contrib json2csv

[Node-RED](http://nodered.org) wrapper to the jsonexport npm module. This
allows for conversion of a json input into a csv file, without needing to
specify the column headers. The headers are populated automatically, making
this node simple to use for JSON data that is generated by apps or read from
databases.

## Install

Run the following command in the root directory of your Node-RED install:

````
    npm install node-red-contrib-json2csv
````

## Usage

### Input
Set msg.payload to a json stream buffer. The file inject from node-red-contrib-browser-utils works well as input to this node.

### Output
msg.payload will be a csv string.


## Contributing
For simple typos and fixes please just raise an issue pointing out our mistakes. If you need to raise a pull request please read our [contribution guidelines](https://github.com/ibm-early-programs/node-red-contrib-json2csv/blob/master/CONTRIBUTING.md) before doing so.
## Copyright and license

Copyright 2017 IBM Corp. under the Apache 2.0 license.
