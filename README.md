prompt-text-el
================

Various Information in Minibuffer Prompt


![ss.png](ss.png)



Overview
--------

Enable global major-mode `prompt-text-mode` to print additional information
always when Emacs asks you something via minibuffer.

You can configure `prompt-text-format` to change the text to print.
This value will be formatted with `format-mode-line`: see docstring of
`mode-line-format` for available expressions.

By default the text includes your login name, hostname, current working
directory and printed in the format like:

    10sr@mba0:~/prompt-text-el


License
-------

This software is unlicensed.
