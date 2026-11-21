<div align="center">
  <img src="icon.svg" alt="Our Free Model UA — бесплатные модели для DeepSeek Harness" width="120">

# dsh-our-free-model-ua

[Українська](README.md) | [English](README_EN.md) | **Русский** | [简体中文](README_ZH.md)

  <img alt="license" src="https://img.shields.io/badge/license-MIT-263146?style=flat-square">
  <img alt="zero dependencies" src="https://img.shields.io/badge/dependencies-zero-4b6fff?style=flat-square">
  <img alt="build step" src="https://img.shields.io/badge/build%20step-none-7da1de?style=flat-square">
  <img alt="dsh kernels" src="https://img.shields.io/badge/dsh-0.1.5--0.1.7--rc.2-2f6f4f?style=flat-square">
  <img alt="localization" src="https://img.shields.io/badge/localization-100%25%20UA%20%7C%20RU-005BBB?style=flat-square">
  <br>
  <strong>Полная украинская и восточноевропейская локализация плагина бесплатных моделей для DeepSeek Harness (DSH).</strong>
</div>

---

## 🌟 О плагине

**`dsh-our-free-model-ua`** — это адаптированная, на 100% локализованная версия популярнейшего плагина для DeepSeek Harness (**82,000+ ⭐**). Плагин открывает прямой доступ к передовым AI-моделям абсолютно бесплатно, без необходимости регистрации, ввода API-ключей или оплаты.

Все 927 текстовых ключей, диалоговых окон, графиков, тепловых карт, статусов и подсказок переведены на естественный, профессиональный украинский и русский языки.

---

## ✨ Основные возможности

* 🆓 **Бесплатный доступ к топовым моделям**: DeepSeek V4.1 Flash, Kimi K3, Muse Spark, MiMo и многим другим.
* 🧠 **Управление рассуждениями (Thinking / Reasoning Effort)**: Реальный контроль бюджета токенов на рассуждения (от минимального до максимального).
* 🔄 **Локальный OpenAI-совместимый шлюз**: Возможность использовать модели из плагина в сторонних программах (Cherry Studio, NextChat, VS Code, Cursor) через стандартный эндпоинт `http://127.0.0.1:18900/v1`.
* 📊 **Аналитический дашборд**: Тепловая карта активности, подсчет сэкономленных токенов, статус скорости первого токена и стабильность каналов.
* 🌐 **Полная локализация (100%)**:
  * 🇺🇦 **Украинский**: Родной интерфейс.
  * 🇷🇺 **Русский**: Полная поддержка для совместимости.
  * 🇬🇧 **Английский** и 🇨🇳 **Китайский** сохранены как альтернативные варианты.
* ⚡ **Zero Dependencies в веб-оболочке**: Не требует сборки, работает на чистых веб-компонентах и быстром ModuleLoader.

---

## 🚀 Установка

### Вариант 1: Установка через DSH

В терминале вашего окружения DeepSeek Harness выполните команду:

```powershell
dsh plugin add Kdjkvv7886/dsh-our-free-model-ua
```

Или через pnpm в профиле DSH:

```powershell
cd ~/.dsh/profiles/desktop
pnpm add https://github.com/Kdjkvv7886/dsh-our-free-model-ua.git
```

### Вариант 2: Автономный режим (Standalone)

Плагин также может работать как полностью автономный локальный сервер без установки самого DSH:

```powershell
git clone https://github.com/Kdjkvv7886/dsh-our-free-model-ua.git
cd dsh-our-free-model-ua
npm install
npm run start:standalone
```

---

## 👤 Автор локализации

- **Автор / Maintainer**: [Xila (Kdjkvv7886)](https://github.com/Kdjkvv7886)
- **Оригинальный проект**: [Ebony-Vinyl/dsh-our-free-model](https://github.com/Ebony-Vinyl/dsh-our-free-model)

## 📄 Лицензия

Распространяется под лицензией [MIT](LICENSE).
