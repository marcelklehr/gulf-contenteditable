# gulf-contenteditable
Convenient wrapper for contenteditable elements.

## Install

```
npm install gulf-contenteditable
```

## Usage

```
var bindEditor = require('gulf-contenteditable')

var editable = document.querySelecor('#doc[contenteditable]')
var doc = bindEditor(editable)
```

## API
### bindEditor(editable:DOMElement, [storageAdapter])
  * `editable` -- a contenteditable Element to be wired up with gulf
  * `storageAdapter` -- a gulf storage adapter (optional; defaults to the in-memory Adapter)
  * *returns* the `gulf.EditableDocument` (see http://github.com/marcelklehr/gulf#readme)


## Legal
(c) 2015 by Marcel Klehr

GNU General Public License