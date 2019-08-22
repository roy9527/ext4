# Ext4-学习笔记

From [https://www.kernel.org/doc/html/latest/filesystems/ext4/overview.html](https://www.kernel.org/doc/html/latest/filesystems/ext4/overview.html)  

This document attempts to describe the on-disk format for ext4 filesystems. The same general ideas should apply to ext2/3 filesystems as well, though they do not support all the features that ext4 supports, and the fields will be shorter.

NOTE: This is a work in progress, based on notes that the author (djwong) made while picking apart a filesystem by hand. The data structure definitions should be current as of Linux 4.18 and e2fsprogs-1.44. All comments and corrections are welcome, since there is undoubtedly plenty of lore that might not be reflected in freshly created demonstration filesystems.

