This is need to be run in terminal so that some custom terminal word can be used later from my terminal.

i used ```& disown``` so that if i close my terminal app it will not shut down my running app.


The Below Text is just for a simple example,
Run The Below Content to just run in the terminal.



```



(cat << 'EOF' && cat ~/.bashrc) > ~/.bashrc.tmp && mv ~/.bashrc.tmp ~/.bashrc

# This is for my favourite terminal shortcut i used
alias 3_apps='brave-browser & ~/.apps_and_softwares/Telegram/Telegram & code & exit'
alias 3='brave-browser & ~/.apps_and_softwares/Telegram/Telegram & code & exit'

# this below is for github
alias github='brave-browser https://github.com/RanaUniverse?tab=repositories & disown && exit'
alias g='brave-browser https://github.com/RanaUniverse?tab=repositories & disown && exit'

# For YouTube full and short
alias youtube='brave-browser https://www.youtube.com/ & disown && exit'
alias y='brave-browser https://www.youtube.com/ & disown && exit'

# For ChatGPT full and short
alias chatgpt='brave-browser https://chatgpt.com/ & disown && exit'
alias c='brave-browser https://chatgpt.com/ & disown && exit'

EOF



```
