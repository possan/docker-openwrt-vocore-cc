OpenWRT Buildroot for VoCore (work in progress)

Install image
```
docker pull possan/openwrt-vocore-cc
```

Or build it yourself:
```
make
```

Start build environment
```
docker run -v ~/Projects/myproject:/myproject -t -i possan/openwrt-vocore-cc sudo -iu openwrt bash
```

