javascript-react.tmbundle
=========================

Textmate Bundle for JSX (React). Currently allows

* Basic syntax highlighting
* Compile/check on save (via jsxhint/jsx)

Requires

* [react-tools](https://www.npmjs.org/package/react-tools)
* [jsxhint](https://www.npmjs.org/package/jsxhint)

Borrows heavily from [textmate/html.tmbundle](https://github.com/textmate/html.tmbundle) and [textmate/javascript.tmbundle](https://github.com/textmate/javascript.tmbundle).

Installation
------------

Clone the bundle to `Library/Application Support/Avian/Pristine Copy/Bundles/`:

```
git clone https://github.com/jjeising/javascript-react.tmbundle.git
```

To use compile on save install the following dependencies

```
npm install react-tools jsxhint
```

Compile on save
---------------

If you manage and compile files with other tools you can disable the command via *Edit Bundles…* > *JavaScript React* > *Menu Actions* > *Compile JSX* and uncheck *Enable this item*.


License
-------

Release under The MIT License (MIT), Copyright (c) 2014 Jannes Jeising
