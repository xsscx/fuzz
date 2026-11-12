# ICC Signature Word Lists

These lists provide ICC tag-signature inputs for fuzzing ICC profile parsers
and related tools that accept word lists. Use them as seeds or mutation
dictionaries; entries are provided one per line.

- `icc-tag-signatures-iccdev-named.txt` contains singleton signatures with
  named iccDEV enum definitions.
- `icc-tag-signatures-private-generic.txt` contains singleton signatures
  retained through the generic/private path.
- `icc-tag-signatures-reserved-ranges.txt` expands registered reservation
  ranges into individual entries, including hexadecimal values.

Trailing spaces in some singleton signatures are part of their four-byte
values. Preserve them when copying or processing these lists.

\n