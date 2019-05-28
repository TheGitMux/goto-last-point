# goto-last-point

[![License: GPL
v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![MELPA](https://melpa.org/packages/goto-last-point-badge.svg)](https://melpa.org/#/goto-last-point)

A minor-mode to record and jump to the last point in the buffer.

Chris Done created the original
[goto-last-point](https://github.com/chrisdone/emacs-config/blob/master/packages/goto-last-point/goto-last-point.el).
This is only a polished version for MELPA.

## Setup

`goto-last-point` is available on MELPA. You can easily install and configure it
with [use-package](https://github.com/jwiegley/use-package):

``` emacs-lisp
(use-package goto-last-point
  :ensure t
  :config (progn
            (setq goto-last-point-max-length 10)
            (bind-key "C-<" #'goto-last-point)
            (goto-last-point-mode)))
```
