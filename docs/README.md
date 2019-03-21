## Terms
* **To-Do item** - task that must be executed by user.
  * **Description** - description of To-Do item.

* **To-Do items list** - several To-Do items.

## Resources

* Todo item

## Features

| #       | Title      | Since |
| ------- | ---------- | ----- |
| **TDL** | To-do list | 0.1   |

## Use cases

| #            | Description                                                  | Status     | Since |
| ------------ | ------------------------------------------------------------ | ---------- | ----- |
| **UC-TDL-1** | As user I want to see my **To-Do items list** ordered by *creation time* from new to old | developing | 0.1   |
| **UC-TDL-1** | As user I want to create **To-Do item** with text **description** | developing | 0.1   |

## Requirements

| #             | Description                                                  | UC #     | Links | Type status            | S           | RelationsParent | Since |
| ------------- | ------------------------------------------------------------ | -------- | ----- | --------------------------- | --------------- | ----- | ----- |
| **R-TDL-1**   | List To-Do-s ordered by creation time from new to old        | UC-TDL-1 |       | functional  | :hammer: |                 | 0.1   |
| **R-TDL-2**   | Add new to-do item with text description                     | UC-TDL-2 |       | functional  | :hammer: |                 | 0.1   |
| **R-TDL-2-1** | Input field for To-do item's title with hint: "To-do description" | UC-TDL-2 |       | UI          | :hammer:  |                 | 0.1   |
| **R-TDL-2-2** | "Add" button for item creation                               | UC-TDL-2 |       | UI          | :hammer:  |                 | 0.1   |
| **R-TDL-2-3** | After adding new one: Update To-Do list, Empty Input field   | UC-TDL-2 |       | UX          | :hammer:  |                 | 0.1   |
| **R-TDL-2-4** | Maximum length of Todo-item title - 50 symbols               | UC-TDL-2 |       | restriction | :hammer: |                 | 0.1   |
| **R-TDL-2-5** | Minimum length of Todo-item title - 1 symbol                 | UC-TDL-2 |       | restriction | :hammer: |                 | 0.1   |
| **R-TDL-2-6** | When trimmed todo-item title < 1 symbol - show red label under input "Minimum length of Todo-item title - 1 symbol" | UC-TDL-2 |       | UX          | :hammer:  |                 | 0.1   |
| **R-TDL-2-7** | When trimmed todo-item title > 50 symbols - show red label under input "Maximum length of Todo-item title - 50 symbols" | UC-TDL-2 |       | UX          | :hammer:  |                 | 0.1   |
| **R-TDL-2-8** | On error while adding new todo item show popup "Unable to add new To-do item" | UC-TDL-2 |       | UX          | :hammer:  |                 | 0.1   |
| **R-TDL-2-9** | On error while adding new todo item return exception: "{'text':'Unable to add new To-do item'}" | UC-TDL-2 |       | exceptions  | :hammer: |                 | 0.1   |

## Requirements template

| #                                 | Description                                                  | UC #                            | Links                                                        | Type and status                                              | Relations                           | Since |
| --------------------------------- | ------------------------------------------------------------ | ------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------------------------- | ----- |
| R-TDL-1<br />*Requirement number* | List To-Do-s ordered by creation time from new to old<br />*Requirement description* | UC-TDL-1<br />*Use-case number* | Task:<br />PR:<br />Discussion:<br />Code: *Link to GitHub search* | **Types**<br />functional - ex.: what data should be fetched and in what order (sorting)<br />architecture - task for improving or changing developing lifecycle<br />UI - user interface<br />restrictions - input values restrictions<br />exceptions - exception messages<br />UX - user interface elements interaction<br />dev-ops:hammer:<br />**Statuses**<br />:heavy_check_mark: active, :heavy_multiplication_x: canceled, :heavy_minus_sign: changed, :hammer: developing | Parent: R-TDL-3<br />Child: R-TDL-4 | 0.1   |
