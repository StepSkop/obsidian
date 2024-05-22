---

database-plugin: basic

---

```yaml:dbfolder
name: new database
description: new description
columns:
  Nationality:
    input: select
    accessorKey: Nationality
    label: Nationality
    key: Nationality
    id: Nationality
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 96
    options:
      - { label: "🇨🇿", value: "🇨🇿", color: "hsl(0,0%,15%)"}
      - { label: "🇺🇸", value: "🇺🇸", color: "hsl(0,0%,15%)"}
      - { label: "🇬🇧", value: "🇬🇧", color: "hsl(0,0%,15%)"}
      - { label: "🇫🇷", value: "🇫🇷", color: "hsl(0,0%,15%)"}
      - { label: "🇩🇪", value: "🇩🇪", color: "hsl(0,0%,15%)"}
      - { label: "🇳🇴", value: "🇳🇴", color: "hsl(0,0%,15%)"}
      - { label: "🇵🇱", value: "🇵🇱", color: "hsl(0,0%,15%)"}
      - { label: "[,🇨🇿]", value: "[,🇨🇿]", color: "hsl(194, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
      content_alignment: text-align-left
  Author:
    input: text
    accessorKey: Author
    label: Author
    key: Author
    id: Author
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 204
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_alignment: text-align-left
  File:
    input: text
    accessorKey: File
    label: File
    key: File
    id: File
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 226
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      wrap_content: false
      content_alignment: text-align-left
  Na potítku:
    input: text
    accessorKey: Na potítku
    label: Na potítku
    key: Na potítku
    id: Na potítku
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 419
    config:
      enable_media_view: false
      link_alias_enabled: false
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_alignment: text-align-left
  Read:
    input: select
    accessorKey: Read
    label: Read
    key: Read
    id: Read
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    isSorted: false
    isSortedDesc: false
    options:
      - { label: "Read", value: "Read", color: "hsl(121,41%,35%)"}
      - { label: "Ago", value: "Ago", color: "hsl(47,100%,41%)"}
      - { label: "Never", value: "Never", color: "hsl(0,0%,24%)"}
      - { label: "Audio", value: "Audio", color: "hsl(76, 95%, 90%)"}
      - { label: "[,Never]", value: "[,Never]", color: "hsl(179, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
      content_alignment: text-align-left
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 2
    isHidden: false
    sortIndex: -1
    isSorted: false
    isSortedDesc: false
    width: 248
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_alignment: text-align-left
  Druhy:
    input: select
    accessorKey: Druhy
    key: Druhy
    id: Druhy
    label: Druhy
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 50
    options:
      - { label: "DR", value: "DR", color: "hsl(348,98%,25%)"}
      - { label: "PR", value: "PR", color: "hsl(24,100%,30%)"}
      - { label: "PO", value: "PO", color: "hsl(44,100%,35%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
      content_alignment: text-align-left
  Finished:
    input: checkbox
    accessorKey: Finished
    key: Finished
    id: Finished
    label: Finished
    position: 1
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 89
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Year:
    input: text
    accessorKey: Year
    key: Year
    id: Year
    label: Year
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: 0
    width: 64
    isSorted: true
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_alignment: text-align-left
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
  show_metadata_tags: false
  source_data: tag
  source_form_result: "#Book"
  source_destination_path: CJL/Díla
  row_templates_folder: CJL/Díla
  current_row_template: 
  pagination_size: 20
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```