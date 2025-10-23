# Projecte: Auditoria DNS – DigiCore

## Context

Com a membres cada cop més integrats de l'equip tècnic de la consultora **EverPia**, teniu davant un nou repte.  
El vostre client, una empresa de màrqueting digital (**DigiCore**), experimenta errors de connectivitat a certes aplicacions.  
El seu equip tècnic sospita que la causa principal pot ser una **resolució de noms (DNS)** incorrecta o lenta.

La vostra missió és realitzar una **auditoria teòrica i pràctica del servei DNS** per formar el personal del client i oferir-los eines de diagnosi ràpides i efectives.

---

## Fase Teòrica: Sessió Formativa

Com a part de la formació, cal elaborar un **material formatiu** per al personal del client.  
Els directors tècnics han preparat unes sessions prèvies perquè domineu els conceptes següents:

### Conceptes a treballar

#### Jerarquia i estructura
- Explicació de l'estructura en arbre del DNS:  
  `Root > TLDs > Segon Nivell`

#### Procés de resolució
- Diferència entre consultes **iteratives** i **recursives**.  
- Definició de **servidor d'arrel (Root Server)** i **servidor autoritatiu**.

#### Tipus de zones
- Zona **directa** i **inversa**.  
- Zona **primària** i **secundària**.

#### Tipus de registres clau (Records)
- **A**, **CNAME**, **MX**, **NS** i **SRV** — funcions i utilitats.

#### Conceptes essencials
- **Resposta autoritativa**: què significa i com identificar-la.  
- **TTL (Time To Live)**: funció i impacte en la propagació i rendiment.  
- **SOA (Start of Authority)**: informació essencial i importància.  
- **Reenviadors**: condicionals i incondicionals.  
- **Resolució local** i el protocol **mDNS**.

---

### Activitat Teòrica

Prepareu una **píndola formativa en vídeo** (durada: 10–15 minuts)  
que expliqui de manera breu però clara els conceptes anteriors.

---

## Fase Pràctica: Diagnosi de Noms (Auditoria amb CLI)

Heu de demostrar l'ús de les principals **eines de diagnosi DNS** en diferents sistemes operatius (**Linux/macOS i Windows**).  
Per a cada eina, cal executar les comandes indicades i **analitzar els resultats**.

Utilitzeu un equip **Zorin** amb dues interfícies:
- Primera: NAT  
- Segona: adaptador pont amb IP configurada segons les indicacions dels responsables.

---

### A. Diagnosi avançada amb `dig` (Linux / macOS)

#### 1. Consulta bàsica de registre A
```bash
dig xtec.cat A
