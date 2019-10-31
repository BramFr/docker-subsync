# docker-subsync
docker version of https://github.com/sc0ty/subsync

With -v options you have to determine the volume (path) of series/movies

Examples:\
docker run -ti -v /mnt/nfs/:/mnt/nfs/ bramfr/docker-subsync

For help ouput use:\
docker run -ti -v /mnt/nfs/:/mnt/nfs/ bramfr/docker-subsync -h

Single sync example:\
docker run -ti -v /mnt/nfs/:/mnt/nfs/ bramfr/docker-subsync sync --sub /path/to/serie/serie.en.srt --ref /path/to/serie/serie.mkv --out /path/to/serie/serie.en2.srt
