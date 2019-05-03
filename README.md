# my_baidu_input_skin
A Baidu mobile phone input method skin optimized for one-handed input of English.

### Baidu mobile phone input method

#### Download

https://srf.baidu.com/default/

#### Advanced skinning function

##### Choose skin

setting->super skin->lcoal

##### Use custom skin

1. Download the appropriate "*.bds" file.
2. Single click to enable. 
   1. If the file has an internal error, the input method will prompt an error and use the initial skin.
   2. The above internal error usually refers to the use of the wrong compression method.
3. If the character of the button response does not match the picture of the button, you can solve this by choose a background (anything is okay, for example, a pure white background) for the keyboard with the built-in customize skin function.

### Preparation of skin files

#### File structure

```shell
.
├── demo.png
├── Info.txt
├── land (Landscape)
├── port (Portrait)
│   ├── en_26.ini (26 key keyboard for english input)
│   ├── en_26s.ini (26 key layout after pressing the shift key)
│   ├── others
└── res
```

#### Example

```ini
[KEY1]
BACK_STYLE=118
FORE_STYLE=337
VIEW_RECT=5,65,44,75
TOUCH_RECT=5,65,44,75
UP=1
LEFT=1
RIGHT=1
CENTER=q
```

Of course, other changes are needed.