[@ai16z/eliza v0.1.4-alpha.3](../index.md) / GenerationOptions

# Interface: GenerationOptions

Configuration options for generating objects with a model.

## Properties

### runtime

> **runtime**: [`IAgentRuntime`](IAgentRuntime.md)

#### Defined in

[packages/core/src/generation.ts:901](https://github.com/ai16z/eliza/blob/main/packages/core/src/generation.ts#L901)

***

### context

> **context**: `string`

#### Defined in

[packages/core/src/generation.ts:902](https://github.com/ai16z/eliza/blob/main/packages/core/src/generation.ts#L902)

***

### modelClass

> **modelClass**: `TiktokenModel`

#### Defined in

[packages/core/src/generation.ts:903](https://github.com/ai16z/eliza/blob/main/packages/core/src/generation.ts#L903)

***

### schema?

> `optional` **schema**: `ZodSchema`

#### Defined in

[packages/core/src/generation.ts:904](https://github.com/ai16z/eliza/blob/main/packages/core/src/generation.ts#L904)

***

### schemaName?

> `optional` **schemaName**: `string`

#### Defined in

[packages/core/src/generation.ts:905](https://github.com/ai16z/eliza/blob/main/packages/core/src/generation.ts#L905)

***

### schemaDescription?

> `optional` **schemaDescription**: `string`

#### Defined in

[packages/core/src/generation.ts:906](https://github.com/ai16z/eliza/blob/main/packages/core/src/generation.ts#L906)

***

### stop?

> `optional` **stop**: `string`[]

#### Defined in

[packages/core/src/generation.ts:907](https://github.com/ai16z/eliza/blob/main/packages/core/src/generation.ts#L907)

***

### mode?

> `optional` **mode**: `"auto"` \| `"json"` \| `"tool"`

#### Defined in

[packages/core/src/generation.ts:908](https://github.com/ai16z/eliza/blob/main/packages/core/src/generation.ts#L908)

***

### experimental\_providerMetadata?

> `optional` **experimental\_providerMetadata**: `Record`\<`string`, `unknown`\>

#### Defined in

[packages/core/src/generation.ts:909](https://github.com/ai16z/eliza/blob/main/packages/core/src/generation.ts#L909)