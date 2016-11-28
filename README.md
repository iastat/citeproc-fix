This repo documents a fix for using pandoc-citeproc with the isuthesis document class.

As you can see [here](https://github.com/iastat/citeproc-fix/commit/2ff5f6be771e26945a52461b21b765518387a548#diff-16f0118e110c279d8b2289542da1c30aL340), the default output of citeproc produces way too large `\vbox`, resulting in incorrect page breaking in the bibliography.

The current "fix" is to insert explicit line breaks between each reference as is done [here](https://github.com/iastat/citeproc-fix/commit/2ff5f6be771e26945a52461b21b765518387a548#diff-74fa2632841970e47d9329457732ee0aR17)
