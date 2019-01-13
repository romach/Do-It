## Use cases

- **[UC-1]** as user I want to see all my To-Do-s ordered by creation time from earlier to later
- **[UC-2]** as user I want to create to-do items with text description

## Requariments

- **[R-1]** list To-Do-s ordered by creation time from earlier to later. Parent - [UC-1]

- **[R-2]** add new To-do item. Parent - [UC-2]
	- **[R-2-1]** input field for To-do item's title. Parent - [UC-2]
	- **[R-2-2]** "Add" button for item creation. Parent - [UC-2]
	- **[R-2-3]** update To-Do list after adding new one. Parent - [UC-2]

## Business rules

- **[BR-1]** Maximum length of Todo-item title - 100 symbols
