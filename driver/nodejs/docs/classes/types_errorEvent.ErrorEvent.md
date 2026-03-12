[@jprayner/piconet-nodejs](../README.md) / [Exports](../modules.md) / [types/errorEvent](../modules/types_errorEvent.md) / ErrorEvent

# Class: ErrorEvent

[types/errorEvent](../modules/types_errorEvent.md).ErrorEvent

Fired by the firmware to indicate that an error has occurred.

These events may be fired at any time, even if a command is not in-progress (for example, if a
received packet fails to parse).

## Table of contents

### Constructors

- [constructor](types_errorEvent.ErrorEvent.md#constructor)

### Properties

- [description](types_errorEvent.ErrorEvent.md#description)

### Methods

- [toString](types_errorEvent.ErrorEvent.md#tostring)

## Constructors

### constructor

• **new ErrorEvent**(`description`)

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `description` | `string` | A human-readable description of the error. |

#### Defined in

[types/errorEvent.ts:8](https://github.com/maq1017/piconet/blob/9487712/driver/nodejs/src/types/errorEvent.ts#L8)

## Properties

### description

• **description**: `string`

A human-readable description of the error.

#### Defined in

[types/errorEvent.ts:12](https://github.com/maq1017/piconet/blob/9487712/driver/nodejs/src/types/errorEvent.ts#L12)

## Methods

### toString

▸ **toString**(): `string`

#### Returns

`string`

#### Defined in

[types/errorEvent.ts:15](https://github.com/maq1017/piconet/blob/9487712/driver/nodejs/src/types/errorEvent.ts#L15)
