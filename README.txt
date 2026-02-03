====================================
VP6 to MP4 Converter - README
====================================

This project provides a simple Windows batch tool
for converting VP6 video files into MP4 format
using FFmpeg.

It is designed mainly for extracting and converting
legacy game videos for editing and uploading.

------------------------------------
Requirements
------------------------------------

- Windows 10 / 11 (64-bit)
- FFmpeg (included in the Tools folder)
- .vp6 video files

------------------------------------
Tool Used
------------------------------------

FFmpeg is used for all video conversion.

Location:
Tools\ffmpeg-2026-02-02-git-7e9fe341df-full_build\bin\ffmpeg.exe

------------------------------------
How To Use
------------------------------------

1. Put your .vp6 files in the ".Bat files" folder
2. Double-click "VP6 to mp4.bat"
3. Wait for the conversion to finish
4. Find your .mp4 files in the "Converted" folder

------------------------------------
Output
------------------------------------

- Format: MP4
- Video Codec: H.264
- Audio Codec: AAC
- Quality: High

Original files are not modified.

------------------------------------
Troubleshooting
------------------------------------

If conversion fails:

- Check that ffmpeg.exe exists
- Check file locations
- Make sure filenames use standard characters
- Try running as Administrator

------------------------------------
Documentation
------------------------------------

- README.txt   - Main guide
- DIRECTORY.txt - Folder layout
- SUPPORT.txt  - Support and fixes

------------------------------------
Author
------------------------------------

Created by RETR0

====================================
