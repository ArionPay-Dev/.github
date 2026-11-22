<p align="center">
  <img src="logo-400.jpg" width="120" alt="ArionPay">
</p>

<h1 align="center">ArionPay</h1>

<p align="center">
  <b>Non-custodial crypto payments.</b> Customers pay on the ArionPay payment page and the money goes straight to the merchant's own wallet.<br>
  ArionPay never holds your funds or your keys.
</p>

<p align="center">
  <a href="https://arionpay.com"><img src="https://img.shields.io/badge/Website-arionpay.com-1d4ed8" alt="Website"></a>
  <a href="https://x.com/arionpayhq"><img src="https://img.shields.io/badge/X-@arionpayhq-111827?logo=x" alt="X"></a>
  <a href="https://www.linkedin.com/company/arionpay"><img src="https://img.shields.io/badge/LinkedIn-ArionPay-0a66c2" alt="LinkedIn"></a>
  <a href="mailto:info@arionpay.com"><img src="https://img.shields.io/badge/Email-info%40arionpay.com-16a34a" alt="Email"></a>
</p>

<p align="center">
  Bitcoin, USDT, Litecoin, Ethereum, TRON and more · prices in USD, EUR, GBP and 18 other currencies · a free sandbox with simulated payments
</p>

---

### 🛒 E-commerce

| Platform | Repository |
| --- | --- |
| WooCommerce | [arionpay-woocommerce](https://github.com/ArionPay-Dev/arionpay-woocommerce) |
| Magento 2 / Adobe Commerce | [arionpay-magento2](https://github.com/ArionPay-Dev/arionpay-magento2) |
| PrestaShop 1.7 – 9 | [arionpay-prestashop](https://github.com/ArionPay-Dev/arionpay-prestashop) |
| OpenCart 3 and 4 | [arionpay-opencart](https://github.com/ArionPay-Dev/arionpay-opencart) |
| Shopware 6 | [arionpay-shopware](https://github.com/ArionPay-Dev/arionpay-shopware) |
| Drupal Commerce | [arionpay-drupal-commerce](https://github.com/ArionPay-Dev/arionpay-drupal-commerce) |
| Joomla VirtueMart | [arionpay-virtuemart](https://github.com/ArionPay-Dev/arionpay-virtuemart) |
| Easy Digital Downloads | [arionpay-edd](https://github.com/ArionPay-Dev/arionpay-edd) |
| Odoo 17 – 20 | [arionpay-odoo](https://github.com/ArionPay-Dev/arionpay-odoo) |
| HikaShop (Joomla) | [arionpay-hikashop](https://github.com/ArionPay-Dev/arionpay-hikashop) |
| Medusa 2 | [arionpay-medusa](https://github.com/ArionPay-Dev/arionpay-medusa) |

### 🖥️ Hosting and billing

| Platform | Repository |
| --- | --- |
| WHMCS | [arionpay-whmcs](https://github.com/ArionPay-Dev/arionpay-whmcs) |
| Blesta | [arionpay-blesta](https://github.com/ArionPay-Dev/arionpay-blesta) |
| FOSSBilling | [arionpay-fossbilling](https://github.com/ArionPay-Dev/arionpay-fossbilling) |
| Paymenter | [arionpay-paymenter](https://github.com/ArionPay-Dev/arionpay-paymenter) |

### 🎓 Memberships, courses and donations

| Platform | Repository |
| --- | --- |
| Paid Memberships Pro | [arionpay-pmpro](https://github.com/ArionPay-Dev/arionpay-pmpro) |
| LifterLMS | [arionpay-lifterlms](https://github.com/ArionPay-Dev/arionpay-lifterlms) |
| Tutor LMS | [arionpay-tutor-lms](https://github.com/ArionPay-Dev/arionpay-tutor-lms) |
| GiveWP | [arionpay-givewp](https://github.com/ArionPay-Dev/arionpay-givewp) |
| Charitable | [arionpay-charitable](https://github.com/ArionPay-Dev/arionpay-charitable) |
| WordPress "Pay with crypto" buttons | [arionpay-wp-buttons](https://github.com/ArionPay-Dev/arionpay-wp-buttons) |

### 🧑‍💻 Developer libraries

| Language | Install | Repository |
| --- | --- | --- |
| Node.js / TypeScript | `npm install arionpay` | [arionpay-node](https://github.com/ArionPay-Dev/arionpay-node) |
| Python | `pip install arionpay` | [arionpay-python](https://github.com/ArionPay-Dev/arionpay-python) |
| PHP | `composer require arionpay/arionpay-php` | [arionpay-php](https://github.com/ArionPay-Dev/arionpay-php) |
| Laravel | `composer require arionpay/arionpay-laravel` | [arionpay-laravel](https://github.com/ArionPay-Dev/arionpay-laravel) |
| Go | `go get github.com/ArionPay-Dev/arionpay-go` | [arionpay-go](https://github.com/ArionPay-Dev/arionpay-go) |
| Ruby | `gem install arionpay` | [arionpay-ruby](https://github.com/ArionPay-Dev/arionpay-ruby) |
| Java / Kotlin | `com.arionpay:arionpay-java` | [arionpay-java](https://github.com/ArionPay-Dev/arionpay-java) |
| .NET | `dotnet add package ArionPay` | [arionpay-dotnet](https://github.com/ArionPay-Dev/arionpay-dotnet) |

### ⚙️ Automation and bots

| Tool | Repository |
| --- | --- |
| AI assistants: MCP server for Claude, Cursor, VS Code | [arionpay-mcp](https://github.com/ArionPay-Dev/arionpay-mcp) |
| n8n (community node + trigger) | [n8n-nodes-arionpay](https://github.com/ArionPay-Dev/n8n-nodes-arionpay) |
| Telegram shop bot | [arionpay-telegram-bot](https://github.com/ArionPay-Dev/arionpay-telegram-bot) |
| Discord shop bot | [arionpay-discord-bot](https://github.com/ArionPay-Dev/arionpay-discord-bot) |

---

### How every integration works

- The customer pays on the ArionPay payment page. Coming back to the shop never marks anything paid by itself.
- An order is marked paid only by a **signed `invoice.paid` webhook** for the right amount and currency. Each integration also checks with ArionPay directly when the customer comes back, so a lost webhook is caught.
- Small differences inside your store's payment tolerance are accepted automatically. Anything else waits for your decision in **Payment Radar**.
- Every integration was tested on a real install with sandbox payments before release. Each repository's README says what was tested.

### Security

Found a security problem? Please email [info@arionpay.com](mailto:info@arionpay.com) instead of opening a public issue.
