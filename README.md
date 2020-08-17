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
