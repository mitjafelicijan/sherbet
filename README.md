# A theme inspired by sorbet

It's mostly the same as `sorbet` theme with couple of tweaks:

- No background
- Status line is light gray
- Cursor line is very light gray

![Preview](https://github.com/user-attachments/assets/60e12740-899a-4fcf-916d-aa417a34b3f3)

These are the changes made to `sorbet` theme.

```vimrc
hi Normal guibg=NONE ctermbg=NONE
hi StatusLine ctermfg=245 ctermbg=235 cterm=none
hi StatusLineNC ctermfg=245 ctermbg=none cterm=none
hi CursorLine cterm=none ctermbg=233 ctermfg=none
```

