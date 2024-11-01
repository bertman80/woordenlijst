# (wachtwoorden) woordenlijst
Een woordenlijst om wachtwoorden mee te creeren. Als het goed is staan hier geen aanstootgevende woorden in.

Er zijn heel veel woorden lijsten, maar vaak zitten daar ook woorden tussen die aanstootgevend kunnen zijn. Daarom heb ik deze lijst gemaakt!

Huidig aantal woorden: **2382**

## Onderwerpen:
- werkzaamheden
- nederland
- lidwoorden
- landbouw
- muziek
- dieren
- vakantie
- huishouden
- eten
- dansen
- natuur
- speelgoed

## Vervangen:
- ë -> e
- é -> e
- ' -> (leeg)
- (spatie) -> (leeg)

## Powershell
Simpel voorbeeld om deze in Powershell aan te roepen. Als je hierbij hulp nodig hebt, dan laat het maar weten.
```
$words = invoke-restmethod -uri "https://raw.githubusercontent.com/bertman80/woordenlijst/refs/heads/main/woorden.json" -erroraction stop
$words | get-random
```
