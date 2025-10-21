# Informe Tècnic

## 1. Introducció i Justificació

La seguretat de les contrasenyes és un pilar fonamental en la protecció dels sistemes d’informació corporatius. Actualment, molts incidents de seguretat deriven de l’ús de **contrasenyes febles**, **reutilitzades** o **mal gestionades** pels usuaris.  

Els atacs més habituals que exploten aquestes debilitats són:

- **Atac de diccionari:** els atacants proven combinacions de paraules habituals o patrons coneguts per accedir a comptes.  
- **Credential stuffing:** ús massiu de combinacions d’usuari i contrasenya obtingudes d’altres filtracions per intentar accedir a nous serveis.  
- **Phishing i keylogging:** enganys o programes maliciosos que roben les credencials quan l’usuari les introdueix manualment.  

### Funció d’un gestor de contrasenyes

Un gestor de contrasenyes és una eina dissenyada per emmagatzemar, generar i protegir contrasenyes de manera segura. Genera automàticament contrasenyes fortes i úniques. Emmagatzematge xifrat de totes les credencials en un únic lloc segur Redueix el risc de reutilització o pèrdua de contrasenyes. Facilita l'accés i sincronització entre dispositius.  Possibilitat d’auditar i compartir credencials dins d’equips de treball de forma controlada.

L’adopció d’un gestor de contrasenyes corporatiu és, per tant, una mesura clau dins de l’estratègia de **ciberseguretat preventiva** de l’empresa.

---

## 2. Comparativa Tècnica

| **Característica** | **Bitwarden (Online)** | **KeePassXC (Offline)** |
|-----------------|------------------------|--------------------------|
| **Model** | Núvol, sincronització automàtica. | Local, fitxer KDBX. |
| **Seguretat** | Xifratge E2E (AES-256, Argon2). | Xifratge local (AES-256). |
| **Accessibilitat** | Web, mòbil, extensió navegador. | Aplicació d’escriptori. |
| **Codi** | Open Source. | Open Source. |
| **Cost** | Gratuït / Premium (~10 €/any). | Gratuït. |
| **Integració** | SSO, 2FA, Active Directory. | Sense integració. |

---

## 3. Avantatges i Inconvenients

| **Aspecte** | **Bitwarden** | **KeePassXC** |
|----------|----------------|---------------|
| **Seguretat** | Molt bona, però al núvol. | Excel·lent, 100% local. |
| **Usabilitat** | Fàcil i automàtic. | Més tècnic. |
| **Privadesa** | Dependència del servidor. | Total control local. |
| **Manteniment** | Mínim. | Manual. |

---

## 4. Recomanació

**Recomanat:** Bitwarden

- Combina seguretat, comoditat i sincronització.  
- Ideal per a equips tècnics i usuaris generals.  
- Permet integracions corporatives i allotjament propi.  

**Alternativa:** KeePassXC per entorns aïllats o d’alta seguretat.

---

## 5. Conclusió

L’ús d’un gestor com Bitwarden reforça la seguretat corporativa i redueix riscos d’atacs per contrasenyes compromeses.
