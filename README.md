# nenv

Creates new chroot environment easily.

Uses Alpine chroot distro.

## How to use

### Create new chroot

```sh
nenv $new_chroot
chroot $new_chroot
```

### Delete created nenv chroot

```sh
rm -rf $old_chroot
```

## How to install

### Do something similar

```sh
git clone https://github.com/wmartinmimi/nenv
cd nenv && chmod 700 nenv
echo "alias nenv=$(pwd)/nenv" >> ~/.bashrc
```

## License

Licensed under ```Unlicense License```
