---
banner: "![[dashboardimage.jpg]]"
---
---
cssclass: dashboard
banner: "![[dashboardimage.jpg]]"
banner_y: 0.33708
---

# TODOS
```dataview
TASK 
FROM !#TEMPLATE
WHERE !completed
SORT file.mtime asc
```

# Vault Info

- 🗄️ Recent file updates

`$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(4).file.link)`

- 〽️ Stats
	* File Count: `$=dv.pages().length`
		- Fleeting Notes: `$=dv.pages('"Fleeting"').length`
		- Hub Notes: `$=dv.pages('"Hub"').length`
		- Literature Notes: `$=dv.pages('"Literature"').length`
		- Permanent Notes: `$=dv.pages('"Permanent"').length`

- 🔖 Tagged: favorite

	locations: `$=dv.list(dv.pages('#favorite').sort(f=>f.file.name,"desc").limit(2).file.link)`
- 🔖 Tagged: favorite
	subjects: `$=dv.list(dv.pages('#correctness').sort(f=>f.file.name,"desc").limit(2).file.link)`

# Family
- [[Family Calendar]]
- [[Guest list]]

- 👨‍👩‍👦 Objectives

	- [[Yearly Budget]]

# Trackers
- ```tracker
searchType: frontmatter
searchTarget: bloodp_hi, bloodp_lo, heart_beat
folder: Fleeting/Diary
datasetName: bloodp_hi, bloodp_lo, heart_beat
fixedScale: 0.5
startDate: 2023-07-07
line:
	title: Blood Pressure and Heart Beat (Y)
	yAxisLabel: Hi
	yAxisLocation: left, right
	yAxisLabel: bloodp_hi (R), bloodp_lo (G)
	lineColor: red, green, yellow 
	xAxisLabel: Date  

- ```tracker
searchType: frontmatter
searchTarget: mood, pomodoros
folder: Fleeting/Diary
datasetName: pomodoros, mood
fixedScale: 0.5
line:
	title: Mood & Pomodoros
	lineColor: yellow, red
	yAxisLabel: MOOD
	xAxisLabel: Date
	yAxisLocation: left, right
	yAxisLabel: mood, pomodoros
	showLegend: True```
- ```tracker
searchType: frontmatter
searchTarget: weight
folder: Fleeting/Diary
datasetName: weight
fixedScale: 0.5
line:
	title: Weight
	yAxisLabel: Weight
	xAxisLabel: Date


# Work

- 💼 Projects

- [[Tracking Usage]]

- [[Data Backup]]

- [[Asset Deployment]]

- [[Education Plan]]
