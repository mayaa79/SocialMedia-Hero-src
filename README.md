# Agent LinkedIn

Asystent do konta LinkedIn (Marcin Majewski). Tryb pracy: **asystent z zatwierdzaniem** –
agent przygotowuje szkice i raporty, a każdą publikację, komentarz, reakcję lub wiadomość
zatwierdza użytkownik. Agent działa przez Claude Code w zalogowanej przeglądarce użytkownika.

## Zakres
1. **Posty** – szkice postów IT (System Administrator, Windows Server, AD, Claude, cyberbezpieczeństwo,
   „co robię / co piszę", ciekawostki branżowe) → `szkice/`
2. **Oferty pracy** – wyszukiwanie ofert dopasowanych do doświadczenia z profilu → `raporty/`
   (kryteria: `config/oferty-kryteria.md`)
3. **Monitoring polubień** – przegląd tego, co użytkownik polubił, wnioski i inspiracje do postów
   (`config/monitoring-polubien.md`)
4. **Komentarze** – propozycje komentarzy do zatwierdzenia (bez wysyłania)

## Struktura
- `CLAUDE.md` – instrukcje i zasady dla agenta
- `config/` – profil, ton postów, kryteria ofert, zasady monitoringu
- `szkice/` – szkice postów i komentarzy (`RRRR-MM-DD-temat.md`)
- `raporty/` – raporty ofert pracy i polubień (`RRRR-MM-DD-oferty.md`)
