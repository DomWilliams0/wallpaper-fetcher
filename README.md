# wallpaper-fetcher
Fetches random wallpapers from wallhaven.cc

## Install
Install with either

`sudo sh -c "$(wget https://raw.githubusercontent.com/DomWilliams0/wallpaper-fetcher/master/install.sh -O -)"`

or

`sudo sh -c "$(curl -fsSL https://raw.githubusercontent.com/DomWilliams0/wallpaper-fetcher/master/install.sh)"`

## Usage
<pre>
usage: wallpaper-fetcher.py [-h] [-n N] [-d OUT_DIR] [--url URL] [--no-feh]
                           [--local] [--timeout TIMEOUT] [--feh-args ...]

  -h, --help         show this help message and exit
  -n N               The number of wallpapers to download and set
  -d OUT_DIR         The directory to save downloaded wallpapers to
  --url URL          The wallhaven URL to steal wallpapers from
  --no-feh           If given, just print the wallpaper paths, otherwise call
                     feh with --bg-fill. If feh is not installed, then this is
                     assumed to be true
  --local            If given, local images from the output directory are
                     used, instead of downloading new ones
  --timeout TIMEOUT  Sets the socket timeout in seconds
  --feh-args ...     Optional arguments to pass to feh. Anything after this
                     will be passed to feh.Note that you can override the
                     default --bg-fill by specifying another optionin this
                     parameter list
</pre>
  
## TODO
- ~~Parameter passthrough for feh~~
- ~~Allow finer control over feh (--bg-fill etc.)~~
- Control over category/resolution search
