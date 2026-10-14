# Wtyczki WordPress moveUP Agency – aktualizacje

Źródło aktualizacji dla wtyczek moveUP na stronach klientów. Każda wtyczka (od wersji z modułem `includes/moveup-aktualizacje.php`) ma w nagłówku `Update URI: https://github.com/jbalabuch/moveup-wtyczki` i raz na 12 godzin czyta `wtyczki.json`. Nowa wersja pojawia się w kokpicie WordPressa (Kokpit → Aktualizacje) jak aktualizacja z wordpress.org – jednym kliknięciem albo automatycznie.

| Wtyczka | Co robi |
|---|---|
| moveUP – Dostępność | panel ułatwień dostępu (WCAG) |
| moveUP – Agenci AI | Markdown dla asystentów AI, /llms.txt, reguły w robots.txt |
| moveUP – Wydajność | odchudzone fonty, CSS w stronie, defer skryptów Kadence |
| Jadłospisy | jadłospisy w PDF z zakresem dat (blok, widżet, shortcode) |

## Zawartość

- `wtyczki.json` – aktualna wersja każdej wtyczki, adres paczki, wymagania, opis zmian
- `paczki/<wtyczka>-<wersja>.zip` – paczki gotowe do instalacji (folder wtyczki w środku)

Wydanie nowej wersji: skrypt `wydaj_wtyczke.py` w repozytorium roboczym moveUP.

Licencja wtyczek: GPLv2 lub nowsza.
