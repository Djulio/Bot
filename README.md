# PlaceBG Bot
Fork от бота на PlaceNL Bot. Thanks guys!  
Бот за PlaceBG! На всеки няколко минути, ботът дърпа [плановете](https://github.com/placeDE/pixel), um zu verhindern, dass Bots miteinander kollidieren.

## Инсталация

Провери, че може да се поставя нов пиксел и не си на cooldown (нямаш течащ таймер отдолу)

1. Инсталирай browser extension-на [Tampermonkey](https://www.tampermonkey.net/) или [Violentmonkey (Firefox)](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/).
2. Отвори този линк: [https://github.com/justMemou/Bot/blob/main/placedebot.user.js](https://github.com/justMemou/Bot/blob/main/placedebot.user.js). Ако всичко е както трябва, Tampermonkey ще предложи да инсталира скрипта. Кликни на **Инсталирай**/**Install**.
3. Отвори страницата или таба с **r/place**. Ако вече ти е отворена - презареди я (F5). Ако всичко е наред, ще видиш съобщенията от скрипта в горния десен ъгъл "Заявка за токен...". Това означава, че бота е активен и ще започне да поставя пиксели. Следи информацията в горния десен ъгъл, за да видиш какво прави скрипта.

## Слабости на бота

- Ботът не актуализира съобщението за cooldown-на, така че изглежда, че може да се постави друг пиксел. Въпреки това ботът вече е поставил пиксела и сега изчаква cooldown-на. При презареждане на страницата, можеш да видиш текущия cooldown.
- Ботът не проверява дали имаш течащ cooldown! Затова преди да го стартираш, провери дали не ти тече таймерът. В най-лошия случай, ботът ще постави новия пиксел след 5 минути.