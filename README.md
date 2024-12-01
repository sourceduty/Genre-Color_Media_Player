https://github.com/user-attachments/assets/6b93c427-a661-40e3-9f80-fda3e4fd362d

> Dynamically changing the background color of the application based on the genre of the song being played.
#

Genre-Color Media Player is a Python-based media player designed to enhance your music experience by dynamically changing the background color of the application based on the genre of the song being played. The player uses metadata from audio files (such as MP3 and WAV) to identify the genre and applies a corresponding color theme, making each song feel unique as it plays. For songs that lack metadata, a random color is generated, ensuring that every song, regardless of its metadata status, has a personalized interface.

The player allows users to easily load and play songs from their file system. You can load individual music files or select entire folders to import multiple songs at once. Once the songs are loaded, the user can interact with a clean and straightforward interface that displays the title, genre, artist, and duration of each song in an organized list. The player supports basic music controls, including play, pause, stop, and volume adjustments. All controls are neatly placed for easy access, ensuring a smooth user experience.

In addition to the genre-based color customization, the application includes a logo display at the top of the window, along with the program title, "Genre-Color Media Player." The program is built using Python's Tkinter for the graphical user interface, pygame for music playback, and mutagen to read metadata from audio files. This lightweight and visually engaging media player is perfect for anyone who enjoys listening to music with a colorful and interactive interface.

#
### VLC Plugin Concept

To transform the Genre-Color Media Player into a VLC plugin, you would need to integrate it with the VLC media player’s plugin architecture, which is based on C or C++ with Lua scripting support. By leveraging VLC’s extensive plugin system, you could create a Lua script or a native extension that communicates with the core VLC application. The plugin would access VLC’s playback engine, retrieve metadata for the currently playing song, and modify the GUI based on the genre, similar to how the standalone version works. The player could use VLC’s interface to display the song list and dynamically change the background color based on the identified genre, offering users a vibrant, genre-responsive interface while retaining VLC's powerful media playback capabilities. This would combine VLC's advanced features with the visually interactive aspects of the Genre-Color Media Player, making it an enhanced music experience within the VLC ecosystem.

#
![Genre-Color_Media_Player](https://github.com/user-attachments/assets/76cd2481-c888-4521-ba83-d1f99fd50472)

#
### Related Links

[Audio Analyzer](https://github.com/sourceduty/Audio_Analyzer)
<br>
[Guitar Tab Writer](https://github.com/sourceduty/Guitar_Tab_Writer)
<br>
[Song Collab](https://github.com/sourceduty/Song_Collab)
<br>
[Song Logo](https://github.com/sourceduty/Song_Logo)

***
Copyright (C) 2024, Sourceduty - All Rights Reserved.
