# Структура

```
src
|── features
|   └── form
|       |── index.js
|       |── form.jsx
|       |── test.js
|       |── readme.md
|       |── model
|       └── ui
|           └── templates
|               └── form-template.jsx
|── api
|── pages
|   |── slide-1
|   └── slide-2
|── routes
└── ui
|   └── assets
|   |   |── fonts
|   |   |── images
|   |   └── svg
|   └── atoms
|   |   └── button
|   |      |── index.js
|   |      |── style.js
|   |      |── test.js
|   |      |── readme.md
|   |      └── button.jsx
|   |── molecules
|   |── organisms
|   └── templates
└── lib
```


##  Алиасы

```js
import { Feature } from '@features';
import { Buttom, Icon } from '@ui';
import { getData } from '@api';
import { Slide_1 } from '@pages';
import { arrowIcon } from '@icons';
```

## Atomic design

![atomic design](http://bradfrost.com/wp-content/uploads/2015/12/atomic-gif-3.gif)

![atomic design](https://miro.medium.com/max/1575/1*-EpDbcdrdn_sgz5AbRAHFw.gif)

![atomic design](https://miro.medium.com/max/2048/1*i1H2mYXq_v1tSs587n2zwg.gif)
