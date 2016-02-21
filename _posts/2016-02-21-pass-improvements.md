---
layout: post
title: pass improvements
---
These are things I think pass, the standard unix password manager, needs
improving on. Maybe I'll fix them some day.

- When using pass edit, don't just store the file in plaintext format on
  /dev/shm. Anyone can read it there. Maybe use <a
  href="http://www.vim.org/scripts/script.php?script_id=3645">this</a> plugin?

- Also, add the option to let the user define security settings for their
  preferred editor
