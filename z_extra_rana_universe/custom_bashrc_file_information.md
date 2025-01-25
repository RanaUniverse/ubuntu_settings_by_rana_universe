This is need to be run in terminal so that some custom terminal word can be used later from my terminal.

i used ```& disown``` so that if i close my terminal app it will not shut down my running app.


The Below Text is just for a simple example,

```
(cat << 'EOF' && cat ~/.bashrc) > ~/.bashrc.tmp && mv ~/.bashrc.tmp ~/.bashrc

# This is for my favourite terminal shortcut i used
alias 3_apps='brave & ~/.apps_and_softwares/Telegram/Telegram & code & exit'
alias 3='brave & ~/.apps_and_softwares/Telegram/Telegram & code & exit'

# this below is for github
alias github='brave https://github.com/RanaUniverse?tab=repositories & disown && exit'
alias g='brave https://github.com/RanaUniverse?tab=repositories & disown && exit'

# For YouTube full and short
alias youtube='brave https://www.youtube.com/ & disown && exit'
alias y='brave https://www.youtube.com/ & disown && exit'

# For ChatGPT full and short
alias chatgpt='brave https://chatgpt.com/ & disown && exit'
alias c='brave https://chatgpt.com/ & disown && exit'

EOF
```
