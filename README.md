# rEFInd config

My config for [rEFInd Boot Manager](http://www.rodsbooks.com/refind/)].

# Install instructions

Download and extract the zip file from [here](http://www.rodsbooks.com/refind/getting.html).

```bash
cd refind-bin-0.10.1
./refind-install
```

Mounting volume in Mac OS X

```bash
sudo mkdir /Volumes/ESP; sudo mount -t msdos /dev/disk0s1 /Volumes/ESP
```

Config location

```bash
/Volumes/ESP/EFI/refind/
```

# Theme

[Minimalistic rEFInd theme](https://github.com/EvanPurkhiser/rEFInd-minimal)

# License

MIT
