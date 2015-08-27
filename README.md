# company-mode completion back-end for Python JEDI [![melpa badge][melpa-badge]][melpa-link] [![melpa stable badge][melpa-stable-badge]][melpa-stable-link]

## Installation

`company-jedi` is available on [MELPA](http://melpa.org).

You can install `company-jedi` with the following command.

<kbd>M-x package-install [RET] company-jedi [RET]</kbd>

**Please do not install jedi package for company users, it is an [auto-complete](https://github.com/auto-complete/auto-complete) plugin of jedi**


## Setup

```el
(defun my/python-mode-hook ()
  (add-to-list 'company-backends 'company-jedi))

(add-hook 'python-mode-hook 'my/python-mode-hook)
```

[melpa-link]: http://melpa.org/#/company-jedi
[melpa-stable-link]: http://stable.melpa.org/#/company-jedi
[melpa-badge]: http://melpa.org/packages/company-jedi-badge.svg
[melpa-stable-badge]: http://stable.melpa.org/packages/company-jedi-badge.svg
