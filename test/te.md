---

database-plugin: basic

---

```yaml:dbfolder
name: new database
description: new description
columns:
 column1:
  input: text
  key: column1
  accessorKey: column1
  label: Column 1
  position: 0
  config:
   enable_media_view: true
   media_width: 100
   media_height: 100
   isInline: false
filters:
 enabled: false
 conditions:
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
  row_templates_folder: /
  current_row_template: 
  pagination_size: 10
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: yyyy-MM-dd HH:mm:ss
  metadata_date_format: yyyy-MM-dd HH:mm:ss
  enable_footer: false
  implementation: default
```