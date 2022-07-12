# React_app_template
Шаблон для React-приложения, описывающий структуру файлов

## Структура папок:
<pre>
.
│   package-lock.json // файл, предназначенный для отслеживания точных версий установленных пакетов  
│   package.json  // файл-манифест, содержит информацию о названии, текущей версии приложения, зависимостях и т.д.  
│   README.md  
│  
├───public  
│       index.html // основная страница  
│  
└───src  
    │   App.css // стиль компонента App  
    │   App.js // компонент App, обычно включает в себя остальные компоненты  
    │   index.css // стиль основной страницы  
    │   index.js // рендерит компонент App  
    │  
    └───components // папка с дочерними компонентами  
        ├───Footer // папка для описание компонента Footer  
        │       Footer.css // стиль компонента App  
        │       Footer.js // компонент App  
        │  
        ├───Header // папка для описание компонента  
        │       Header.css // стиль компонента Header  
        │       Header.js // компонент Header  
        │  
        └───Sidebar // папка для описание компонента  
                Sidebar.css // стиль компонента Sidebar  
                Sidebar.js // компонент Sidebar  
</pre>
