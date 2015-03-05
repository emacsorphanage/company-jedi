# company-mode completion back-end for Python JEDI

## Installation

`company-jedi` is available on [MELPA](http://melpa.org).

You can install `company-jedi` with the following command.

<kbd>M-x package-install [RET] company-jedi [RET]</kbd>


## Setup

```el
(defun my/python-mode-hook ()
  (add-to-list 'company-backends 'company-jedi))

(add-hook 'python-mode-hook 'my/python-mode-hook)
```
