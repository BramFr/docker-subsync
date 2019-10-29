# docker-subsync
docker version of https://github.com/sc0ty/subsync


Examples:\
docker run -ti -v /mnt/nfs/:/mnt/nfs/ bramfr/docker-subsync

For help ouput use:\
docker run -ti -v /mnt/nfs/:/mnt/nfs/ bramfr/docker-subsync -h

Single sync example:\
docker run -ti -v /mnt/nfs/:/mnt/nfs/ bramfr/docker-subsync --verbose 3 sync --sub /path/to/serie/serie.en.srt --ref /path/to/serie/serie.mkv --out /path/to/serie/serie.en2.srt