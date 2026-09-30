**Сборка и состав проекта**

Версия Unity: 6000.3.25f1 (Unity 6.3 LTS)

**Настройки сборки (Build Settings)**

* Платформа: Windows (Intel 64-bit)
* Сцена в сборке: IndieMarc/PlatformerDemo/PlatformerDemo (сцену TopDownDemo убрали из списка, потому что из-за неё падала сборка GitHub Actions)

Доступные платформы: только Windows. Остальные (macOS, Linux, Android, iOS, Web и другие) есть в списке, но неактивны, потому что их модули не установлены.

**Пакеты (Package Manager)**

Из Asset Store:

* Simple 2D Template 1.2

Пакеты Unity (добавились автоматически при создании проекта из шаблона Universal 2D):

* 2D Animation 13.0.6
* 2D Aseprite Importer 3.0.2
* 2D Common 12.0.4
* 2D PSD Importer 12.0.2
* 2D Sprite 1.0.0
* 2D SpriteShape 13.0.0
* 2D Tilemap Editor 1.0.0
* 2D Tilemap Extras 6.0.3
* 2D Tooling 1.0.4
* Burst 1.8.30
* Collections 2.6.8
* Custom NUnit 2.0.5
* Input System 1.20.0
* JetBrains Rider Editor 3.0.40
* Mathematics 1.3.3
* Mono Cecil 1.11.6
* Multiplayer Center 1.0.1
* Performance testing API 3.5.0
* Scriptable Render Pipeline Core 17.3.0
* Searcher 4.9.5
* Shader Graph 17.3.0
* Test Framework 1.6.0
* Timeline 1.8.13
* uGUI 2.0.0
* Unity Version Control 2.13.6
* Universal Render Pipeline 17.3.0
* Universal Render Pipeline Config 17.0.3
* Visual Scripting 1.9.12
* Visual Studio Editor 2.0.26

**Структура папок**

* Assets

  * IndieMarc

    * PlatformerDemo

      * Editor
      * Materials
      * Prefabs
      * Scripts
      * Sprites

        * Background
        * Character
        * Lever
      * Tilemap

        * Black
        * Old
  * Scenes
  * Settings

    * Scenes
* Packages
* ProjectSettings

**Ассеты**

* Спрайты: фон (деревья), персонаж, рычаг (в сцене не используется), тайлы для уровня
* Звуки: нет
* Материалы: SpriteDiffuseP, Tilemap, Trees1, Trees2, Trees3

**Размер проекта**

* Assets: 5,85 МБ
* Library: 2,02 ГБ
* Весь проект: 2,04 ГБ
* Репозиторий на GitHub: 1,41 МБ

Почти весь размер занимает папка Library. Это кэш, который Unity создаёт сам, поэтому она исключена через .gitignore и в репозиторий не попадает.

