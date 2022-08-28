# **4.0 Pointers**
<!-- explain  memory with a table. Explain everything visually!-->
Pointers are a concept that is rather fundamental in Computer Science. Without pointers many important system like operating system kernels wouldn't even exist. But to understand pointers, we first need to understand how a computers memory works

## **4.1 How memory looks - Memory visualized**

Memory is simply like a table. You have addresses and data living at that address. The table below aims to visualize that.

| Address | Data |
| :--: | :--: |
| 0x00 | 'c' |
| 0x01 | 255 |
| 0x02 | 0xFF |
| 0x03 | 'f' |
| ... | |
| 0xFF | 'o' |

> **Note**, that in this example at each address only one byte of information can be stored. This is not always the case though.

## **4.2 What are pointers**

A pointer just points to such an address. So a pointer to an int basically means that the variable itself holds the address to the integer value. Like so:

| Address | Data |
| --: | :-- |
| 0xfffa | 84572 |
| ``int pointer:`` 0xfffb | ``->`` 10 |

So in this example ``int pointer`` has the address 0xfffb and at that address is the value 10

## **4.3 Why are pointers useful**

## **4.4 How to use pointers in Mik**

> If you don't have experience with pointers. **Please don't read any further** as this will perhaps initially lead to a lot of confusion!

# **4.5 Advanced Topics**
