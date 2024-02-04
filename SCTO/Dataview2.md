````plain
```dataview 
LIST file.ctime
```
````

```dataview 
LIST file.ctime
```

```dataview
LIST
FROM "≡ƒôå Activity"
```


```dataview
TASK
WHERE !completed
LIMIT 10
GROUP BY file.link
SORT rows.file.ctime ASC
```

```dataview
CALENDAR file.mtime
FROM ""
```

```dataview
TASK
```