# CTS Annotation

The [table](./table_keys_values.md) shows the values for the keys:

* urn_cts
* urn_cts_author
* urn_cts_work
* urn_cts_edition
* author
* title
* cts

For example, the values for `urn_cts`, `urn_cts_author`, `urn_cts_work`,
`urn_cts_edition`, `author`, and `title`
for the work with CTS URN `phi0588.abo014.perseus-lat2` are, respectively,
`phi0588.abo014.perseus-lat2`, `phi0588`, `abo014`, `perseus-lat2`, `Nepos, Cornelius`,
and `Datames` (check it
in the [table](./table_keys_values.md)).

## CTS URN

The metadata concerning CTS URNs (including author names and work titles)
were retrieved automatically from the
texts. This means that their values may contain
inconsistencies and errors, which can also be found
in the [table](./table_keys_values.md).

The field `cts` refers to a passage inside a work. In the
[table](./table_keys_values.md), the column `cts` tries to provide
a summary of all admissible values: for example, `1-2_1-8` means
that the text has two main divisions (`_` identifies them)
and that the ranges for them are
1-2 and 1-8, respectively. Therefore, a sound query could be `cts=1_7`.

The values found in the column `cts` are sometimes a (long) list, if
the range for a specific division does not consist of pure numbers.
More in general, inconsistencies and errors are present since the
original texts sometimes provide slightly different CTS URN
implementations.
