<div align="center">
  <img src="icon.svg" alt="Our Free Model UA — безкоштовні моделі для DeepSeek Harness" width="120">

# dsh-our-free-model-ua

**Українська** | [English](README_EN.md) | [Русский](README_RU.md) | [简体中文](README_ZH.md)

  <img alt="license" src="https://img.shields.io/badge/license-MIT-263146?style=flat-square">
  <img alt="zero dependencies" src="https://img.shields.io/badge/dependencies-zero-4b6fff?style=flat-square">
  <img alt="build step" src="https://img.shields.io/badge/build%20step-none-7da1de?style=flat-square">
  <img alt="dsh kernels" src="https://img.shields.io/badge/dsh-0.1.5--0.1.7--rc.2-2f6f4f?style=flat-square">
  <img alt="localization" src="https://img.shields.io/badge/localization-100%25%20UA%20%7C%20RU-005BBB?style=flat-square">
  <br>
  <strong>Повна українська та східноєвропейська локалізація плагіна безкоштовних моделей для DeepSeek Harness (DSH).</strong>
</div>

---

## 🌟 Про плагін

**`dsh-our-free-model-ua`** — це адаптована, на 100% локалізована версія найпопулярнішого плагіна для DeepSeek Harness (**82,000+ ⭐**). Плагін відкриває прямий доступ до передових AI-моделей абсолютно безкоштовно, без необхідності реєстрації, введення API-ключів чи оплати.

Усі 927 текстових ключів, діалогових вікон, графіків, теплових карт, статусів та підказок перекладено живою, професійною українською мовою без машинних кальок і спотворень.

---

## ✨ Основні можливості

* 🆓 **Безкоштовний доступ до топових моделей**: DeepSeek V4.1 Flash, Kimi K3, Muse Spark, MiMo та багатьох інших.
* 🧠 **Керування міркуваннями (Thinking / Reasoning Effort)**: Реальний контроль бюджету токенів на міркування (від мінімального до максимального).
* 🔄 **Локальний OpenAI-сумісний шлюз**: Можливість використовувати моделі з плагіна у сторонніх програмах (Cherry Studio, NextChat, VS Code, Cursor) через стандартний ендпоінт `http://127.0.0.1:18900/v1`.
* 📊 **Аналітичний дашборд**: Теплова карта активності, підрахунок заощаджених токенів, статус швидкості першого токена та стабільність каналів.
* 🌐 **Повна локалізація (100%)**:
  * 🇺🇦 **Українська**: Повний рідний інтерфейс.
  * 🇷🇺 **Російська**: Повна підтримка для сумісності.
  * 🇬🇧 **Англійська** та 🇨🇳 **Китайська** збережені як альтернативні варіанти.
* ⚡ **Zero Dependencies у веб-оболонці**: Не потребує збірки, працює на чистих веб-компонентах та швидкому ModuleLoader.

---

## 🚀 Встановлення

### Варіант 1: Встановлення через DSH

У терміналі вашого середовища DeepSeek Harness виконайте команду:

```powershell
dsh plugin add Kdjkvv7886/dsh-our-free-model-ua
```

Або через pnpm у профілі DSH:

```powershell
cd ~/.dsh/profiles/desktop
pnpm add https://github.com/Kdjkvv7886/dsh-our-free-model-ua.git
```

### Варіант 2: Автономний режим (Standalone)

Плагін також може працювати як повністю автономний локальний сервер без встановлення самого DSH:

```powershell
git clone https://github.com/Kdjkvv7886/dsh-our-free-model-ua.git
cd dsh-our-free-model-ua
npm install
npm run start:standalone
```

Після запуску у терміналі з'явиться безпечне одноразове посилання для відкриття панелі керування у браузері (за замовчуванням порт `18900`).

---

## ⚙️ Сумісність з OpenAI API

Якщо ви хочете підключити сторонній застосунок (наприклад, [Cherry Studio](https://github.com/CherryHQ/cherry-studio)):

* **API Base URL**: `http://127.0.0.1:18900/v1`
* **API Key**: Будь-який довільний рядок (наприклад, `sk-dsh-free`)
* **Моделі**: Автоматично транслюються з каталогу плагіна.

---

## 🛠️ Структура локалізації

- `locale/uk.json`: Метадані та опис для каталогу DSH українською мовою.
- `locale/ru.json`: Метадані для російськомовного середовища.
- `client.js`: Повний словник `DICT.uk` та `DICT.ru` (927 ключів), адаптований рендерер та обробник мовних налаштувань.

---

## 👤 Автор локалізації

- **Автор / Maintainer**: [Xila (Kdjkvv7886)](https://github.com/Kdjkvv7886)
- **Оригінальний проєкт**: [Ebony-Vinyl/dsh-our-free-model](https://github.com/Ebony-Vinyl/dsh-our-free-model)

## 📄 Ліцензія

Розповсюджується під ліцензією [MIT](LICENSE).
