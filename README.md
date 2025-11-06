#Tasklin — Mobile (React Native / Expo)

To-do simplu, rapid, local (fără backend). Statusuri clare: Upcoming, Overdue, Completed, Canceled.
Persistență cu AsyncStorage, notificări locale (Expo), gesturi rapide, dark mode.

Funcționalități

 Creare / editare / ștergere task-uri (titlu obligatoriu)

 Statusuri: Upcoming / Overdue / Completed / Canceled

 Subtask-uri (checklist, progres)

 Notificări locale (reminder înainte și la termen)

 Gesturi rapide: swipe (acțiuni), long-press (meniu)

 Dark mode + listă fluentă (țintă ~500 item-uri)

 Reguli status (pe scurt)

Completed / Canceled = setare manuală.

Altfel:

Overdue dacă termenul e în trecut.

Upcoming dacă termenul e în viitor sau lipsește.

Test rapid (manual)

 Creează task (fără titlu = mesaj de eroare)

 Editează/șterge task (confirmare + undo dacă există)

 Marchează Completed/Canceled (revocare posibilă)

 Verifică Upcoming ↔ Overdue după termen

 Subtask-uri: adaugă/bifează, vezi progresul

 Notificări: permisiune, reminder, anulare la Completed/Deleted

 Gesturi: swipe/long-press fără conflict cu scroll

 Dark mode + performanță listă

Contribuitori

Mobile: Ionita David-Theodor, Crăciun Andrei

Web (React): Negru Andreea, Bradac Daniel
