This repo documents a fix for using pandoc-citeproc with the isuthesis document class.

As you can see [here](https://github.com/iastat/citeproc-fix/commit/2ff5f6be771e26945a52461b21b765518387a548#diff-16f0118e110c279d8b2289542da1c30aL340), the default output of citeproc produces way too large `\vbox`, resulting in incorrect page breaking in the bibliography.

The current "fix" is to insert explicit line breaks between each reference as is done [here](https://github.com/iastat/citeproc-fix/blob/08f10506ebadda7b22391e1fab07b7130068980a/MRE/bib-test.tex#L10-L13)
