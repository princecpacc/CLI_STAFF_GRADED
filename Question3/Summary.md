## Creating the Question3 workspace

I created the required folder structure to store the report, screenshots, and summary for this experiment.

## Command: echo ... > original.txt

This command created a text file named `original.txt` and stored sample content in it for the link analysis experiment.

## Command: ln

The `ln` command created a hard link that points to the same inode as the original file.

## Command: ln -s

The `ln -s` command created a symbolic link that stores the pathname of the original file.

## Command: ls -li

The `ls -li` command displays inode numbers and file details. The original file and hard link share the same inode, while the symbolic link has a different inode.

## Command: stat

The `stat` command displays metadata such as inode number, size, permissions, timestamps, and ownership for each file.

## Command: rm original.txt

Deleting the original file removes one directory entry. The hard link still works because it points to the same inode, while the symbolic link becomes invalid because its target no longer exists.
