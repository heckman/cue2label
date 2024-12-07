# cue2label

Given a .cue sheet prints an audacity labels file to standard out.

## Usage

```
cue2label < foo.cue > foo.labels
```

## Dependencies

This implementation of _cue2labels_
is an _awk_ script,
so it requires _awk_.
It has been lightly tested with `awk version 20200816`,
included in MacOS Sequoia.
It should work just fine with other flavours of _awk_.

## Configuration

Modify the `label_name` function
to chanage the naming scheme of the tracks.
There's an example there that should show you how.
As it is, the track title is used.

## Feedback

Please let me know if you find this useful,
or if you've found an edge case
that mucks things up.
If there are any escaped characters in the titles
there could be trouble.
