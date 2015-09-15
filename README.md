# Sketch Sublime Text Theme Template

Attempting to create a Sketch template to help with creating themes for Sublime Text.

This template will include all of the user interface elements that are available in Sublime Text. Or, at the very least, all that is needed to create a complete theme.

## Not Ready For Use

This is barebones at the moment. Do not use it. Will update when ready.

## To Do List / Progress

Keep track of progress by viewing the todo list below.

#### Key

(#) - Image Name
//# - Comment
::# - Attribute
.# - Class

### Empty Window

[x] sheet_container_control

### Grid Lines

[x] grid_layout_control

### Dialog Popup

[x] progress_gauge_control
[x] dialog
[x] progress_bar_control

### Code Folding

[x] fold_button_control  (fold-right)
[x] fold_button_control::hover  (fold-right--hover)
[x] fold_button_control::expanded  (fold-down)
[x] fold_button_control::expanded::hover  (fold-down--hover)

### Autocomplete

[x] popup_control
[x] auto_complete
[x] auto_complete_label
[x] table_row & ::selected

### Tool Tip

[x] tool_tip_control
[x] tool_tip_label_control

### Overlay Panels

[ ] overlay_control  (overlay-bg)
[ ] mini_quick_panel_row
[ ] mini_quick_panel_row::selected
[ ] quick_panel  (quick-panel-background)
[ ] quick_panel_row  // project manager
[ ] quick_panel_row  // common panel - cmd + shift + p
[ ] quick_panel  // inside overlay_control - cmd + shift + p)
[ ] quick_panel_row::selected
[ ] quick_panel_label
[ ] quick_panel_path_label
[ ] quick_panel_score_label

### Tabs

[x] tab_control  // tab background
[x] tab_control::selected  (tab-current)
[ ] tab_control::hover
[ ] tab_control::selected::hover
[x] tab_label
[x] tab_label::selected

### Tab Icons

[ ] tab_close_button
[ ] tab_close_button icon  (close-icon)
[ ] tab_close_button icon::hover  (close-icon--hover)
[x] tab_close_button dirty icon  (dirty-icon)
[ ] tab_close_button dirty icon::hover  (dirty-icon--hover)

### Tabset

[x] scroll_tabs_left_button  (arrow-left)
[ ] scroll_tabs_left_button::hover  (arrow-left--hover)
[x] scroll_tabs_right_button  (arrow-right)
[ ] scroll_tabs_right_button::hover  (arrow-right-hover)

### Tab Overflow

[ ] show_tabs_dropdown_button  (overflow-menu)
[ ] show_tabs_dropdown_button::hover  (overflow-menu--hover)

### Sidebar

[x] sidebar_container
[ ] sidebar_tree
[ ] sidebar_heading
[ ] sidebar_heading::selected (tree_highlight.png)
[ ] sidebar_label
[ ] sidebar_label::hover
[ ] sidebar_label::selected
[ ] sidebar_label::expandable
[ ] sidebar_label::expandable::selected
[ ] sidebar_label::expanded
[ ] sidebar_label::expanded::selected

### Icons

#### Files

[ ] icon_file_type (file labels)

#### Folder

[ ] icon_folder  (folder)
[ ] icon_folder::hover  (folder--hover)
[ ] icon_folder::expanded::hover  (folder-expanded--hover)
[ ] icon_folder_loading  (spinner-##)  // animated with 10 frames

#### Symlink Folder

[ ] icon_folder_dup
[ ] icon_folder_dup::hover
[ ] icon_folder_dup::expanded

### Scrollbars

[ ] scroll_bar_control  (normal-bar-vertical)
[ ] scroll_bar_control.overlay-control
[ ] scroll_bar_control::horizontal
[ ] scroll_bar_control.overlay-control::horizontal
[ ] scroll_corner_control  (normal_bar_corner)
[ ] puck_control  (thumb-vertical)
[ ] puck_control::horizontal  (thumb-horizontal)

### Minimap

[ ] minimap_control
[ ] minimap_control::hover

### Status Bar

[ ] label_control
[ ] label_control.status_bar  // Text field label
[ ] status_button

### Widget Panel

[ ] panel_control
[ ] panel_close_button  (close_icon, close_icon--hover)
[ ] text_line_control  (input-field-border)
[ ] text_line_control.overlay_control  (input-field-border--short)
[ ] dropdown_button_control  (overflow-menu, overflow-menu--hover)

### Buttons (Panels - Find & Replace)

[ ] label_control.button-control
[ ] button_control  (full-button--indented, full-button-highlight)
[ ] button_control::pressed
[ ] button_control::pressed::hover
[ ] button_control::hover
[ ] icon_button_control  // small icon buttons

### Button Icons

[ ] icon_regex  (find-regex)
[ ] icon_regex::selected  (find-regex--hover)
[ ] icon_case  (find-case)
[ ] icon_case::selected  (find-case--hover)
[ ] icon_whole_word  (find-word)
[ ] icon_whole_word::selected  (find-word--hover)
[ ] icon_wrap  (find-wrap)
[ ] icon_wrap::selected  (find-wrap--hover)
[ ] icon_in_selection  (find-inselection)
[ ] icon_In_selection::selected  (find-inselection--hover)
[ ] icon_preserve_case  (replace-preserve-case)
[ ] icon_preserve_case::selected  (replace-preserve-case--hover)
[ ] icon_context  (find-context)
[ ] icon_context::selected  (find-context--hover)
[ ] icon_use_buffer  (use-buffer)
[ ] icon_use_buffer::selected  (use-buffer--hover)
[ ] icon_reverse  (find-reverse)
[ ] icon_reverse::hover  (find-reverse--hover)
