### Основные настройки vscode

Расположение `File > Preferences > Settings > Open Settings (JSON)

```jsonc
{
  // Выключаем крошки
  "breadcrumbs.enabled": false,

  // Выключаем мини-карту
  "editor.minimap.enabled": false,

  // Выставляем отступы
  "editor.padding.top": 11,
  "editor.padding.bottom": 11,

  // Выставляем размер отступов
  "editor.tabSize": 4,

  // Включаем перенос строк
  "editor.wordWrap": "on",

  // Выключаем мигание указателя
  "editor.cursorBlinking": "solid",

  // Подключаем шрифт с легатурой и фоллбэки
  "editor.fontFamily": "'JetBrains Mono', 'Operator Mono SSm Lig', 'Fira Code', 'Cascadia Code', Consolas, monospace",

  // Выставляем размеры и отступы
  "editor.fontWeight": 200,
  "editor.fontSize": 13,
  "editor.lineHeight": 24,

  // Включаем те самые лигатуры
  "editor.fontLigatures": true,
  "editor.renderControlCharacters": false,

  // Форматируем код при сохранении
  "editor.formatOnSave": true,

  // Форматер по умолчанию для всего что не в окружении
  "editor.defaultFormatter": "esbenp.prettier-vscode",

  // Предупреждаем при удалении
  "explorer.confirmDelete": false,

  // Непонятно что это тут делает ...
  "explorer.confirmDragAndDrop": false,

  // Определяем окружение для html
  "[html]": {
    // Форматер по умолчанию для html
    "editor.defaultFormatter": "vscode.html-language-features"
  },

  // Определяем окружение для javascript
  "[javascript]": {
    // Форматер по умолчанию для javascript
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  // Параметры для Go
  "go.useLanguageServer": true,
  "go.languageServerExperimentalFeatures": {
    "diagnostics": true // Что-то тут проверяем ...
  },

  // Что-то обновляем ...
  "go.toolsManagement.autoUpdate": true,

  // Определяем окружение для Go
  "[go]": {
    // Форматер по умолчанию для Go
    "editor.defaultFormatter": "golang.go",

    // "editor.snippetSuggestions": "none", // Если закомментировано, значит так было нужно ...

    // Форматируем код при сохранении
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
      "source.organizeImports": true
    }
  },

  // Выключаем подтверждение при синхронизации Git
  "git.confirmSync": false,

  // Что-то связанное с коммитами ...
  "git.enableSmartCommit": true,

  // SSH доступные сервера. Если имеется расширение RemoteSSH
  "remote.SSH.remotePlatform": {
    "HK": "linux"
  },

  // Отступы для дерева
  "workbench.tree.indent": 12,

  // Убираем приветствие
  "workbench.startupEditor": "none",

  // Что-то определяем. Непонятно как это тут оказалось ...
  "workbench.editorAssociations": [
    {
      "viewType": "jupyter.notebook.ipynb",
      "filenamePattern": "*.ipynb"
    }
  ],

  // Задаем тему
  "workbench.colorTheme": "Material Theme"
}
```
