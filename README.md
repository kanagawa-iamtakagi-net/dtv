# dtv

## Images
- [Chinachu/Mirakurun](https://github.com/Chinachu/Mirakurun)
    - [yude/Mirakurun](https://github.com/yude/Mirakurun)
        - [kanagawa-iamtakagi-net/Mirakurun](https://github.com/kanagawa-iamtakagi-net/Mirakurun)
- [l3tnun/EPGStation](https://github.com/l3tnun/EPGStation)
    - [kanagawa-iamtakagi-net/EPGStation](https://github.com/kanagawa-iamtakagi-net/EPGStation)
- [tsukumijima/KonomiTV](https://github.com/tsukumijima/KonomiTV)
    - [kanagawa-iamtakagi-net/KonomiTV](https://github.com/kanagawa-iamtakagi-net/KonomiTV)
- [mariadb](https://hub.docker.com/_/mariadb)

## References
- [l3tnun/docker-mirakurun-epgstation](https://github.com/l3tnun/docker-mirakurun-epgstation)
- [yude/EPGS-to-Discord-v2](https://github.com/yude/EPGS-to-Discord-v2)
- [nns779/px4_drv](https://github.com/nns779/px4_drv)

## Notes
- Mirakurun 起動時、Entrypoint (`container-init.sh`) 呼び出し時に `Unexpected token "export"` 等のエラーが発生する場合、`chmod +x container-init.sh` 等で権限を付与してから、コンテナを立ち上げると成功する場合があります。

## LICENSE
MIT License.