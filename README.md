# List Making App

## Basic Premise

Create a console-based list making app. Your program can represent a to-do list, shopping list, packing list, reading list, watch list, or another type of ordered list.

The user should be able to build and manage the list through a simple menu. The focus of this activity is adding items, accessing items by index, removing items, displaying list contents, and using `copy()` to undo the most recent change.

## Basic File Structure

Your starter folder will contain:

```text
basic/
└── main.py
```

## Basic Requirements

* [ ] Begin with an empty list that will store items entered by the user.
* [ ] Repeatedly display a menu that allows the user to **Add an Item**, **Remove an Item**, **Display the List**, **Undo the Previous Change**, or **Exit**.
* [ ] Allow the user to add a new item to the end of the list using `append()`.
* [ ] Allow the user to remove an item by selecting its **index**. Display the list with its indices so the user knows which item to select.
* [ ] Display all current items in the list by traversing the list rather than simply printing the entire list variable.
* [ ] Before adding or removing an item, save an independent copy of the list using `copy()`. The Undo option should restore the list to its state before the most recent change.
* [ ] Allow the user to exit the program through the menu.

> Fully completing the Basic Requirements earns **16/20 marks, or 80%**.

## Basic Assessment — 16 Marks

| Assessment Item | Criteria | Marks |
|---|---|---:|
| Menu and List Setup | Begins with an empty list and provides the required menu options while the program is running. | 2 |
| Adding Items | Accepts an item from the user and correctly adds it to the end of the list. | 3 |
| Removing Items | Displays usable indices and removes the item selected by the user. | 3 |
| Displaying the List | Traverses the list and clearly displays each current item. | 2 |
| Undo | Uses an independent copy of the list to correctly restore its state before the most recent add or remove operation. | 4 |
| Exiting | Allows the user to exit the menu and end the program normally. | 2 |
|  | **Total** | **16** |

## Advanced Premise

Extend your Basic List Making App into a more complete **to-do list**.

Your Advanced program should keep all of the features from the Basic version. You should be able to begin by copying your completed Basic `main.py` into the Advanced folder and building on it.

The Advanced version will manage two lists:

- A **to-do list** containing unfinished items.
- A **completed list** containing items that have been checked off.

In addition to the Basic features, the user should be able to replace an existing item and check an item off as completed.

## Advanced File Structure

Your starter folder will contain:

```text
advanced/
└── main.py
```

You may begin by copying your completed Basic program into this file.

## Advanced Requirements

* [ ] Keep all functionality from the Basic version, including adding, removing, displaying, undoing, and exiting.
* [ ] Maintain separate **to-do** and **completed** lists.
* [ ] Add an option that allows the user to replace an existing to-do item by selecting its index and entering a new value.
* [ ] Add an option to **check off** a to-do item. The selected item should be removed from the to-do list and added to the completed list.
* [ ] Allow the user to choose whether they want to view the current **to-do list** or the **completed list**.
* [ ] Validate menu choices and list indices so invalid selections are not used.
* [ ] Use error handling where appropriate so incorrect user input does not crash the program and the user can correct their input.

## Advanced Assessment — 4 Marks

| Assessment Item | Criteria | Marks |
|---|---|---:|
| Replacing Items | Allows the user to select an existing to-do item by index and replace it with a new value. | 1 |
| Completing Items | Correctly moves a selected item from the to-do list into the completed list. | 1 |
| Viewing Lists | Allows the user to separately view both unfinished and completed items. | 1 |
| Validation and Error Handling | Prevents invalid menu choices and indices from crashing the program and allows the user to correct invalid input. | 1 |
|  | **Total** | **4** |