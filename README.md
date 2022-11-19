# goto-last-point

A minor-mode to record and jump to the last point in the buffer.

Chris Done created the original
https://github.com/chrisdone/emacs-config/blob/master/packages/goto-last-point/goto-last-point.el.
This is only a polished version for MELPA.

## Setup

`goto-last-point` is available on MELPA. You can easily install and configure it
with https://github.com/jwiegley/use-package:

```
(use-package goto-last-point
  :ensure t
  :demand t
  :bind ("C-<" . goto-last-point)
  :config (goto-last-point-mode))
```
