# Video-Debanding
Quick script for debanding or fixing artificial bands / stepping artifacts in video where it should be smooth gradients (lighting, shadows).

Download: https://github.com/pftq/Video-Debanding/releases/tag/20261102<br>
You may also find these useful (one-click to download all [here](https://drive.google.com/drive/folders/1nvQFC5uwsZlf-82LuskCP-qut9xHw-lt?usp=sharing)):\
• [Video Compare](https://github.com/pftq/Video-Compare) (to check export errors, differences, etc)\
• [MP4 Audio Delay Fix](https://github.com/pftq/MP4-Audio-Delay-Fix) (20ms delay at start of file)\
• [Video Frame Sync](https://github.com/pftq/Video-Frame-Sync) (syncing 2 files that drift out of sync)\
• [Video Color Match](https://github.com/pftq/VideoColorMatch) (correcting color grading drift)\
• [Screencaps Generator](https://github.com/pftq/Screencaps-Generator) (smart screencaps selection + gallery grid sheet)\
• [Video Splicer](https://github.com/pftq/Video-Splicer) (trim or join MP4s without re-encoding)

The functionality is primarily from FFMPEG, which this sits on top of as a UI you can drag/drop videos onto.

<img width="1320" height="440" alt="image" src="https://github.com/user-attachments/assets/afb8ef4e-0151-49a0-b24c-2867067412e5" />

Credits:
- Python, application runtime
- Tcl/Tk, user interface
- FFmpeg, video decoding, debanding, and encoding
- PyInstaller, Windows executable packaging
