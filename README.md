# Choice your place

This is a project that get text and articles of tourism sites and analyse with the Kmeans and separate for groups according with text. The files use are: data.csv, run.py and choice_cities.txt

<h3>Metodology </h3>
For do this project got caught the 10 cities in 20 coutries most biggest of worlds in 2018, secound https://www.e-unwto.org/doi/pdf/10.18111/9789284421152. Before get the text in web sites (oficials of government and tourism)

<h3>Files </h3>
<ul>
  <li>choice_cities.txt: List of coutries and cities</li>
  <li>data.csv: Cotains 3 columns city, description, reference</li>
  <li>run.py: Executable</li>
</ul>

<h3>Libraries</h3>
<ul>
  <li>nltk: Library of Neuro-linguistic programming for download use pip install nltk</li>
  <li>pandas: Library for manipulate csv for donwload pip install pandas</li>
  <li>sklearn: Library of Marchine Leaning and tecnicals of AI (Artificial Inteligence) for donwload pip install skleanr</li>
  <li>math: Library for mathematical calculations</li>
  <li>string: Library for manipulate strings</li>
</ul>
  
<h3>Texto das cidades</h3>

"Paris https://www.lonelyplanet.com/france/paris"
"Lyon https://www.lonelyplanet.com/france/burgundy-and-the-rhone/lyon"
"Nice https://www.lonelyplanet.com/france/nice"
"Marseille https://www.lonelyplanet.com/france/provence/marseille"
"Bordeaux https://www.lonelyplanet.com/france/southwestern-france/bordeaux"
"Toulouse https://www.lonelyplanet.com/france/toulouse"
"Strasbourg https://www.lonelyplanet.com/france/alsace-and-lorraine/strasbourg"
"Montpellier https://www.lonelyplanet.com/france/languedoc-roussillon/montpellier"
"Lille https://www.lonelyplanet.com/france/northern-france/lille"
"Nantes https://www.lonelyplanet.com/france/southwestern-france/nantes"
"Udon Thani http://www.thailand-guide.com/udon-thani/"
"Bangkok https://www.hoteis.com/go/thailand/bangkok?pos=HCOM_BR&locale=pt_BR"
"Samut Prakan https://portal.tourismthailand.org/About-Thailand/Destination/Samut-Prakan"
"Nonthaburi https://www.tourismthailand.org/Destinations/Provinces/Nonthaburi/226"
"Chonburi https://www.tourismthailand.org/Destinations/Provinces/Chon-Buri/464"
"Nakhon Ratchasima https://www.tourismthailand.org/Destinations/Provinces/Nakhon-Ratchasima/580"
"Chiang Mai https://www.lonelyplanet.com/thailand/chiang-mai-province/chiang-mai"
"Hat Yai https://www.tourismthailand.org/Destinations/Provinces/Hat-Yai/362"
"Sri racha https://thailandlongstay.info/Sriracha.html"
"Pak Kret http://tourismthailand.in/destinations/things-to-do-in-pak-kret/"
"New York City https://www.visiteosusa.com.br/destination/cidade-de-nova-york"
"Los Angeles https://www.visiteosusa.com.br/destination/los-angeles"
"Houston https://www.visiteosusa.com.br/destination/houston"
"Philadelaphia https://www.visiteosusa.com.br/destination/filadelfia"
"Phoenix https://www.visiteosusa.com.br/destination/phoenix"
"San Antonio https://www.visiteosusa.com.br/destination/san-antonio"
"San Diego https://www.lonelyplanet.com/usa/san-diego"
"Chicago https://www.lonelyplanet.com/usa/chicago"
"Dallas https://www.visittheusa.com/destination/dallas 
"San Jose Tourism-g33020-San_Jose_California-Vacations.html?fid=5363fadd-8963-48b9-9dee-70cbc0dc8d67"
"Madrid https://www.spain.info/en/que-quieres/ciudades-pueblos/grandes-ciudades/madrid.html"
"Barcelona https://www.spain.info/en/que-quieres/ciudades-pueblos/grandes-ciudades/barcelona.html"
"Sevilla https://www.spain.info/en/que-quieres/ciudades-pueblos/grandes-ciudades/sevilla.html"
"Valencia 
"Malaga https://www.spain.info/en/que-quieres/ciudades-pueblos/grandes-ciudades/malaga.html"
"Zaragoza https://www.spain.info/en/que-quieres/ciudades-pueblos/grandes-ciudades/zaragoza.html"
"Bilbao https://www.spain.info/en/que-quieres/ciudades-pueblos/grandes-ciudades/bilbao.html"
"Murcia https://www.spain.info/en/que-quieres/ciudades-pueblos/otros-destinos/murcia.html"
"Palma https://www.spain.info/en/que-quieres/ciudades-pueblos/grandes-ciudades/palma.html"
"Las Palmas Canary Island https://www.spain.info/en_US/que-quieres/ciudades-pueblos/provincias/la_palma.html 
"Pequim https://www.lonelyplanet.com/china/beijing"
"Shanghai https://www.lonelyplanet.com/china/shanghai"
"Xian https://www.lonelyplanet.com/china/shaanxi-shanxi/xian"
"Guilin https://www.lonelyplanet.com/china/guangxi/guilin"
"Chengdu https://www.lonelyplanet.com/china/sichuan/chengdu"
"Shenzhen https://www.lonelyplanet.com/china/guangdong/shenzhen"
"Wuhan https://www.lonelyplanet.com/china/hubei/wuhan"
"Dongguan https://trip101.com/article/best-things-to-do-in-dongguan-china"
"Guangzhou https://www.lonelyplanet.com/china/guangdong/guangzhou"
"Tiajin https://www.lonelyplanet.com/china/tianjin"
"Rome http://www.italia.it/en/discover-italy/lazio/rome.html?no_cache=1&h=rome"
"Milan http://www.visititaly.com/holiday/milan.aspx"
"Naples https://www.lonelyplanet.com/italy/campania/naples"
"Genoa https://www.lonelyplanet.com/italy/liguria-piedmont-and-valle-daosta/genoa"
"Bologna https://www.lonelyplanet.com/italy/emilia-romagna-and-san-marino/bologna"
"Florence https://www.lonelyplanet.com/italy/florence 
"Catania https://www.lonelyplanet.com/italy/sicily/catania"
"Bari https://www.lonelyplanet.com/italy/puglia/bari"
"Turin https://www.lonelyplanet.com/italy/lombardia/turin"
"Istanbul https://www.lonelyplanet.com/turkey/istanbul"
"Ankara https://www.lonelyplanet.com/turkey/central-anatolia/ankara"
"Ismir https://www.lonelyplanet.com/turkey/aegean-coast/izmir"
"Bursa https://www.lonelyplanet.com/turkey/bursa"
"Adana https://www.lonelyplanet.com/turkey/adana"
"Gaziantep https://www.lonelyplanet.com/turkey/central-anatolia/gaziantep-antep"
"Konya https://www.lonelyplanet.com/turkey/central-anatolia/konya"
"Bagcilar https://www.turkeyexpert.com/Istanbul/Bagcilar-basin-express-highway?p=9"
"Antalya https://www.lonelyplanet.com/turkey/mediterranean-coast/antalya"
"Cankaya https://www.expedia.co.in/Cankaya.d6323099.Holidays-City-Breaks"
"Hong Kong https://www.lonelyplanet.com/china/hong-kong"
"Mexico City https://www.visitmexico.com/es/destinos-principales/ciudad-de-mexico/ciudad-de-mexico"
"Puebla City https://www.visitmexico.com/es/destinos-principales/puebla/puebla"
"Guadalajara https://www.visitmexico.com/en/main-destinations/jalisco/guadalajara"
"Juarez https://www.visitmexico.com/en/main-destinations/chihuahua/juarez"
"Leon https://www.visitmexico.com/en/main-destinations/guanajuato/leon"
"Tijuana https://www.visitmexico.com/es/destinos-principales/baja-california/tijuana"
"Iztapalapa http://cdmxtravel.com/en/visitor-info/districts/iztapalapa.html"
"Zapopan https://cityofguadalajara.com/zapopan/"
"Ecatepec https://www.expedia.com.sg/Ecatepec-De-Morelos.d179274.Destination-Travel-Guides"
"Gustavo Adolfo Madero  https://www.tripmondo.com/mexico/ciudad-de-mexico/gustavo-a-madero/gustavo-adolfo-madero/"
"Berlin https://www.germany.travel/en/towns-cities-culture/towns-cities/berlin.html"
"Hamburg https://www.germany.travel/en/towns-cities-culture/towns-cities/magic-cities/hamburg.html"
"Munich https://www.germany.travel/en/towns-cities-culture/towns-cities/munich.html"
"Cologne https://www.germany.travel/en/towns-cities-culture/towns-cities/magic-cities/cologne.html"
"Frankfurt https://www.germany.travel/en/towns-cities-culture/towns-cities/magic-cities/frankfurt.html"
"Stuttgart https://www.germany.travel/en/towns-cities-culture/towns-cities/stuttgart.html 
"Düsseldorf https://www.germany.travel/en/towns-cities-culture/towns-cities/magic-cities/duesseldorf.html"
"Bremen https://www.germany.travel/en/towns-cities-culture/towns-cities/magic-cities/bremen.html"
"Dortmund https://www.lonelyplanet.com/germany/north-rhine-westphalia/dortmund 
"Essen https://www.lonelyplanet.com/germany/north-rhine-westphalia/essen"
"London https://www.visitbritain.com/gb/en/england/london"
"Birmingham https://www.visitbritain.com/gb/en/england/central-england/birmingham"
"Liverpool https://www.visitbritain.com/gb/en/england/northern-england/liverpool"
"Nottingham https://www.visitbritain.com/gb/en/england/central-england/nottingham"
"Bristol https://www.visitbritain.com/gb/en/england/south-west/bristol"
"Glasgow https://www.visitbritain.com/gb/en/scotland/glasgow"
"Leicester https://www.visitbritain.com/gb/en/england/central-england/leicester"
"Edinburgh https://www.visitbritain.com/gb/en/scotland/edinburgh"
"Leeds https://www.visitbritain.com/gb/en/england/northern-england/leeds"
"Sheffield http://www.welcometosheffield.co.uk/visit"
"Tokyo https://www.japan.travel/en/destinations/kanto/tokyo/"
"Kyoto https://www.japan.travel/en/destinations/kansai/kyoto/
"Yokohama https://www.japan-guide.com/e/e2156.html"
"Osaka https://www.japan-guide.com/e/e2157.html"
"Nagoya https://www.japan-guide.com/e/e2155.html"
"Sapporo https://www.japan-guide.com/e/e2163.html"
"Kobe https://www.japan-guide.com/e/e2159.html"
"Fukuoka https://www.japan-guide.com/e/e2161.html"
"Kawasaki https://www.japan-guide.com/e/e3250.html"
"Saitama https://www.japan-guide.com/e/e6525.html"
"Vienna https://www.lonelyplanet.com/austria/vienna"
"Graz https://www.lonelyplanet.com/austria/the-south/graz"
"Linz https://www.lonelyplanet.com/austria/the-danube-valley/linz"
"Salzburg https://www.lonelyplanet.com/austria/salzburg"
"Innsbruck https://www.lonelyplanet.com/austria/tirol/innsbruck"
"Klagenfurt https://www.lonelyplanet.com/austria/the-south/klagenfurt"
"Villac https://www.lonelyplanet.com/austria/tirol/villach"
"Dornbirn https://www.lonelyplanet.com/austria/dornbirn"
"Wiener https://www.lonelyplanet.com/austria/wiener-neustadt"
"Steyr https://www.lonelyplanet.com/austria/steyr"
"Athens https://www.lonelyplanet.com/greece/athens"
"Thessaloniki https://www.lonelyplanet.com/greece/northern-greece/thessaloniki"
"Larissa https://www.lonelyplanet.com/greece/larisa"
"Piraeus https://www.lonelyplanet.com/greece/athens/piraeus"
"Acharnes https://www.hellotravel.com/greece/acharnes"
"Kallith http://visitkassandra.com/halkidiki/kallithea/"
"Heraklion http://www.visitgreece.gr/en/main_cities/heraklion"
"Peristeri https://www.triphobo.com/places/peristeri-attica-greece/things-to-do"
"Kalamaria https://www.triphobo.com/places/kalamaria-greece/things-to-do"
"Kuala Lumpur http://www.kuala-lumpur.ws"
"Johor Bahru http://www.malaysia-hotels.net/culturalcities/johor-bahru.htm"
"Kota Bharu https://www.lonelyplanet.com/malaysia/peninsular-malaysia-east-coast/kota-bharu"
"Klang https://www.lonelyplanet.com/malaysia/klang-pelabuhan-klang"
"Kampung Baru Suba https://www.lonelyplanet.com/malaysia/kampung-benuk"
"Ipoh hops https://www.lonelyplanet.com/malaysia/peninsular-malaysia-west-coast/ipoh"
"Kuching https://www.lonelyplanet.com/malaysia/malaysian-borneo-sarawak/kuching"
"Petaling https://www.lonelyplanet.com/malaysia/petaling-jaya-shah-alam"
"Shah Alam hah Alam https://www.triphobo.com/places/shah-alam-malaysia/things-to-do"
"Kota Kinabalu https://www.lonelyplanet.com/malaysia/malaysian-borneo-sabah/kota-kinabalu"
"Moscow https://www.lonelyplanet.com/russia/moscow"
"St Petersburg https://www.lonelyplanet.com/russia/moscow"
"Kazan https://www.lonelyplanet.com/russia/volga-region/kazan"
"Novosibirsk https://www.lonelyplanet.com/russia/siberia/novosibirsk"
"Ekaterinburg https://www.lonelyplanet.com/russia/the-urals/yekaterinburg"
"Nizhny Novgorod https://www.lonelyplanet.com/russia/volga-region/nizhny-novgorod"
"Samara https://www.lonelyplanet.com/russia/volga-region/samara"
"Omsk https://www.lonelyplanet.com/russia/siberia/omsk"
"Chelyabinsk https://www.lonelyplanet.com/russia/the-urals/chelyabinsk"
"Rostov-on-Don https://www.lonelyplanet.com/russia/russian-caucasus/rostov-on-don"
"Lisbon https://www.lonelyplanet.com/portugal/lisbon"
"Porto https://www.lonelyplanet.com/portugal/the-north/porto"
"Amadora https://www.visitlisboa.com/pt-pt/regions/arredores-de-lisboa/amadora"
"Braga https://www.lonelyplanet.com/portugal/the-north/braga"
"Setúbal https://www.lonelyplanet.com/portugal/lisbon/setubal"
"Coimbra https://www.lonelyplanet.com/portugal/central-portugal/coimbra"
"Queluz https://www.portugalrotasetours.com/pt/tour/tour-queluz-sintra"
"Funchal https://www.lonelyplanet.com/portugal/funchal"
"Cacem https://www.visitportugal.com/en/NR/exeres/2E42BEB7-3958-463F-9601-89A6C3A1B4F2"
"Vila Nova de Gaia https://www.lonelyplanet.com/portugal/porto/vila-nova-de-gaia"
"Scarborough https://www.seetorontonow.com/explore-toronto/neighbourhoods/scarborough/"
"Toronto https://www.lonelyplanet.com/canada/toronto
"Montreal https://www.lonelyplanet.com/canada/montreal"
"Calgary https://www.lonelyplanet.com/canada/alberta/calgary"
"Montreal https://www.lonelyplanet.com/canada/montreal"
"Ottawa https://www.lonelyplanet.com/canada/ontario/ottawa"
"Edmonton https://www.lonelyplanet.com/canada/alberta/edmonton"
"Mississauga https://www.thecrazytourist.com/15-best-things-mississauga-ontario-canada/"
"North York https://www.rome2rio.com/s/Downtown-Toronto/North-York"
"Winnipeg https://www.lonelyplanet.com/canada/manitoba/winnipeg"
"Vancouver https://www.lonelyplanet.com/canada/vancouver"
"Warsaw https://www.poland.travel/en/cities/warsaw"
"Łódź https://www.poland.travel/en/cities/lodz"
"Krakow https://www.poland.travel/en/cities/krakow"
"Wrocław https://www.poland.travel/en/cities/wroclaw"
"Poznan https://www.poland.travel/en/cities/poznan"
"Gdańsk https://www.poland.travel/en/cities/gdansk-and-tricity"
"Szczecin https://www.lonelyplanet.com/poland/pomerania/szczecin"
"Bydgoszcz https://www.poland.travel/en/cities/bydgoszcz"
"Lublin https://www.poland.travel/en/cities/lublin"
"Katowice https://www.poland.travel/en/cities/katowice"
"Amsterdam https://www.lonelyplanet.com/the-netherlands/amsterdam"
"Rotterdam https://www.lonelyplanet.com/the-netherlands/rotterdam"
"The Hague https://www.iamsterdam.com/en/plan-your-trip/day-trips/netherlands/the-hague"
"Utrecht https://www.lonelyplanet.com/the-netherlands/the-randstad/utrecht-city"
"Eindhoven https://www.lonelyplanet.com/the-netherlands/eindhoven"
"Tilburg https://www.lonelyplanet.com/the-netherlands/tilburg"
"Groningen https://www.lonelyplanet.com/the-netherlands/the-north-and-east/groningen-city"
"Almere https://www.triphobo.com/places/almere-the-netherlands"
"Breda https://www.lonelyplanet.com/the-netherlands/breda"
"Nijmegen https://www.lonelyplanet.com/the-netherlands/nijmegen"
   
