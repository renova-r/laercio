# laercio 1.0.1.9001

Renova release, based on CRAN laercio 1.0-1 (archived on CRAN 2022-03-06).

- `NAMESPACE`: `importFrom("stats", "pchisq", "qtukey")` and `importFrom("utils", "read.table")` added.
- `DESCRIPTION`: `Title` in title case without the trailing period; `Description` reworded to describe the three tests without starting with `The package` (metadata only).
- `DESCRIPTION`: `Author` replaced by `Authors@R` for the same single author and maintainer (metadata only).
- `DESCRIPTION`: stale optional `Date` field removed (metadata only).

Release preparation:

- `DESCRIPTION`: `Version` set to `1.0.1.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL version 3 text) was added; the `License` field is unchanged.
- `README.md` was added and is excluded from the R build.
- `NEWS.md` was added and is excluded from the R build.
