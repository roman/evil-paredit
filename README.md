= evil-paredit

This package helps you to not screw up your paredit setup when using evil-mode.

In order to accomplish this whenever you try to use a modifier command
like "d, c, y", to modify the paredit buffer, it will stop you to do
so in the case you break the parity of parenthesis.

== Installation

Install via [el-get](https://github.com/dimitri/el-get/)

== Setup

```elisp
(add-hook 'emacs-lisp-mode-hook 'evil-paredit-mode)
```
