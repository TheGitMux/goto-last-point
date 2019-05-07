# goto-last-point

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

A minor-mode to record and jump to the last point in the buffer.

Chris Done created the original
[goto-last-point](https://github.com/chrisdone/emacs-config/blob/master/packages/goto-last-point/goto-last-point.el).
This is only a polished version for MELPA.

## Setup

`goto-last-point` is not available on MELPA yet. You can easily install and
configure it with [use-package](https://github.com/jwiegley/use-package):

``` emacs-lisp
(use-package goto-last-point
  :load-path "path/to/goto-last-point"
  :bind ("C-x C-x" . goto-last-point)
  :config (goto-last-point-mode))
```
