## Audio Video Converter

* Author: Rainer Brell

## Functionality

The *Audio Video Converter* saves and converts a YouTube video or a multimedia link from within a browser into MP3 or MP4 format. It can also save the subtitles of a YouTube video as text.

If you are on a YouTube page in your browser, the YouTube video will be saved in the desired format without advertisements. This also works if ads are still playing at the beginning.

A one‑hour YouTube video can be saved as an MP3 in about 2 minutes. This depends on the performance of the computer.

Once the conversion command has been activated, the browser can be closed. The process continues running in the background, which is indicated by sounds.

At the same time, a text file containing a description is created for each YouTube video. It may contain useful information. The text file can be read with the Windows Editor. Creating this file can be adjusted in the settings.

If you are not on YouTube, the addon checks whether you are on a link that points to a multimedia file. If this is the case, the target is saved accordingly and converted into the desired format.

During conversion, a quiet notification sound is played so you know that the process is still running. This sound can be disabled in the settings.

The results are saved in a dedicated folder, which you can open with a single shortcut key. The folder can be adjusted in the NVDA settings.

Channels or playlists are not automatically saved in full. This behavior can be configured in the NVDA menu.

It is now also possible to extract the subtitles of a YouTube video as text — even for foreign languages.

Example: Your language is Spanish and you are playing a YouTube video in Italian. Press **NVDA+Alt+Y**, and the addon will attempt to save the spoken content as Spanish text. This does not always work, as it depends on many technical factors that I cannot influence. The target language can be set in the NVDA menu.

### Shortcut keys

* **NVDA+Y** – Converts to MP3  
* **NVDA+Shift+Y** – Converts to MP4  
* **NVDA+Alt+Y** – Saves subtitles as text, if possible  
* **NVDA+Ctrl+Y** – Opens the folder containing the results

## Supported formats

These audio and video formats are recognized and converted into the desired format when you are on a multimedia link with one of the following extensions:

aac, avi, flac, mkv, m3u8, m4a, m4s, m4v, mpg, mov, mp2, mp3, mp4, mpeg, mpegts, ogg, ogv, oga, ts, vob, wav, webm, wmv, f4v, flv, swf, avchd, 3gp

## Changes up to version 2026.01.24

* “Speak when needed” works  
* Background components are updated automatically  
* More logging to provide better assistance in case of problems  
* Subtitle saving added  
* Subtitle language selection added  
* Playlists and channels are no longer loaded completely by default; can be configured in the NVDA menu  
* Translation into Arabic and Finnish

## Changes in version 2024.04.27

* Works only with Windows 64‑bit for technical reasons  
* Now works again in Firefox  
* Hosted on GitHub and available in the NVDA Store  
* The results folder can be adjusted in the NVDA settings  
* Settings are now saved reliably  
* Localization in Turkish, Polish, Italian, French, Spanish, Vietnamese, Ukrainian, and Portuguese

## Acknowledgements

Thanks to all helpers who took the time to translate my addon and provide feedback.