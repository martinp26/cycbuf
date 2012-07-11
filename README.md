Cycle amongst buffers in Emacs.

To install with maramalade:

`M-x package-install cycbuf`

You can then:

`M-x cycbuf-init`

or you could add a post init hook to do that to your `init.el`:

`(add-hook 'after-init-hook 'cycbuf-init)`

The keys, which are defined in `cycbuf-init` are:

`meta right         cycbuf-switch-to-next-buffer`

`meta left          cycbuf-switch-to-previous-buffer`

`meta super right   cycbuf-switch-to-next-buffer-no-timeout`

`meta super left    cycbuf-switch-to-previous-buffer-no-timeout`

