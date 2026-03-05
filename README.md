# Sendtoken.sh

Script bash per trasferire 1000 Solana sulla blockchain Solana.

## Descrizione

`Sendtoken.sh` è uno script semplice che utilizza il comando `solana transfer` per eseguire trasferimenti di SOL (Solana) sulla rete Solana.

## Requisiti

- Solana CLI installata
- Accesso a un wallet Solana con almeno 1000 SOL + commissioni
- `solana` disponibile nel PATH
- Configurazione del keypair locale

## Installazione

1. Clona il repository:
```bash
git clone https://github.com/alfaromeo166s-prog/Sendtoken.sh.git
cd Sendtoken.sh
```

2. Rendi lo script eseguibile:
```bash
chmod +x Inizio
```

## Uso

Esegui lo script:
```bash
./Inizio
```

### Cosa fa

Lo script trasferisce **1000 SOL** a un indirizzo Solana:

- **Quantità**: `1000 SOL`
- **Destinatario**: `23YzWYQ2emXbEfd4rmkeu6oN1aPfSshiavaZyFLMW53P9`

## Parametri

Per modificare il trasferimento, edita il file `Inizio` e cambia:
- La quantità di SOL
- L'indirizzo del destinatario

## Note Importanti

⚠️ **Attenzione**: Questo script trasferisce fondi reali. Assicurati che:
- Il wallet abbia i fondi necessari
- L'indirizzo del destinatario sia corretto
- Hai configurato il tuo keypair Solana locale

## Licenza

MIT