App::JYJ
========

Convert JSON to YAML to JSON to...

## Synopsis

```
$ cat file.json | jyj             # YAML
$ cat file.json | jyj | jyj       # JSON
$ cat file.json | jyj | jyj |jyj  # YAML
```

## Description

This module installs a commandline tool called `jyj`.

It reads stdin.

If it looks like JSON, it print the YAML dump of the JSON decode.

If it looks like YAML, it print the JSON encode of the YAML load.

That's it.

## Author

Ingy döt Net <ingy@cpan.org>

## Copyright and License

Copyright 2022. Ingy döt Net.

This program is free software; you can redistribute it and/or modify it under
the same terms as Perl itself.
