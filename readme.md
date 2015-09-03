# Restreamer project #
## Libraries ##
* ffmpeg (https://www.ffmpeg.org)
* nginx (http://nginx.org)
* nginx-rtmp-module (https://github.com/arut/nginx-rtmp-module)

## How to launch restreamer ##

```
#!bash

./restreamer -i(or --input) input-url(or file) -n(or --name) output-name
./restreamer -i http://vevoplaylist-live.hls.adaptive.level3.net/vevo/ch1/06/prog_index.m3u8 -n test
```