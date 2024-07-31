# Rofi todo

![alt text](todo.jpg "todo girl")

A simple Bash script to manage a todo list using `rofi`, allowing for the adding and deletion of tasks directly from within `rofi`.

## Features

+ **View Todo List**: Displays the current todo list using..
+ **Add New Item**: Easily add new todo items..
+ **Delete Item**: Delete existing todo items with confirmation..


## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/furycd001/todo-rofi.git
    cd todo-rofi
    ```

2. **Ensure the script is executable and located in a directory included in your PATH:**
    ```bash
    chmod +x todo
    mv todo.sh ~/.local/bin/todo
    ```
## Usage

### Interact with the Todo List

1. **Open `rofi` and type `todo`:**

> I launch `rofi` with `rofi -show drun`, but `rofi -show run` will work as well..
>
>  The todo list is stored in `~/Documents/todo.txt`. If this file does not exist, it will be created automatically the first time the script runs..
>
>  Each todo item should be on its own line with nothing in between..

2. **Add New Items:**
    + Select **"Add New Item"** from the list and press `Enter`.
    + A new prompt will appear. Type in the new item and press `Enter`.
    + The new item will be added to the list and saved to the `todo.txt`.

3. **Deleting Items:**
    + Highlight the item you want to delete and press `Enter`.
    + A confirmation prompt will appear asking **"Are you sure you want to delete this item?"**.
    + Select **"Yes"** and press `Enter` to confirm deletion, or select **"No"** to cancel.
    + If confirmed, the item will be removed from the list and `todo.txt` will be updated.

## Example

1. **Add New Item**:
    - Open `rofi` and type `todo`.
    - Select "Add New Item".
    - Type the new task and press `Enter`.

2. **Delete Item**:
    - Open `rofi` and type `todo`.
    - Select the task you want to delete.
    - Confirm deletion by selecting "Yes".
