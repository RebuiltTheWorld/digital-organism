# Digitális Organizmus

A Rebuilt_The_World / Human & AI - LAB auditált, redaktált és reprodukálható publikus kiadása.

## Publikus kiadás

A közzétett `v1.0.0` egy befagyasztott történeti snapshot. Kizárólag a jóváhagyott, hatfájlos publikus réteget tartalmazza; a teljes RAW_ONLY auditcsomag, az eredeti források és az érzékeny indexek privátak maradnak.

- Csomag: `DIGITAL_ORGANISM_RAW_ONLY_PUBLIC_v1.0.0.zip`
- SHA-256: `0e5bc28110aab18c6ebf77fd79170883f7aca6680b28038db174ef6bb3e4bfa1`
- Manifest SHA-256: `6a78a572ce671846e41acc233350debcb680db556a6794298f6a8e7189460eed`
- Emberi jóváhagyás: `APPROVED`
- OpenTimestamps: `BITCOIN_ANCHOR_CONFIRMED`
- Attesztációs blokkok: `953408`, `953410`, `953423`

A ZIP belső dokumentumai a 2026-06-12-i, timestamp-beküldés előtti állapotot őrzik, ezért bennük még `OTS_STAMP_PENDING` és `BITCOIN_ANCHOR_PENDING` szöveg szerepelhet. A release-hez csatolt későbbi `.ots` receiptek a változatlan ZIP és manifest Bitcoin-blokkattestációit tartalmazzák.

## Szerzőség és AI-közreműködés

- Elkán Krisztián: emberi alkotó, kezdeményező és a publikációs döntés jogosultja.
- Codex (OpenAI): AI-közreműködő, technikai megvalósító és auditor.
- ChatGPT (OpenAI): AI-közreműködő, szerkesztő és strukturáló társ.

Elkán Krisztián emberi szerzői igényt rögzít a projekt emberi gondolatmagjára, szerkesztett szerkezeti formájára és publikációs döntéseire. A jogi felülvizsgálat státusza: `LEGAL_REVIEW_PENDING`.

Codex és ChatGPT AI-rendszerek. Az AI-közreműködés projektkredit és munkamegosztási jelölés; nem állítás arról, hogy az AI emberi szerző vagy jogalany lenne.

## Bizonyítási határ

A hash, az OpenTimestamps receipt és a Bitcoin-attestáció a pontos fájlbájtok integritását és legkésőbbi létezési idejét támogatja. Nem bizonyítja a dokumentum tartalmi állításainak igazságát, szerzőséget, tulajdonjogot vagy wallet-hozzáférést.

A receiptek blokkheader-, Merkle-root- és Proof of Work kontrollja külső blokkadatokból reprodukálódott. Saját Bitcoin Core RPC-vel végzett teljes helyi ellenőrzés nincs állítva.

## Ellenőrzés

```bash
shasum -a 256 DIGITAL_ORGANISM_RAW_ONLY_PUBLIC_v1.0.0.zip
ots info DIGITAL_ORGANISM_RAW_ONLY_PUBLIC_v1.0.0.zip.ots
ots verify DIGITAL_ORGANISM_RAW_ONLY_PUBLIC_v1.0.0.zip.ots
```

Az `ots verify` teljes futásához használható, szinkronizált Bitcoin Core node vagy más megfelelő ellenőrzési környezet szükséges lehet.

## Adatvédelmi határ

A release nem tartalmazhat privát kulcsot, WIF-et, seed phrase-t, wallet backupot, jelszót vagy más hozzáférési titkot. A teljes RAW_ONLY munkakönyvtár nem része ennek a publikációnak.

## Licenc

Ehhez a történeti kiadáshoz nem került automatikusan licencfájl hozzáadásra. A jogi és licencelési felülvizsgálat státusza: `LEGAL_REVIEW_PENDING`.
