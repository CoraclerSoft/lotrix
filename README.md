<div align="center">

<img src="images/logo.svg" width="110" alt="Lotrix">

# Lotrix

**Бесплатный бот для продавцов FunPay — приложение для Windows**<br>
Без Python, сервера и конфигов: установил, вставил ключ, включил.

[![Скачать](https://img.shields.io/badge/⬇_Скачать-Lotrix_1.0-0a84ff?style=for-the-badge)](https://github.com/CoraclerSoft/lotrix/releases/latest/download/Lotrix-Setup-1.0.0-x64.exe)
[![Telegram](https://img.shields.io/badge/Telegram-@coraclersoft-2ea6ff?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/coraclersoft)

[![VirusTotal](https://img.shields.io/badge/VirusTotal-0%20%2F%2061-30d158?style=flat-square)](https://www.virustotal.com/gui/file/9d511e381ec1c2ccfd9c43dca9ed17663d909c99f17fc50a9bbcfd3551c41c59)
![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-5e5ce6?style=flat-square)
![Цена](https://img.shields.io/badge/цена-бесплатно-30d158?style=flat-square)
![Версия](https://img.shields.io/github/v/release/CoraclerSoft/lotrix?style=flat-square&label=версия&color=8e8cff)

<img src="images/lotrix-card.png" alt="Lotrix — FunPay работает, пока вы спите">

</div>

## Что умеет

| | |
|---|---|
| 🔼 **Автоподнятие** | Поднимает все ваши разделы, как только FunPay разрешает. Таймер берётся из ответа FunPay, лишних запросов нет. В трее есть «Поднять лоты сейчас» |
| 📦 **Автовыдача** | Заказ оплачен → товар сразу уходит в чат заказа от вашего имени. Товары хранятся только у вас в приложении, на FunPay не загружаются |
| 💬 **Чаты и автоответы** | Вся переписка в одном окне, быстрые ответы, приветствие, ответы по ключевым словам, свой шаблон ответа на отзыв для каждой оценки |
| 🛒 **Автоскупка** | Следит за разделами по вашим фильтрам и цене «от – до» и присылает новые лоты в Telegram с кнопкой «✅ Купить». Покупает только после вашего нажатия |
| 🔎 **Маркет** | Поиск и покупка любых лотов FunPay с фильтрами, как на сайте. Подсвечивает, каким способом оплаты дешевле всего |
| 🧾 **Лоты** | Редактор как на сайте, описание RU и EN с автопереводом, копирование лота, пачка лотов из .txt |
| 💰 **Финансы** | Баланс, операции, вывод денег. Заявка уходит только по вашей кнопке |
| 👥 **Аккаунты и прокси** | Несколько аккаунтов, свой прокси (HTTP / SOCKS5) на каждый, уведомления в Windows и Telegram |

## Скриншоты

<table>
<tr>
<td><img src="images/01-obzor.png" alt="Обзор"></td>
<td><img src="images/02-podnyatie.png" alt="Поднятие"></td>
</tr>
<tr>
<td align="center">Обзор — ваш профиль, продажи и выручка</td>
<td align="center">Автоподнятие по таймеру FunPay</td>
</tr>
<tr>
<td><img src="images/03-avtovydacha.png" alt="Автовыдача"></td>
<td><img src="images/04-chaty.png" alt="Чаты"></td>
</tr>
<tr>
<td align="center">Автовыдача: товары хранятся у вас</td>
<td align="center">Чаты с быстрыми ответами</td>
</tr>
<tr>
<td><img src="images/06-avtoskupka.png" alt="Автоскупка"></td>
<td><img src="images/07-market.png" alt="Маркет"></td>
</tr>
<tr>
<td align="center">Автоскупка с кнопкой «Купить» в Telegram</td>
<td align="center">Маркет: любые лоты FunPay</td>
</tr>
<tr>
<td><img src="images/08-deshevle-vsego.png" alt="Дешевле всего"></td>
<td><img src="images/10-finansy.png" alt="Финансы"></td>
</tr>
<tr>
<td align="center">Самый дешёвый способ оплаты</td>
<td align="center">Финансы и вывод денег</td>
</tr>
</table>

<sub>На скриншотах демо-данные.</sub>

## Установка

1. Скачайте [**Lotrix-Setup-1.0.0-x64.exe**](https://github.com/CoraclerSoft/lotrix/releases/latest/download/Lotrix-Setup-1.0.0-x64.exe) (или переносную версию .zip в [релизах](https://github.com/CoraclerSoft/lotrix/releases)). Права администратора не нужны.
2. Если Windows покажет «Windows защитила ваш компьютер», нажмите «Подробнее» → «Выполнить в любом случае». У приложения пока нет платной цифровой подписи.
3. Во вкладке «Аккаунт» вставьте свой Golden Key: funpay.com → `F12` → Application → Cookies → `golden_key`.
4. Включите нужное: «Поднятие», «Автовыдача», «Автоответы». Окно можно закрыть, Lotrix останется работать в трее.

## Безопасность

- Golden Key вводите вы сами. Он хранится **только на вашем компьютере** в зашифрованном виде (Windows DPAPI) и отправляется **только на funpay.com**.
- У Lotrix нет своих серверов: ключ, товары для автовыдачи и переписка никуда не уходят.
- Деньги выводятся и лоты покупаются только по вашей кнопке и после подтверждения.
- Проверка файла: [VirusTotal — 0 / 61](https://www.virustotal.com/gui/file/9d511e381ec1c2ccfd9c43dca9ed17663d909c99f17fc50a9bbcfd3551c41c59).

```
SHA-256  Lotrix-Setup-1.0.0-x64.exe
9d511e381ec1c2ccfd9c43dca9ed17663d909c99f17fc50a9bbcfd3551c41c59
```

Проверить у себя в PowerShell: `Get-FileHash .\Lotrix-Setup-1.0.0-x64.exe`. Если хеш не совпадает, файл не наш, не запускайте.

## Вопросы

**Это бесплатно?** Да.

**Нужен ли включённый браузер?** Нет. Lotrix работает сам, в трее.

**Где новости и поддержка?** В Telegram-канале [@coraclersoft](https://t.me/coraclersoft).

---

<div align="center"><sub>© CoraclerSoft. Lotrix — независимый проект и не связан с FunPay.</sub></div>
