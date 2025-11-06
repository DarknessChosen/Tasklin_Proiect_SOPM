## Tasklin — Mobile (React Native / Expo)

To-do simplu, rapid, local. Statusuri clare: Upcoming, Overdue, Completed, Canceled.
Persistență cu AsyncStorage, notificări locale (Expo), gesturi rapide, dark mode.

<br>

## 🌈 Reguli status (pe scurt)

- ✅ **Completed** / 🚫 **Canceled** = setare manuală.  
- ⏰ **Overdue** — dacă termenul e în trecut.  
- 📅 **Upcoming** — dacă termenul e în viitor sau lipsește.  

<br>

## 🧪 Test rapid (manual)

- [ ] ✍️ **Creează** un task (fără titlu → mesaj de eroare)
- [ ] ✏️ **Editează** / 🗑️ **Șterge** (confirmare + *undo* dacă există)
- [ ] ✅ **Marchează** *Completed* / 🚫 *Canceled* (revocare posibilă)
- [ ] ⏳ **Verifică** trecerea **Upcoming ↔ Overdue** după termen
- [ ] 🧩 **Subtask-uri:** adaugă / bifează, urmărește progresul
- [ ] 🔔 **Notificări:** permisiune, reminder, anulare la *Completed* / *Deleted*
- [ ] 👆 **Gesturi:** *swipe* / *long-press* fără conflict cu *scroll*
- [ ] 🌙⚡ **Dark mode** + performanță listă (fluid cu ~500 item-uri)

<br>

## 🤝 Contribuitori

- 📱 **Mobile:** Ionita David-Theodor, Crăciun Andrei  
- 🌐 **Web (React):** Negru Andreea, Bradac Daniel
