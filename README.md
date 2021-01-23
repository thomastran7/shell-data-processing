# Shell Data Processing Cheat Sheet

## Powershell
- ni: creates a new empty item
```
ni file_name.txt
```

## Bash

- mkdir: creates new folder
```
mkdir folder_name
```

- cd: change directory
```
cd
cd ..
```

- ls: list the contents of the current directory
```
ls
ls -l
ls -a
```
- Sort numeric
```
-n
```
- Sort reverse
```
-r
```

- Bash redirect (>): redirects contents of your directory into a file
```
ls > file.txt
```

- Bash redirect & appened (>>): appends rather than overwrite
```
ls >> file.txt
```

- curl: getting data from a url
```
curl "url_link"
curl "url_link" -o url.txt
``` 
- Transform each space '' into a return character
```
tr ' ' '\12' < returnedfile
```

- Pipe the output to sort 
```
tr ' ' '\12' < returnedfile | sort
```

- Pipe the sorted output to uniq -c to count
```
tr ' ' '\12' < returnedfile | sort | uniq -c
```

- Pipe the reduced output to sort with the -nr flag
```
tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr
```

- Redirect the output to result.txt
```
tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr > result.txt
```
 

