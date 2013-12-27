Last.fm scrobbler on perl.
This script just sends info to last.fm of random track from directory you point.
Nothing else.
:>
## Usage
Usage ./scrobbler.pl -u <user> -p <password> -d <directory_or_file> [-t timeout] [--help]
The script scrobbles random file from the directory (it may use a single file)
with a specified interval.
-u <user>           - your login on last.fm
-p <password>       - your password on last.fm
-d <directory>      - path to directory with mp3 files to scrobble. 
                      You can specify a signle file
-t <delay>          - an interval. Default value is 60 seconds
