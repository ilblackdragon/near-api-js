---
id: "_generated_rpc_error_types_.signerdoesnotexist"
title: "SignerDoesNotExist"
sidebar_label: "SignerDoesNotExist"
---

## Hierarchy

  ↳ [InvalidTxError](_generated_rpc_error_types_.invalidtxerror.md)

  ↳ **SignerDoesNotExist**

## Index

### Constructors

* [constructor](_generated_rpc_error_types_.signerdoesnotexist.md#constructor)

### Properties

* [message](_generated_rpc_error_types_.signerdoesnotexist.md#message)
* [name](_generated_rpc_error_types_.signerdoesnotexist.md#name)
* [signer_id](_generated_rpc_error_types_.signerdoesnotexist.md#signer_id)
* [stack](_generated_rpc_error_types_.signerdoesnotexist.md#optional-stack)
* [type](_generated_rpc_error_types_.signerdoesnotexist.md#type)

## Constructors

###  constructor

\+ **new SignerDoesNotExist**(`message?`: string, `type?`: string): *[SignerDoesNotExist](_generated_rpc_error_types_.signerdoesnotexist.md)*

*Inherited from [TypedError](_utils_errors_.typederror.md).[constructor](_utils_errors_.typederror.md#constructor)*

*Defined in [src.ts/utils/errors.ts:14](https://github.com/nearprotocol/nearlib/blob/de49029/src.ts/utils/errors.ts#L14)*

**Parameters:**

Name | Type |
------ | ------ |
`message?` | string |
`type?` | string |

**Returns:** *[SignerDoesNotExist](_generated_rpc_error_types_.signerdoesnotexist.md)*

## Properties

###  message

• **message**: *string*

*Inherited from [BorshError](_utils_serialize_.borsherror.md).[message](_utils_serialize_.borsherror.md#message)*

Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:974

___

###  name

• **name**: *string*

*Inherited from [BorshError](_utils_serialize_.borsherror.md).[name](_utils_serialize_.borsherror.md#name)*

Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:973

___

###  signer_id

• **signer_id**: *any*

*Defined in [src.ts/generated/rpc_error_types.ts:310](https://github.com/nearprotocol/nearlib/blob/de49029/src.ts/generated/rpc_error_types.ts#L310)*

___

### `Optional` stack

• **stack**? : *string*

*Inherited from [BorshError](_utils_serialize_.borsherror.md).[stack](_utils_serialize_.borsherror.md#optional-stack)*

Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:975

___

###  type

• **type**: *string*

*Inherited from [TypedError](_utils_errors_.typederror.md).[type](_utils_errors_.typederror.md#type)*

*Defined in [src.ts/utils/errors.ts:14](https://github.com/nearprotocol/nearlib/blob/de49029/src.ts/utils/errors.ts#L14)*
