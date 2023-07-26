---
Aliases: Tracker
---
#tracker #metric #atom

This uses the Obsidian tracker plug-in. 

Examples of the syntax can be found here:[Sample Code Repo](https://github.com/pyrochlore/obsidian-tracker/blob/master/examples/BloodPressureTracker.md)

See more tracked statistics: [[Weight Tracker]], [[Event Tracker]]

```tracker
searchType: frontmatter
searchTarget: tracked
folder: Fleeting/Diary
startDate: 2023-07-11
fixedScale: 1.5
month:
	color: red
	mode: annotation
	annotation: 👍
```


```tracker
searchType: frontmatter
searchTarget: tracked
folder: Fleeting/Diary
startDate: 2023-07-11
summary:
    template: "Longest Streak: {{maxStreak()}} day(s)\nLongest Breaks: {{maxBreaks()}} day(s)\nLast streak: {{currentStreak()}} day(s)"
    
```

## References
[[@fromsergioBuildingUSEFULHabit2022]]

[[@clearAtomicHabitsTiny2018]]
