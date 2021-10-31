# 비콘기반 코로나 알리미
>비콘기반 코로나 알리미를 제작하기 위한 프로그램의 일부분이다
* GUI
* Chat Bot

<br>

## ⚙ STRUCTURE
![structure](https://github.com/PGWOO/Lab1/blob/main/structure.png)
* 최종제출물의 전체적인 구조
* 본인이 구현한 부분은 빨간색 파트

<br>

## Chat Bot Service
코로나 확진자가 방문했을 시, 매장주인에게 '코로나 확진자 방문'이라는 알림이 가도록 한다
```python
import telegram
from telegram.ext import Updater
from telegram.ext import MessageHandler, Filters
```
- Chat Bot ID : @Corona19_update_bot
1. socket을 통해 입력받은 방문자 확진여부 판정
2. 확진판정시, telegram의 Chat Bot으로 매장주인에게 알림
<br>

### 🧷 Chat Bot Image
![ChatBotImage](https://github.com/PGWOO/Lab1/blob/main/ChatBotFrofile.png)
![ChatBotImage](https://github.com/PGWOO/Lab1/blob/main/ChatBotsend.png)

<br>

<br>

## GUI system
코로나 확진자가 방문했을 시, 매장내 모니터에 경고 알림창을 띄운다.
```python
import tkinter.messagebox as msgbox
from tkinter import *
```
![Gui](https://github.com/PGWOO/Lab1/blob/main/GUI.png)

<br>

## Libraries
* tkinter : To implement the GUI
* telegram : To implement the chatbot

  
 
