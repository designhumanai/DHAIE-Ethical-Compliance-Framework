# DHAIE Visual Assets Concept (Updated)

Концепция визуальных активов для стандарта DHAIE — обновлённая версия

*For discussion purposes — draft for internal review*
*Документ для обсуждения — черновик для внутреннего рассмотрения*

---

## 🏷 0. Core Brand Identity | Основная идентичность бренда

**Logo & Wordmark | Логотип и фирменное написание:**

* Concept: Geometric, modern, human-centered, minimalistic
* Цвет: основной — Platinum `#E5E4E2`, акценты — Bronze-Gold gradient
* Safe area: 16px от границ визуального блока
* Placeholder: `LOGO_PLACEHOLDER.svg / LOGO_PLACEHOLDER.png`
* Usage: Print, web, social media, dashboards

**Tone of Voice | Тон коммуникации:**

* Technical but approachable | Техничный, но доступный
* Authoritative yet inspiring | Авторитетный, но вдохновляющий
* Consistent terminology | Единая терминология, лаконичность

**Patterns & Textures | Паттерны и текстуры:**

* Digital pattern for Data Stewardship (code blocks, binary lines)
* Organic pattern for Socio-Economic Ecology (leaves, globe motifs)
* Abstract geometric gradients for Bronze-Gold-Platinum levels
* Placeholder files: `PATTERNS_PLACEHOLDER.svg / PATTERNS_PLACEHOLDER.png`

---

## 🎨 1. Design System | Дизайн-система

**Color Palette | Палитра цветов:**

* 🥉 Bronze: `#CD7F32` → gradient `#A65C1F`
* 🥈 Silver: `#C0C0C0` → gradient `#A0A0A0`
* 🥇 Gold: `#FFD700` → gradient `#FFB347`
* 💎 Platinum: `#E5E4E2` → gradient `#F5F5F5`

**Typography | Шрифты:**

* Headlines: **Inter Bold**, 24-36pt
* Body: **Inter Regular**, 14-16pt
* Data: **JetBrains Mono**, 12-14pt (для ECS показателей)

**Spacing System | Система отступов:**

* Base unit: 8px
* Scale: 8px → 16px → 24px → 32px → 48px

---

## 🖼 2. Icons for Principles | Иконки принципов

| # | Principle                 | Icon Concept                | Style Guide                        |
| - | ------------------------- | --------------------------- | ---------------------------------- |
| 1 | Active Partnership        | 🤝 Две переплетённые руки   | Контурный стиль, толщина линии 2px |
| 2 | Ethical Architecture      | 🛡️ Щит с узором кода       | Геометрический, симметричный       |
| 3 | Governance Ecosystem      | 🌐 Сеть соединённых узлов   | Точечный, соединённые круги        |
| 4 | Proactive Risk Management | 📈 Стрелка роста с щитом    | Динамичный, с направлением         |
| 5 | Transparency              | 🔍 Лупа над открытой книгой | Минималистичный, чистые линии      |
| 6 | Data Stewardship          | 🔐 Ключ с бинарным кодом    | Технический, точный                |
| 7 | Socio-Economic Ecology    | 🌱 Росток в глобусе         | Органический, плавные кривые       |

**Technical Specs | Технические характеристики:**

* Format: SVG + PNG (512×512, 256×256, 128×128)
* Style: Outline, 2px stroke, square canvas
* Color: Monochrome, adapts to level colors

---

## 🌳 3. Main Diagram: "Tree of Principles" | Дерево принципов

**Visual Structure | Визуальная структура:**

```
      [PLATINUM Fruits]
          /    \
[GOLD Branches]  [SILVER Branches]
         \\    //
      [BRONZE Trunk]
         //    \
[7 Roots - Principles]
```

**Implementation | Реализация:**

* Static: SVG with CSS variables for color themes
* Interactive: D3.js with hover effects showing principle details
* Animation: Lottie JSON showing growth from Bronze → Platinum

**Additional Concept | Дополнительная идея:**

* Isometric illustration of Ethical Architecture as trust framework

---

## 📊 4. ECS Compliance Scale | Шкала соответствия ECS

**Design | Дизайн:**

```
[BRONZE 33%]━━━━[SILVER 57%]━━━━[GOLD 81%]━━━━[PLATINUM 100%]
   ████████████████████████████████████████████████████████
```

**Variants | Варианты:**

* Horizontal progress bar with level badges
* Circular gauge for dashboards
* Minimal version for social media

---

## 📱 5. Social Media Toolkit | Набор для соцсетей

**Template Sizes | Размеры шаблонов:**

* Instagram: 1080×1080px (square), 1080×1350px (story)
* Twitter: 1200×675px (header), 800×418px (card)
* LinkedIn: 1200×627px (article)

**Content Blocks | Контент-блоки:**

* Principle Cards (icon + title + short description)
* Company Journey Timeline
* ECS Progress Showcase
* Templates for webinars, case studies, quotes from standard

---

## 🗂 6. File Structure | Структура файлов

```
VISUAL_ASSETS/
├── design-system/           # Colors, fonts, patterns, tone of voice
├── core-brand/              # Logo & wordmark placeholders
├── icons/
│   ├── principles/          # 7 principle icons (SVG/PNG)
│   └── levels/              # Bronze-Platinum badges
├── diagrams/
│   ├── tree-of-principles/  # Main diagram variants
│   ├── ethical-architecture/ # Isometric / schematic diagram
│   └── compliance-scale/    # Progress bars
├── social-media/
│   ├── instagram/           # Sized templates
│   ├── twitter/             # Header & card templates
│   └── linkedin/            # Article & post templates
└── interactive/
    ├── web-components/      # ECS progress generator
    └── animations/          # Lottie JSON files
```

---

## 🚀 7. Implementation Roadmap | План реализации

**Phase 1** (Week 1-2): Design system + principle icons + logo concept + patterns
**Phase 2** (Week 3-4): Main diagram + Ethical Architecture schematic + compliance scale
**Phase 3** (Week 5-6): Social media toolkit + templates
**Phase 4** (Week 7-8): Interactive elements + animations

**Tools | Инструменты:** Figma, Adobe Illustrator, D3.js, Lottie
