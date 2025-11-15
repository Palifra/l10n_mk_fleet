# Macedonian Translations for Odoo 18 Fleet Module
# Македонски преводи за Odoo 18 Fleet модул

[![License: LGPL-3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)
[![Odoo Version](https://img.shields.io/badge/Odoo-18.0-875A7B.svg)](https://www.odoo.com/)
[![Language](https://img.shields.io/badge/Language-Macedonian-red.svg)](https://en.wikipedia.org/wiki/Macedonian_language)

## 📋 Overview / Преглед

This module provides **Macedonian (mk_MK)** translations for the Odoo 18 Fleet/Vehicle Management module.

Овој модул обезбедува **македонски (mk_MK)** преводи за Odoo 18 Fleet/Vehicle Management модулот.

## 📊 Translation Statistics / Статистика на преводот

- **Total entries:** 445
- **Translated:** 445 (100%)
- **Quality:** 100% (all placeholders and HTML preserved)
- **Characters:** 9,000+

### Coverage / Покриеност

- ✅ Vehicle / Возило
- ✅ Fleet / Флота
- ✅ Driver / Возач
- ✅ Service / Сервис
- ✅ Contract / Договор
- ✅ Cost / Трошок
- ✅ Fuel / Гориво
- ✅ Odometer / Километража
- ✅ Maintenance / Одржување
- ✅ Insurance / Осигурување

## 🚀 Installation / Инсталација

### Method 1: Manual Installation

1. Download this module:
```bash
cd /path/to/odoo/addons
git clone https://github.com/Palifra/l10n_mk_fleet.git
```

2. Restart Odoo:
```bash
sudo systemctl restart odoo
# or
docker-compose restart odoo
```

3. Install the module:
   - Go to **Apps**
   - Remove the **Apps** filter
   - Search for **"North Macedonia - Fleet"**
   - Click **Install**

4. Activate Macedonian language:
   - Go to **Settings → Users → Preferences**
   - Select **Language → Macedonian / македонски јазик**
   - Click **Save**
   - Refresh the page (F5)

### Method 2: Docker

Add to your `docker-compose.yml`:
```yaml
volumes:
  - ./l10n_mk_fleet:/mnt/extra-addons/l10n_mk_fleet
```

## 📦 Dependencies / Зависности

- `fleet` (Odoo Fleet/Vehicle Management module)

## 🔧 Technical Details / Технички детали

### Module Structure / Структура на модулот

```
l10n_mk_fleet/
├── __init__.py
├── __manifest__.py
├── i18n/
│   └── mk_MK.po          # 445 translated terms
└── README.md
```

### Translation Quality / Квалитет на преводот

- ✅ **0 placeholder errors** - All `%(variable)s` placeholders preserved
- ✅ **0 HTML errors** - All HTML tags and attributes preserved
- ✅ **100% accuracy** - Verified with automated quality scanner

### Key Terminology / Клучна терминологија

| English | Македонски |
|---------|-----------|
| Vehicle | Возило |
| Fleet | Флота |
| Driver | Возач |
| Service | Сервис |
| Contract | Договор |
| Cost | Трошок |
| Fuel Log | Дневник на гориво |
| Odometer | Километража |
| Maintenance | Одржување |
| Insurance | Осигурување |

## 🌍 About Macedonian Language / За македонскиот јазик

Macedonian (македонски јазик) is a South Slavic language spoken primarily in North Macedonia. This translation follows official terminology used in automotive and fleet management contexts.

Македонскиот јазик е јужнословенски јазик што се зборува главно во Северна Македонија. Овој превод ја следи официјалната терминологија што се користи во автомобилски и fleet management контекст.

## 🤝 Contributing / Придонес

Contributions are welcome! If you find translation errors or have suggestions:

1. Open an issue on GitHub
2. Submit a pull request
3. Contact: info@eskon.com.mk

## 📄 License / Лиценца

This module is licensed under **LGPL-3.0** - same as Odoo.

## 👥 Credits / Заслуги

**Author / Автор:** ЕСКОН-ИНЖЕНЕРИНГ ДООЕЛ Струмица

**Translation Method / Метод на превод:**
- DeepL API (Beta Macedonian language)
- Automated masking technique for placeholder/HTML preservation
- Glossary-based consistency (3,681 terms)
- Manual quality control and corrections

**Tools Used / Користени алатки:**
- DeepL API for translation
- polib for PO file manipulation
- Custom masking algorithm for quality assurance
- Automated quality scanner for validation

## 📧 Contact / Контакт

- **Organization:** ЕСКОН-ИНЖЕНЕРИНГ ДООЕЛ Струмица
- **Email:** info@eskon.com.mk
- **Website:** https://www.eskon.com.mk
- **GitHub:** https://github.com/Palifra

## 🔗 Related Modules / Поврзани модули

- [l10n_mk_inventory](https://github.com/Palifra/l10n_mk_inventory) - Inventory/Stock translations
- [l10n_mk_invoicing](https://github.com/Palifra/l10n_mk_invoicing) - Invoicing/Accounting translations
- [l10n_mk_base](https://github.com/Palifra/l10n_mk_base) - Base module translations
- [l10n_mk_project](https://github.com/Palifra/l10n_mk_project) - Project management translations
- [l10n_mk](https://github.com/OCA/l10n-macedonia) - Chart of Accounts for North Macedonia

---

**Supported Odoo Version:** 18.0
**Language:** Macedonian (mk_MK)
**Last Updated:** 2025-11-15

**Среќно со македонскиот Odoo! 🇲🇰**
