The Front-End Prototype of the OpenPPRN
============
View this prototype live at demo.openpprn.org

This is the front-end programming prototype for the OpenPPRN.
While it serves as a prototype, this is written in haml and sass, using bootstrap, and so could be eventual production code.

This codebase should remain as a static prototype, separate from the main dynamic application codebase. This makes it so changes to the front-end can be demonstrated quickly and in isolation without fear of messing up the functionality of the production application. This approach keeps the prototype code simple, fast, and without the burdens of dealing with integrating with model/controller code.

This code is using the Middleman framework (http://middlemanapp.com/). Middleman is a static website generator, and in this configuration is using haml, and sass, and layouts to generate a prototype of the production OpenPPRN app.

Current Status
---
This prototype is currently about ready for high level review by the Sleep Apnea and CCFA PPRN. It's not intended to currently be a mandate for development.

Required Assets
---
The "Required Assets" file keeps a running list of non-engineering contributions that will be required to get this codebase up and running. Things like images, copy (text), design decisions, and human resources.

Contributors
---
The main contributor to this codebase is Sean Ahrens.
