- **staple**: Combines many image files into one PDF. Requires convert (from
  ImageMagick) and ghostscript.
- **vcompile**: Combines many videos from youtube-dl compatible URLs into one
  video. Requires ffmpeg, and ffmpeg-normalize. ffmpeg must have been compiled
  with `--enable-libfreetype`.
- **cigs**: Collect .gitignore style files in the current directory, given a
  filename. Outputs each line of each .ignore file prepended with the
  appropriate relative paths.
- **cited**: Prints the cite keys of a given bibfile which are not used in the
  given text file.
