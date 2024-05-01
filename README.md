
## Dependencias

### Polybar

you need to install polybar

Arch Linux
```
sudo pacman -S polybar
```

Ubuntu Debian
```
sudo apt install polybar
```

### Nerd Fonts
This theme uses JetBrains MonoNL font to display icons.  

・download  
https://www.nerdfonts.com/font-downloads

・cheat-sheet  
https://www.nerdfonts.com/cheat-sheet

## Usage
```
cp config.ini ~/.config/polybar/
polybar &
```

```
# start polybar
polybar &

#  OR start polybar select monitor & reload option
MONITOR=HDMI-A-1 polybar --reload mybar &

# stop bolybar
killall -q polybar
```

## Style

![image](https://github.com/yuuki-fuji/polybar/assets/68770062/1086e69a-b6e4-4b1f-80d9-3350d605cc71)
