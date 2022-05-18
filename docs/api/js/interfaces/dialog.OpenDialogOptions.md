[@tauri-apps/api](../README.md) / [dialog](../modules/dialog.md) / OpenDialogOptions

# Interface: OpenDialogOptions

[dialog](../modules/dialog.md).OpenDialogOptions

Options for the open dialog.

## Properties

### defaultPath

• `Optional` **defaultPath**: `string`

Initial directory or file path.

#### Defined in

[dialog.ts:51](https://github.com/tauri-apps/tauri/blob/393c774/tooling/api/src/dialog.ts#L51)

___

### directory

• `Optional` **directory**: `boolean`

Whether the dialog is a directory selection or not.

#### Defined in

[dialog.ts:55](https://github.com/tauri-apps/tauri/blob/393c774/tooling/api/src/dialog.ts#L55)

___

### filters

• `Optional` **filters**: [`DialogFilter`](dialog.DialogFilter.md)[]

The filters of the dialog.

#### Defined in

[dialog.ts:49](https://github.com/tauri-apps/tauri/blob/393c774/tooling/api/src/dialog.ts#L49)

___

### multiple

• `Optional` **multiple**: `boolean`

Whether the dialog allows multiple selection or not.

#### Defined in

[dialog.ts:53](https://github.com/tauri-apps/tauri/blob/393c774/tooling/api/src/dialog.ts#L53)

___

### recursive

• `Optional` **recursive**: `boolean`

If `directory` is true, indicates that it will be read recursively later.
Defines whether subdirectories will be allowed on the scope or not.

#### Defined in

[dialog.ts:60](https://github.com/tauri-apps/tauri/blob/393c774/tooling/api/src/dialog.ts#L60)

___

### title

• `Optional` **title**: `string`

The title of the dialog window.

#### Defined in

[dialog.ts:47](https://github.com/tauri-apps/tauri/blob/393c774/tooling/api/src/dialog.ts#L47)
