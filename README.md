# Cod reducere Huawei — fetch automat de pe shopilo.ro

Modul Python pentru fetch automat de **coduri de reducere Huawei** de pe [shopilo.ro](https://shopilo.ro/magazin/consumer.huawei.com). Returneaza **cupoane Huawei** active in format JSON, gata de integrat intr-un bot Telegram, extensie de browser sau orice alt tool.

**Pagina live:** [shopilo-ro.github.io/cod-reducere-huawei](https://shopilo-ro.github.io/cod-reducere-huawei/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Instalare

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-ro/cod-reducere-huawei
cd cod-reducere-huawei
python fetch.py
```

## Output exemplu

```json
[
  {
    "store": "Huawei",
    "code": "SHOPILO10",
    "discount": "10%",
    "description": "10% reducere la telefoane si accesorii Huawei",
    "expires": "2026-10-02",
    "source": "https://shopilo.ro/magazin/consumer.huawei.com"
  }
]
```

## Cupoane Huawei disponibile

| Reducere | Descriere | Sursa |
|----------|-----------|-------|
| 10% | 10% reducere la telefoane si accesorii Huawei | [shopilo.ro](https://shopilo.ro/magazin/consumer.huawei.com) |

Codurile active: **[shopilo.ro/magazin/consumer.huawei.com](https://shopilo.ro/magazin/consumer.huawei.com)**

## Intrebari frecvente

### Cum folosesc un cod de reducere Huawei?
Copiaza codul din tabelul de mai sus sau de pe [shopilo.ro](https://shopilo.ro/magazin/consumer.huawei.com), adauga produsele in cos pe Huawei, si introdu codul la checkout in campul dedicat.

### Cat timp sunt valabile cupoanele Huawei?
Fiecare cupon are data de expirare afisata in coloana "Expira". Scriptul fetch.py returneaza doar cupoanele active la momentul rularii.

### Unde gasesc cele mai noi voucher-uri Huawei?
Pagina [shopilo.ro/magazin/consumer.huawei.com](https://shopilo.ro/magazin/consumer.huawei.com) este actualizata zilnic cu cele mai noi cod reducere Huawei, voucher Huawei si cupon promotional Huawei.

### Codul nu functioneaza. Ce fac?
Verifica data de expirare si conditiile (valoare minima cos, produse eligibile). Unele coduri sunt valabile doar in aplicatia mobila sau pentru prima comanda.

## Despre Huawei

Huawei este unul dintre magazinele online populare. Gasesti pe [shopilo.ro](https://shopilo.ro/magazin/consumer.huawei.com) cele mai bune cod reducere Huawei, cupoane Huawei verificate si voucher Huawei active, actualizate zilnic.

## Instalare npm

```bash
npm install cod-reducere-huawei
```

```javascript
const { fetchCoupons } = require('cod-reducere-huawei');
fetchCoupons().then(data => console.log(data));
```

## Licenta

MIT — date sursa de pe [shopilo.ro](https://shopilo.ro)
