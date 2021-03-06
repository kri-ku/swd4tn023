# Ohjelmistokehityksen teknologioita [![Build Status](https://travis-ci.org/haagahelia/swd4tn023.svg?branch=master)](https://travis-ci.org/haagahelia/swd4tn023)

Tervetuloa kurssille!

Ohjelmistokehittäjän työ on suurimmaksi osaksi muuta kuin jonkin tietyn ohjelmointikielen syntaksin suvereenia hallintaa. Tämän kurssin tavoitteena on esitellä ohjelmistokehittäjälle tärkeitä taitoja, työkaluja ja tekniikoita, joita ei suoraan ole tullut esille ohjelmoinnin peruskursseilla tai projektityökursseissa. Kurssi toimii samalla myös tukikurssina ohjelmistoprojekti 2-kurssille, jossa tämän kurssin asioita päästään soveltamaan käytännössä.

Opettajina kurssilla toimivat Ohto Rainio ja Teemu Havulinna (etunimi.sukunimi@haaga-helia.fi).

![Kurssin aiheet](img/kurssin_aiheet.png)

## Linkit

* [Opintojaksokuvaus](https://opinto-opas.haaga-helia.fi/course_unit/SWD4TN023)
* [Teams](https://teams.microsoft.com/)

## Kurssin suoritustapa
Kurssin alkupuoliskolla esitellään viikoittain eri aiheita ja opiskelijat tekevät niihin liittyviä harjoitustehtäviä. Jokaisesta esiteltävästä aiheesta on myös mahdollista tehdä laajempi seminaaritehtävä kurssin jälkimmäisellä puoliskolla. Seminaarivaiheessa, kurssin jälkimmäisellä puoliskolla, jokainen opiskelija valitsee kurssin aiheista itseään eniten kiinnostavan ja tekee siihen liittyvän seminaaritehtävän. Seminaaritehtävän voi valita joko opettajien ehdotuksista tai seminaaritehtävän aihetta voi ehdottaa myös itse. Seminaaritehtävä voi liittyvä läheisesti opiskelijan ohjelmistoprojekti 2-projektiin. Saman seminaariaiheen valinneet opiskelijat osallistuvat sen aiheen yhteiseen seminaariin, jossa analysoidaan ja kommentoidaan myös muiden opiskelijoiden seminaaritöitä. Lopuksi järjestetään vielä mahdollinen yhteinen seminaari, jossa jokaisen pienemmän seminaarin tärkeimmät (tai parhaat) tulokset esitellään kaikille.

## Opintojakson oppitunnit ja päivämäärät

**Kurssin aikataulun päivittäminen on kesken. Aikatauluun on tulossa merkittäviä muutoksia.**

<table>
    <thead>
        <tr>
            <th>Päivämäärä</th>
            <th>Aihe</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>pe 22.1.</td>
            <td>
                <a href="00_linux">Kurssin johdanto, ympäristöt ja Linux/Unix-komentorivi</a><br />
                <a href="00_linux/asennukset.md">⭐ Ennakkotehtävä: kurssin kehitysympäristön asennus</a>
            </td>
        </tr>
        <tr>
            <td>pe 29.1.</td>
            <td>
                <a href="01_python">Python-ohjelmointi</a><br />
                <ul>
                    <li>Ehto- ja toistorakenteet</li>
                    <li>Perustietotyypit ja kokoelmat</li>
                    <li>Http-pyynnöt</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>pe 5.2.</td>
            <td>
                <a href="02_testaus">Testaus</a><br />
                <ul>
                    <li>Testauksen tasot</li>
                    <li>Yksikkötestaus</li>
                    <li>Test driven development</li>
                    <li>Testikattavuus, fixturet, mock:it</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>pe 12.2.</td>
            <td>
                <a href="03_infra_ja_automaatio">Infra ja automaatio</a><br />
                <ul>
                    <li>Continuous integration</li>
                    <li>Git: branch, merge, rebase...</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>pe 19.2.</td>
            <td>
                <a href="04_tietorakenteet_ja_algoritmit">Tietorakenteet ja algoritmit</a><br />
                <ul>
                    <li>Lajittelualgoritmit</li>
                    <li>Hakualgoritmit</li>
                    <li>Algoritmien tehokkuus</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>pe 26.2.</td>
            <td><del>Talvilomaviikko</del></td>
        </tr>
        <tr>
            <td>pe 5.3.</td>
            <td>
                <a href="05_es6_node">Node / JavaScript</a><br />
                <ul>
                    <li>ES6-syntaksit</li>
                    <li>filter, map, reduce</li>
                    <li>currying</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>pe 12.3.</td>
            <td>
                <a href="05_es6_node">Node / JavaScript</a><br />
                <ul>
                    <li>Express.js</li>
                    <li>Promise</li>
                    <li>Async/await</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>pe 19.3.</td>
            <td>
                <a href="06_ohjelmistoarkkitehtuurit_ja_patternit">Ohjelmistoarkkitehtuurit ja patternit</a>
            </td>
        </tr>
        <tr>
            <td>pe 26.3.</td>
            <td><del>Intensiiviviikko</del></td>
        </tr>
        <tr>
            <td>pe 2.4.</td>
            <td>
                Pitkäperjantai: <strong>ei oppituntia</strong><br />
                Azure-videomateriaalit itseopiskeluun
            </td>
        </tr>
        <tr>
            <td>pe 9.4.</td>
            <td>
                <a href="06_ohjelmistoarkkitehtuurit_ja_patternit">Ohjelmistoarkkitehtuurit ja patternit</a>
            </td>
        </tr>
        <tr>
            <td>pe 16.4.</td>
            <td>
                <a href="06_ohjelmistoarkkitehtuurit_ja_patternit">Ohjelmistoarkkitehtuurit ja patternit</a>
                <ul>
                    <li>Tehtävien purku</li>
                    <li>Vierailu</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>pe 23.4.</td>
            <td>
                <a href="07_koneoppiminen">Koneoppiminen</a>
            </td>
        </tr>
        <tr>
            <td>pe 30.4.</td>
            <td><a href="08_seminaari">Seminaarien käynnistys</a></td>
        </tr>
        <tr>
            <td>pe 7.5.</td>
            <td>Seminaarityön tekemistä<br />
                <em>Yksilöllistä ohjausta Teamsissa</em></td>
        </tr>
        <tr>
            <td>pe 14.5.</td>
            <td>Seminaarityön tekemistä<br />
                <em>Yksilöllistä ohjausta Teamsissa</em></td>
        </tr>
        <tr>
            <td>pe 21.5.</td>
            <td>Seminaariesityksiä</td>
        </tr>
    </tbody>
</table>

## Viestintäkanavat

Tällä kurssilla oppitunnit järjestetään MS Teams -palvelussa. Teams tarjoaa myös luontevan kanavan kysyä ja keskustella oppituntien ulkopuolella. Jos jäät jumiin tehtävän kanssa tai et ymmärrä materiaaleja tai tehtävänantoja, kysy rohkeasti vinkkejä Teamsissa. Todennäköisesti samaa ongelmaa pohtii kanssasi myös moni muu, joten lähetäthän sisältöä ja tehtävänantoja koskevat kysymykset yhteiselle kanavalle eikä yksityisviestinä.

Kurssilla suositellaan käytettävän Teamsin työpöytäsovellusta. Kirjautuminen Teamsiin tapahtuu Haaga-Helian opiskelijatunnuksella.

Liittymisohje kurssin työtilaan löytyy sähköpostitse lähetetystä tiedotteesta.

* [Teams Quick Start -ohje (pdf)](https://download.microsoft.com/download/D/9/F/D9FE8B9E-22F5-47BF-A1AB-09539C41FCD0/Teams%20QS.pdf)
* [Teams](https://teams.microsoft.com/)
* [Teams-lataussivu](https://teams.microsoft.com/downloads)

## Työkalut

Kurssilla käytetään lukuisia eri teknologioita ja työkaluja, joten joudut todennäköisesti tekemään tietokoneellesi lukuisia erilaisia asennuksia. 

Ohjelmistojen asentaminen ja käyttäminen eri käyttöjärjestelmillä poikkeaa toisistaan merkittävästi, minkä lisäksi saman ohjelmiston eri versiot toimivat joskus hyvin eri tavoilla. Asennus- ja yhteensopivuusongelmien minimoimiseksi kurssilla suositellaan vahvasti oman erillisen Linux-virtuaalikoneen asentamista kurssin tehtävien tekemistä varten. Virtuaalikoneeseen tekemäsi asennukset eivät vaikuta tietokoneesi normaaliin käyttöön, ja käyttämällä virtuaalikonetta saat käyttötukea myös kurssin puolesta. 

Linux voidaan asentaa myös tietokoneen pääkäyttöjärjestelmäksi tai "dual boot"-vaihtoehdolla nykyisen käyttöjärjestelmän rinnalle, mutta näitä vaihtoehtoja ei kurssin puolesta tueta.

Mikäli sinulla on valmiiksi käytössäsi Linux tai muu Unix-pohjainen käyttöjärjestelmä, kuten macOS, voit käyttää sitä kurssilla. Myös Raspberry Pi tai etäyhteydellä käytettävät Linux-ympäristöt, kuten [DigitalOcean](https://www.digitalocean.com/github-students/), sopivat kurssin tarkoituksiin, mutta  niihin pystymme tarjoamaan vain vähäistä käyttötukea.

Lisää ohjeita löydät kurssin [ensimmäisen viikon materiaalista](00_linux).

Kurssin aikana teemme asennuksia Ubuntun `apt`-työkalulla, Pythonin `pip`-työkalulla sekä Noden `npm`-työkalulla. Nämä työkalut lisäävät tietokoneellesi suoritettavaa ohjelmakoodia, jonka yhteydessä tulee aina huomioida myös tietoturva. Asennusten tekeminen erillisessä virtuaalikoneessa on oiva lisä oman tietokoneesi suojaamiseksi, vaikka olemmekin pyrkineet valitsemaan vain erittäin tunnettuja ja hyvämaineisia ohjelmistoja tälle kurssille.


## Arviointi

Kurssi arvioidaan asteikolla 0-5. Kurssin arviointi perustuu viikkoaiheiden yhteydessä suoritettuihin tehtäviin (60% arvosanasta) sekä kurssin toisella puoliskolla tehtävään seminaarityöhön (40%).

Kunkin yksittäisen viikon tehtävien painoarvo kokonaisarvosanassa on yhtä suuri riippumatta viikon maksimipistemäärästä. Pisteet skaalataan yhteneviksi vasta loppuarvosanaa varten.

Yksittäinen palauttamatta jäänyt tai arvosanalla 0 arvioitu tehtävä ei estä seuraavien tehtävien tekemistä, kunhan kokonaisuutena viikkotehtävistä muodostuu hyväksytty arvosana.

## Lähteiden käyttäminen

Tämän kurssin materiaali perustuu suurelta osin valmiisiin netistä löytyviin dokumentaatioihin ja tutoriaaleihein. Tällä sivulla eri aihealueiden yhteydessä tarjotaan linkkejä aihetta koskeviin materiaaleihin, mutta **joudut sen lisäksi merkittävissä määrin etsimään itse tietoa aiheista**.

Ohjelmointiongelmiin löytyy usein valmiita tai osittaisia ratkaisuja ympäri Internetiä niin keskustelupalstoilta kuin tutoriaaleista. Huonossa tapauksessa löydät toimivan ratkaisun ongelmaasi, mutta et osaa aivan tulkita mitä löytämäsi koodi tekee ja miksi se ratkaisee ongelmasi. Ammattimaisessa ohjelmistokehityksessä tästä seuraa mahdollisesti suuriakin vahinkoja.

Nettilähteiden hyödyntäminen ja niistä mallin ottaminen on sallittua ja kannustettavaa, mutta et saa vain kopioida ratkaisuja, vaan sinun tulee ymmärtää, miten koodisi toimii. Lisäksi, erityisesti koska kyseessä on korkeakoulun opintojakso, sinun tulee merkitä lähteet lainatessasi esimerkiksi StackOverflow:sta löytämääsi koodia. Lähdeviitteeksi riittää esimerkiksi verkkosivun osoite kommenttina lainatun koodin yhteydessä, tai käyttämäsi lähteen käyttöehtojen mukainen muu lähdeviite.
