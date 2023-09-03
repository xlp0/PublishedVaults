## Tasks

```
TASK from ""
```

```dataview
TASK from ""
```

```
CALENDAR file.mtime from "Literature/PKM/Tools"
```

```dataview
CALENDAR file.mtime from "Literature/PKM/Tools"
```
```
LIST profession
WHERE type="person"
```
```dataview
LIST profession
WHERE type="person"
```
```
TABLE project 
WHERE project = "Univalent Foundations Program"
```



```dataview
TABLE project 
WHERE project = "Univalent Foundations Program"
```

```
TABLE project, profession
WHERE type = "person"
SORT file.name DESC
```

```dataview
TABLE project, profession
WHERE type = "person"
SORT file.name DESC
```
```
TABLE project, profession
WHERE type = "person" AND contains(profession, "author")
SORT file.time ASC
```
```dataview
TABLE project, profession
WHERE type = "person" AND contains(profession, "author")
SORT file.time ASC
```

Note that contains as a function is case sensitive
```
TABLE File as Page, software, website as WWW, github_repo as GITHUB FROM "Literature/PKM/Tools/Obsidian"
WHERE contains(software, "Software")
```

```dataview
TABLE software, website as WWW, github_repo as GITHUB FROM "Literature/PKM/Tools"
WHERE contains(software, "Software")
```