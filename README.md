# <p align="center" width="100%"> <img src="./logo.png" width="250" height="250"> </p>

# <p align="center" width="100%"> Swagger macooa OIH Connector </p>

## Description

[![Generic badge](https://img.shields.io/badge/Status-NotTested!-lightgrey.svg)](https://shields.io/)

A generated OIH connector for the Swagger macooa API (version 1.0.0).

Generated from: https://macooa.com/restapi/v1<br/>
Generated at: 2021-05-18T13:46:09+02:00

## Authorization

API Token

## Actions

:exclamation: Please note: All DELETE actions have been removed from the component.json, but kept in the lib folder for reference. They were auto-generated, but are not expected to work with the current version (21.0.1) of the framework. :exclamation:

### create a new person for given tenant

_Tags:_ `person`

### update an existing person

_Tags:_ `person`

### deactivate an existing person

_Tags:_ `person`

### Find person by Id

> Returns a single person<br/>

_Tags:_ `person`

#### Input Parameters

- `Id` - _required_ - ID of person to return<br/>

### create a new organisation for given tenant

_Tags:_ `organisation`

### update an existing organisation

_Tags:_ `organisation`

### deactivate an existing organisation

_Tags:_ `organisation`

### Find organisation by Id

> Returns a single organisation<br/>

_Tags:_ `organisation`

#### Input Parameters

- `Id` - _required_ - ID of organisation to return<br/>

### create a new contact assigned to an organisation

> create a contact assigned to an organisation<br/>

_Tags:_ `contact`

### update an existing contact

_Tags:_ `contact`

### deactivate an existing contact

_Tags:_ `contact`

### Find contact by Id

> Returns a single contact<br/>

_Tags:_ `contact`

#### Input Parameters

- `Id` - _required_ - ID of contact to return<br/>

### create a new address assigned to an organisation or person

> create a contact assigned to an organisation or person<br/>

_Tags:_ `address`

### update an existing address

_Tags:_ `address`

### deactivate an existing address

_Tags:_ `address`

### Find address by Id

> Returns a single address<br/>

_Tags:_ `address`

#### Input Parameters

- `Id` - _required_ - ID of address to return<br/>

### create new contactdata assigned to a contact or person

> create a contactdata assigned to a contact or person<br/>

_Tags:_ `contactdata`

### update existing contactdata

_Tags:_ `contactdata`

### deactivate existing contactdata

_Tags:_ `contactdata`

### Find contactdata by Id

> Returns contactdata<br/>

_Tags:_ `contactdata`

#### Input Parameters

- `Id` - _required_ - ID of contactdata to return<br/>

## License

: macooa-component<br/>
<br/>

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
