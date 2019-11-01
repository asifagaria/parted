# parted

> parted -a optimal /dev/sdb

> mklabel gpt

Type Y

> mkpart primary ext4 0% 100%

> print

> quit

> mkfs.ext4 /dev/sdb1
