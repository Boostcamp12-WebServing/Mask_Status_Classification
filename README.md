# ๐Mask Status Classification Service
๋ฐ๋ชจ ํ์ด์ง: https://dc49-146-56-140-223.ngrok.io/  
2021.09.04 ~ 2021.10.27

## ๐Summary

> [๋ถ์คํธ์บ ํ ์ด๋ฏธ์ง ๋ถ๋ฅ ๋ํ](https://github.com/boostcampaitech2/image-classification-level1-12/tree/master)์ ๋ชจ๋ธ์ ์ฌ์ฉํ์ฌ, ๋ง์คํฌ ์ฐฉ์ฉ ์ํ ๊ตฌ๋ถ ์น์๋น์ค  
> ๋ง์คํฌ ์ฐฉ์ฉ ์ํ, ์ฐ๋ น๋, ์ฑ๋ณ์ ๊ตฌ๋ถํ๊ณ , ๋ง์คํฌ๋ฅผ ์ฌ๋ฐ๋ฅด๊ฒ ์ฐฉ์ฉํ์ง ์์์ ์ ๊ฒฝ๊ณ ๋ฉ์ธ์ง๋ฅผ ๋์์ค  

## ๐ Team

|                            ํ์ ํ                            |                            ์์ฑ๋ฏผ                            |                            ์ด์คํ                            |                            ์ค์ฃผ์                            |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| [![Avatar](https://avatars.githubusercontent.com/u/54921730?v=4)](https://github.com/herjh0405) | [![Avatar](https://avatars.githubusercontent.com/u/49228132?v=4)](https://github.com/mickeyshoes) | [![Avatar](https://avatars.githubusercontent.com/u/49234207?v=4)](https://github.com/kmouleejunhyuk) | [![Avatar](https://avatars.githubusercontent.com/u/69762559?v=4)](https://github.com/Jy0923) |
|                  `์ผ๊ตด ์ธ์ ๋ฐ ๋ถ๋ฅ ๋ชจ๋ธ๋ง`                  |                     `๋ชจ๋ธ ์๋น` `๋ฐฑ์๋`                     |                   `๋ชจ๋ธ ๊ฒฝ๋ํ` `์์ด๋์ด`                   |                         `ํ๋ก ํธ์๋`                         |

## ์ฌ์ฉ๋ฐฉ๋ฒ
![32](https://user-images.githubusercontent.com/49234207/138724656-beb67505-76c9-4bb6-85cf-f258c7cba173.png)
  

## ํ๋ก์ธ์ค flow
![process](https://user-images.githubusercontent.com/49234207/138725376-95a17c4e-d0d0-426e-bab0-fe7ce502f3ac.png)
*update(20211102): ๋งํฌ์์๋ ์ด์  cropface ํด๋์ค๋ฅผ ์ฌ์ฉํด ์ผ๊ตด์ด ์์ ๊ฒฝ์ฐ NO Face ๋ผ๋ฒจ์ ์ถ๋ ฅํฉ๋๋ค

### File Structure
```text
Mask_Status_Classification
โโโ README.md
โโโ future
โ   โโโ cam.py          # use local cam
โโโ main.py             # execute main
โโโ model.onnx
โโโ model.pickle
โโโ requirements.txt
โโโ templates
โ   โโโ index.html
โโโ utils
    โโโ modelserve.py   # quantize model
```

### Install Requirements
```
$ pip install -r requirements.txt
```

### Run server

```
$ python main.py
```
