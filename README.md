# company-mode completion back-end for Python JEDI

## Installation

## Setup

```el
(defun my/python-mode-hook ()
  (add-to-list 'company-backends 'company-jedi))

(add-hook 'python-mode-hook 'my/python-mode-hook)
```
