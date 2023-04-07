# Pioneer DJ File Format support

A handy table of format support taken from the various user manuals

| Model       | Year | MP3 | AAC                | WAV/AIFF*          | FLAC              | Apple Lossless    | Notes                                     |
|-------------|------|-----|--------------------|-------------------|-------------------|-------------------|-------------------------------------------|
| CDJ-3000    | 2020 | All | up to 48kHz/16-bit | up to 96kHz/24-bit| up to 96kHz/24-bit| up to 96kHz/24-bit|                                           |
| CDJ-2000NXS2| 2016 | All | up to 48kHz/16-bit | up to 96kHz/24-bit| up to 96kHz/24-bit| up to 96kHz/24-bit|                                           |
| CDJ-TOUR1   | 2016 | All | up to 48kHz/16-bit | up to 96kHz/24-bit| up to 96kHz/24-bit| up to 96kHz/24-bit|                                           |
| CDJ-2000NXS | 2012 | All | up to 48kHz/16-bit | up to 48kHz/24-bit| N/A               | N/A               |                                           |
| CDJ-900NXS  | 2013 | All | up to 48kHz/16-bit | up to 48kHz/24-bit| N/A               | N/A               |                                           |
| CDJ-2000    | 2009 | All | up to 48kHz/16-bit | up to 48kHz/24-bit| N/A               | N/A               |                                           |
| CDJ-900     | 2009 | All | up to 48kHz/16-bit | up to 48kHz/24-bit| N/A               | N/A               |                                           |
| XDJ-1000MK2 | 2016 | All | up to 48kHz/16-bit | up to 48kHz/24-bit| up to 48kHz/24-bit| up to 48kHz/24-bit|                                           |
| XDJ-700     | 2015 | All | up to 48kHz/16-bit | up to 48kHz/24-bit| N/A               | N/A               |                                           |
| XDJ-1000    | 2014 | All | up to 48kHz/16-bit | up to 48kHz/24-bit| N/A               | N/A               |                                           |
| OPUS-QUAD   | 2023 | All | up to 48kHz/16-bit | up to 96kHz/24-bit| up to 96kHz/24-bit| up to 96kHz/24-bit|                                           |
| XDJ-XZ      | 2019 | All | up to 48kHz/16-bit | up to 48kHz/24-bit| up to 48kHz/24-bit| N/A               | FLAC support added in 2019 FW update       |
| XDJ-RX3     | 2021 | All | up to 48kHz/16-bit | up to 48kHz/24-bit| up to 48kHz/24-bit| N/A               |                                           |
| XDJ-RR      | 2018 | All | up to 48kHz/16-bit | up to 48kHz/24-bit| N/A               | N/A               |                                           |
| XDJ-RX2     | 2017 | All | up to 48kHz/16-bit | up to 48kHz/24-bit| N/A               | N/A               |                                           |
| XDJ-RX2  | 2017 | All | up to 48kHz/16-bit  | up to 48kHz/24-bit | N/A       | N/A            |       |
| XDJ-RX   | 2015 | All | up to 48kHz/16-bit  | up to 48kHz/24-bit | N/A       | N/A            |       |
| XDJ-R1   | 2013 | All | up to 48kHz/16-bit  | up to 48kHz/24-bit | N/A       | N/A            |       |
| XDJ-AERO | 2012 | All | up to 48kHz/16-bit  | up to 48kHz/24-bit | N/A       | N/A            |       |

* WAV/AIFF Issues:

All players up to and including CDJ-3000 may have issues playing some WAV files which should otherwise be supported. The issue may be more prevalent on outdated (pre-2022) firmware. As always keep your firmware up to date to get the most out of your Pioneer DJ equipment!

Source: https://www.reddit.com/r/DJs/comments/kb36z9/a_tool_to_fix_compatibility_issues_with_wav_files/

tl;dr…

“I always had issues with Pioneer CDJ's not playing some regular wav files (even on the new CDJ-3000!!) and I know lots of people who've had the same experience. It baffled me why I can't play a 48kHz/24-bit file on a player that clearly supports it.”  

…  

“The actual issue with these WAV files and CDJ's is due to a (often hidden) property embedded into the wav's metadata called WAV_EXTENSIBLE. It's meant to add support for things like multi-channel audio, speaker mappings, etc. It is also used in common wav files, like the hi-res tracks downloaded from Bandcamp- and this is the source of the issue. CDJ's read these files and go 'nope,' despite otherwise being compatible.”"
