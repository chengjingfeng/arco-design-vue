```yaml
meta:
  type: Component
  category: Navigation
title: Dropdown
description: When there are too many commands on the page, the alternative commands can be stored in the floating container that expands downward.
```

*Auto translate by google.*

@import ./__demo__/basic.md

@import ./__demo__/position.md

@import ./__demo__/trigger.md

@import ./__demo__/group.md

@import ./__demo__/submenu.md

@import ./__demo__/context-menu.md

@import ./__demo__/icon.md


### `<dropdown>` Props

|Attribute|Description|Type|Default|
|---|---|---|:---:|
|popup-visible **(v-model)**|Whether the popup is visible|`boolean`|`-`|
|default-popup-visible|Whether the popup is visible by default (uncontrolled mode)|`boolean`|`false`|
|trigger|Trigger method|`'hover' \| 'click' \| 'focus' \| 'contextMenu'`|`'click'`|
|position|Popup position|`'top' \| 'tl' \| 'tr' \| 'bottom' \| 'bl' \| 'br'`|`'bottom'`|
|popup-container|Mount container for popup|`string \| HTMLElement \| null \| undefined`|`-`|
### `<dropdown>` Events

|Event Name|Description|Parameters|
|---|---|---|
|popup-visible-change|Triggered when the display status of the drop-down box changes|-|
|select|Triggered when the user selects|-|
### `<dropdown>` Slots

|Slot Name|Description|Parameters|
|---|---|---|
|content|Content|-|








### `<dgroup>` Props

|Attribute|Description|Type|Default|
|---|---|---|:---:|
|title|Group title|`string`|`-`|






