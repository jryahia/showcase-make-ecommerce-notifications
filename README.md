# Make E-Commerce Notifications

**One endpoint that fans order notifications out to Slack, Telegram, WhatsApp and branded email, from six store platforms.**

> **This is a proprietary project. Source code is private. This page showcases the system's architecture and results.**

**Case study page:** [https://jryahia.github.io/showcase-make-ecommerce-notifications/](https://jryahia.github.io/showcase-make-ecommerce-notifications/)

![Make E-Commerce Notifications](assets/00-dashboard.png)

## Problem it solves

Shops selling on several platforms get order alerts in several places, or not at all. This hub accepts orders from all of them and notifies the team on the channels they actually watch.

## Architecture

![Architecture](assets/architecture.svg)

1. An order arrives from any connected platform at a single webhook.
2. It is normalized and stored with a timeline.
3. Notifications go out to each enabled channel; high-value orders are flagged.
4. Every attempt is logged and can be reprocessed.

## Key features

- Six store platforms on one endpoint
- Four notification channels
- High-value order alerts
- Raw webhook log for debugging
- CSV export and reprocessing

## Tech stack

![Python](https://img.shields.io/badge/Python-161b22?style=for-the-badge&labelColor=161b22&color=161b22) ![FastAPI](https://img.shields.io/badge/FastAPI-161b22?style=for-the-badge&labelColor=161b22&color=161b22) ![Make.com](https://img.shields.io/badge/Make.com-161b22?style=for-the-badge&labelColor=161b22&color=161b22) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-161b22?style=for-the-badge&labelColor=161b22&color=161b22) ![Slack](https://img.shields.io/badge/Slack-161b22?style=for-the-badge&labelColor=161b22&color=161b22) ![Telegram](https://img.shields.io/badge/Telegram-161b22?style=for-the-badge&labelColor=161b22&color=161b22) ![Jinja2](https://img.shields.io/badge/Jinja2-161b22?style=for-the-badge&labelColor=161b22&color=161b22)

## What it does in practice

- Gives a multi-channel seller one place for order visibility.

## Screenshots

**Orders and revenue by platform**

![Orders and revenue by platform](assets/00-dashboard.png)

---

Built by [Yahya Jarray](https://github.com/jryahia). Interested in a similar system? [Get in touch](mailto:yahiajarray43@gmail.com).
