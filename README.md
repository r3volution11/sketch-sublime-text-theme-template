# Sketch Sublime Text Theme Template

Attempting to create a Sketch template to help with creating themes for Sublime Text.

This template will include all of the user interface elements that are available in Sublime Text. Or, at the very least, all that is needed to create a complete theme.

Each element is grouped and labelled as is necessary in a Sublime Text Theme file. Some are included without any styles at all. However they will still help with determining the proper settings.

## Screenshot of Current Progres

![Screenshot of current progress](http://dch.link/dFoj/Image%202015-09-19%20at%201.17.09%20AM.png)

## Not Quite Ready For Use

This is about 75% done. At this point it's rather helpful but not all of the way there. The status bar and widget panel are up next. After that I'll be working on a set of **pixel perfect** icons for file types.

## To Do List / Progress

You can keep track of my progress by viewing this to do list.

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

[x] overlay_control  (overlay-bg)  
[x] mini_quick_panel_row  
[x] mini_quick_panel_row::selected  
[x] quick_panel  (quick-panel-background)  
[x] quick_panel_row  // project manager  
[x] quick_panel_row  // common panel - cmd + shift + p  
[x] quick_panel  // inside overlay_control - cmd + shift + p)  
[x] quick_panel_row::selected  
[x] quick_panel_label  
[x] quick_panel_path_label  
[x] quick_panel_score_label  

### Tabs

[x] tab_control  // tab background  
[x] tab_control::selected  (tab-current)  
[x] tab_control::hover  
[x] tab_control::selected::hover  
[x] tab_label  
[x] tab_label::selected  

### Tab Icons

[ ] tab_close_button  
[x] tab_close_button icon  (close-icon)  
[x] tab_close_button icon::hover  (close-icon--hover)  
[x] tab_close_button dirty icon  (dirty-icon)  
[x] tab_close_button dirty icon::hover  (dirty-icon--hover)  

### Tabset

[x] scroll_tabs_left_button  (arrow-left)  
[x] scroll_tabs_left_button::hover  (arrow-left--hover)  
[x] scroll_tabs_right_button  (arrow-right)  
[x] scroll_tabs_right_button::hover  (arrow-right-hover)  

### Tab Overflow

[x] show_tabs_dropdown_button  (overflow-menu)  
[x] show_tabs_dropdown_button::hover  (overflow-menu--hover)  

### Sidebar

[x] sidebar_container  
[x] sidebar_tree  
[x] sidebar_heading  
[ ] sidebar_heading::selected (tree_highlight.png)  
[x] sidebar_label  
[ ] sidebar_label::hover  
[ ] sidebar_label::selected  
[x] sidebar_label::expandable  
[ ] sidebar_label::expandable::selected  
[x] sidebar_label::expanded  
[ ] sidebar_label::expanded::selected  

### Icons

#### Files

[x] icon_file_type (file labels)  

#### Folder

[x] icon_folder  (folder)  
[ ] icon_folder::hover  (folder--hover)  
[x] icon_folder::expanded::hover  (folder-expanded--hover)  
[ ] icon_folder_loading  (spinner-##)  // animated with 10 frames  

#### Symlink Folder

[ ] icon_folder_dup  
[ ] icon_folder_dup::hover  
[ ] icon_folder_dup::expanded  

### Scrollbars

[x] scroll_bar_control  (scroll-bar-vertical)
[x] scroll_bar_control.overlay-control
[x] scroll_bar_control::horizontal  (scroll-bar-horizontal)
[x] scroll_bar_control.overlay-control::horizontal
[x] scroll_corner_control  (scroll-bar-corner)
[x] puck_control  (puck-vertical)
[x] puck_control::horizontal  (puck-horizontal)

### Minimap

[x] minimap_control  
[x] minimap_control::hover  

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
