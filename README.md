# Terminator-Layout

[global_config]
  enabled_plugins = CustomCommandsMenu, TerminalShot, LaunchpadCodeURLHandler, APTURLHandler, Logger, LaunchpadBugURLHandler
  suppress_multiple_term_dialog = True
[keybindings]
[layouts]
  [[default]]
    [[[child0]]]
      fullscreen = False
      last_active_term = ad2af6b1-65fc-46e6-a1ce-04d1e89064b1
      last_active_window = True
      maximised = True
      order = 0
      parent = ""
      position = 65:24
      size = 1301, 744
      title = bash  /home/xxxxx
      type = Window
    [[[child1]]]
      order = 0
      parent = child0
      position = 647
      ratio = 0.499615680246
      type = HPaned
    [[[child2]]]
      order = 0
      parent = child1
      position = 369
      ratio = 0.5
      type = VPaned
    [[[child5]]]
      order = 1
      parent = child1
      position = 369
      ratio = 0.5
      type = VPaned
    [[[terminal3]]]
      command = ssh xxxxx@xxxxxxxx ; bash
      directory = /home/xxxxx
      order = 0
      parent = child2
      profile = default
      type = Terminal
      uuid = ad2af6b1-65fc-46e6-a1ce-04d1e89064b1
    [[[terminal4]]]
      command = ssh xxxxx@xxxxx ; bash
      directory = /home/xxxxx
      order = 1
      parent = child2
      profile = default
      type = Terminal
      uuid = ab52b5cc-3c6e-4aaf-90a0-969466fed015
    [[[terminal6]]]
      command = ssh xxxxx@xxxxxxx ; bash
      directory = /home/xxxxxxx
      order = 0
      parent = child5
      profile = default
      type = Terminal
      uuid = eb32ffd1-637a-42e2-9be0-8f527cd414f9
    [[[terminal7]]]
      command = ssh xxxxxxx@xxxxxxxxx; bash
      directory = /home/xxxxxxx
      order = 1
      parent = child5
      profile = default
      type = Terminal
      uuid = 0a8c4f46-2518-4dd0-b8eb-013767cb18a1
[plugins]
[profiles]
  [[default]]
    background_image = None
    custom_command = /usr/bin/bash
    login_shell = True
    scrollback_infinite = True
    use_custom_command = True
