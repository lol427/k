# Renumerotarea problemelor — volumul 4 (algebră, clasa a XII-a)

Fișiere modificate: `corp-ro/pb-alg-enunt-12.tex` (enunțuri) și `corp-ro/pb-alg-sol-12.tex` (soluții).

Pe scurt, față de prima numerotare:

- **S-au adăugat 5 probleme noi, originale**, la sfârșitul secțiunii ONM (numerotate aici „ONM.31–35 (nou)”; acum ONM.25–29).
- **4 soluții de la ONM au devenit autonome** (nu mai citează rezultate grele nedemonstrate):
  - fosta ONM.12 (congruențele pe $S_n$): în locul simplității lui $A_n$, soluția demonstrează direct că orice subgrup normal netrivial al lui $S_n$ conține $A_n$;
  - fosta ONM.18 (grupurile de ordin $p_n p_{n+1}$): postulatul lui Bertrand este demonstrat în soluție, iar reducerea la $p\nmid q-1$ se face prin Propoziția 2.141 (`prop:pqciclic`), cu argumentul reamintit;
  - fosta ONM.20 ($G\simeq H\times H$): numărarea se face în soluție și se folosește doar existența descompunerii în factori ciclici, nu și unicitatea ei;
  - fosta ONM.24: enunțul a fost reformulat pentru inele care **nu sunt corpuri** (și se cere în plus $x^3=x$), iar soluția a fost rescrisă.
- **16 probleme au fost mutate între niveluri** (vezi regulile de mai jos).
- **S-a eliminat o singură problemă: OJM.1**, dublură exactă a problemei OLM.1 (clasica „$x^2=e$ pentru orice $x$ $\Rightarrow$ $G$ abelian”), care se păstrează la OLM.
- Cele 13 probleme scoase anterior doar pentru că enunțul lor coincide cu un rezultat din partea de teorie (OLM.1, OLM.2, OLM.3, OLM.6, OLM.11, OJM.2, OJM.13, OJM.21, OJM.22, OJM.23, ONM.5, ONM.7, ONM.21) **au fost repuse**, cu enunțul și soluția (inclusiv „Răspuns” și observații) preluate textual din versiunea inițială, fiecare în secțiunea ei inițială.

Numerele „vechi” sunt cele din prima numerotare: OLM.1–20, OJM.1–24, ONM.1–30, plus cele 5 probleme noi, ONM.31–35 (nou).

## Reguli aplicate

- Problemele **coborâte** (OJM → OLM, ONM → OJM, ONM → OLM) sunt puse **la sfârșitul** secțiunii noi. Între ele se păstrează ordinea: întâi cele venite din OJM, apoi cele din ONM, fiecare grup în ordinea numerelor vechi.
- Problemele **urcate** (OLM → OJM, OJM → ONM) sunt puse **la începutul** secțiunii noi.
- Cele 5 probleme noi stau **la sfârșitul** secțiunii ONM, în ordinea în care au fost adăugate.
- O problemă repusă stă în secțiunea ei inițială, imediat după cea mai apropiată predecesoare inițială (același nivel, număr vechi mai mic) rămasă pe loc; dacă nu există una, stă la începutul secțiunii, după eventualele probleme urcate. Astfel, în fiecare nivel problemele rămase pe loc apar exact în ordinea inițială.
- Numerotarea este automată: în fiecare nivel problemele sunt din nou 1, 2, 3, …
- Enunțurile din cele două fișiere sunt identice, în aceeași ordine (verificat automat: 78 = 78, nicio diferență; fiecare problemă are soluție).

## Număr de probleme pe nivel

| Nivel | Înainte | După |
|---|---|---|
| OLM | 20 | 29 |
| OJM | 24 | 20 |
| ONM | 35 (30 + 5 noi) | 29 |
| **Total** | **79** | **78** |

Bilanț: OLM = 20 − 1 (urcată) + 10 (coborâte: 7 din OJM, 3 din ONM) = 29; OJM = 24 − 1 (eliminată) − 7 (coborâte la OLM) − 1 (urcată) + 1 (urcată din OLM) + 4 (coborâte din ONM) = 20; ONM = 35 − 3 (coborâte la OLM) − 4 (coborâte la OJM) + 1 (urcată din OJM) = 29.

## Tabel vechi → nou

| Vechi | Nou | Observație |
|---|---|---|
| OLM.1 | OLM.1 | restaurată la locul inițial (enunțul coincide cu Propoziția 2.11 (`prop:x2e`) din teorie, dar problema rămâne în culegere) |
| OLM.2 | OLM.2 | restaurată la locul inițial (enunțul coincide cu Lema 2.39 (`lema:bezoutexp`) cu $H=\{e\}$ și Propoziția 2.26 (`prop:exponent`) (i) din teorie, dar problema rămâne în culegere) |
| OLM.3 | OLM.3 | restaurată la locul inițial (enunțul coincide cu Teorema 2.155 (`teo:produs`) (iii) din teorie, dar problema rămâne în culegere) |
| OLM.4 | OLM.4 | neschimbată |
| OLM.5 | OLM.5 | neschimbată |
| OLM.6 | OLM.6 | restaurată la locul inițial (enunțul coincide cu Propoziția 2.26 (`prop:exponent`) (ii), (iii) din teorie, dar problema rămâne în culegere) |
| OLM.7 | OLM.7 | neschimbată |
| OLM.8 | OLM.8 | neschimbată |
| OLM.9 | OLM.9 | neschimbată |
| OLM.10 | OLM.10 | neschimbată |
| OLM.11 | OLM.11 | restaurată la locul inițial (enunțul coincide cu Observația de după Propoziția 3.6 (`prop:reguli`) din teorie, dar problema rămâne în culegere) |
| OLM.12 | OLM.12 | neschimbată |
| OLM.13 | OLM.13 | neschimbată |
| OLM.14 | OLM.14 | neschimbată |
| OLM.15 | OLM.15 | neschimbată |
| OLM.16 | OLM.16 | neschimbată |
| OLM.17 | OLM.17 | neschimbată |
| OLM.18 | OLM.18 | neschimbată |
| OLM.19 | OJM.1 | mutată OLM → OJM (urcată; la începutul secțiunii OJM) |
| OLM.20 | OLM.19 | renumerotată |
| OJM.1 | — (eliminată) | eliminată: dublură exactă a problemei OLM.1 ($x^2=e$ pentru orice $x$ $\Rightarrow$ $G$ abelian), care se păstrează la OLM |
| OJM.2 | OJM.2 | restaurată la locul inițial (enunțul coincide cu Teorema lui Cauchy 2.89 (`teo:cauchy`), cazul $p=2$ din teorie, dar problema rămâne în culegere) |
| OJM.3 | OJM.3 | neschimbată |
| OJM.4 | OJM.4 | neschimbată |
| OJM.5 | OJM.5 | neschimbată |
| OJM.6 | OLM.20 | mutată OJM → OLM (coborâtă un nivel; la sfârșitul secțiunii OLM) |
| OJM.7 | OLM.21 | mutată OJM → OLM (coborâtă un nivel; la sfârșitul secțiunii OLM) |
| OJM.8 | OJM.6 | renumerotată |
| OJM.9 | OJM.7 | renumerotată |
| OJM.10 | OJM.8 | renumerotată |
| OJM.11 | ONM.1 | mutată OJM → ONM (urcată; la începutul secțiunii ONM) |
| OJM.12 | OLM.22 | mutată OJM → OLM (coborâtă un nivel; la sfârșitul secțiunii OLM) |
| OJM.13 | OJM.9 | restaurată la locul inițial (enunțul coincide cu Teorema fundamentală de izomorfism 2.114 (`teo:fundamental`) din teorie, dar problema rămâne în culegere) |
| OJM.14 | OJM.10 | renumerotată |
| OJM.15 | OLM.23 | mutată OJM → OLM (coborâtă un nivel; la sfârșitul secțiunii OLM) |
| OJM.16 | OLM.24 | mutată OJM → OLM (coborâtă un nivel; la sfârșitul secțiunii OLM) |
| OJM.17 | OJM.11 | renumerotată |
| OJM.18 | OJM.12 | renumerotată |
| OJM.19 | OJM.13 | renumerotată |
| OJM.20 | OLM.25 | mutată OJM → OLM (coborâtă un nivel; la sfârșitul secțiunii OLM) |
| OJM.21 | OJM.14 | restaurată la locul inițial (enunțul coincide cu Propoziția 3.37 (`prop:finitcorp`) din teorie, dar problema rămâne în culegere) |
| OJM.22 | OJM.15 | restaurată la locul inițial (enunțul coincide cu Propoziția 3.66 (`prop:machalegen`) din teorie, dar problema rămâne în culegere) |
| OJM.23 | OJM.16 | restaurată la locul inițial (enunțul coincide cu Propoziția 3.82 (`prop:subcorpuri`) din teorie, dar problema rămâne în culegere) |
| OJM.24 | OLM.26 | mutată OJM → OLM (coborâtă un nivel; la sfârșitul secțiunii OLM) |
| ONM.1 | OLM.27 | mutată ONM → OLM (coborâtă două niveluri; la sfârșitul secțiunii OLM) |
| ONM.2 | ONM.2 | neschimbată |
| ONM.3 | OLM.28 | mutată ONM → OLM (coborâtă două niveluri; la sfârșitul secțiunii OLM) |
| ONM.4 | ONM.3 | renumerotată |
| ONM.5 | ONM.4 | restaurată la locul inițial (enunțul coincide cu Teorema 3.59 (`teo:kk1`) din teorie, dar problema rămâne în culegere) |
| ONM.6 | OJM.17 | mutată ONM → OJM (coborâtă un nivel; la sfârșitul secțiunii OJM) |
| ONM.7 | ONM.5 | restaurată la locul inițial (enunțul coincide cu Observația (a) de după Lema 2.63 (`lema:centrutrivial`) din teorie, dar problema rămâne în culegere) |
| ONM.8 | ONM.6 | renumerotată |
| ONM.9 | ONM.7 | renumerotată |
| ONM.10 | ONM.8 | renumerotată |
| ONM.11 | OJM.18 | mutată ONM → OJM (coborâtă un nivel; la sfârșitul secțiunii OJM) |
| ONM.12 | ONM.9 | renumerotată; soluție rescrisă, autonomă: în locul simplității lui $A_n$ se demonstrează direct că orice subgrup normal netrivial al lui $S_n$ conține $A_n$ |
| ONM.13 | ONM.10 | renumerotată |
| ONM.14 | OJM.19 | mutată ONM → OJM (coborâtă un nivel; la sfârșitul secțiunii OJM) |
| ONM.15 | ONM.11 | renumerotată |
| ONM.16 | ONM.12 | renumerotată |
| ONM.17 | ONM.13 | renumerotată |
| ONM.18 | ONM.14 | renumerotată; soluție rescrisă, autonomă: postulatul lui Bertrand este demonstrat în soluție (în locul citării lui și a criteriului numerelor ciclice) |
| ONM.19 | ONM.15 | renumerotată |
| ONM.20 | ONM.16 | renumerotată; soluție rescrisă, autonomă: numărarea soluțiilor lui $x^n=e$ se face în soluție și se folosește doar existența descompunerii ciclice, nu și unicitatea ei |
| ONM.21 | ONM.17 | restaurată la locul inițial (enunțul coincide cu Propoziția 3.18 (`prop:centrumatrice`) din teorie, dar problema rămâne în culegere) |
| ONM.22 | OJM.20 | mutată ONM → OJM (coborâtă un nivel; la sfârșitul secțiunii OJM) |
| ONM.23 | OLM.29 | mutată ONM → OLM (coborâtă două niveluri; la sfârșitul secțiunii OLM) |
| ONM.24 | ONM.18 | renumerotată; enunț reformulat pentru inele care nu sunt corpuri (se cere și $x^3=x$); soluție rescrisă, autonomă |
| ONM.25 | ONM.19 | renumerotată |
| ONM.26 | ONM.20 | renumerotată |
| ONM.27 | ONM.21 | renumerotată |
| ONM.28 | ONM.22 | renumerotată; în fișierul de enunțuri, textul a fost aliniat cu cel din soluții (ghilimele, o rupere de rând) |
| ONM.29 | ONM.23 | renumerotată |
| ONM.30 | ONM.24 | renumerotată |
| ONM.31 (nou) | ONM.25 | problemă nouă, originală ($(1+u)^9=1+u$ pentru unități); la sfârșitul secțiunii ONM |
| ONM.32 (nou) | ONM.26 | problemă nouă, originală (idempotenți și ecuația $x^2-x=a$); la sfârșitul secțiunii ONM |
| ONM.33 (nou) | ONM.27 | problemă nouă, originală (polinoame ireductibile de grad $2p$ cu $f(X+1)=f(X)$); la sfârșitul secțiunii ONM |
| ONM.34 (nou) | ONM.28 | problemă nouă, originală (sistemul $xy=z+t$, $zt=x+y$ în $\mathbb{Z}_p$); la sfârșitul secțiunii ONM |
| ONM.35 (nou) | ONM.29 | problemă nouă, originală (gradul inversei unei bijecții polinomiale a lui $\mathbb{Z}_p$); la sfârșitul secțiunii ONM |

## Trimiteri între probleme (în `pb-alg-sol-12.tex`)

Corectate acum (numerele se schimbaseră prin repunerea problemelor ONM.5 și ONM.7):

- **OLM.29** (fosta ONM.23), în observație: „marginea $\tfrac58 n^2$ … (problema ONM.8)” a devenit „(problema ONM.10)”. Problema cu $\tfrac58 n^2$ este fosta ONM.13, acum **ONM.10**.
- **OJM.18** (fosta ONM.11), în observație: „problema ONM.6 este cazul $r=2$” a devenit „problema ONM.8 este cazul $r=2$”. Este vorba de fosta ONM.10 ($|G|=p^\alpha q^\beta$, $G=HK$), acum **ONM.8**.

Reformulări din etapa anterioară, păstrate pentru că sunt în continuare corecte (trimit la teorie, nu la un număr de problemă):

- **OLM.19** (fosta OLM.20, Frobenius): „descompunerilor de felul celei din problema OJM.1”. Problema precedentă inițială (corpul cu 8 elemente, fosta OLM.19) a urcat și este **OJM.1**; trimiterea rămâne corectă, pentru că problemele urcate stau la începutul secțiunii OJM.
- **OLM.20** (fosta OJM.6): „(Propoziția~\ref{prop:x2e})”, în loc de „(problema OLM.1)”. OLM.1 a fost repusă și are același număr, dar trimiterea la teorie e la fel de bună.
- **OJM.6** (fosta OJM.8), în observație: trimiterea la Lema~\ref{lema:bezoutexp} (cazul $H=\{e\}$), în loc de „problema OLM.2”.
- **ONM.6** (fosta ONM.8), în observație: „(Observația (a) de după aceeași lemă)”, adică Lema~\ref{lema:centrutrivial}, în loc de „problema ONM.7” (acum ONM.5).
- **OJM.18** (fosta ONM.11): „formula produsului pentru două subgrupuri (Lema~\ref{lema:produsHK} din partea de teorie)”, în loc de „problema ONM.10”, ca soluția de la OJM să nu depindă de o problemă de nivel mai înalt.
- **ONM.19** (fosta ONM.25): „exact ca în Propoziția~\ref{prop:machalegen}”, în loc de „exact ca la problema OJM.22” (acum OJM.15).

## Trimiteri verificate și lăsate neschimbate

- **OLM.18** (fosta OLM.18): „problema despre automorfismul lui Frobenius, de mai jos” este corectă: acea problemă este OLM.19, imediat dedesubt.
- **OLM.11** (repusă): „ca la problema cu $KL=\{e\}$ de mai sus” este corectă: acea problemă este OLM.10, imediat deasupra.
- **OLM.26** (fosta OJM.24): „problema OJM.28 din volumul de algebră pentru clasa a XI-a” trimite la alt volum.
- Problemele repuse nu conțin alte trimiteri la numere de probleme; trimiterile lor la teorie (`\ref{...}`) sunt toate definite.
- Etichetele definite în soluții (`lema:bezoutZ`, `lema:conjinn`, `lema:treiexp`) nu sunt citate din altă parte.
- `corp-ro/structuri.tex` și `corp-ro/constructii.tex` nu conțin trimiteri la numerele problemelor; mențiunile „ONM” de acolo sunt generale („instrument frecvent la ONM”, „shortlist ONM”).

## Compilare

`xelatex -interaction=nonstopmode -halt-on-error vol4-ro.tex` (de două ori) se termină fără erori (`grep '^!' vol4-ro.log` nu găsește nimic) și fără referințe nedefinite. Rezultă 218 pagini.
