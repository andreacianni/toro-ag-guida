# Guida Merge Branch Claude → Main

## Quando usare questa guida
Dopo che Claude Code Web ha lavorato su un branch `claude/guide-confirmation-XXXXXXX`, devi portare le modifiche su `main` per aggiornare GitBook.

---

## Comandi da eseguire (copia-incolla)

### 1. Scarica le modifiche da GitHub
```bash
git fetch origin
```

**✅ SICURO**: Questo comando scarica solo info, non modifica nulla sul tuo computer.

---

### 2. Vai sul branch main
```bash
git checkout main
```

**Cosa vedrai:**
- Se dice `Already on 'main'` → ok, continua
- Se dice `Switched to branch 'main'` → ok, continua

---

### 3. Controlla lo stato
```bash
git status
```

**⚠️ CONTROLLA:**
- Se dice `Your branch is up to date with 'origin/main'` → ok, continua
- Se dice `You have uncommitted changes` o `Changes not staged` → **STOP! Non continuare, chiedi aiuto**

---

### 4. Fai il merge
```bash
git merge origin/claude/guide-confirmation-XXXXXXX
```

**⚠️ IMPORTANTE:** Sostituisci `XXXXXXX` con il codice che ti dice Claude (es. `01QqaEzJz1QoxF8AbfYK4rQB`)

**Cosa vedrai:**
- Se dice `Fast-forward` e mostra file modificati → **✅ OK, continua**
- Se dice `CONFLICT` → **❌ STOP! C'è un conflitto, chiedi aiuto**
- Se dice `Already up to date` → non c'è niente da fare, il merge è già stato fatto

---

### 5. Pusha su GitHub
```bash
git push origin main
```

**✅ SICURO se:**
- Il passo 4 è andato bene senza conflitti

**Cosa vedrai:**
- Se dice `To https://github.com/andreacianni/toro-ag-guida.git` e mostra `7c0f826..e79ec4c  main -> main` → **✅ FATTO!**
- Se dice `rejected` o `error` → **❌ STOP! Qualcosa non va, chiedi aiuto**

---

## Riepilogo veloce (quando hai già fatto tutto una volta)

```bash
git fetch origin
git checkout main
git merge origin/claude/guide-confirmation-XXXXXXX
git push origin main
```

---

## Segnali di pericolo - QUANDO FERMARTI

**❌ STOP se vedi:**
- `CONFLICT`
- `uncommitted changes`
- `Changes not staged for commit`
- `rejected`
- `error: failed to push`

**In questi casi:** Non proseguire, chiedi a Claude cosa fare.

---

## Dopo il merge

GitBook si sincronizza automaticamente con `main` entro qualche minuto.

Puoi verificare su: https://andyaea.gitbook.io/toro-ag-guida-amministratore

---

## Se qualcosa va storto

**Annullare un merge NON ancora pushato:**
```bash
git merge --abort
```

**Tornare indietro dopo un push sbagliato:**
**❌ NON farlo da solo**, chiedi aiuto. È possibile ma può causare problemi.
