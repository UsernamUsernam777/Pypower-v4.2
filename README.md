# pypower (New Version)
Note: this lib is updated everytime
🛠 Pypower Full Documentation

to install with pip: pip install pypower-v4


🕒 Time: For managing clock operations and time conversions
    minus_clock: Calculates the time difference between two 'HH:MM:SS' strings

    convert_to_iterable_and_int: Converts 'HH:MM:SS' string to an iterable of ints

    how_many_hms_in_s: Calculates how many hours, minutes, and seconds in total seconds

    reverse_many_hms: Converts 'HH:MM:SS' string back into total seconds


🔍 Other: General utilities for system and browser automation
    search_google: Opens a browser tab with a Google search for text

    in_bg: Run action in a background thread after duration seconds

🚀 Apps: Tools for application lifecycle and distribution
    create_app: Build a standalone .exe from a .py file using PyInstaller


📂 Files: Simple file system and directory management
    read_write_txt_file: Reads or writes text to a file with optional creation

    make_if_not_exists: Create a folder or empty file at path if it doesn't exist

    append_to_pypower: Append a labeled code block to pypower.py

    append_to_file: Append text to a file removing double blank lines


🎨 GUI: Modern wrappers for CustomTkinter and Turtle graphics
    CustomTk (Sub Class): For automating modern UI components
        copy_style: Copies visual style from one widget and applies it to another

        dont_enter: Restricts specific characters from being entered into a CTkEntry

        len_entry: Creates a live character counter for a CTkEntry

        label_widget: Places a temporary floating label above or below a widget

        manager_same: Syncs the layout manager from one widget to another

        entry_label: Toggles a widget between a Label and an Entry on events

        options: Creates a right-click context menu with custom commands

        table: Generates a professional scrollable table from a dictionary

        duplicate_double_click: Enables recursive widget cloning on double-click

        clone_widget: Deep-clones any widget with its internal configuration

        add_texts_to_file: Scans a master and appends all widget texts to a file

        has_text: Validates if a widget supports and contains text

        has_text_iterable: Filters widgets to return only those containing text

        show_hide_message: Displays a temporary message label that auto-destroys

        change_mode: Creates a toggle button for Dark and Light appearance modes

        limit_len: Sets a maximum character limit for a CTkEntry

        sync_entry_with_label: Links a CTkEntry's text with a CTkLabel in real-time

        console: Generates a button grid linked to an Entry for text insertion

        console_num: Creates a 0-9 numeric keypad linked to an entry

        show_hide_entry_btn: Adds a toggle button to show/hide text in entries

        move: Makes any widget draggable across the master window

        good_size: Resizes a list of widgets to match the largest one

        sort_colors: Automatically sorts widgets into color-coded categories

        tidy_up: Arranges widgets in a perfect grid based on fixed per row

        all_objects: Returns a flat list of all child widgets inside a master

        edit_all_widgets_texts: Batch edits font and color for all text widgets

        info: Creates a tooltip that appears on hover

        mouse_wheel_num: Enables number scrolling inside an Entry using mouse wheel

        Timer (Inner Class): For creating functional countdown timers
            start: Begins the countdown and updates the target object

            stop: Pauses the timer

            resume_timer: Resumes a paused timer from its current duration

    Turtle (Sub Class): For advanced turtle graphics and window boundaries
        moving: Binds arrow keys to move the turtle object with custom heading

        in_circle: Draws a repeated shape in a circular pattern

        rock_bottom: Checks if the turtle object has hit the window boundaries


📝 String: Advanced methods for text analysis and manipulation
    super_join: Insert sep every few characters in the string

    reverse: Reverse the order of parts split by a separator

    replace_objects_with_one: Replace multiple characters with a single new one

    replace_many: Map and replace a set of characters with another set

    between: Extract the text located between two specific characters

    line_if_in: Returns lines from a string that contain a specific keyword


📊 Iterable: Management for Lists, Tuples, and Dictionaries
    opponents: Returns the opposite element from a two-item iterable

    flat_list: Recursively flattens nested lists into a single list

    search_iterable: Filters an iterable for items containing a keyword

    numred: Formats a list into a numbered string (e.g., 1. Item)

    indexes: Returns all indices of a specific object in an iterable

    replace_iterable: Replace or remove an object in a list by index

    all_any_in: Checks if elements of one list exist within another

    Dict (Sub Class): For specialized dictionary operations
        swap_dict: Swaps keys and values in a dictionary

        return_dict_in_lines: Return a dict formatted as 'key: value' lines


🔢 Math: Fast mathematical shortcuts and sequence generators
    int_or_float: Validates if a number is a valid integer or float string

    iter_num: Return sum, average, max, and min of an iterable as a dict

    arrays: Split a range into consecutive [start, end] pairs by step
