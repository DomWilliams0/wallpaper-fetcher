# wallpaper-fetcher
Fetches random wallpapers from wallhaven.cc

## Usage
<pre>usage: fetch_wallpapers.py [-h] [-n N] [-d OUT_DIR] [--url URL] [--no-feh] [--local] [--timeout TIMEOUT]

  -h, --help         show this help message and exit
  -n N               The number of wallpapers to download and set
  -d OUT_DIR         The directory to save downloaded wallpapers to
  --url URL          The wallhaven URL to steal wallpapers from
  --no-feh           If given, just print the wallpaper paths, otherwise call feh with --bg-fill. If feh is not installed, then this is assumed to be true
  --local            If given, local images from the output directory are
                     used, instead of downloading new ones
  --timeout TIMEOUT  Sets the socket timeout in seconds</pre>
  
## TODO
X Parameter passthrough for feh
- Allow finer control over feh (--bg-fill etc.)
- Control over category/resolution search
