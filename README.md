# enb-css-preprocessor [![Build Status](https://travis-ci.org/enb-make/enb-css-preprocessor.svg)](https://travis-ci.org/enb-make/enb-css-preprocessor)

**Модуль устарел!** Рекомендуется использовать плагины [postcss](https://github.com/postcss/postcss): [postcss-import](https://github.com/postcss/postcss-import) + [postcss-url](https://github.com/postcss/postcss-url).

Данный модуль перенесен из [enb@0.17.x](https://github.com/enb-make/enb/blob/v0.17.2/lib/preprocess/css-preprocessor.js) для обратной совместимости с [enb@1.x](https://github.com/enb-make/enb/tree/v1.0.0).

## Установка

**Требования:** зависимость от пакета [enb](https://github.com/enb-make/enb) версии `0.16.0` или выше.

```bash
$ npm install enb-css-preprocessor --save-dev
```

## Использование

```js
var CssPreprocessor = require('enb-css-preprocessor');
var preprocessCss = new CssPreprocessor();
```

**API** модуля можно посмотреть в [исходниках](./lib/css-preprocessor.js).

## Лицензия

© 2015 YANDEX LLC. Код лицензирован [Mozilla Public License 2.0](LICENSE.txt).
