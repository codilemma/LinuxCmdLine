| Wildcard | Meaning |
| -------- | ------- |
| * | Matches any characters|
| ? | Matches any single character|
| [characters] | Matches any character that is a emeber of the set *characters* |
| [!characters] | Matches any character that is NOT a member of the set *characters* |
| [[:class:]] | matches any character that is a member of the specified class|
| Character | classMeaning |
| [:alnum:] | Matches any alphanumeric character |
| [:alpha:] | Matches any alphabetic character |
| [:digit:] | Matches any numeral |
| [:lower:] | Matches any lowercase letter |
| [:upper:] | Matches any uppercase letter |
| Examples | Wildcard Examples |
| * | All files |
| g* | Any file beinning with *g* |
| b*.txt | Any file beginning with *b* followed by any charcters and ending with *.txt* |
| *Data???* | Any file beginning with *Data* followed by exactly three characters |
| [abc]* | Any file beginning with either an 
a, b, or c |
| BACKUP.[0-9][0-9][0-9] | Any file beginning with BACKUP. followed by exactly three numerals |
| [[:upper:]]* | any file beginning wiht an uppercase letter
| [![:digital:]] | Any file not beginning with a numeral |
| *[[:lower:]123] | Any file ending with a lowercase letter or the numberals 1, 2, or 3 |
