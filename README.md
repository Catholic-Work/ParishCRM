# ParishCRM

## ⛪ Welcome to ParishCRM

**ParishCRM** is a free, open-source parish management system purpose-built for **Catholic parishes**. It is a fork of [ChurchCRM](https://github.com/ChurchCRM/CRM), extended with Catholic-specific features including sacramental registers, religious education management, liturgical ministry scheduling, diocesan reporting, and more.

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)
[![Upstream](https://img.shields.io/badge/upstream-ChurchCRM%207.3.1-blue)](https://github.com/ChurchCRM/CRM)

## 🎯 Why ParishCRM?

While ChurchCRM is an excellent general-purpose church management system, Catholic parishes have **specific canonical and operational needs** that generic tools don't address:

- **Sacramental Records** — Baptisms, Confirmations, First Holy Communions, Marriages, and Deaths with proper marginal notations, godparent/sponsor tracking, and certificate generation
- **Religious Education** — CCD/PSR enrollment with sacramental preparation tracks (FHC/Penance Year 1-2, Confirmation Year 1-2, RCIA/OCIA)
- **Liturgical Ministry Scheduling** — Lectors, EMHCs, Altar Servers, Cantors, Sacristans, Ushers, and 20+ additional ministry roles
- **Diocesan Compliance** — Automated annual reports for the Chancery, fund-based accounting, and IRS-compliant contribution statements
- **Safeguarding** — Background check and Safe Environment training tracking with expiration alerts

## 🚀 Demo

Visit our live demo populated with the fictitious **Holy Spirit Catholic Parish**:

**[https://crm.catholic.work](https://crm.catholic.work)**

## 🛠️ Technical Stack

| Component | Technology |
|-----------|-----------|
| Backend | PHP 8.4+ / Slim Framework v4 |
| ORM | Propel |
| Database | MySQL 8.0+ / MariaDB 10.5+ |
| Frontend | Tabler (Bootstrap 5) + React + Webpack |
| Testing | Cypress (E2E) + PHPUnit |

## 📦 Getting Started

### Prerequisites
- PHP 8.4+
- MySQL 8.0+ or MariaDB 10.5+
- Apache 2.4+ with `mod_rewrite`
- Node.js 24+
- Composer

### Installation

```bash
# Clone the repository
git clone https://github.com/Catholic-Work/ParishCRM.git
cd ParishCRM

# Install PHP dependencies
cd src && composer install --no-dev && cd ..

# Install JS dependencies and build frontend
npm install
npm run build

# Configure your database
cp src/Include/Config.php.example src/Include/Config.php
# Edit Config.php with your database credentials
```

For detailed installation instructions, see the [ChurchCRM Documentation](https://docs.churchcrm.io/).

## 🤝 Contributing

ParishCRM welcomes contributions from developers, designers, and parish staff who understand Catholic parish operations. Whether it's a bug fix, a new feature, or feedback on how your parish could use the software — your input is invaluable.

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📜 License

ParishCRM is released under the [MIT License](LICENSE), the same as the upstream ChurchCRM project.

## 🙏 Acknowledgments

ParishCRM is built on the excellent work of the [ChurchCRM](https://github.com/ChurchCRM/CRM) community. We are grateful for their ministry of open-source software for the Church.

---

*Ad Maiorem Dei Gloriam* 🕊️
