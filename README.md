# ๐ Book Mark Saver

ํฅํด99 12๊ธฐ 12์กฐ ํ ์ดํ๋ก์ ํธ 23.01.09 - 23.01.12

## ํ์

| ํ์   | ์คํ         | ํ์๊ตฌ๋ถ | ๊นํ๋ธ                                          | ๋ธ๋ก๊ทธ                                                   |
| ------ | ------------ | -------- | ----------------------------------------------- | -------------------------------------------------------- |
| ๊น์ ์ค | `ํ๋ก ํธ์๋` | `ํ์ฅ`   | [Seogun95](https://github.com/Seogun95)         | [์๊ทผ๊ฐ๋ฐ๋ธํธ](https://seons-dev.tistory.com/)         |
| ๋ฐ์ฑ์ธ | `ํ๋ก ํธ์๋` | ํ์     | [Adult96](https://github.com/Adult96)           | [Adultํ](https://adult.tistory.com/)                  |
| ๋๋๊ด | `๋ฐฑ์๋`     | ํ์     | [DOGWANNA](https://github.com/DOGWANNA)         | [๊ฐ๋ฐ ๊ฟ๋๋ฌด์ ์ฑ์ฅ์ผ๊ธฐ](https://9401ndk.tistory.com/) |
| ์ ๊ฒฝ์ฐ | `๋ฐฑ์๋`     | ํ์     | [bestfarmer94](https://github.com/bestfarmer94) | [bestfarmer](https://velog.io/@bestfarmer)             |

## ํ๋ก์ ํธ ์๊ฐ

**Book Mark Saver**์ ๋ก๊ทธ์ธ์ ํ๊ณ  ๋ณธ์ธ๋ง์ ํ๋ผ์ด๋นํ ์น์ฌ์ดํธ๋ฅผ ์ ์ฅํด๋ณด์ธ์! 

์นดํ๊ณ ๋ฆฌ๋ณ / ํ๊ทธ๋ณ๋ก ์ ์ฅ๋ ๊ฐ๋ฅํ๊ณ  ํ์ํ๋ค๋ฉด ์ญ์ ๊น์ง!

 ๊น๋ํ UI๋ฅผ ํตํด ์ ์ฅํ๋ ค๋ ์น์ฌ์ดํธ์ ์ด๋ฏธ์ง์ ํ์ดํ์ ํ์ธํ์ค ์ ์์ต๋๋ค.



## ํ๋ก์ ํธ ์์ฐ ์์

[Book Mark Saver Youtube](https://www.youtube.com/watch?v=4hvtKdHu_VM)

## ๊ธฐ์  ์คํ

<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"><img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"><img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"><img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"><img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">

<img src="https://img.shields.io/badge/mongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white"><img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white">

## ์ฌ์ฉํ ๋ผ์ด๋ธ๋ฌ๋ฆฌ

[toastr](https://codeseven.github.io/toastr/), [tagify](https://yaireo.github.io/tagify/), [AOS](https://michalsnik.github.io/aos/)

## API Table

| Index | Method | URL            | Desc                               | Request                     | Response                      |
| ----- | ------ | -------------- | ---------------------------------- | --------------------------- | ----------------------------- |
| 1     | `POST` | /login         | ๋ก๊ทธ์ธ/ํ์๊ฐ์                    | id, password, passwordCheck | /token                        |
| 2     | `POST` | /token         | ํ ํฐ ๋ฐ ์ฟ ํค์์ฑ                   | id, password                | token /main                   |
| 3     | `GET`  | /main          | ๋ฉ์ธํ๋ฉด(์ฟ ํคO), ๋ก๊ทธ์ธํ๋ฉด(์ฟ ํคX) |                             | /show_bookmark or login.html  |
| 4     | `POST` | /show_bookmark | ๋ฉ์ธํ๋ฉด ๋ฆฌ์คํธ์์ฑ                | (id)                        | bookmarks_list, category_list |
| 5     | `POST` | /save_bookmark | ๋ถ๋งํฌ ์ถ๊ฐ                        | (id) url, comment, category | /show_bookmark                |
| 6     | `POST` | /delete        | ๋ถ๋งํฌ ์ญ์                         | number                      | /main                         |

## ๊ตฌํ ๊ธฐ๋ฅ

### 1. ๋ฉ์ธ ํ์ด์ง

![CleanShot 2023-01-14 at 18 02 09](https://user-images.githubusercontent.com/76584961/212464545-995c421b-fca8-4d5d-bd22-7469f39ad8e4.png)

typing ํ์คํธ ํจ๊ณผ๋ฅผ ํฌํจํ ๋ฉ์ธ ํ ํ์ด์ง. ๋ฐ๋ก ์์ํ๊ธฐ ํด๋ฆญ์ ๋ก๊ทธ์ธ ํ์ด์ง๋ก ์ด๋

### 2. ๋ก๊ทธ์ธ ํ์ด์ง

![CleanShot 2023-01-14 at 18 03 22](https://user-images.githubusercontent.com/76584961/212464563-5b43bf5a-2cd5-4dd7-a0da-d403adc58b25.png)

`PyJWT` ๋ฐฉ์์ผ๋ก ์ฟ ํค๋ฅผ ์ฌ์ฉํด ๊ตฌํ. ํ์ ๊ฐ์ ๋ฒํผ ํด๋ฆญ์ `input`์ด ์ถ๊ฐ๋๋ฉฐ ํ์๊ฐ์์ ์งํ ํ  ์ ์๋ค. ์ค๋ณต ์์ด๋ ๋๋ ๋ง์ง ์์ ํจ์ค์๋๋ฅผ ์๋ ฅ์ `Toastr` ๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ฅผ ์ฌ์ฉํ `Toast` ๋ฉ์ธ์ง๊ฐ ๋ํ๋๋ค.

### 3. ๋ฉ์ธ ํ์ด์ง
![image-20230114165524196](https://user-images.githubusercontent.com/76584961/212464577-326adf10-0cdc-4b3a-8330-b328488ec45e.png)
![image](https://user-images.githubusercontent.com/76584961/212464618-bdca6691-c800-4527-b582-799142da9f72.png)
์ ์ฅํ  ์ฌ์ดํธ์ URL, ์นดํ๊ณ ๋ฆฌ, ํ๊ทธ๋ฅผ ์๋ ฅํ๊ฒ ๋๋ฉด ํด๋น ์น์ฌ์ดํธ์ ์ธ๋ค์ผ๊ณผ ํด๋ฆญํด ์ด๋ํ  ์ ์๋ ๋งํฌ, ์นดํ๊ณ ๋ฆฌ์ ํ๊ทธ๊ฐ ๋ํ๋๊ฒ ๋ฉ๋๋ค. ๊ทธ๋ฆฌ๊ณ  ๋ถ๋งํฌ๋ฒํผ์ ๋๋ฅด๊ฒ ๋๋ฉด ์ ๋ฉ์ธ ํ์ด์ง ์ด๋ฏธ์ง ์ฒ๋ผ ์๋์ ํฌ์คํธ์นด๋ ํ์์ผ๋ก ๋ฟ๋ ค์ง๊ฒ ๋ฉ๋๋ค.
#### 3-1 ๊ตฌํ ํ๋ฉด
![CleanShot 2023-01-15 at 00 03 48](https://user-images.githubusercontent.com/76584961/212478632-6c59c561-6659-4e51-85fa-83ca4b56b402.gif)

