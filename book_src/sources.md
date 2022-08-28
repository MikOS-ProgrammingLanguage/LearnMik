# **This chapter only has some additional sources for reading about types and the language keywords in general**

----

## **Full compendium of base types**

| Type | Information | Size |
| :-- | :--:        | --: |
| int | standard 32-bit signed Integer | 32-bit = 4-byte |
| int8 | 8-bit signed Integer value | 8-bit = 1-byte |
| int16 | 16-bit signed Integer | 16-bit = 2-byte |
| int32 | 32-bit signed Integer | 32-bit = 4-byte |
| int64 | 64-bit signed Integer | 64-bit = 8-byte |
| | | |
| uint8 | 8-bit unsigned Integer value | 8-bit = 1-byte |
| uint16 | 16-bit unsigned Integer | 16-bit = 2-byte |
| uint32 | 32-bit unsigned Integer | 32-bit = 4-byte |
| uint64 | 64-bit unsigned Integer | 64-bit = 8-byte |
| | | |
| flt | 64-bit signed floating point number |  64-bit = 8-byte
| | | |
| chr | 8-bit unsigned integer | 8-bit = 1-byte |
| | | |
| str | minimum 2-byte char array. Max size is undefined | 2-bytes - undefined |
| | | |
| bool | 1-bit integer. Either true(=1) or false(=0) | 1-bit |
| | | |
| cock | unsigned volatile long long int (= 64-bit unsigned integer) | 64-bit = 8-byte |
| | | |
| void | non type | 0 |
| void* | untyped address | 8-bit = 1-byte |

## **Full compendium of variable behavior descriptors**

| Variable behavior descriptor | Functionality |
| :-- | --: |
| global | brings this variable into any scope in the program |
| local | hides the variable in the current section |
| imut  | imut(=immutable) creates a constant value (can not be changed) |
| \_\_noret\_\_ | Is specifically for functions. Makes returning to a variable optional. E.g.: puts() returns an Integer, but you can just call it with ``puts()`` and not ``int p = puts()`` |

## **Full compendium of type descriptors**
