# option.toml
```toml

[
  {
    "patchName": "Custom branding",
    "options": [ 
      { "key": "appName", "value": "YomaruExt" },
      { "key": "iconPath", "value": "revanced-magisk-module/icons" } 
    ]
 }
]
        

```

# config.toml
```toml
logging-to-file = true        # enables logging of every patch process to a seperate file
enable-magisk-update = false   # set this to false if you do not want to receive updates for the module in magisk app

# add 'enabled = false' for not patching a specific app or remove it from the config
# see https://github.com/j-hc/revanced-magisk-module/blob/main/CONFIG.md for more detailed explanations

# [YouTube]
# build-mode = "apk"                                                   # 'both', 'apk' or 'module'
# excluded-patches = ""                                                 # space-seperated patches to exclude (multiline strings are not supported)
# included-patches = ""                                                 # space-seperated patches to include (non-excluded patches are included by default)
# version = "auto"                                                      # 'auto', 'latest', 'beta' or a custom one like '17.40.41'
# apkmirror-dlurl = "https://www.apkmirror.com/apk/google-inc/youtube/"
#
# [Spotify]
# enabled = true
# uptodown-dlurl = "https://spotify.en.uptodown.com/android"
#
# [YouTube-Extended] # unmaintained
# enabled = false
# app-name = "YouTube"
# patches-source = "inotia00/revanced-patches"
# integrations-source = "inotia00/revanced-integrations"
# cli-source = "inotia00/revanced-cli"
# rv-brand = "ReVanced Extended"
# build-mode = "both"
# apkmirror-dlurl = "https://www.apkmirror.com/apk/google-inc/youtube/"
# [YouTube]
# apkmirror-dlurl = "https://apkmirror.com/apk/google-inc/youtube/"
# version = "latest"
# included-patches = "remove-player-controls-background"

# my change

[YouTube]
apkmirror-dlurl = "https://apkmirror.com/apk/google-inc/youtube/"
version = "latest"
included-patches = "remove-player-controls-background"


````

