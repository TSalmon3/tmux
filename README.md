# TMUX

## Usual Command

* `tmux new -s [session name]`
* `tmux attach -t [target session name]`
* `tmux kill-session -t [target session name]`

## Keybinding

prefix = alt + a

### 1. session

| Operation | Key Conbination |
| :--- | :--- |
|  list all session | \<prefix> + s |
| detach current session | \<prefix> + d |
| rename current session | \<prefix> + $ |

### 2. window

| Operation | Key Conbination |
| :--- | :--- |
| create a new window | \<prefix> + c |
| go to next window | \<prefix> + n |
| go to prev window | \<prefix> + p |
| rename a window | \<prefix> + ,|
| list all window | \<prefix> + w |

### 3. pane

| Operation | Key Conbination |
| :--- | :--- |
| vertical split | \<prefix> + % |
| horizontal split | \<prefix> + " |
| switch to up pane | \<prefix> + j |
| switch to down pane | \<prefix> + k |
| switch to left pane | \<prefix> + h |
| switch to right pane | \<prefix> + l |
| kill current pane | \<prefix> + x |

