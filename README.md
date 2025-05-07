# DP-700_LAB06c
# Microsoft Fabric: Een Datawarehouse Monitoren

Deze repository bevat een handleiding voor het monitoren van een datawarehouse in **Microsoft Fabric**, met gebruik van dynamische beheeroverzichten (DMV's) en query-inzichten.

## Overzicht

Microsoft Fabric biedt een relationele database die geoptimaliseerd is voor grootschalige analyses. Deze gids laat je zien hoe je de activiteit en query's in een datawarehouse kunt volgen met behulp van ingebouwde beheerfuncties.

## Voorwaarden

- Een actieve proefversie van **Microsoft Fabric** is vereist.
- Ongeveer **30 minuten** nodig om deze lab te voltooien.

## Stappen

### 1. Werkruimte aanmaken

1. Ga naar [Microsoft Fabric](https://app.fabric.microsoft.com/home?experience=fabric) en log in.
2. Klik op **Werkruimtes** in het menu.
3. Maak een nieuwe werkruimte aan met een geschikte naam en kies een licentiemodus zoals **Proef**, **Premium**, of **Fabric**.

### 2. Voorbeeld Datawarehouse Maken

1. Klik op **Maken** en kies onder **Datawarehouse** de optie *Voorbeeld-warehouse*.
2. Noem het nieuwe warehouse `sample-dw`.

### 3. Dynamische Beheeroverzichten (DMV's) Verkennen

Met DMV's kun je actieve verbindingen, sessies en verzoeken in het datawarehouse analyseren. Voorbeelden van beschikbare overzichten:

- `sys.dm_exec_connections`
- `sys.dm_exec_sessions`
- `sys.dm_exec_requests`

Je kunt ook deze overzichten combineren voor diepere inzichten in actieve processen.

### 4. Query-inzichten Verkennen

Gebruik `queryinsights`-overzichten om meer te leren over query-prestaties:

- `exec_requests_history`
- `frequently_run_queries`
- `long_running_queries`

### 5. Opruimen

Na afloop kun je de werkruimte verwijderen:

- Ga naar **Instellingen** van de werkruimte.
- Kies **Verwijderen** om de werkruimte op te ruimen.

## Meer Informatie

Bezoek de officiële [Microsoft Fabric documentatie](https://learn.microsoft.com/nl-nl/fabric/) voor meer details over DMV's en query-inzichten.

---

📘 Dit project is bedoeld voor educatieve doeleinden en vereist geen programmatiekennis.


![Schermafbeelding 2025-05-07 234516](https://github.com/user-attachments/assets/4ee884a7-9324-4744-93bd-1d7f8b18e935)

![Schermafbeelding 2025-05-07 235348](https://github.com/user-attachments/assets/310a7b38-6567-4d8f-bda7-01db4a411d98)


![Schermafbeelding 2025-05-07 235424](https://github.com/user-attachments/assets/bd5995ba-0db1-4cb1-9a51-f465cff5a207)

![Schermafbeelding 2025-05-07 235554](https://github.com/user-attachments/assets/219201bf-41bf-478a-9300-3fcbed096165)

![Schermafbeelding 2025-05-07 235611](https://github.com/user-attachments/assets/ebfd0742-2a83-4baf-b07b-a309d2952951)


![Schermafbeelding 2025-05-07 235704](https://github.com/user-attachments/assets/06412723-ed21-453e-ad8e-49e698b55a63)

![Schermafbeelding 2025-05-07 235724](https://github.com/user-attachments/assets/33aecd04-6219-452a-a539-776acdc675d7)


![Schermafbeelding 2025-05-07 235843](https://github.com/user-attachments/assets/35959bca-534d-4292-8996-49574dbfd830)



![Schermafbeelding 2025-05-08 000016](https://github.com/user-attachments/assets/38394f82-4dfb-4397-b909-342c721997ed)


![Schermafbeelding 2025-05-08 000101](https://github.com/user-attachments/assets/cb5bf7e4-0799-420b-baf6-be0df0bd0066)

















