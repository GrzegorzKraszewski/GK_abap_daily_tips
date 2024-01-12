This short program show's how to trim last char in string


```console
data: lv_data TYPE string value 'HelloAbapers',
lv_len TYPE i,
lv_data1 TYPE char25.

lv_data1 = lv_data.
lv_len = strlen( lv_data ).
lv_len = lv_len - 1.
lv_data1+lv_len(1) = ''.
write: / lv_data.
skip.
write: / lv_data1.
```
Result:


![helloabapers](https://github.com/GrzegorzKraszewski/GK_abap_daily_tips/assets/141272893/59d9f830-2528-47aa-ad09-91c679f01882)
