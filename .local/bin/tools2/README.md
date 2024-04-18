# MARS tools

These scripts are part of a collection inspired by [Luke Smith's voidrice repository](https://github.com/LukeSmithxyz/voidrice), with modifications and additions. They serve various purposes, enhancing file management, providing command-line utilities, managing web and RSS tasks, configuring system settings, and offering miscellaneous functionalities.

# Scripts and Descriptions

## File Management

| <div style="width:135px">Script</div> | <div style="width:665px">Description</div>                                                          |
|---------------------------------------|-----------------------------------------------------------------------------------------------------|
| **booksplit**                         | Split audio based on timecodes and add metadata.                                                    |
| **ext**                               | Automatically extracts archived content based on extension.                                         |
| **getcomproot**                       | A helper script for LaTeX/groff files used by `compiler` and `opout`.                               |
| **linkhandler**                       | Handles URLs/files: images (sxiv), videos (mpv), downloads music/PDFs, opens web links.             |
| **opout**                             | A general handler for opening a file's intended output, useful in vim and vifm.                     |
| **rotdir**                            | SXIV script for cycling through images in a directory.                                              |

## Command-line Utilities

| <div style="width:135px">Script</div> | <div style="width:665px">Description</div>                                                          |
|---------------------------------------|-----------------------------------------------------------------------------------------------------|
| **calc**                              | Opens a simple command-line terminal.                                                               |
| **compiler**                          | Compiles or runs finishing operations on a document, can be executed via vim.                       |
| **getkeys**                           | Prints the hotkeys for programs like ncmpcpp, mutt, sxiv etc.                                       |
| **pacupgrade**                        | Synchronizes and updates all packages from the AUR before refreshing the user's session.            |
| **sd**                                | Opens a terminal in the current working directory.                                                  |

## Web and RSS

| <div style="width:135px">Script</div> | <div style="width:665px">Description</div>                                                          |
|---------------------------------------|-----------------------------------------------------------------------------------------------------|
| **qandl**                             | Newsboat script for downloading YouTube videos.                                                     |
| **queueandnotify**                    | Newsboat script for reading and downloading queued YouTube videos using qandl.                      |
| **rssadd**                            | Newsboat script for adding RSS feed URLs.                                                           |

## System Configuration

| <div style="width:135px">Script</div> | <div style="width:665px">Description</div>                                                          |
|---------------------------------------|-----------------------------------------------------------------------------------------------------|
| **ifinstalled**                       | Checks if the dependent package is installed, otherwise sending a notification to the user.         |
| **remaps**                            | Startup script for remapping super, escape and capslock keys.                                       |
| **setbg**                             | Sets the wallpaper, generating a new color scheme if `wal` is installed.                            |
| **shortcuts**                         | Loads shell configurations, aliases, and mappings.                                                  |

## Miscellaneous

| <div style="width:135px">Script</div> | <div style="width:665px">Description</div>                                                          |
|---------------------------------------|-----------------------------------------------------------------------------------------------------|
| **tag**                               | Uses ffmpeg to tag media files with artist, title, album, track, release date and genre.            |
| **weather**                           | Displays precipitation chance, daily low/high, and the moon's phase.                                |

