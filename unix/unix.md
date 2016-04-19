## fast grep
```bash
find . -type f | parallel -k -j150% -n 1000 -m grep -H -n STRING {}
```
Where `STRING` is the needle in the haystack.

Taken originally from https://stackoverflow.com/questions/9066609/fastest-possible-grep
