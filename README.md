- Превью: https://kseylo.github.io/3-column-preview-card-component/
## Установка:

Установка node_modules
```
pnpm install
```

Запуск
```
pnpm dev
```


## Скриншоты:

### ПК:
![desktop](screenshots/desktop.png)

### Телефон:
![preview](screenshots/mobile.png)

## Технологии которые использовал:
- HTML
- CSS

## Проблемы с которыми столкнулся:

- Подзабыл как использовать media-queries

Решение:
```css
/* Для телефонов */
@media screen and (max-width: 70em) {
	/* какой-то код */
}

/* Для пк */
@media screen and (min-width: 70em) {
	/* какой-то код */
}
```
