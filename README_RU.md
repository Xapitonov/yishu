# ![icon](data/icon.png) Yishu (艺术)

[English](README.md) | **Русский**

## Простой и оригинальный клиент Todo.txt

[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.lainsce.yishu)

[![Build Status](https://travis-ci.org/lainsce/yishu.svg?branch=master)](https://travis-ci.org/lainsce/yishu)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)

![Screenshot](data/shot.png)

## Пожертвования

Хотите поддержать развитие этого приложения и вывести его на новый уровень? Тогда:

[Поддержите меня на Patreon](https://www.patreon.com/lainsce)

## Зависимости

Перед сборкой убедитесь, что у вас установлены следующие зависимости.

```bash
granite
gtk+-3.0
meson
libhandy-1
```

Сборка

Просто клонируйте этот репозиторий, затем выполните:

```bash
meson build && cd build
meson configure -Dprefix=/usr
sudo ninja install
```
