
# Sublime Text Config

Configuración y snippets para Sublime Text.

Los snippets son fragmentos de código para sistemas web en Python, Flask y Google Cloud DataStore.

### 1. Paquetes

Ejecutar

    CTRL-SHIFT-P > Install Package Control
    CTRL-SHIFT-P > Install Package

Instalar

* Language - Spanish
* Theme - Afterglow
* Python 3

Instalar color scheme

* Packages/Python 3/Gloom.tmTheme

Instalar diccionario

* Packages/Language - Spanish/es_ES.dic

### 2. Configuración

Editar `Preferences.sublime-settings`

    {
        "color_scheme": "Packages/Theme - Afterglow/Afterglow.tmTheme",
        "file_exclude_patterns":
        [
            ".directory",
            "*.pyc",
            "*.sublime-workspace"
        ],
        "folder_exclude_patterns":
        [
            ".git",
            "__pycache__"
        ],
        "font_face": "Hack",
        "font_size": 13,
        "ignored_packages":
        [
            "Vintage"
        ],
        "tabs_small": true,
        "theme": "Afterglow-orange.sublime-theme",
        "translate_tabs_to_spaces": true,
        "trim_trailing_white_space_on_save": true
    }

### 3. Snippets

Copie o haga enlances de los archivos sublime-snippet a `~/.config/sublime-text-3/Packages/User/`
