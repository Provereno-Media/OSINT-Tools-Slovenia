# OSINT-Tools-Slovenia
<img src="https://flagcdn.com/w320/si.png" alt="Slovenia_FLAG"/>
A list of OSINT resources and tools that may be useful to you when conducting investigations related to Slovenia. Most of the resources and tools has versions in Slovene, some also in English. Key identifiers: company registration number (matična številka), tax number (davčna številka), personal number (EMŠO); real estate is searched by cadastral municipality (katastrska občina) + parcel or building number. Many official services are JavaScript applications and load slowly or not at all in automated tools; open them in a normal browser. The beneficial ownership register (RDL) is no longer public: after the CJEU judgment of 22 November 2022 (C-37/20, C-601/20) and the amendment of the AML/CFT Act (ZPPDFT-2), access is granted on request to obliged entities, journalists, civil-society organisations and persons with a proven legal interest. From 1 March 2026 the Official Gazette (Uradni list RS) is published only electronically in PISRS; earlier issues remain on uradni-list.si as an archive.

**Last Updated:** 2026-10-12

## Contributions
Feel free to join this project — [OSINT For Countries V2.0](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)

## Table of contents:
 - [Open Data portals](#open-data-portals)
 - [Legal Entities](#legal-entities)
 - [Cadastral and other Maps](#maps)
 - [Vehicles](#vehicles)
 - [People, phones, social etc.](#people)
 - [Public procurements](#public-procurement)
 - [WHOIS](#whois)

## Open Data portals
(Country Open Data, Stock Exchange, Courts)
- [Odprti podatki Slovenije – OPSI (Open Data Slovenia)](https://podatki.gov.si/) — national open data catalogue of public-sector datasets in 14 thematic areas, with an API store (OPSIapi) and an applications showcase; includes the AJPES CSV list of registered business entities (refreshed twice a month). Search by keyword or theme. *Lang: SL.* 🏛️
- [PISRS – Pravno informacijski sistem Republike Slovenije (Legal Information System)](https://pisrs.si/) — free database of Slovenian and EU legislation with consolidated texts, version comparison, links between acts, public consultations and an API; since 1 March 2026 the Official Gazette is issued here. Search by title, keyword or act ID. *Lang: SL.* 🏛️
- [Uradni list RS (Official Gazette of the Republic of Slovenia)](https://www.uradni-list.si/) — Official Gazette issues as PDFs (regulations section, announcements section, international treaties) with per-issue indexes; archive of issues up to February 2026. Browse by issue and date. *Lang: SL.* 🏛️
- [Ustavno sodišče Republike Slovenije (Constitutional Court)](https://www.us-rs.si/) — Constitutional Court website with decisions listed by case number (U-I, Up etc.), pending cases and session schedules. *Lang: SL.* 🏛️
- [Na sodišču (Slovenian Judiciary Information Portal)](https://nasodiscu.si/) — judiciary portal with court procedure guides, court statistics, electronic judicial auctions (e-dražbe) and access instructions for the electronic land register. *Lang: SL.* 🏛️
- [SURS – Statistični urad Republike Slovenije (Statistical Office)](https://www.stat.si/) — official statistics by theme (population, economy, environment, elections), the SI-STAT data portal with table export, statistical atlas and name database. *Lang: SL, EN.* 🏛️
- [SEOnet – Ljubljanska borza (Ljubljana Stock Exchange Disclosure System)](https://seonet.ljse.si/default_en.aspx?doc=PUBLIC_ANNOUNCMENTS&language=en) — regulated disclosures of listed issuers: inside information, annual and audit reports, major shareholding notifications, prospectuses. Search by keyword, issuer, ISIN, LEI, date and document type. *Lang: SL, EN.*

## Legal Entities
- [AJPES ePRS – Poslovni register Slovenije (Business Register of Slovenia)](https://www.ajpes.si/prs) — official register of all business entities: search by entity, by person (founder, shareholder, representative, supervisory board member) and business-name check; shows whether an entity holds accounts abroad; free e-extracts for court-registered entities and sole traders. *Lang: SL.* 🏛️ ⚠️
- [AJPES eObjave – Uradne objave (Official Notices)](https://www.ajpes.si/Uradne_objave) — free official web notices: business and court register entries with the Collection of documents (Zbirka listin), insolvency notices published by courts, company notices under the Companies Act (ZGD-1), notarial real estate sales under ZFZ. Browse by notice type. *Lang: SL.* 🏛️
- [AJPES eINSOLV – Vpisnik zadev v postopkih zaradi insolventnosti (Insolvency Case Register)](https://www.ajpes.si/eINSOLV) — view of the Supreme Court case register (Vpisnik zadev) for insolvency proceedings; complements the court insolvency notices in eObjave. *Lang: SL.* 🏛️
- [AJPES RDL – Register dejanskih lastnikov (Beneficial Ownership Register)](https://www.ajpes.si/Registri/Drugi_registri/Register_dejanskih_lastnikov/Splosno) — no longer public; access on request for obliged entities, journalists and media, civil-society organisations (incl. NGOs and academics) working on AML, or on proven legal interest. Apply via eRDL (user profile + qualified digital certificate), signed e-mail or post; fees may apply. *Lang: SL.* 🏛️ ⚠️
- [FURS – Seznam nepredlagateljev obračunov REK in neplačnikov davkov (Financial Administration: List of REK Non-filers and Tax Debtors)](https://www.fu.gov.si/e_storitve/seznam_nepredlagateljev_obracunov_rek_in_neplacnikov_davkov_furs/) — official monthly public list (published by the 10th) of taxpayers whose overdue tax debt exceeded €5,000 and is older than 90 days on the 25th of the previous month, in ten size bands, plus employers who failed to file REK payroll returns; published since August 2014. *Lang: SL.* 🏛️

## Maps
(Cadastral Maps if available, GIS etc.)
- [GURS – Javni vpogled v podatke o nepremičninah (Public Real Estate Viewer)](https://ipi.eprostor.gov.si/jv/) — parcels, buildings and building parts from the land cadastre, building cadastre, real estate register and register of spatial units, incl. publicly available owner data. Search by cadastral municipality code + parcel/building number or by clicking on the map. *Lang: SL.* 🏛️
- [GURS – Vpogled v aktualne cene nepremičnin (Real Estate Prices)](https://eprostor.gov.si/ETN-JV/) — recent sale prices from the real estate market register (ETN) on a map; informative data that may contain reporting errors. *Lang: SL.* 🏛️
- [GURS – Javni vpogled v vrednosti nepremičnin (Real Estate Values)](https://vrednotenje.gov.si/EV_JV/) — generalised (mass-valuation) values of properties. *Lang: SL.* 🏛️
- [PIS – Prostorski informacijski sistem (Spatial Information System)](https://pis.eprostor.gov.si/pis) — state, regional and municipal spatial plans, construction administrative acts (building permits), legal regimes and the building land register, with the "Grafični vpogled" map viewer. *Lang: SL.* 🏛️
- [eZKN – Pregledovalnik arhivskih zemljiškokatastrskih načrtov (Archival Cadastral Maps Viewer)](https://geohub.gov.si/ezkn) — archival land cadastre plans (DjVu) and Franciscean and Reambulation cadastre maps from the Archives of Slovenia. *Lang: SL.* 🏛️
- [eUprava – Iskalnik katastrskih postopkov (Cadastral Procedures Search)](https://e-uprava.gov.si/javne-evidence/katastrski-postopki.html) — published cadastral procedures concerning a parcel or building (visible for 2 years, 3 for new surveys). Input: cadastral municipality + parcel or building number. *Lang: SL.* 🏛️
- [eSodstvo – e-Zemljiška knjiga (Electronic Land Register)](https://esodisce.si/spa/) — land register (ownership, mortgages, easements); search by cadastral municipality + parcel, building/part number, property ID or right ID. Online view requires SI-PASS login (at least smsPASS) and an EMŠO. *Lang: SL.* 🏛️ ⚠️ 🪪

## Vehicles

### Land
- [eUprava – Motorna vozila (Motor Vehicles Public Record)](https://e-uprava.gov.si/si/javne-evidence/motorna-vozila.html) — data on a vehicle from the public record. Input: registration certificate type + number AND licence plate, so it verifies a known vehicle document rather than searching by plate alone. *Lang: SL.* 🏛️

### Maritime
- [eUprava – Plovila / Vpisnik čolnov (Boat Register)](https://e-uprava.gov.si/si/javne-evidence/plovila.html) — boat and engine particulars, owners, registration mark, name, restrictions on disposal, navigation permit validity and encumbrances. Search by registration mark or boat name. *Lang: SL.* 🏛️
- [Luka Koper – Najave ladij, plan pilotaž in stanje na privezih (Port of Koper Ship Arrivals)](https://www.luka-kp.si/storitve-in-terminali/najave-ladij-plan-pilotaz-in-stanje-na-privezih/) — arrival plan, pilotage plan and berth status for the Port of Koper. Filters by date, ship code, agent code, berth and cargo. *Lang: SL.*
- [VesselFinder](https://www.vesselfinder.com/) — global AIS vessel tracking map; use for ships calling at Koper and in the Gulf of Trieste. *Lang: EN.* 💲 Freemium: live map free; real-time and historical AIS data paid

### Aviation
- [CAA – Seznam imetnikov spričevala letalskega prevoznika (Civil Aviation Agency: AOC Holders)](https://www.caa.si/seznami-imetnikov-dovoljenj.html) — Slovenian air operators with certificate number (SI.AOC.xx/yyyy), operation type, status and AOC certificate PDFs. *Lang: SL.* 🏛️
- [CAA – Seznami (Civil Aviation Agency: Lists of Approved Organisations)](https://www.caa.si/seznami.html) — Part-145, Part-147, CAMO, CAO and 21G organisations, training organisations (ATO/DTO), examiners and aero-medical examiners. *Lang: SL.* 🏛️
- [CAA – Seznam imetnikov dovoljenj in izjav UAS (Civil Aviation Agency: Drone Authorisations)](https://www.caa.si/seznam-imetnikov-dovoljenj-in-izjav-uas.html) — PDF lists of UAS operators holding specific-category authorisations and declarations. *Lang: SL.* 🏛️
- [CAA – Poizvedbe iz registra (Civil Aviation Agency: Aircraft Register Queries)](https://www.caa.si/poizvedbe-iz-registra.html) — the civil aircraft register (S5- marks) is public by registration mark, but online viewing is currently unavailable; queries are answered by e-mail. *Lang: SL.* 🏛️
- [Flightradar24](https://www.flightradar24.com/) — global live flight tracking; useful for S5- registered aircraft and Ljubljana (LJU) traffic. *Lang: EN.* 💲 Freemium: live map and flight search free; alerts and extended features in paid plans

## People
(Names, Addresses, Yellow Pages, White Pages etc.)
- [KPK – Javna objava sprememb premoženjskega stanja (Anti-Corruption Commission: Officials' Asset Changes)](https://www.kpk-rs.si/sl/instituti/premozenjsko-stanje/javna-objava-sprememb-premozenjskega-stanja) — reported changes in the assets of MPs, the President, PM, ministers, state secretaries, mayors and deputy mayors, Bank of Slovenia council members and Constitutional Court judges; published since February 2022, since 5 March 2025 in Erar. *Lang: SL.* 🏛️
- [eUprava – Statusi dokumentov (Document Status Check)](https://e-uprava.gov.si/si/javne-evidence/statusi-dokumentov.html) — status of an ID card, passport, driving licence, firearms certificate or residence permit. Input: document serial number + issue date. *Lang: SL.* 🏛️
- [KPK – Register lobistov (Anti-Corruption Commission: Register of Lobbyists)](https://www.kpk-rs.si/sl/instituti/lobiranje/register-lobistov) — public register of registered lobbyists (97 listed on 2026-10-12): name, lobbying policy areas, often company, address and e-mail; links a PDF of lobbyists sanctioned for non-reporting. KPK warns of possible data inaccuracies. *Lang: SL.* 🏛️
- [Detektor premoženja (Asset Detector, Oštro)](https://detektorpremozenja.si/) — journalist-built database of assets (real estate, company stakes and other assets) of the PM, ministers, state secretaries, MPs, MEPs, mayors and their close family; browse by category and personal profile. *Lang: SL.*
- [TIS – Telefonski imenik Slovenije (Slovenian Telephone Directory)](https://itis.siol.net/) — directory of persons and companies with phone, e-mail and address; search by name with advanced search, region and business-activity filters, map view. *Lang: SL.*
- Try [OSINT Industries](https://app.osint.industries) and don't forget about the [Digital Profiler's Toolkit](https://github.com/paulpogoda/Digital-Profiler-s-Toolkit)

## Public procurement
- [Portal javnih naročil – PJN (Public Procurement Portal)](https://enarocanje.si/) — official publication of public procurement notices ("Pregled objav"); the public part is accessible without login. Search by contracting authority or procurement title (exact full names), default period 3 months. *Lang: SL.* 🏛️
- [e-JN – Aktualna javna naročila (e-Procurement: Current Tenders)](https://ejn.gov.si/ponudba/pages/aktualno/aktualna_javna_narocila.xhtml) — tenders run in the e-JN system with contracting authority, title, procedure, PJN number, deadlines and status. Filters by authority, title, status, procedure type and dates. *Lang: SL.* 🏛️
- [Odprta Skrinja (Open Chest: Procurement Analytics)](https://ejn.gov.si/skrinja.html) — official analytical tool displaying public procurement data of the Republic of Slovenia. *Lang: SL, EN.* 🏛️
- [Erar (Anti-Corruption Commission Spending Tracker)](https://erar.si/) — transactions of public-sector bodies and state- and municipally-owned companies to recipients, e-invoices since 1 September 2024, plus lobbying contacts, gifts, officials' asset changes and business restrictions (JavaScript application). *Lang: SL.* 🏛️
- [TED – Tenders Electronic Daily](https://ted.europa.eu/en/) — EU Official Journal procurement notices, incl. Slovenian above-threshold tenders and awards; advanced search with place of performance and CPV. *Lang: EN + EU languages.* 🏛️

## WHOIS
- [Register.si – .si Domain Lookup / WHOIS](https://www.register.si/en/) — official .si registry run by ARNES: domain status, registrar and expiry; for natural persons only a contact e-mail is public. *Lang: SL, EN.* 🏛️
- [Register.si – RDAP](https://www.register.si/rdap/) — RDAP (JSON) for .si domains, nameservers and registrars, e.g. `https://rdap.register.si/domain/<domain>`; anonymous queries return no registrant data, search is limited to authenticated users. *Lang: SL.* 🏛️
- [Register.si – Disclosure of Information about a .si Domain Holder](https://www.register.si/en/disclosure-of-information-about-a-si-domain-holder/) — procedure to request non-public holder data with a justified reason (e.g. IP rights, court proceedings), by e-mail or post. *Lang: SL, EN.* 🏛️
- [IANA – .si Delegation Record](https://www.iana.org/domains/root/db/si.html) — ccTLD manager (ARNES), WHOIS server (whois.register.si) and RDAP server for .si. *Lang: EN.*
- [Imenik domen (.si Domain Directory)](https://www.imenik-domen.com/) — private directory of .si domains (since 2009) with site content and historical owner information; owner data is no longer updated. *Lang: SL.*
- [ICANN Lookup](https://lookup.icann.org/) — registration data for gTLD domains and IP number resources; use for non-.si domains of Slovenian entities. *Lang: EN.*

---

## Contributing

To contribute to this repository:
1. Verify all links are working and accessible
2. Provide accurate descriptions of database contents
3. Follow the 7-category structure
4. Include official government sources when available
5. Submit pull requests with detailed change descriptions

## Legal Disclaimer

This repository is for educational and legitimate investigative purposes only. Users are responsible for:
- Complying with all applicable laws and regulations
- Respecting terms of service for all databases and tools
- Using information ethically and responsibly
- Obtaining proper authorization when required

The information provided is for informational purposes only and should not be considered legal advice.

---

**Repository maintained by the [OSINT-for-Countries-V2.0 community](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)**
