# Small python scripts

## audio-cleaner.py

### Gloal

- [ ] Downloads an audio file if necessary from a server : [youtube](https://www.youtube.com) or (s)ftp
- [ ] Trims scilences at the beginning and ending of the audio file with [ffmpeg](https://github.com/FFmpeg/FFmpeg)
- [ ] Tries to complete metadata with [DiscogsTagger](https://github.com/jesseward/discogstagger)
- [ ] Stores the file in $HOME/user/music/*Artist*/*Album*/*file*
- [ ] Calls the function passed as argument (optionnal) with the final absolute path

### Params

* URI or absolute path
* Optionnal: another function to be called with the absolute path
