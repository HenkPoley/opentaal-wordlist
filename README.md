ALPHA RELEASE!

_for English, please see below_


# Nederlandse woordenlijst

Dit is de Nederlandse woordenlijst van
[Stichting OpenTaal](https://www.opentaal.org). Mits aan volledige
bronvermelding wordt gedaan en de licenties worden gerespecteerd, is deze lijst
vrij te gebruiken. De exacte voorwaarden zijn te vinden in het bestand
[LICENSE](LICENSE). Lees deze goed door.

![logo Stichting OpenTaal](images/logo-shape-white-640x360.png?raw=true)

Deze woordenlijst is samengesteld door ontelbare individuele bijdragen,
specifieke delen uit bronnen zonder auteursrecht en intensieve eindredactie. De
lijst heeft van de [Taalunie](http://taalunie.org) het
[Keurmerk Spelling](http://taalunieversum.org/inhoud/spelling-meer-hulpmiddelen/keurmerk)
gekregen. Dit betekent dat de woorden in deze lijst voldoen aan de officiële
spelling.

![logo Keurmerk Spelling](images/keurmerk.png?raw=true)


## Inhoud

De woordenlijst bestaat de volgende type woorden:
- gekeurde [basiswoorden](https://nl.wikipedia.org/wiki/Lemma_(naslagwerk))
zoals `tafel`
- ongekeurde basiswoorden bestaande uit eigennamen zoals `Jansen`, toponiemen
zoals `Schin op Geul` en samenstellingen met een eigennaam zoals `Facebookgroep`
- [flexies](https://nl.wikipedia.org/wiki/Flexie_(taalkunde)) zoals `stoeltjes`

Deze woorden zijn te vinden in een
[UTF-8 Unicode](https://nl.wikipedia.org/wiki/UTF-8) tekstbestand genaamd
**[wordlist.txt](wordlist.txt)**. Elke regel bevat een apart woord en dat zijn
er in totaal 406.837 woorden. Let op, een woord kan een spatie bevatten, dat
komt 4319 keer voor. Alle woorden zijn verder alfabetisch gesorteerd met
[`sort`](http://www.gnu.org/software/coreutils/sort).

Er is een apart bestand met delen van woorden die een spatie bevatten. Dit is
een [TSV-bestand](https://en.wikipedia.org/wiki/Tab-separated_values) met in de
tweede kolom een or meer woorden waar dit deel vandaag komt. Indien dat meerdere
woorden zijn, zijn die gescheiden door een puntkomma. Dit bestand heet
**[wordparts.tsv](parts-of-words.tsv)** en bevat 933 delen van woorden die vaak
gebruikt worden. Een voorbeeld is `hoc` van `ad hoc;post hoc`. Let op, in dit
bestand staan ook woorden in die niet in de woordenlijst staan maar in verkorte
vorm worden gebruikt. Voorbeelden zijn `voor-` uit `voor- en nadelen` en `-zus`
in `tweelingbroer of -zus`.

Ook is er een bestand met fout gespelde woorden. Dit is
**[errors.tsv](errors.tsv)** en is ook in TSV-formaat. In de tweede kolom staan
nul of meerdere correcties, gescheiden met een puntkomma. De meest relevante
correctie staat dan vooraan.

Het versienummer en de datum en tijd van bovenstaande bestanden is te vinden in
respectievelijk de bestanden **[version.txt](version.txt)** en
**[datetime.txt](datetime.txt)**.


## Optioneel

Het is mogelijk om in een volgende versie meerdere bestanden op te nemen,
bijvoorbeeld bestanden met woorden:
- die t.o.v. een vorige versie niet meer in de lijst voorkomen
- die een flexie zijn met bijbehorende basisvorm
- die een basiswoord zijn met bijbehorende flexies
- die alternatieven van andere woorden zijn
- die verouderd of archaïsch zijn
- die om verwarring te voorkomen niet geschikt zijn voor spellingcontrole

Het is ook mogelijk om maatwerkbestanden in een versie op te nemen.


## Karakters

In het huidige tijdperk van Unicode is deze woordenlijst voorzien van karakters
die **niet** deel uitmaken van
[ASCII](https://nl.wikipedia.org/wiki/ASCII_(tekenset)). Voorbeelden hiervan
zijn cijfers in super- en subscript zoals een `₂` in `CO₂-emissie` en `³` in
`m³`. Als er een behoefte is aan bestanden uit deze woordenlijst die alleen maar
ASCII-tekens bevatten, neem dan [contact](https://www.opentaal.org/contact) op
met Stichting OpenTaal. Let op, dit heeft als impact dat bepaalde woorden
ontdubbeld moeten worden, sommige woorden en foutcorrecties zullen verdwijnen.
Omdat we het gebruik van Unicode aanbevelen, hebben we deze ondersteuning voor
ASCII momenteel niet.


## Installatie

Besturingssystemen bieden softwarepakketten die deze woordenlijst installeren en
automatisch updaten. Voorbeelden hiervan zijn:
- [wdutch](https://packages.ubuntu.com/search?keywords=wdutch) voor Ubuntu
- [wdutch](https://packages.debian.org/search?keywords=wdutch) voor Debian
- [wdutch](https://raspberryconnect.com/sitesearch?q=wdutch) voor Raspbian

Het upstream bronpakket is https://packages.debian.org/stable/wdutch


## Spellingcontrole

Deze woordenlijst moet **niet** gebruikt woorden voor een (zelfgebouwde)
spellingcontrole. Het controleren van spelling en aanbieden van suggesties is
voor het Nederlands totaal niet triviaal. Hiervoor is speciale software
beschikbaar zoals [Hunspell](https://hunspell.github.io) of
[Nuspell](https://nuspell.github.io).

OpenTaal maakt de Nederlandse ondersteuning voor deze spellingcontroles. Die is
deels gebaseerd op deze woordenlijst maar ook op een veel maatwerkregels,
vervoegingen en andere speciale gevallen. Daarnaast zijn deze geoptimaliseerde
spellingcontroles ook nog veel sneller dan eigen implementaties. In het eerste
kwartaal van 2020 zal een nieuwe versie van de Nederlandse ondersteuning van
spellingcontroles uit komen.

## Toetsenbord

Voor Android is er een toetsenbord dat gebruik maakt van deze woordenlijst. Zie
dit
[artikel](https://www.opentaal.org/het-laatste-nieuws/projectnieuws/51-publicaties/221-anysoftkeyboard)
op onze website voor meer informatie. In het eerste kwartaal van 2020 zal deze
app een update krijgen en de laatste versie van deze woordenlijst gebruiken.


## Wordfeud

Of een woord wel of niet wordt geaccepteerd in Wordfeud of bepaalde andere
woordspellen is niet de verantwoordelijkheid van Stichting OpenTaal. Hiervoor
kan het beste contact opgenomen worden met [TaalTik](https://taaltik.nl).


# Dutch word list

This is the Dutch word list by [Stichting OpenTaal](https://www.opentaal.org).
As long as full attribution is provided and the licenses are being respected,
this list can be used freely. The exact conditions can be found in the file
[LICENSE](LICENSE). Please, read these carefully.

![logo Stichting OpenTaal](images/logo-shape-white-640x360.png?raw=true)

This word list has been compiled from countless individual contributions,
specific parts from sources without copyright and intense final editing. This
list has received from the Dutch Language Union
([Taalunie](http://taalunie.org)) the Quality Mark Spelling
([Keurmerk Spelling](http://taalunieversum.org/inhoud/spelling-meer-hulpmiddelen/keurmerk)).
This means that the words in this list are according to the official spelling.

![logo Keurmerk Spelling](images/keurmerk.png?raw=true)


## Contents

TODO translate


## Installation

Operating systems offer software packages which install this word list and
update it automatically. Examples of this are:
- [wdutch](https://packages.ubuntu.com/search?keywords=wdutch) for Ubuntu
- [wdutch](https://packages.debian.org/search?keywords=wdutch) for Debian
- [wdutch](https://raspberryconnect.com/sitesearch?q=wdutch) for Raspbian

The upstream source package is https://packages.debian.org/stable/wdutch


## Spell checking

This word list should **not** be used for (self made) spell checking. Checking
spelling and offering suggestions is for Dutch not trivial at all. Use special
software for this such as [Hunspell](https://hunspell.github.io) or
[Nuspell](https://nuspell.github.io).

OpenTaal supports Dutch for these spell checkers. That is partly based on this
word list but also on many custom rules, conjugations and other special cases.
Additionally, these optimized spell checkers are much faster than own
implementations. In the first quarter, a new version of the Dutch support for
these spell checkers will be published.


## Keyboard

TODO translate


## Wordfeud

TODO translate


Please, help us create free and open Dutch writing tools. Donate tax free to our foundation at https://www.opentaal.org/vrienden-van-opentaal


