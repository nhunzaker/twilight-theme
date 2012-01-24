# Yet another Twilight Theme

Yes I know. However I could never find one I particularly liked, so I modified the wonderful 
[Django Theme by Andrzej Sliwa](https://github.com/andrzejsliwa/django-theme.el)

## Get Started

`git clone git@github.com:nhunzaker/twilight-theme.git`

Set the proper configuration in your init file. Here's how I do it:

``` lisp
;; Twilight Theme
(add-to-list 'load-path "~/.emacs.d/themes/twilight")
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/twilight")

;; Enable the following theme:
(load-theme 'twilight)
```