# rEFInd config

> My config for the [rEFInd Boot Manager](http://www.rodsbooks.com/refind/).

# Install instructions

Download and extract the [zip](http://www.rodsbooks.com/refind/getting.html).

```bash
cd refind-bin-0.10.1
./refind-install
```

Mount volume in Mac OS X

```bash
sudo mkdir /Volumes/ESP; sudo mount -t msdos /dev/disk0s1 /Volumes/ESP
```

Go to config location

```bash
cd /Volumes/ESP/EFI/refind/
```

Replace `refind.conf` and install theme.

# Theme

[Minimalistic rEFInd theme](https://github.com/EvanPurkhiser/rEFInd-minimal)

# License

MIT
