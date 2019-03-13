## Features

| #    | Title      | Since |
| ---- | ---------- | ----- |
| TDL  | To-do list | 0.1   |



## Use cases

| #        | Description                                                  | Status     | Since |
| -------- | ------------------------------------------------------------ | ---------- | ----- |
| UC-TDL-1 | As user I want to see all my To-Do-s ordered by creation time from new to old | developing | 0.1   |
| UC-TDL-1 | As user I want to create to-do items with text description (**title**)  | developing | 0.1   |

## Requirements

| #         | Description                                                  | UC #     | Type        | Task # | PR   | Discussion links | Code links | Status     | Parent | Child | Since |
| --------- | ------------------------------------------------------------ | -------- | ----------- | ------ | ---- | ---------------- | ---------- | ---------- | ------ | ----- | ----- |
| R-TDL-1   | List To-Do-s ordered by creation time from new to old        | UC-TDL-1 | functional  |        |      |                  |            | developing |        |       | 0.1   |
| R-TDL-2   | Add new to-do item with text description                     | UC-TDL-2 | functional  |        |      |                  |            | developing |        |       | 0.1   |
| R-TDL-2-1 | Input field for To-do item's title with hint: "To-do description" | UC-TDL-2 | UI          |        |      |                  |            | developing |        |       | 0.1   |
| R-TDL-2-2 | "Add" button for item creation                               | UC-TDL-2 | UI          |        |      |                  |            | developing |        |       | 0.1   |
| R-TDL-2-3 | After adding new one: Update To-Do list, Empty Input field   | UC-TDL-2 | UX          |        |      |                  |            | developing |        |       | 0.1   |
| R-TDL-2-4 | Maximum length of Todo-item title - 50 symbols               | UC-TDL-2 | restriction |        |      |                  |            | developing |        |       | 0.1   |
| R-TDL-2-5 | Minimum length of Todo-item title - 1 symbol                 | UC-TDL-2 | restriction |        |      |                  |            | developing |        |       | 0.1   |
| R-TDL-2-6 | When trimmed todo-item title < 1 symbol - show red label under input "Minimum length of Todo-item title - 1 symbol" | UC-TDL-2 | UX          |        |      |                  |            | developing |        |       | 0.1   |
| R-TDL-2-7 | When trimmed todo-item title > 50 symbols - show red label under input "Maximum length of Todo-item title - 50 symbols" | UC-TDL-2 | UX          |        |      |                  |            | developing |        |       | 0.1   |
| R-TDL-2-8 | On error while adding new todo item show popup "Unable to add new To-do item" | UC-TDL-2 | UX          |        |      |                  |            | developing |        |       | 0.1   |
| R-TDL-2-9 | On error while adding new todo item return exception: "{'text':'Unable to add new To-do item'}" | UC-TDL-2 | exceptions  |        |      |                  |            | developing |        |       | 0.1   |