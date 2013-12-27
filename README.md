scrobbler
====
**scrobbler** is a script written on Perl. It sends information (scrobbles) about music files from specified directory with specified interval in background. That is it imitates a music player.
## Usage
    Usage ./scrobbler.pl -u <user> -p <password> -d <directory_or_file> [-t delay] [--help]
    -u <user>           - your login on last.fm
    -p <password>       - your password on last.fm
    -d <directory>      - path to directory with mp3 files to scrobble. 
                          You can specify a signle file
    -t <delay>          - an interval. Default value is 60 seconds
