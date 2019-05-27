# Docker version of [vcflib](https://github.com/vcflib/vcflib)

Collection of Docker files to build different vcflib versions.
Indicative usage:

```
docker run -ti --rm \
    -v /my/full/local/vcf/path:/path/in/container \
    hybridstat/vcflib:1.0.0-rc2 \
    vcfuniq /path/in/container/my.vcf > /path/in/container/my.uniq.vcf
```
