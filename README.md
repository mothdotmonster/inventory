# inventory

Move files like an old text adventure.

***

USAGE:

To list files in your inventory, use `inventory`.

To pick up a file, use `take (file)`.

To drop a file, use `drop (file)`.

By default, `inventory` uses `~/.inventory` to store files. To change this, set the `INVDIR` environment variable to the desired directory.

If you need to delete a file in your inventory, just drop it first, and then delete it with `rm`.

You can only pick up or drop one file at a time, as doing more would be too greedy.