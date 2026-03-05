# 🌳 BotanyPots Trees

Un datapack per Minecraft che aggiunge ricette per alberelli compatibili con la mod BotanyPots.

[![Versione](https://img.shields.io/badge/versione-1.0.0-blue.svg)]()
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1-green.svg)](https://www.minecraft.net/)
[![Pack Format](https://img.shields.io/badge/Pack%20Format-61-lightgrey.svg)]()
[![Licenza](https://img.shields.io/badge/Licenza-MIT-yellow.svg)](../LICENSE)

[![en](https://img.shields.io/badge/lang-en-red.svg)](../README.md)
[![it](https://img.shields.io/badge/lang-it-green.svg)](README.it.md)

> 📝 **Changelog**: Vedi [CHANGELOG.it.md](CHANGELOG.it.md) per la cronologia delle versioni.

## 📋 Descrizione

Questo datapack fornisce ricette personalizzate per far crescere vari alberelli nei Vasi Botanici. Include ricette per tutti i tipi di alberi vanilla di Minecraft, permettendoti di coltivare alberi in modo efficiente in vasi botanici compatti.

## ✨ Funzionalità

- **Collezione Completa di Alberi**: Ricette per tutti gli alberi vanilla di Minecraft
- **Tempi di Crescita Ottimizzati**: Velocità di crescita bilanciate per un gameplay equo
- **Drop Configurabili**: Ogni albero fornisce alberelli e tronchi con probabilità personalizzabili

## 🌳 Alberi Supportati

- Quercia
- Betulla
- Abete
- Acacia
- Quercia Scura
- Giungla
- Ciliegio
- Mangrovia

## 📦 Requisiti

- **Minecraft**: 1.21.4+ (o versione compatibile)
- **Mod BotanyPots**: Necessaria per il funzionamento del datapack
- **Forge/Fabric**: A seconda della versione di BotanyPots utilizzata

## 🔧 Installazione

1. Scarica il datapack
2. Posiziona la cartella del datapack nella cartella `datapacks` del tuo mondo
   - Percorso: `.minecraft/saves/[NomeDelTuoMondo]/datapacks/`
3. Ricarica i datapack in gioco usando `/reload` o riavvia il mondo
4. Verifica l'installazione con `/datapack list`

## 🎮 Utilizzo

1. Crea o ottieni un Vaso Botanico (dalla mod BotanyPots)
2. Aggiungi il terreno appropriato (i terreni a base di terra funzionano per tutti gli alberi)
3. Pianta qualsiasi alberello supportato
4. Attendi che il vaso faccia crescere e raccolga automaticamente i drop
5. Raccogli tronchi e alberelli aggiuntivi dal vaso

## ⚙️ Configurazione

Ogni ricetta può essere personalizzata modificando i file JSON in:
```
data/botanypots/recipe/minecraft/crops/
```

Parametri che puoi modificare:
- `grow_time`: Tempo in tick per il ciclo di crescita completo (1200 = 60 secondi)
- `chance`: Probabilità di drop (da 0.0 a 1.0)
- `minRolls`/`maxRolls`: Numero di oggetti droppati per raccolto

## ❓ FAQ

**D: Funziona su mondi esistenti?**
R: Sì, aggiungi il datapack al tuo mondo ed esegui `/reload`.

**D: Posso usarlo con altri datapack?**
R: In generale sì, a meno che un altro datapack non modifichi le ricette BotanyPots per gli alberi nello stesso namespace.

**D: Funziona senza BotanyPots?**
R: No. La mod BotanyPots è necessaria — il datapack sarà inattivo senza di essa.

**D: Posso personalizzare la velocità di crescita o i drop?**
R: Sì! Modifica i file JSON in `data/botanypots/recipe/minecraft/crops/`. Vedi la sezione Configurazione per i dettagli.

## 📄 Licenza

Questo progetto è rilasciato sotto la [Licenza MIT](../LICENSE). Sentiti libero di includerlo nelle tue modpack!

## 👤 Autore

**Franchino961** — [GitHub](https://github.com/Franchino961-DataPack)

## 🤝 Contributi

I contributi sono benvenuti!
- Apri una [Issue](../../issues) per segnalare bug o suggerire nuove ricette
- Apri una [Pull Request](../../pulls) per contribuire

## 💬 Supporto

Se riscontri problemi o hai domande:
- Controlla le [issue esistenti](../../issues)
- Crea una nuova issue includendo: versione di Minecraft e versione di BotanyPots

## 🔗 Link

- [Mod BotanyPots](https://www.curseforge.com/minecraft/mc-mods/botany-pots)
- [Wiki di Minecraft - Alberi](https://minecraft.fandom.com/wiki/Tree)

## 📝 Changelog

Vedi [CHANGELOG.it.md](CHANGELOG.it.md) per la cronologia completa delle versioni.

---

> ⚠️ **Nota**: Questo datapack richiede l'installazione della mod BotanyPots. Non funzionerà in Minecraft vanilla.