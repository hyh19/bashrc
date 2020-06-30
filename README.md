# Bash 环境配置

```bash
mkdir $HOME/.bashrc.d && \
(echo; echo "for i in \$(ls \$HOME/.bashrc.d/*); do source \$i; done"; echo) >> $HOME/.bashrc
```

```bash
echo 'if [ -f ~/.bashrc ]; then . ~/.bashrc; fi' >> ~/.bash_profile
```
