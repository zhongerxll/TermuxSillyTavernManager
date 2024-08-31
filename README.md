# TermuxSillyTavernManager

A simple script to install SillyTavern in termux

# How to install
```bash
curl -Lo "$PREFIX/bin/TSTM" "$(curl -s --head --connect-timeout 3 http://www.google.com | grep "200" -q || echo "https://mirror.ghproxy.com/")https://raw.githubusercontent.com/zhongerxll/TermuxSillyTavernManager/main/TSTM" && chmod +x "$PREFIX/bin/TSTM"
echo "TSTM" > ~/.bashrc && TSTM
```
