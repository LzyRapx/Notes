### terminator的配色：
```
sudo vim ~/.config/terminator/config
```
建议第一个：
```
[global_config]
  handle_size = -3
  enabled_plugins = CustomCommandsMenu, LaunchpadCodeURLHandler, APTURLHandler, LaunchpadBugURLHandler
  title_transmit_fg_color = "#000000"
  suppress_multiple_term_dialog = True
  title_transmit_bg_color = "#3e3838"
  inactive_color_offset = 1.0
[keybindings]
[profiles]
  [[default]]
    palette = "#000000:#5a8e1c:#2d5f5f:#cdcd00:#1e90ff:#cd00cd:#00cdcd:#e5e5e5:#4c4c4c:#868e09:#00ff00:#ffff00:#4682b4:#ff00ff:#00ffff:#ffffff"
    background_image = ""
    background_darkness = 0.90
    scrollback_lines = 3000
    background_type = transparent
    use_system_font = False
    scroll_background = False
    show_titlebar = False
    cursor_shape = ibeam
    font = Liberation Mono 12
    background_color = "#0e2424"
    foreground_color = "#e8e8e8"
[layouts]
  [[default]]
    [[[child1]]]
      type = Terminal
      parent = window0
      profile = default
    [[[window0]]]
      type = Window
      parent = ""
      size = 925, 570
[plugins]
```
***
```
[global_config]
  title_transmit_bg_color = "#d30102"
  focus = system
  suppress_multiple_term_dialog = True
[keybindings]
[profiles]
  [[default]]
    palette = "#2d2d2d:#f2777a:#99cc99:#ffcc66:#6699cc:#cc99cc:#66cccc:#d3d0c8:#747369:#f2777a:#99cc99:#ffcc66:#6699cc:#cc99cc:#66cccc:#f2f0ec"
    background_color = "#2D2D2D" # 背景颜色
    background_image = None   
    background_darkness = 0.85 
    cursor_color = "#2D2D2D" # 光标颜色
    cursor_blink = True # 光标是否闪烁
    foreground_color = "#EEE9E9" # 文字的颜色
    use_system_font = False # 是否启用系统字体
    font = Ubuntu Mono 13  # 字体设置，后面的数字表示字体大小
    copy_on_selection = True # 选择文本时同时将数据拷贝到剪切板中
    show_titlebar = False # 不显示标题栏，也就是 terminator 中那个默认的红色的标题栏
[layouts]
  [[default]]
    [[[child1]]]
      type = Terminal
      parent = window0
      profile = default
    [[[window0]]]
      type = Window
      parent = ""
[plugins]
```
```
[global_config]
  title_transmit_bg_color = "#d30102"
  focus = system
[keybindings]
[profiles]
  [[default]]
    # solarized-dark
    #palette = "#073642:#dc322f:#859900:#b58900:#268bd2:#d33682:#2aa198:#eee8d5:#002b36:#cb4b16:#586e75:#657b83:#839496:#6c71c4:#93a1a1:#fdf6e3"
    #foreground_color = "#eee8d5"
    #background_color = "#002b36"
    #cursor_color = "#eee8d5"

  [[solarized-dark]]
    palette = "#073642:#dc322f:#859900:#b58900:#268bd2:#d33682:#2aa198:#eee8d5:#002b36:#cb4b16:#586e75:#657b83:#839496:#6c71c4:#93a1a1:#fdf6e3"
    foreground_color = "#eee8d5"
    background_color = "#002b36"
    cursor_color = "#eee8d5"

  [[solarized-light]]
    palette = "#073642:#dc322f:#859900:#b58900:#268bd2:#d33682:#2aa198:#eee8d5:#002b36:#cb4b16:#586e75:#657b83:#839496:#6c71c4:#93a1a1:#fdf6e3"
    background_color = "#eee8d5"
    foreground_color = "#002b36"
    cursor_color = "#002b36"

[layouts]
  [[default]]
    [[[child1]]]
      type = Terminal
      parent = window0
      profile = solarized-dark
    [[[window0]]]
      type = Window
      parent = ""
[plugins]
```
