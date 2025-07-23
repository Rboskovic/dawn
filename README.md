# 🌟 STHLM Toys – Shopify Theme (Based on Dawn)

This repository is a fork of [Shopify/Dawn](https://github.com/Shopify/dawn), customized and developed for the **STHLM Toys** Shopify store using modern tools like Shopify CLI, DevContainers, and live CodeSandbox environments.

---

## 🛠 Development Environment

> Fully configured for use with **CodeSandbox**, **VS Code DevContainers**, or **GitHub Codespaces**

- `.devcontainer/devcontainer.json` ensures reproducible setup
- Uses `npx shopify theme dev` to sync changes to Shopify in real-time
- All ports and environment variables are correctly wired

---

## 🔐 Environment Variables

To connect to your Shopify store securely, create a `.env` file at the root:

```env
SHOPIFY_STORE=sthlmtoys-games.myshopify.com
SHOPIFY_PASSWORD=shptka_XXXXXXXXXXXXXXXXXXXXXXXXXXXX
