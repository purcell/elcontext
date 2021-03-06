![img](./title.png)

> Bring your editing experience to the next level with context-based actions for emacs


# Installation

```emacs-lisp
(add-to-list 'load-path "path-to-elcontext")
(require 'elcontext)
(elcontext-global-mode)
```


# Usage

Use `M-x elcontext` for on overview of all contexts. Within this overview several hydras will guide through the API, press `?` to open the help hydra.

Contexts can consist of a

-   name,
-   location (only for macOS),
-   timespan,
-   directory,
-   and action.

![img](./screenshot.png)

If any part of a context is omitted it part is always valid e.g. no location means anywhere, no time means anytime. Each command is triggered once per day.


# Use Cases


### Work / Home development environment

Start all work applications when you're in the office, stop them when you're home (and start others). This was the initial reason to create `elcontext`. It integrates well with [prodigy](https://github.com/rejeep/prodigy.el). You can define all applications you need at work or home as prodigy-services.


### Add yours!

If your using `elcontext` I am happy to hear about your use cases!
