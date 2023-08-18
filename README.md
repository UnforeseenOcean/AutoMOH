# AutoMOH
Convert any WAV/MP3 file into crappy call center-quality music

# Requirements
- `ffmpeg` with at least `libopus` and `libmp3lame` codecs enabled
- `opusdec` present inside the folder or in the path variable

# How to use
1. Prepare a music file at around 70~80% volume in a format `ffmpeg` supports
2. Drag and drop the file onto the script
3. Wait for the window to disappear
4. Your finished track will be inside the folder where the script is, named the same as your original file
5. You're done!

Note: You can delete the remaining files, or examine them individually for your essay on the process. This is why the script does not delete the temporary files until you run it again.

To make it clean up everything after it's done, simply copy the `del` section onto the end of the script.
