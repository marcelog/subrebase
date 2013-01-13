# About

This is a useful tool to "rebase" a video subtitle an amount of seconds "up"
or "down". If you've just found the right subtitles for a video but they seem
to be out of sync with the audio, this might be useful to you.

# How to use it

This tool accepts 3 arguments, in order:

 * Amount of seconds to add or substract from each subtitle.
 * Input .srt file.
 * Output .srt file.

## Positive offsets
    subrebase 8 my_substitle.srt my_subtitle_rebased.srt

## Negative offsets
    subrebase -8 my_substitle.srt my_subtitle_rebased.srt

