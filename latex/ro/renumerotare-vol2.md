# Renumerotarea problemelor — volumul 2 (analiză, clasa a XII-a)

Fișiere modificate: `corp-ro/pb-an-enunt-12.tex` (enunțuri) și `corp-ro/pb-an-sol-12.tex` (soluții). `corp-ro/clasa12.tex` nu conține trimiteri la numerele problemelor, deci nu a fost modificat.
Nu s-a adăugat nicio problemă nouă. S-au eliminat 2 probleme (dubluri exacte), s-au mutat 14 între niveluri, iar restul au fost doar renumerotate. Enunțurile și soluțiile nu au fost modificate, cu excepția trimiterilor la numerele problemelor (vezi mai jos).

Numerele „vechi” sunt cele din numerotarea inițială: OLM.1–15, OJM.1–20, ONM.1–22.

## Reguli aplicate

- Problemele **coborâte** (OJM → OLM, ONM → OJM) sunt puse **la sfârșitul** secțiunii noi, în ordinea numerelor vechi. La OJM au intrat doar probleme venite din ONM.
- Singura problemă **urcată** (OJM.11 → ONM) este pusă **la începutul** secțiunii ONM.
- Fiecare problemă mutată și-a schimbat culoarea nivelului (primul argument al lui `\prob`), dar și-a păstrat mențiunea (de exemplu „Clasică”).
- Numerotarea este refăcută: în fiecare nivel problemele sunt din nou 1, 2, 3, …, iar ordinea relativă a celor rămase pe loc s-a păstrat.
- Fiecare problemă eliminată a fost scoasă din ambele fișiere. În fișierul de soluții s-a eliminat tot blocul: enunțul reluat, soluția și observațiile.
- Problemele OLM.3, OJM.2 și ONM.4 (metoda Feynman) **rămân** pe loc, deși coincid cu exemple din partea de teorie: autorul vrea să le păstreze.
- Enunțurile din cele două fișiere sunt identice și în aceeași ordine. Verificarea automată a dat 55 = 55 de etichete, în aceeași ordine, și nicio diferență între enunțuri.

## Număr de probleme pe nivel

| Nivel | Înainte | După | Detalii |
|---|---|---|---|
| OLM | 15 | 19 | −1 eliminată (OLM.7), +5 coborâte din OJM |
| OJM | 20 | 21 | −1 eliminată (OJM.9), −5 coborâte la OLM, −1 urcată la ONM, +8 coborâte din ONM |
| ONM | 22 | 15 | −8 coborâte la OJM, +1 urcată din OJM |
| **Total** | **57** | **55** | −2 eliminate |

## Tabel vechi → nou

| Vechi | Nou | Observație |
|---|---|---|
| OLM.1 | OLM.1 | neschimbată |
| OLM.2 | OLM.2 | neschimbată |
| OLM.3 | OLM.3 | neschimbată; rămâne, deși coincide cu un exemplu din partea de teorie (la cererea autorului) |
| OLM.4 | OLM.4 | neschimbată |
| OLM.5 | OLM.5 | neschimbată |
| OLM.6 | OLM.6 | neschimbată |
| OLM.7 | — (eliminată) | caz particular al problemei OLM.11 (acum OLM.10): $\lim\int_0^1\frac{dx}{1+x^n}$ este $\lim\int_0^1 f(x^n)\,dx=f(0)$ pentru $f(t)=\frac{1}{1+t}$; s-a păstrat OLM.11 |
| OLM.8 | OLM.7 | renumerotată |
| OLM.9 | OLM.8 | renumerotată |
| OLM.10 | OLM.9 | renumerotată |
| OLM.11 | OLM.10 | renumerotată |
| OLM.12 | OLM.11 | renumerotată |
| OLM.13 | OLM.12 | renumerotată |
| OLM.14 | OLM.13 | renumerotată |
| OLM.15 | OLM.14 | renumerotată |
| OJM.1 | OJM.1 | neschimbată |
| OJM.2 | OJM.2 | neschimbată; rămâne, deși coincide cu un exemplu din partea de teorie (la cererea autorului) |
| OJM.3 | OLM.15 | mutată OJM → OLM (coborâtă un nivel; pusă la sfârșitul secțiunii OLM) |
| OJM.4 | OLM.16 | mutată OJM → OLM (coborâtă un nivel; pusă la sfârșitul secțiunii OLM) |
| OJM.5 | OJM.3 | renumerotată |
| OJM.6 | OJM.4 | renumerotată |
| OJM.7 | OJM.5 | renumerotată |
| OJM.8 | OJM.6 | renumerotată |
| OJM.9 | — (eliminată) | aceeași recurență ca OJM.8 (acum OJM.6): cu $e_n=1-b_n$, recurența $b_{n+1}=\frac{1+b_n^2}{2}$ devine exact $e_{n+1}=e_n-\frac{e_n^2}{2}$ din OJM.8 (observație făcută chiar în soluția ei); s-a păstrat OJM.8 |
| OJM.10 | OLM.17 | mutată OJM → OLM (coborâtă un nivel; pusă la sfârșitul secțiunii OLM) |
| OJM.11 | ONM.1 | mutată OJM → ONM (urcată un nivel; pusă la începutul secțiunii ONM) |
| OJM.12 | OJM.7 | renumerotată |
| OJM.13 | OLM.18 | mutată OJM → OLM (coborâtă un nivel; pusă la sfârșitul secțiunii OLM) |
| OJM.14 | OJM.8 | renumerotată |
| OJM.15 | OJM.9 | renumerotată |
| OJM.16 | OLM.19 | mutată OJM → OLM (coborâtă un nivel; pusă la sfârșitul secțiunii OLM) |
| OJM.17 | OJM.10 | renumerotată |
| OJM.18 | OJM.11 | renumerotată |
| OJM.19 | OJM.12 | renumerotată |
| OJM.20 | OJM.13 | renumerotată |
| ONM.1 | ONM.2 | renumerotată |
| ONM.2 | ONM.3 | renumerotată |
| ONM.3 | ONM.4 | renumerotată |
| ONM.4 | ONM.5 | renumerotată; rămâne la ONM (metoda Feynman), deși coincide cu un exemplu din partea de teorie (la cererea autorului) |
| ONM.5 | OJM.14 | mutată ONM → OJM (coborâtă un nivel; pusă la sfârșitul secțiunii OJM) |
| ONM.6 | OJM.15 | mutată ONM → OJM (coborâtă un nivel; pusă la sfârșitul secțiunii OJM) |
| ONM.7 | OJM.16 | mutată ONM → OJM (coborâtă un nivel; pusă la sfârșitul secțiunii OJM) |
| ONM.8 | OJM.17 | mutată ONM → OJM (coborâtă un nivel; pusă la sfârșitul secțiunii OJM) |
| ONM.9 | OJM.18 | mutată ONM → OJM (coborâtă un nivel; pusă la sfârșitul secțiunii OJM) |
| ONM.10 | ONM.6 | renumerotată |
| ONM.11 | ONM.7 | renumerotată |
| ONM.12 | ONM.8 | renumerotată |
| ONM.13 | ONM.9 | renumerotată |
| ONM.14 | ONM.10 | renumerotată |
| ONM.15 | ONM.11 | renumerotată |
| ONM.16 | ONM.12 | renumerotată |
| ONM.17 | OJM.19 | mutată ONM → OJM (coborâtă un nivel; pusă la sfârșitul secțiunii OJM) |
| ONM.18 | OJM.20 | mutată ONM → OJM (coborâtă un nivel; pusă la sfârșitul secțiunii OJM) |
| ONM.19 | OJM.21 | mutată ONM → OJM (coborâtă un nivel; pusă la sfârșitul secțiunii OJM) |
| ONM.20 | ONM.13 | renumerotată |
| ONM.21 | ONM.14 | renumerotată |
| ONM.22 | ONM.15 | renumerotată |

## Trimiteri reformulate

- **OJM.13** (fosta OJM.20), enunțul din ambele fișiere: „(limita acestui șir a fost calculată în problema OLM.7)” a devenit „(limita acestui șir rezultă din problema OLM.10, pentru $f(t)=\frac{1}{1+t}$)”, pentru că OLM.7 a fost eliminată. OLM.10 este fosta OLM.11, problema păstrată din pereche.
- **OJM.13**, observația din soluție: „Limita de la punctul (a) este problema OLM.7; […] Structural, (a) este și cazul $f(t)=\frac{1}{1+t}$ al problemei OLM.11 (…)” a devenit „Limita de la punctul (a) este cazul $f(t)=\frac{1}{1+t}$ al problemei OLM.10 ($\int_0^1 f(x^n)\,dx\to f(0)$); ceea ce contează aici este […]”.
- Singura trimitere la OJM.9 („exact recurența din Problema OJM.8”) era chiar în soluția lui OJM.9, deci a dispărut odată cu problema.

## Trimiteri actualizate prin tabelul de mai sus

Toate înlocuirile s-au făcut simultan, prin marcaje intermediare, ca să nu se strice lanțurile de renumerotare (de exemplu OLM.11 → OLM.10 și OLM.10 → OLM.9).

- **OLM.12** (fosta OLM.13), observația: „subiectul problemei ONM.15” → „ONM.11”.
- **OLM.13** (fosta OLM.14), enunț și soluție: „Comparați cu problema OJM.13” → „OLM.18”; „contrastul cu OJM.13” → „OLM.18”. Cele două probleme sunt acum la același nivel.
- **OLM.14** (fosta OLM.15): „fenomen ca la OJM.18” → „OJM.11”.
- **OJM.12** (fosta OJM.19): „în problema ONM.13” → „ONM.9”.
- **OJM.20** (fosta ONM.18): „fenomenului din OLM.11 și OJM.20” → „OLM.10 și OJM.13”.
- **OJM.21** (fosta ONM.19): „problema ONM.6” (de trei ori) → „OJM.15”. Ambele probleme au coborât la OJM, iar OJM.15 este tot înaintea ei.
- **ONM.6** (fosta ONM.10): „Problema ONM.1” și „la ONM.1” → „ONM.2”.
- **ONM.11** (fosta ONM.15): „OLM.13” → „OLM.12” în enunț (în ambele fișiere) și de două ori în soluție.
- **ONM.15** (fosta ONM.22): „ca în ONM.16” → „ONM.12”.

## Trimiteri verificate și lăsate neschimbate

- **OJM.16** (fosta ONM.7), observația 3: „ca la problemele OLM.2 și OJM.7 din secțiunea „Puntea''” trimite la secțiunea „Puntea între a XI-a și a XII-a” din volumul 1 (`pb-an-enunt-11.tex`). Nu este vorba de numerele din acest volum, așa că nu s-a schimbat.
- `corp-ro/clasa12.tex` nu conține trimiteri de forma OLM.k / OJM.k / ONM.k. Mențiunea „OJM 2026, clasa a XII-a, Problema 4” de la un exemplu se referă la subiectul oficial al olimpiadei, nu la numerotarea din carte.
- Nicio altă parte a cărții nu trimite la numerele problemelor din acest volum.

## Compilare

`xelatex -interaction=nonstopmode -halt-on-error vol2-ro.tex`, rulat de două ori, se termină fără erori: `grep '^!' vol2-ro.log` nu găsește nimic. Rezultă 141 de pagini.
