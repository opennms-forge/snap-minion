# snap-minion
Repository with a proof-of-concept to build a Snap package for a Minion

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/opennms-minion)

## Build with snapcraft

I had the most reliable results using [snapcraft running in docker](https://hub.docker.com/r/opennms/snapcraft/tags).

I've set an alias for `snapcraft` with:

```bash
alias snapcraft='docker run --rm -v $(pwd):/build -w /build opennms/snapcraft:18 snapcraft'
```

Now you can run all the `snapcraft` commands within the `snap-minion` directory.
