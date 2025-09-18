# checkfile

## Request JSON Sysntax

| **Key** | **Description** |
| --- | --- |
| task | task name |
| token | token string encrypted. |

## Request Sample

```
{
    "task":"checkfile","token":"300ea42877b8fd414644196bb44e7a8bea3164a1a5a348c5381b47766536a56664ec74a35eeb28dd7926f07dd201b6aa7926f07dd201b6aa7926f07dd201b6aa7926f07dd201b6aa7926f07dd201b6aa7926f07dd201b6aa7926f07dd201b6aa7926f07dd201b6aa7926f07dd201b6aa7926f07dd201b6aa7926f07dd201b6aa"
}

```


## Response Json Syntax

| **Key** | **Description** |
| --- | --- |
| note | if failed, a brief description will be given here |
| status | execution result, success or failed. |
| task | task name |


## Response Sample

```
{
   "__EXEC_TIME" : "0 ms",
   "note" : "none",
   "status" : "success",
   "task" : "checkfile"
}
```