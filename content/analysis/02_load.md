---
Title: Laddnings tid
Description: My report page for kmom05.
Template: analysis
---


En undersökning om modewebbsidors laddningstid och användarvänlighet
=======================

Syftet med denna uppgift är att få en ökad förståelse för hur en webbsidas uppladdningstid och användarvänlighet kan optimeras för öka dess funktionalitet samt användarupplevelse.

Urval
-----------------------
De webbsidor som undersöks är H&M, Gina Tricot och Nelly. Dessa webbsidor är e-handelsplattformar inriktade på mode och är väldigt populära bland kvinnor inom olika målgrupper. Det förkommer bilder och videos på dessa webbsidor för att marknadsföra kläder och accessoarer. Eftersom innehållet kan påverka både laddningstid och användbarhet är det relevant att analysera hur dessa sidor presterar och jämföra deras optimeringsnivåer.

Metod
-----------------------
Metoden som används i denna undersökning är devtools som är en inbyggd funktion i webbläsaren och webbsidan PageSpeed. Devtools kommer att användas för att mäta webbsidornas laddningstid, resurser samt sidstorlek. PageSpeed kommer användas för att mäta prestandan och användarvänligheten. Den utför en helhetsundersökning och utser betyg beroende på webbsidornas innehåll. De mäter sidors prestanda, tillgänglighet, bästa metoder och SEO för både mobil och datorenheter. Med hjälp av dessa verktyg kan en utförlig undersökning genomföras.

Resultat
-----------------------

Resultatet omfattade tre webbplatser: H&M, Gina Tricot och Nelly, där både mobil- och datorversioner analyserades. Mätningarna fokuserade på prestanda, tillgänglighet, bästa metoder, SEO, sidstorlek, antalet resurser och laddningstid. 
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQdMyX6_fwABbHh2xhbtRIEuAH9sNykWBV29Ijx4tEColKFITh2DchYTyEqg52xKEFeY_2rvEyo9i--/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" class="kalkyl"></iframe>

H&M
Webbplatsen presterar relativt dåligt, speciellt på mobil 42 poäng jämfört med dator 64 poäng. Sidans storlek är cirka 7 MB på mobil och 9,3 MB på dator, vilket resulterar i en lång laddningstid på ca 1 minut på mobil och 1,9 minuter på dator. Däremot fick webbsidan höga betyg för tillgänglighet (93), bästa metoder (96) samt SEO (85). H&Ms webbsida fick däremot godkänt på datorversionen då den fick lagom höga poäng inom alla kategorier.

Gina Tricot
Webbplatsen har en låg prestationsnivå på mobil med endast 20 poäng, medan datorversionen presterar bättre med 56 poäng. Sidans storlek är mindre jämfört med H&M, med 2,1 MB på mobil och 2,4 MB på dator. Detta bidrar till kortare laddningstider på ca 50 sekunder respektive 55 sekunder. Webbplatsen fick högst betyg inom bästa metoder (100), medan tillgänglighet och SEO fick betygen 75 respektive 79.

Nelly
Webbsidan har en väldigt bra laddningstid med 38 sekunder på mobil och 53 sekunder på dator. Sidstorleken är också relativt mindre än de andra webbsidorna med 2,5 MB på mobil och 3,2 MB på dator. Trots detta fick webbsidan prestandabetyget 27 poäng på mobil och 53 poäng på dator. Webbsidan presterade bra inom tillgänglighet med 91 respektive 92 poäng. Därefter fick bästa metoder och SEO betygen 75, 74 och 92.

<div class="gallery">
    <div class="pics">
        <a href="%base_url%/image/Hm.png" target="_blank">
            <picture>
                <img src="%base_url%/image/Hm.png?w=375&h=250&q=80" alt="H&M">
            </picture>
        </a>
        <a href="%base_url%/image/Ginatricot.png" target="_blank">
            <picture>
                <img src="%base_url%/image/Ginatricot.png?w=375&h=250&q=80" alt="Gina Tricot">
            </picture>
        </a>
        <a href="%base_url%/image/Nelly.png" target="_blank">
            <picture>
                <img src="%base_url%/image/Nelly.png?w=375&h=250&q=80" alt="Nelly">
            </picture>
        </a>
    </div>
</div>



Analys
-----------------------

H&M:s webbplats tar längre tid att ladda på både mobil och dator, främst på grund av den stora sidstorleken. Bilder och andra mediefiler verkar vara de största bidragande faktorerna till detta. För att förbättra prestandan och laddningstiden bör H&M optimera sina bilder och minska arbetsbelastningen på modertråden genom att implantera lazy-loading samt minimera och ta bort oanvänd kod inom CSS och JavaScript.

Gina Tricots webbplats presterade betydligt sämre inom prestanda, tillgänglighet och SEO, särskilt i mobilversionen. Däremot har webbsidan en betydligt mindre sidstorlek och laddningstid än H&M. Webbplatsen följer riktlinjerna inom bästa metoder och får högsta betyget inom detta område. För att förbättra prestandan ytterligare bör Gina Tricot implementera lazy-loading genom att skjuta upp inhämtningen av data utanför fönstret och anpassa bildstorleken utifrån typen av enhet. För att öka tillgängligheten bör Gina Tricot anpassa sitt innehåll för skärminläsning genom att lägga till namn på menyalternativen.   

Nelly presterade bäst vad gäller laddningstider och sidstorlek, vilket beror på webbsidan minimalistiska innehåll. Trots detta är prestandapoängen låg, vilket kan kopplas till ineffektiva JavaScript-filer och bristande bildoptimering. För att ytterligare förbättra prestandan bör Nelly fokusera på att reducera sitt dom träd för förbättra användare upplevelsen samt eliminera resurser som kan blockera renderingen av webbsidan. Den höga tillgänglighetspoängen indikerar att webbplatsen är välstrukturerad och användarvänlig.

De vanligaste förbättringsåtgärder som har förslagits är bildoptimering, lazy-loading och minimering av CSS och JavaScript kod. Utifrån resultatet kan slutsatsen tas att Nelly är vinnaren på grund av dess snabba laddningstid samt lagom sidstorlek. Trots låga prestandapoäng har webbsidan lagom höga betyg i de resterande mätvärden vilket är en indikation på att den erbjuder en relativt bra användarupplevelse. Därefter Gina Tricot på andra plats med hänsyn till sin mindre sidstorlek och användarvänliga metoder. H&M rankas på tredje plats på grund av sin långa laddningstid och stora sidstorlek som kan påverka användarupplevelsen negativt.

Jag anser att en optimal laddningstid för en modeinriktad webbplats bör vara cirka 40 sekunder, eftersom det möjliggör en snabb och smidig upplevelse utan att användaren tappar intresset. Utifrån detta gränsvärde presterar Nelly bäst då dess laddningstid ligger inom ramen för det acceptabla (38 sekunder på mobil), medan Gina Tricot och H&M överskrider gränsen med laddningstider på 50 sekunder respektive över 1 minut. Generellt upplevs Nelly som den snabbaste webbplatsen i mitt urval, medan Gina Tricot och H&M känns långsamma och mindre användarvänliga.

Referenser
-----------------------

H&M (n.d.). H&M. Tillgänglig på: https://www2.hm.com/sv_se/index.html (Hämtad: 27 december 2024).
Gina Tricot (n.d.). Gina Tricot. Tillgänglig på https://www.ginatricot.com/se/start (Hämtad: 27 december 2024).
Nelly (n.d.). Nelly. Tillgänglig på: https://nelly.com/se/ (Hämtad: 28 december 2024).
Pagespeed Insights (n.d.). Pagespeed insights. Tillgänglig på: https://pagespeed.web.dev/ (Hämtad: 27 december 2024).

Övrigt
-----------------------
Malak Al Moughabat