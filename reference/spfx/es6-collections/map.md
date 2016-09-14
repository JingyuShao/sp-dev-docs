# Map interface








## Properties

| Property	   | Type	| Description|
|:-------------|:-------|:-----------|
|`size`      | `number` |  |




## Methods

| Method	   |  Returns	| Description|
|:-------------|:-------|:-----------|
|[`clear`](#clear)      | `void` |  |
|[`delete`](#delete)      | `boolean` |  |
|[`forEach`](#foreach)      | `void` |  |
|[`get`](#get)      | `V` |  |
|[`has`](#has)      | `boolean` |  |
|[`set`](#set)      | [`Map<K,V>`](../es6-collections/map.md) |  |
|[`entries`](#entries)      | [`Iterator<[K,V]>`](../es6-collections/iterator.md) |  |
|[`keys`](#keys)      | [`Iterator<K>`](../es6-collections/iterator.md) |  |
|[`values`](#values)      | [`Iterator<V>`](../es6-collections/iterator.md) |  |




### clear



#### Signature
`clear(): void`

#### Returns
`void`


#### Parameters
None


### delete



#### Signature
`delete(key: K): boolean`

#### Returns
`boolean`


#### Parameters


| Parameter	   | Type    | Description |
|:-------------|:---------------|:------------|
| `key`    | `K` |  |


### forEach



#### Signature
`forEach(callbackfn: (value: V,index: K,map: Map<K,V>) => void,thisArg?: any): void`

#### Returns
`void`


#### Parameters


| Parameter	   | Type    | Description |
|:-------------|:---------------|:------------|
| `callbackfn`    | `(value: V,index: K,map: Map<K,V>) => void` |  |
| `thisArg`    | `any` | _Optional._ |


### get



#### Signature
`get(key: K): V`

#### Returns
`V`


#### Parameters


| Parameter	   | Type    | Description |
|:-------------|:---------------|:------------|
| `key`    | `K` |  |


### has



#### Signature
`has(key: K): boolean`

#### Returns
`boolean`


#### Parameters


| Parameter	   | Type    | Description |
|:-------------|:---------------|:------------|
| `key`    | `K` |  |


### set



#### Signature
`set(key: K,value?: V): Map<K,V>`

#### Returns
[`Map<K,V>`](../es6-collections/map.md)


#### Parameters


| Parameter	   | Type    | Description |
|:-------------|:---------------|:------------|
| `key`    | `K` |  |
| `value`    | `V` | _Optional._ |


### entries



#### Signature
`entries(): Iterator<[K,V]>`

#### Returns
[`Iterator<[K,V]>`](../es6-collections/iterator.md)


#### Parameters
None


### keys



#### Signature
`keys(): Iterator<K>`

#### Returns
[`Iterator<K>`](../es6-collections/iterator.md)


#### Parameters
None


### values



#### Signature
`values(): Iterator<V>`

#### Returns
[`Iterator<V>`](../es6-collections/iterator.md)


#### Parameters
None
