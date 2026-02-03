# VP6 to MP4 Converter

A simple Windows batch tool for converting `.vp6` video files into high-quality `.mp4` format using FFmpeg.

This project is designed for easy, one-click conversion with an organised folder structure and clear documentation.

---

## 📌 Features

- Batch converts multiple `.vp6` files at once
- Uses FFmpeg (H.264 + AAC) for high-quality output
- Automatically saves files to a Converted folder
- Keeps original files safe
- Beginner-friendly setup
- Includes full documentation and support files

---

## 📁 Project Structure

See `DIRECTORY.txt` for the full folder layout.

---

## ⚙️ Requirements

- Windows PC
- FFmpeg (included in the Tools folder)
- `.vp6` video files

---

## 🚀 How to Use

1. Download or clone this repository
2. Place your `.vp6` files in the `.Bat files` folder
3. Double-click `VP6 to mp4.bat`
4. Wait for the process to finish
5. Find your converted files in the `Converted` folder

---

## 🎥 Output Settings

The converter uses the following settings by default:

- Video Codec: H.264 (libx264)
- Audio Codec: AAC
- Quality: CRF 18 (High)
- Preset: Slow (Better Quality)

These settings balance quality and file size.

---

## 🛠️ Troubleshooting

### FFmpeg Not Found
Make sure `ffmpeg.exe` exists in the Tools folder and has not been moved.

### No Files Converted
Check that your `.vp6` files are in the same folder as the batch file.

### Low Quality
Upscaling cannot improve low-quality source videos. Results depend on the original file.

### No Audio
Some VP6 files do not contain audio. Check FFmpeg output for warnings.

---

## 📄 Documentation

Additional files included:

- `README.txt` – Basic usage guide
- `DIRECTORY.txt` – Folder structure
- `SUPPORT.txt` – Help and troubleshooting

---

## 👤 Author

Created by **RETR0**

---

## ⚠️ Disclaimer

This tool is provided "as is" with no warranty.  
Always keep backups of your original files before converting.

---

## ⭐ Contributing

Suggestions and improvements are welcome.  
Feel free to fork this repository and submit pull requests.
