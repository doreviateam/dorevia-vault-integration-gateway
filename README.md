# 🔗 Dorevia Vault Integration Gateway (DVIG)  
**Version :** 1.x  
**Licence :** Apache 2.0  
**Langage :** Python  
**Auteur :** Doreviateam  

---

## 🎯 Objectif

DVIG est la passerelle **universelle** entre les ERP et Dorevia Vault.  
Il fournit une interface simple, robuste et multi-tenant.

---

## ✨ Fonctionnalités

- API REST publique ERP → DVIG
- Authentification & autorisation multi-tenant
- Normalisation des flux (factures, paiements, POS, documents)
- Bufferisation et mécanisme de retry
- Journalisation centralisée
- Appels internes sécurisés vers Vault
- Extensible pour tout ERP (Odoo, Dolibarr, Sylius…)

---

## 🧩 Arborescence

```
dvig/
 ├── routes/
 ├── auth/
 ├── normalizers/
 ├── connectors/
 ├── storage/
 └── tests/
```

## 🚀 Démarrage rapide

```
pip install -r requirements.txt
python dvig/main.py
```

---

## 📜 Licence

Apache 2.0 — usage libre, y compris commercial.
