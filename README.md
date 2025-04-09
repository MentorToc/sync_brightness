# sync_brightness.sh (Linux)

🇺🇸 <b>Synchronizing the brightness of displays in Linux</b>

When using different Linux distributions, I have encountered the same problem: When changing the screen brightness on the laptop, the screen brightness on the second display does not change.

I found a solution by using a script that automatically pulls up the current screen brightness, extending it to the second display.

The script caches the brightness information, thus not creating an unnecessary load by constantly changing the screen brightness. Works with both X11 and Wayland.

<b>Installation</b>

1. Install dependencies:
   * ddcutil
   * brightnessctl
   * wget
   * screen or systemctl

2. Coming soon

---------------------------------------------------

🇷🇺 <b>Синхронизация яркости дисплеев в Linux</b>

При использовании различных Linux-дистрибутивов я сталкивался с одной и той же проблемой: При изменении яркости экрана на ноутбуке не меняется яркость экрана на втором дисплее.

Я нашёл решение в использовании скрипта, который в автоматическом режиме подтягивает текущую яркость экрана, распространяя её и на второй дисплей.

Скрипт кэширует информацию о яркости, тем самым не создавая излишней нагрузки, постоянно изменяя яркость экрана. Работает как с X11, так и с Wayland.

Установка

1. Установите зависимости:
   * ddcutil
   * brightnessctl
   * wget
  
2. Совсем скоро
