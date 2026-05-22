<div align="center">

<br/>

<img alt="shop-iraq" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=44&duration=2400&pause=900&color=A78BFA&center=true&vCenter=true&width=900&height=80&lines=shop-iraq"/>

**The e-commerce platform built FOR the Iraqi market.**
_Arabic-first · RTL · Iraqi payments · Multi-vendor · Free + self-hosted._

<br/>

### 🖥️ One-click setup (recommended)

```bash
curl -fsSL https://shop-iraq.com/install | bash
```

This downloads the dashboard installer, runs Docker Compose, opens your store at `localhost:8080`. **No coding required.**

### Or download the installer app

[<img src="https://img.shields.io/badge/Download%20for%20macOS-000000?style=for-the-badge&logo=apple&logoColor=white" height="40"/>](https://github.com/kasimmj/shop-iraq/releases/latest/download/shop-iraq-macos.dmg)
[<img src="https://img.shields.io/badge/Download%20for%20Windows-0078D7?style=for-the-badge&logo=windows&logoColor=white" height="40"/>](https://github.com/kasimmj/shop-iraq/releases/latest/download/shop-iraq-setup.exe)

<br/>

<p>
<img src="https://img.shields.io/badge/Iraq-006C35?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Self--Hosted-A78BFA?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Free-22C55E?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MIT-000000?style=for-the-badge"/>
</p>

<p>
<img src="https://img.shields.io/github/stars/kasimmj/shop-iraq?style=social"/>
<img src="https://img.shields.io/github/forks/kasimmj/shop-iraq?style=social"/>
</p>

</div>

---

## 🇮🇶 الأسباب اللي خلتني أبنيه

Shopify يبدأ بـ $29/شهر + رسوم على كل معاملة.
WooCommerce يحتاج WordPress + شراء plugins للدفع العراقي.
Salla مغلق المصدر + رسوم.

**لا واحد منهم مصمم للسوق العراقي:**
- ❌ ZainCash / FIB / AsiaCell — تكامل دفع ضعيف أو غير موجود
- ❌ التوصيل بالمحافظات العراقية مو موجود
- ❌ الأسعار بالدولار وليس IQD
- ❌ الصياغة الإنجليزية أو RTL مكسور

**shop-iraq يحل كل هذا.** مفتوح المصدر. تشغّله بنفسك. تملك كل شي.

---

## ✨ ما يميزه

- 🇮🇶 **Arabic + RTL first** — مو إعداد لاحق، مصمم من الأساس
- 💳 **كل بوابات الدفع العراقية** عبر [iraq-pay](https://github.com/kasimmj/iraq-pay)
- 🚚 **التوصيل في 18 محافظة عراقية** مع شركاء محليين
- 🏪 **متاجر متعددة** — منصة marketplace ولا متجر واحد
- 📱 **PWA + تطبيق Flutter** للزبائن (عبر [web2flutter](https://github.com/kasimmj/web2flutter))
- 🎨 **محرر مرئي للمتجر** — Drag-and-drop بدون كود
- 📊 **لوحة تحكم بصرية كاملة** — للمالك + للبائعين + للزبائن
- 🆓 **مجاني للأبد** — افتح كود، self-host، لا رسوم

---

## 🖥️ The Admin Dashboard

After installation, `http://localhost:8080/admin`:

```
╭───────────────────────────────────────────────────────────────────╮
│  🛒 shop-iraq Admin                              admin@iraqshop ▾  │
├───────────────────────────────────────────────────────────────────┤
│                                                                   │
│   ◐ Dashboard      📊 اليوم                                       │
│   📦 Products      ┌───────────┬───────────┬───────────┐         │
│   🛒 Orders        │  المبيعات  │  الطلبات   │  الزوار   │         │
│   👥 Customers     │ 8.2M IQD  │    127    │   3,421   │         │
│   🚚 Shipping      └───────────┴───────────┴───────────┘         │
│   💳 Payments      ╭─────────────────────────────────────╮       │
│   🎨 Storefront    │   📈 Sales Trend (Last 30 Days)     │       │
│   🌐 Domains       │   ▁▂▃▅▇▆▄█▇▆▅▇█▆▅▄▃▅▇▆▅▇▆█▇▆▅▇█▇  │       │
│   🔧 Settings      ╰─────────────────────────────────────╯       │
│                                                                   │
│                    📦 Recent Orders                               │
│                    ┌─────────────────────────────────────────┐   │
│                    │ #4521  قاسم محمد   2 items   58K IQD  ✓ │   │
│                    │ #4520  أحمد علي    5 items  144K IQD  ✓ │   │
│                    │ #4519  ليلى حسين   1 item    32K IQD  ⏳│   │
│                    │ #4518  مصطفى       3 items   78K IQD  🚚│   │
│                    └─────────────────────────────────────────┘   │
│                                                                   │
│                    🚀 Quick Actions                               │
│                    [+ منتج جديد]  [📦 إضافة طلب]  [🎨 تعديل التصميم]│
│                                                                   │
╰───────────────────────────────────────────────────────────────────╯
```

---

## 🎨 The Storefront Builder (visual)

Drag-and-drop sections to design your store. **No code. No themes file. No HTML.**

- 🏗️ **40+ pre-built sections** (Hero, Featured Products, Testimonials, FAQ, Footer)
- 🎨 **Live preview** — see changes instantly
- 🌗 **Dark mode toggle** — for stores that want it
- 📱 **Mobile preview** — design for both at once
- 🎭 **Theme presets** — Modern, Classic, Bold, Minimal — change everything with one click
- 🌐 **Multi-language** — Arabic + English content side-by-side

---

## 💳 Iraqi payment integration (out of the box)

```yaml
# config/payments.yaml
zaincash:
  enabled: true
  merchant_id: ${ZAINCASH_MERCHANT_ID}

fib:
  enabled: true
  client_id: ${FIB_CLIENT_ID}

asiacell_cash:
  enabled: true
  api_key: ${ASIACELL_API_KEY}

fastpay:
  enabled: true
  merchant_code: ${FASTPAY_MERCHANT_CODE}

qi_card:
  enabled: true
  terminal_id: ${QI_TERMINAL_ID}

# Cash on delivery (still common in Iraq)
cod:
  enabled: true
  available_cities: [baghdad, basra, mosul, erbil, najaf, karbala, hilla]
  delivery_fee_iqd: 5000
```

In the admin UI, each gateway has a **one-click enable** + a credentials wizard.

---

## 🚚 Shipping & Logistics (Iraqi-specific)

Pre-integrated with:
- ✅ **iCargo** (Iraqi-Cargo) — most common
- ✅ **OneCargo** — fast in Baghdad
- ✅ **Tanyat** — North Iraq specialist
- ✅ **Custom rates** — for in-house delivery

Auto-calculates:
- 💸 Delivery fee based on city + weight
- ⏱️ Expected delivery date
- 📍 City + neighborhood dropdown (1500+ Iraqi locations)
- 🗺️ Map picker for exact addresses (Mapbox)

---

## 👥 Multi-vendor mode

Run as:
- **Single store** (default) — one owner, one storefront
- **Marketplace** — multiple vendors, your platform takes a cut

Marketplace mode includes:
- 👤 Vendor accounts + KYC
- 📊 Vendor dashboards (sales, payouts, ratings)
- 💰 Automated payout splitting via [iraq-pay](https://github.com/kasimmj/iraq-pay)
- 📝 Vendor agreements + onboarding flow
- ⭐ Vendor reputation scores

---

## 📱 Customer-facing mobile app

Every shop-iraq install can ship a Flutter app:

```bash
shop-iraq build-mobile-app
```

Uses [web2flutter](https://github.com/kasimmj/web2flutter) under the hood. You get:
- 📦 iOS + Android apps ready for stores
- 🔔 Push notifications for order status
- 📍 Live order tracking
- 💳 Native Iraqi payment flows

---

## 🛠️ Tech Stack

- **Backend:** Node.js (Fastify) + Postgres + Redis
- **Frontend:** Next.js 15 (App Router) + Tailwind
- **Admin UI:** React + shadcn/ui
- **Search:** Meilisearch (Arabic + English)
- **Storage:** S3-compatible (MinIO included)
- **Email:** Local SMTP support + SendGrid/Postmark
- **Deployment:** Docker Compose (single-host) or Kubernetes (multi-host)

---

## 🚀 Getting started

### Option 1: One-click installer (recommended)
Download the installer above, double-click, follow the wizard.

### Option 2: Docker Compose
```bash
git clone https://github.com/kasimmj/shop-iraq
cd shop-iraq
cp .env.example .env  # edit credentials
docker compose up -d
```

### Option 3: Production VPS
```bash
ssh root@your-server
curl -fsSL https://shop-iraq.com/install-vps.sh | bash
```

The VPS installer:
- Installs Docker
- Auto-provisions SSL (Let's Encrypt)
- Configures backups (S3 daily)
- Sets up monitoring (Prometheus + Grafana)

---

## 🌟 Real stores using shop-iraq

> _coming soon — submit yours to be featured_

---

## 🤝 Contributing

Especially welcome:
- 🌐 More Iraqi cities + delivery integrations
- 🎨 More storefront section templates
- 💳 Connectors for additional Iraqi payment methods
- 🌍 Translations to other Arabic dialects (Egyptian, Levantine, Gulf)

---

## 📜 License

MIT. **Use it commercially.** Run your own competitor to Shopify. We support that.

---

<div align="center">

**Star ⭐ to support open Iraqi e-commerce.**

</div>
