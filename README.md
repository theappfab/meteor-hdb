# meteor-hdb

# Introduction
This is a wrapper around the NPM package hdb. The version of hdb used is 0.4.1.

The npm hdb module provides a server side connection to a SAP HANA in-memory database. For further information, please refer to [the original npm documentation.](http://https://www.npmjs.com/package/hdb)

Currently, cloud based SAP HANA trial servers (for testing, i.e. no commercial use) are [provided for free.](http://scn.sap.com/docs/DOC-31722)

You will either need such a free account or a commercial installation to make use of this package.

# Installation

 `meteor add theappfab:hdb`

# Usage
The package provides server side access to SAP HANA in memory databases. As opposed to the built in Meteor Mongo DB mechanism, the HANA DB will not be replicated on the client side. A reasonable approach involves queries to the HANA DB to receive result sets. These results can then be inserted in the Mongo DB and made available for further analysis and drill down of the data on the client side.

# Status
This package is in trial stage and not recommended for any production use.

# License
The wrapper is licensed under the MIT license - use as you like, also for commercial purposes. Any use is at your own risk.

The original npm module is licensed under the Apache 2 license, please refer to the respective site for further information.
