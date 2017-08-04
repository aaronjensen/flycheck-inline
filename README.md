# flycheck-inline

Display flycheck error message with inline popup style.

# Screenshots

![Screenshot](screenshot.png)

# Setup

If you use `use-package`.

```elisp
(use-package flycheck-inline
  :ensure t
  :defer t
  :init
  (add-hook 'flycheck-mode-hook 'flycheck-inline-enable))
```
