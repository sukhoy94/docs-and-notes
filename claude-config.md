# Claude Code — Konfiguracja (notatka)

## Auto-compact `true | false`
Automatyczne kompaktowanie kontekstu gdy okno tokenów jest prawie pełne.  
- `true` — Claude sam skraca historię, żeby nie przekroczyć limitu  
- `false` — brak kompaktowania, ryzyko błędu przy długich sesjach

---

## Show tips `true | false`
Wyświetlanie podpowiedzi w UI terminala.  
- `true` — pojawiają się tipy o skrótach i funkcjach  
- `false` — czysty interfejs bez podpowiedzi

---

## Reduce motion `true | false`
Ograniczenie animacji w interfejsie.  
- `true` — brak animacji (użyteczne przy problemach z percepcją ruchu)  
- `false` — pełne animacje (domyślnie)

---

## Thinking mode `true | false`
Tryb "myślenia" — bardziej glębokie myślenie

---

## Rewind code (checkpoints) `true | false`
Możliwość cofania zmian do poprzedniego punktu kontrolnego.  
- `true` — Claude tworzy checkpointy przed edycją plików, można cofnąć  
- `false` — brak checkpointów, zmiany nieodwracalne w sesji

---

## Verbose output `true | false`
Szczegółowość logów i wyjścia.  
- `true` — pełne logi, wszystkie kroki widoczne w terminalu  
- `false` — minimalne wyjście (domyślnie)

---

## Terminal progress bar `true | false`
Pasek postępu w terminalu podczas operacji.  
- `true` — wizualny wskaźnik postępu  
- `false` — brak paska

---

## Show turn duration `true | false`
Wyświetlanie czasu trwania każdej tury (jednej odpowiedzi Claude'a).  
- `true` — widać ile sekund zajęła odpowiedź  
- `false` — czas niewidoczny

---

## Default permission mode `Accept edits | Ask | Auto`
Domyślna polityka akceptowania zmian w plikach.  
- `Accept edits` — Claude automatycznie zapisuje edycje bez pytania  
- `Ask` — pyta o potwierdzenie przed każdą zmianą  
- `Auto` — tryb autonomiczny, maksymalna automatyzacja

---

## Use auto mode during plan `true | false`
Czy podczas fazy planowania (Plan Mode) używać trybu auto.  
- `true` — w fazie planowania Claude działa autonomicznie  
- `false` — czeka na potwierdzenie kroków planu

---

## Respect .gitignore in file picker `true | false`
Czy picker plików ma pomijać pliki z `.gitignore`.  
- `true` — pliki ignorowane przez git są niewidoczne w pickerze  
- `false` — widoczne wszystkie pliki

---

## Always copy full response (skip /copy picker) `true | false`
Czy kopiować pełną odpowiedź bez otwierania pickera `/copy`.  
- `true` — pełna odpowiedź trafia od razu do schowka  
- `false` — otwiera picker z wyborem fragmentu do skopiowania

---

## Auto-update channel `latest | stable | beta`
Kanał aktualizacji Claude Code.  
- `latest` — najnowsza wersja (może być pre-release)  
- `stable` — tylko stabilne wydania  
- `beta` — wersje beta z nowymi funkcjami

---

## Theme `Light mode (colorblind-friendly) | Dark mode | System`
Motyw kolorystyczny interfejsu.  
- `Light mode (colorblind-friendly)` — jasny, zoptymalizowany pod kątem dostępności  
- `Dark mode` — ciemny motyw  
- `System` — podąża za ustawieniem systemowym

---

## Notifications `Auto | Always | Never`
Powiadomienia systemowe.  
- `Auto` — powiadomienia gdy okno nie jest aktywne  
- `Always` — zawsze  
- `Never` — wyłączone

---

## Output style `default | explanatory | learning`
Styl komunikacji Claude'a podczas pracy.  
- `default` — Claude robi zadanie i odpowiada zwięźle, bez tłumaczenia decyzji  
- `explanatory` — Claude wyjaśnia swoje wybory implementacyjne i wzorce w kodzie  
- `learning` — Claude zatrzymuje się i prosi użytkownika o napisanie fragmentów kodu samodzielnie (tryb nauki)

---

## Language `Default (English) | ...`
Język interfejsu Claude Code.  
- `Default (English)` — angielski  
- Inne dostępne języki zależą od wersji

---

## Editor mode `normal | vim | emacs`
Tryb edytora w polu input.  
- `normal` — standardowe skróty klawiaturowe  
- `vim` — skróty Vi/Vim  
- `emacs` — skróty Emacs

---

## Show PR status footer `true | false`
Wyświetlanie statusu Pull Requesta w stopce.  
- `true` — widoczny status PR (branch, CI) przy pracy z git  
- `false` — brak stopki PR

---

## Model `Default (recommended) | claude-opus-4 | claude-sonnet-4 | ...`
Model Claude używany w sesji.  
- `Default (recommended)` — Anthropic wybiera optymalny model  
- Można wybrać konkretny model ręcznie (np. dla oszczędności tokenów lub mocy)

---

## Auto-connect to IDE (external terminal) `true | false`
Automatyczne połączenie z IDE gdy Claude Code uruchomiony w zewnętrznym terminalu.  
- `true` — automatycznie łączy się z VS Code / JetBrains przez plugin  
- `false` — brak auto-połączenia, trzeba uruchomić ręcznie

---

## Claude in Chrome enabled by default `true | false`
Czy rozszerzenie Claude w Chrome jest aktywne domyślnie.  
- `true` — Claude w Chrome aktywny przy starcie  
- `false` — wyłączony domyślnie, aktywacja ręczna

---

## Enable Remote Control for all sessions `default | always | never`
Zdalne sterowanie sesją Claude Code (np. przez API lub zewnętrzne narzędzia).  
- `default` — decyzja per sesja  
- `always` — zawsze włączone zdalne sterowanie  
- `never` — całkowicie wyłączone
