# APIWrappers
> Wrappers for various APIs, in various programming languages.

The goal of this project is to build API wrappers for
a multitude of service APIs from imgur, dropbox, and discord,
to transaction networks like Visa and Mastercard, and bulk 
information extraction from government sites, surveys
sites and lots more.

> Note: there are probably existing libraries for all of
the wrappers here so consider using those unless
the wrappers in this repository interest you, or if you'd
like to contribute

## Contents

1. [What to Expect](#what-to-expect)
2. [Wrapper Documentation](#wrapper-documentation)
3. [Contribution](#contribution)

## What to Expect

* We would like to include multiple implementations such as:
    * Websocket wrappers for back and forth communication
    * Send a request and capture the response
* Ability to access the API without creating entire requests
and instead pass configurable data to a function for that
request.
* Functions to perform complex tasks outlined by the API
documentation.
* Functions to perform other complex tasks related to
various use cases. For example:
    * Listing content of dropbox folder
    * Looping through elements and performing actions
    * Other functionalities present in the UI for the
service with said API.

## Wrapper Documentation

Documentation for wrappers can be found in their
respective folders (./README.md). Documentation for
the entirety of the APIWrappers repository can be found
on the repository (wiki)[#]

## Contribution

Feel free to improve code in any way but:

* Don't change the wrappers input or output functionality
unless the reason is significant. Keep improvements
within the wrapper.
* If you make any major changes or additions, make sure
to give yourself credit at the top of the file(s) in the
header comment block.


