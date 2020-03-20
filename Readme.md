# Collection of resources for app development

## Unicode Symbols

The [unicode.csv](unicode.csv) file contains a table of Unicode 6 characters sorted by their `Code`. It contains 32k lines, 5 columns, weighs 250Kb compressed and 2.2 Mb uncompressed.

* The `SubCategory` column contains the 2 character official Sub-category of character. [docs](https://www.fileformat.info/info/unicode/category/index.htm)
* The `Block` column contains the official name of contiguous code-range. [docs](https://www.fileformat.info/info/unicode/block/index.htm)
* The `Name` column contains the official names of the characters written with `CAPITAL CASE`. They are relatively descriptive and can be used to group and match characters. 
* The `Group` column contains grouping of `Code`s by their topic (often matches with `Block`).

## TODO

- Merge Emoticons into [unicode.csv](unicode.csv).
-	Map modern geographical regions to every `Block`.
