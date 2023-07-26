
```tracker
searchType: fileMeta
searchTarget: numWords
folder: Fleeting/Diary
line:
	title: Word Counter
	yAxisLabel: Words
	lineColor: red
```


## Across all of this Directory

```tracker
searchType: fileMeta
searchTarget: numWords
folder: Fleeting/Diary
summary:
	template: 'Total number of words: {{sum()}}'
```

# For the Fleeting directory
```tracker
searchType: fileMeta
searchTarget: numWords
folder: Fleeting
line:
	title: Word Counter
	yAxisLabel: Words
	lineColor: blue
```


## Across all of this Directory

```tracker
searchType: fileMeta
searchTarget: numWords
folder: Fleeting
summary:
	template: 'Total number of words: {{sum()}}'
```