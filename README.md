<!-- Переход на внешнюю страницу -->
rel="noreferrer noopener"


<!-- Скрытие заголовка -->
.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  border: 0;
  padding: 0;  
  white-space: nowrap;
  clip-path: inset(100%);
  clip: rect(0 0 0 0);
  overflow: hidden;
}
<!-- Сброс стилей -->
p, h1, h2, h3, h4, h5, h6 {
  margin: 0;
}

ul, ol {
  margin: 0;
  padding-left: 0;
}

html {
  box-sizing: border-box;
}

*, 
*::before,
*::after {
  box-sizing: inherit;
}

img {
  display: block;
  max-width: 100%;
  height: auto;
}

button {
  display: block;
  cursor: pointer;
  border: none;
  border-radius: 4px;
}


<!-- Отмена подчеркивания -->
.list {
  list-style: none;
}

<!-- Позиционирование по центру -->

 position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);