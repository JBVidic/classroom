# Recepti za nameščanje programske opreme

Recepti za nameščanje programske opreme v učilnicah FRI se nahajajo v:

  - linroom/tasks za GNU/Linux
  - windows/tasks za Microsoft Windows

Vsako leto predvidoma popravimo recepte - sezname potrebnih programov in recepte za nameščanje le-teh.

## Zahteve za predmet

V imeniku tasks za vsak predmet obstaja YAML datoteka s seznamom zahtevanih programov.
Na primer, za predmet Komunikacijski protokoli in omrežna varnost obstaja datoteka KPOV-63716.yml.
V datoteki je po ena vrstica z besedo "include" za vsak program, ki ga pri predmetu potrebujemo. 

Trenutno za vsak predmet obstajata po dve datoteki - ena pod linroom/tasks, druga pod winroom/tasks.

## Nameščanje posameznega programa

Datoteke za nameščanje programov se prav tako nahajajo v imeniku tasks.
Na primer, za nameščanje Microsoftovega VSCode, obstaja datoteka vscode.yml.

Za nameščanje pod GNU/Linux in Windows sta datoteki seveda različni.

Ker nekateri programi niso javno dostopni, se pri nekaterih receptih uporabljajo datoteke z datotečnega strežnika UcilniceSMB. Kako to popraviti, je zaenkrat odprto vprašanje.
