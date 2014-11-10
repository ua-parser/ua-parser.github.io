---
layout: default
---

What is `ua-parser`?
--------------------

`ua-parser` is an open-source and community-driven, regexp-based user-agent parser. It has been ported to many different programming languages all of which share the same parser.

Structure
---------

`ua-parser` now has [its own GitHub org][org] which contains:

* [`uap-core`][uap-core]: This is the core parser shared by all language ports. Also contains the test suite.
* [`uap-ref-impl`][uap-ref-impl]: A reference implementation written for node.js.
* [`ua-parser.github.io`][website-repo]: The repository for this website. It also doubles as the home of this project where all meta issues are filed.

A number of language ports are also hosted within this org:

* list of ports goes here
* …

Communication channels
-----------------------

* irc (#ua-parser on freenode) <irc://chat.freenode.net#ua-parser>
* [mailing list](https://groups.google.com/forum/#!forum/ua-parser)
* [Meta-issues](https://github.com/ua-parser/ua-parser.github.io/issues)

Contributing
------------

All contributions are welcomed.

To contributing to a given language port, check its contributing guidelines.

To contribute to the core parser, test suite or simply report news user agent strings, please refer to the uap-core's [contributors' guide](https://github.com/ua-parser/uap-core/blob/master/CONTRIBUTING.md).


FAQ
---

### A user agent string isn't parsed properly, what do I do?

Try parsing it [here][onlineparser]. This should run the latest parser. If that doesn't work, you found a bug (or a new browser). [File an issue!][uap-core-issues]

[onlineparser]: #todo
[uap-core-issues]: https://github.com/ua-parser/uap-core/issues
[uap-core]: https://github.com/ua-parser/uap-core/
[website-repo]: https://github.com/ua-parser/ua-parser.github.io/
[uap-ref-impl]: https://github.com/ua-parser/uap-ref-impl/
[org]: https://github.com/ua-parser/