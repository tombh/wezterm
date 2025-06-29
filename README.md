# Tattoy Fork of Wez's Terminal

Patched crates (and published):
* `wezterm-surface`
* `wezterm-termwiz`
* `wezterm-term` ("patched" only because of its dependency on `wezterm-termwiz` and `wezterm-surface`)

Manually published crates (not patched):
* `wezterm-char-props`
* `wezterm-color-types`
* `wezterm-dynamic`
* `wezterm-input-types`
* `wezterm-escape-parser`
* `wezterm-cell`

> [!IMPORTANT]  
> All these Tattoy-based crates should be namespaced to `tattoy-` for publishing.
