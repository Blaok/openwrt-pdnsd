# pdnsd for OpenWRT

At OpenWRT SDK root or build root:

```
pushd package
git clone https://github.com/Blaok/openwrt-pdnsd.git
popd
scripts/feeds install -d m pdnsd
make package/pdnsd/compile
```

Package should appear at `bin/${arch}/packages/base`.
