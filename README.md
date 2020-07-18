# Notice

This package is obsolete because there is a better alternative in Emacs 26 and later.

Emacs 26 officially provides the `display-line-numbers` function to show the line numbers and you can use the `line-number-current-line`
 face to highlight the current line number.
They show the better performance than `linum-mode` and `hlinum-mode`.


# hlinum-mode

This library extends linum-mode to highlight current line number.
It requires Emacs 24.4 or later.

To use this package, add these lines to your .emacs file:
```elisp
    (require 'hlinum)
    (hlinum-activate)
```

And by using `M-x linum-mode`, you can see line numbers with highlighting current line number.

You can customize the color of highlighting current line by changing `linum-highlight-face`. By default, hlinum highlights current line only in the active buffer. To highlight current line in all buffers, change `linum-highlight-in-all-buffersp` to `t`.
