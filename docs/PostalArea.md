# PostalArea


## GET /postalarea/{parameterAreaType}/{parameterAreaName}
### Response 200 (application/json)
Content: [PostalAreaResponse](PostalAreaResponse.md)

#### Example 1
```
/PostalArea/Local Authority/RICHMOND UPON THAMES
```
```json
{
  "area_type": "Local Authority",
  "area_name": "RICHMOND UPON THAMES",
  "customer_reference": null,
  "add_to_cart": null,
  "ppsm_chart": null,
  "category_d": null,
  "category_s": null,
  "category_t": null,
  "category_f": null,
  "category_o": null,
  "refres_parameters": null,
  "streets": [
    {
      "usrn": "22401230",
      "street": "ABBOTT CLS"
    },
    {
      "usrn": "22403231",
      "street": "ABBOTTSMEDE CLS"
    },
    {
      "usrn": "22407036",
      "street": "ABERCORN MEWS"
    },
    {
      "usrn": "22401231",
      "street": "ACACIA RD"
    },
    {
      "usrn": "13703731",
      "street": "ACCESS RD TO RIVER THAMES FROM SADLERS RIDE"
    },
    {
      "usrn": "22406363",
      "street": "ACORN CLS"
    },
    {
      "usrn": "22403233",
      "street": "ADDISON RD"
    },
    {
      "usrn": "22403234",
      "street": "ADELAIDE RD"
    },
    {
      "usrn": "22405295",
      "street": "ADELAIDE RD"
    },
    {
      "usrn": "22406822",
      "street": "ADMIRALTY RD"
    },
    {
      "usrn": "22407067",
      "street": "ADMIRALTY WAY"
    },
    {
      "usrn": "22403236",
      "street": "AILSA AV"
    },
    {
      "usrn": "22403237",
      "street": "AILSA RD"
    },
    {
      "usrn": "22401931",
      "street": "AIR SEA MEWS"
    },
    {
      "usrn": "21102867",
      "street": "ALBANY CLS"
    },
    {
      "usrn": "22405298",
      "street": "ALBANY CLS"
    },
    {
      "usrn": "22406168",
      "street": "ALBANY PASSAGE"
    },
    {
      "usrn": "22403240",
      "street": "ALBANY RD"
    },
    {
      "usrn": "22401232",
      "street": "ALBEMARLE AV"
    },
    {
      "usrn": "22401233",
      "street": "ALBERT RD"
    },
    {
      "usrn": "22403241",
      "street": "ALBERT RD"
    },
    {
      "usrn": "22403242",
      "street": "ALBERT RD"
    },
    {
      "usrn": "22403243",
      "street": "ALBERT RD"
    },
    {
      "usrn": "22403244",
      "street": "ALBION RD"
    },
    {
      "usrn": "22401234",
      "street": "ALBURY CLS"
    },
    {
      "usrn": "22404009",
      "street": "ALDER RD"
    },
    {
      "usrn": "22404010",
      "street": "ALDERBURY RD"
    },
    {
      "usrn": "22403246",
      "street": "ALEXANDER CLS"
    },
    {
      "usrn": "22403247",
      "street": "ALEXANDRA RD"
    },
    {
      "usrn": "22404013",
      "street": "ALEXANDRA RD"
    },
    {
      "usrn": "22405304",
      "street": "ALEXANDRA RD"
    },
    {
      "usrn": "22403249",
      "street": "ALICE MEWS"
    },
    {
      "usrn": "22403250",
      "street": "ALLBROOK CLS"
    },
    {
      "usrn": "22401236",
      "street": "ALPHA RD"
    },
    {
      "usrn": "22401237",
      "street": "ALTON GARDENS"
    },
    {
      "usrn": "22405311",
      "street": "ALTON RD"
    },
    {
      "usrn": "22401520",
      "street": "AMELIA CLS"
    },
    {
      "usrn": "22406169",
      "street": "AMYAND LANE"
    },
    {
      "usrn": "22403252",
      "street": "AMYAND PRK GARDENS"
    },
    {
      "usrn": "22403253",
      "street": "AMYAND PRK RD"
    },
    {
      "usrn": "22401241",
      "street": "ANDOVER RD"
    },
    {
      "usrn": "22407148",
      "street": "ANGEL CLS"
    },
    {
      "usrn": "22406128",
      "street": "ANGLERS CLS"
    },
    {
      "usrn": "22403255",
      "street": "ANLABY RD"
    },
    {
      "usrn": "22403711",
      "street": "APPLE GROVE"
    },
    {
      "usrn": "22401243",
      "street": "APPLEBY CLS"
    },
    {
      "usrn": "22406365",
      "street": "ARCHER MEWS"
    },
    {
      "usrn": "22404030",
      "street": "ARCHWAY ST"
    },
    {
      "usrn": "22407174",
      "street": "ARDEN CLS"
    },
    {
      "usrn": "22406584",
      "street": "ARGYLE AV"
    },
    {
      "usrn": "22403259",
      "street": "ARLINGTON CLS"
    },
    {
      "usrn": "22403260",
      "street": "ARLINGTON RD"
    },
    {
      "usrn": "22403261",
      "street": "ARLINGTON RD"
    },
    {
      "usrn": "22403262",
      "street": "ARLINGTON RD"
    },
    {
      "usrn": "22406926",
      "street": "AROSA RD"
    },
    {
      "usrn": "22403264",
      "street": "ARRAGON RD"
    },
    {
      "usrn": "22406270",
      "street": "ARTICHOKE WALK"
    },
    {
      "usrn": "22401250",
      "street": "ARUNDEL CLS"
    },
    {
      "usrn": "22404035",
      "street": "ARUNDEL TERR"
    },
    {
      "usrn": "22407002",
      "street": "ASH ISLAND"
    },
    {
      "usrn": "22403266",
      "street": "ASHBURNHAM RD"
    },
    {
      "usrn": "22401251",
      "street": "ASHDALE CLS"
    },
    {
      "usrn": "22401252",
      "street": "ASHDALE WAY"
    },
    {
      "usrn": "22403267",
      "street": "ASHFIELD CLS"
    },
    {
      "usrn": "22404041",
      "street": "ASHLEIGH RD"
    },
    {
      "usrn": "22401254",
      "street": "ASHLEY DRIVE"
    },
    {
      "usrn": "22403268",
      "street": "ASHLEY GARDENS"
    },
    {
      "usrn": "22400719",
      "street": "ASHLEY RD"
    },
    {
      "usrn": "22405319",
      "street": "ASHLEY RD"
    },
    {
      "usrn": "22407187",
      "street": "ASPEN CLS"
    },
    {
      "usrn": "22403270",
      "street": "ATBARA RD"
    },
    {
      "usrn": "22403533",
      "street": "ATHELSTAN PLACE"
    },
    {
      "usrn": "22401257",
      "street": "ATHERLEY WAY"
    },
    {
      "usrn": "22404050",
      "street": "ATHERTON RD"
    },
    {
      "usrn": "22405321",
      "street": "ATWOOD AV"
    },
    {
      "usrn": "22403271",
      "street": "AUDLEY RD"
    },
    {
      "usrn": "22401258",
      "street": "AUGUSTA RD"
    },
    {
      "usrn": "22406136",
      "street": "AUSTIN CLS"
    },
    {
      "usrn": "22403272",
      "street": "AV GARDENS"
    },
    {
      "usrn": "22404056",
      "street": "AV GARDENS"
    },
    {
      "usrn": "22400722",
      "street": "AV RD"
    },
    {
      "usrn": "22403273",
      "street": "AV RD"
    },
    {
      "usrn": "22404059",
      "street": "AVONDALE RD"
    },
    {
      "usrn": "22406175",
      "street": "AYNSCOMBE PATH"
    },
    {
      "usrn": "22403274",
      "street": "BACK LANE"
    },
    {
      "usrn": "22406647",
      "street": "BACK RD PT OF NATIONAL PHYSICS LABORATORY"
    },
    {
      "usrn": "21880139",
      "street": "BAINBRIDGE CLS"
    },
    {
      "usrn": "22407166",
      "street": "BAKEHOUSE MEWS"
    },
    {
      "usrn": "22405332",
      "street": "BARDOLPH RD"
    },
    {
      "usrn": "22406548",
      "street": "BARGE WALK"
    },
    {
      "usrn": "22407116",
      "street": "BARKER CLS"
    },
    {
      "usrn": "22401262",
      "street": "BARLOW RD"
    },
    {
      "usrn": "22407079",
      "street": "BARNEBY CLS"
    },
    {
      "usrn": "22404072",
      "street": "BARNES AV"
    },
    {
      "usrn": "22404073",
      "street": "BARNES HIGH ST"
    },
    {
      "usrn": "21800109",
      "street": "BARNFIELD AV"
    },
    {
      "usrn": "22403281",
      "street": "BARONSFIELD RD"
    },
    {
      "usrn": "22404075",
      "street": "BARONSMEAD RD"
    },
    {
      "usrn": "21880494",
      "street": "BARRONS CHASE"
    },
    {
      "usrn": "22403614",
      "street": "BARRONS CHASE"
    },
    {
      "usrn": "22407018",
      "street": "BAYGROVE MEWS"
    },
    {
      "usrn": "22406766",
      "street": "BAYLEAF CLS"
    },
    {
      "usrn": "22407080",
      "street": "BAYLIS MEWS"
    },
    {
      "usrn": "22403282",
      "street": "BEACONSFIELD RD"
    },
    {
      "usrn": "22403283",
      "street": "BEARD RD"
    },
    {
      "usrn": "22400728",
      "street": "BEARDS HILL"
    },
    {
      "usrn": "22400729",
      "street": "BEARDS HILL CLS"
    },
    {
      "usrn": "22403285",
      "street": "BEATRICE RD"
    },
    {
      "usrn": "22403286",
      "street": "BEAUCHAMP RD"
    },
    {
      "usrn": "22403287",
      "street": "BEAUFORT RD"
    },
    {
      "usrn": "22403288",
      "street": "BEAUFORT RD"
    },
    {
      "usrn": "22403289",
      "street": "BEAULIEU CLS"
    },
    {
      "usrn": "22405335",
      "street": "BEAUMONT AV"
    },
    {
      "usrn": "22400732",
      "street": "BEAVER CLS"
    },
    {
      "usrn": "22400045",
      "street": "BECKETTS PLACE"
    },
    {
      "usrn": "22401272",
      "street": "BEDFORD RD"
    },
    {
      "usrn": "22401273",
      "street": "BEECH WAY"
    },
    {
      "usrn": "22404102",
      "street": "BEECHCROFT RD"
    },
    {
      "usrn": "21800127",
      "street": "BEECHROW"
    },
    {
      "usrn": "22405339",
      "street": "BEECHWOOD AV"
    },
    {
      "usrn": "22401276",
      "street": "BEGONIA PLACE"
    },
    {
      "usrn": "22400737",
      "street": "BELGRADE RD"
    },
    {
      "usrn": "22404104",
      "street": "BELGRAVE RD"
    },
    {
      "usrn": "22403292",
      "street": "BELL LANE"
    },
    {
      "usrn": "22404106",
      "street": "BELLEVUE RD"
    },
    {
      "usrn": "22401277",
      "street": "BELMONT RD"
    },
    {
      "usrn": "22404108",
      "street": "BELOE CLS"
    },
    {
      "usrn": "22403293",
      "street": "BELVEDERE CLS"
    },
    {
      "usrn": "22400051",
      "street": "BENNET CLS"
    },
    {
      "usrn": "22406762",
      "street": "BENNS WALK"
    },
    {
      "usrn": "22403294",
      "street": "BERESFORD AV"
    },
    {
      "usrn": "22404115",
      "street": "BERKELEY RD"
    },
    {
      "usrn": "8400762",
      "street": "BERKELEY ST"
    },
    {
      "usrn": "22407097",
      "street": "BERWICK CLS"
    },
    {
      "usrn": "22403296",
      "street": "BERWYN RD"
    },
    {
      "usrn": "22407098",
      "street": "BESSANT DRIVE"
    },
    {
      "usrn": "22404120",
      "street": "BEVERLEY CLS"
    },
    {
      "usrn": "22404121",
      "street": "BEVERLEY GARDENS"
    },
    {
      "usrn": "22406185",
      "street": "BEVERLEY PATH"
    },
    {
      "usrn": "22400057",
      "street": "BEVERLEY RD"
    },
    {
      "usrn": "22404122",
      "street": "BEVERLEY RD"
    },
    {
      "usrn": "22404124",
      "street": "BEXHILL RD"
    },
    {
      "usrn": "22405345",
      "street": "BICESTER RD"
    },
    {
      "usrn": "22403298",
      "street": "BIRCH CLS"
    },
    {
      "usrn": "22401286",
      "street": "BIRCHWOOD GROVE"
    },
    {
      "usrn": "22401287",
      "street": "BIRD WALK"
    },
    {
      "usrn": "22403299",
      "street": "BIRDWOOD CLS"
    },
    {
      "usrn": "22406694",
      "street": "BISHOPS CLS"
    },
    {
      "usrn": "22406506",
      "street": "BISHOPS GROVE"
    },
    {
      "usrn": "22403300",
      "street": "BLACKMORES GROVE"
    },
    {
      "usrn": "22403301",
      "street": "BLAGDON WALK"
    },
    {
      "usrn": "22400516",
      "street": "BLAGROVE RD"
    },
    {
      "usrn": "22407117",
      "street": "BLAKE MEWS"
    },
    {
      "usrn": "22407131",
      "street": "BLAKEMORE GARDENS"
    },
    {
      "usrn": "22401290",
      "street": "BLANDFORD AV"
    },
    {
      "usrn": "22403302",
      "street": "BLANDFORD RD"
    },
    {
      "usrn": "21700816",
      "street": "BLENHEIM CRESCENT"
    },
    {
      "usrn": "22407068",
      "street": "BLENHEIM PLACE"
    },
    {
      "usrn": "22401292",
      "street": "BLOXHAM CRESCENT"
    },
    {
      "usrn": "22406187",
      "street": "BLUE ANCHOR ALLEY"
    },
    {
      "usrn": "22401293",
      "street": "BLUEFIELD CLS"
    },
    {
      "usrn": "22406695",
      "street": "BLYTH CLS"
    },
    {
      "usrn": "22407012",
      "street": "BODICEA MEWS"
    },
    {
      "usrn": "22404143",
      "street": "BOILEAU RD"
    },
    {
      "usrn": "22403306",
      "street": "BOLTON GARDENS"
    },
    {
      "usrn": "22403307",
      "street": "BONSER RD"
    },
    {
      "usrn": "22403308",
      "street": "BORLAND RD"
    },
    {
      "usrn": "22403310",
      "street": "BOUCHER CLS"
    },
    {
      "usrn": "22406144",
      "street": "BRACKEN CLS"
    },
    {
      "usrn": "22404155",
      "street": "BRACKEN GARDENS"
    },
    {
      "usrn": "22405362",
      "street": "BRADDON RD"
    },
    {
      "usrn": "22403640",
      "street": "BRADSHAW CLS"
    },
    {
      "usrn": "22406648",
      "street": "BRAGG RD PT OF NATIONAL PHYSICS LABORATORY"
    },
    {
      "usrn": "22401299",
      "street": "BRAMBLE LANE"
    },
    {
      "usrn": "22401300",
      "street": "BRAMLEY CLS"
    },
    {
      "usrn": "22407069",
      "street": "BRANKSOME CLS"
    },
    {
      "usrn": "22405366",
      "street": "BRANSTONE RD"
    },
    {
      "usrn": "22406919",
      "street": "BRASENOSE DRIVE"
    },
    {
      "usrn": "22403313",
      "street": "BREAMWATER GARDENS"
    },
    {
      "usrn": "22407039",
      "street": "BREWERS LANE"
    },
    {
      "usrn": "22407081",
      "street": "BREWERY LANE"
    },
    {
      "usrn": "22401302",
      "street": "BRIAR CLS"
    },
    {
      "usrn": "22403315",
      "street": "BRIAR RD"
    },
    {
      "usrn": "22405375",
      "street": "BRICK FARM CLS"
    },
    {
      "usrn": "22406369",
      "street": "BRIDGE CLS"
    },
    {
      "usrn": "22403316",
      "street": "BRIDGE RD"
    },
    {
      "usrn": "22403317",
      "street": "BRIDGE ST"
    },
    {
      "usrn": "22401303",
      "street": "BRIDGE WAY"
    },
    {
      "usrn": "22403318",
      "street": "BRIDGEMAN RD"
    },
    {
      "usrn": "22406799",
      "street": "BRIDLE LANE"
    },
    {
      "usrn": "22401304",
      "street": "BRINSWORTH CLS"
    },
    {
      "usrn": "22407183",
      "street": "BRISCOE MEWS"
    },
    {
      "usrn": "22407143",
      "street": "BRISTOL CLS"
    },
    {
      "usrn": "22406146",
      "street": "BRITANNIA LANE"
    },
    {
      "usrn": "22401305",
      "street": "BROAD LANE"
    },
    {
      "usrn": "22403319",
      "street": "BROAD ST"
    },
    {
      "usrn": "22406115",
      "street": "BROADHURST CLS"
    },
    {
      "usrn": "22401306",
      "street": "BROADLANDS"
    },
    {
      "usrn": "22401307",
      "street": "BROADMEAD CLS"
    },
    {
      "usrn": "20600261",
      "street": "BROADWAY"
    },
    {
      "usrn": "22403320",
      "street": "BROADWAY AV"
    },
    {
      "usrn": "22404178",
      "street": "BROOK GARDENS"
    },
    {
      "usrn": "22403321",
      "street": "BROOK RD"
    },
    {
      "usrn": "22405256",
      "street": "BROOKFIELD MEWS"
    },
    {
      "usrn": "22407132",
      "street": "BROOKLANDS PLACE"
    },
    {
      "usrn": "22404182",
      "street": "BROOKWOOD AV"
    },
    {
      "usrn": "22403322",
      "street": "BROOM CLS"
    },
    {
      "usrn": "22403323",
      "street": "BROOM LOCK"
    },
    {
      "usrn": "22403324",
      "street": "BROOM PRK"
    },
    {
      "usrn": "22403325",
      "street": "BROOM RD"
    },
    {
      "usrn": "22403326",
      "street": "BROOM WATER"
    },
    {
      "usrn": "22403327",
      "street": "BROOM WATER WEST"
    },
    {
      "usrn": "22401310",
      "street": "BROOME RD"
    },
    {
      "usrn": "22403328",
      "street": "BROOMFIELD RD"
    },
    {
      "usrn": "22405387",
      "street": "BROOMFIELD RD"
    },
    {
      "usrn": "22405487",
      "street": "BROTHERSTONE WALK"
    },
    {
      "usrn": "21800004",
      "street": "BROUGH CLS"
    },
    {
      "usrn": "22403329",
      "street": "BROUGHTON AV"
    },
    {
      "usrn": "22401313",
      "street": "BROWNING CLS"
    },
    {
      "usrn": "22401314",
      "street": "BRUNEL WALK"
    },
    {
      "usrn": "22401315",
      "street": "BRUNSWICK CLS"
    },
    {
      "usrn": "22401317",
      "street": "BRYANSTON AV"
    },
    {
      "usrn": "22401320",
      "street": "BUCKINGHAM CLS"
    },
    {
      "usrn": "8400913",
      "street": "BUCKINGHAM GATE"
    },
    {
      "usrn": "22401321",
      "street": "BUCKINGHAM RD"
    },
    {
      "usrn": "22403330",
      "street": "BUCKINGHAM RD"
    },
    {
      "usrn": "22403331",
      "street": "BUCKLANDS RD"
    },
    {
      "usrn": "22406190",
      "street": "BUDDS ALLEY"
    },
    {
      "usrn": "22401738",
      "street": "BURCHAM CLS"
    },
    {
      "usrn": "22405389",
      "street": "BURDENSHOTT AV"
    },
    {
      "usrn": "22405390",
      "street": "BURDETT RD"
    },
    {
      "usrn": "22406742",
      "street": "BURGES GROVE"
    },
    {
      "usrn": "22405392",
      "street": "BURLINGTON AV"
    },
    {
      "usrn": "22403333",
      "street": "BURNELL AV"
    },
    {
      "usrn": "22403334",
      "street": "BURNSIDE CLS"
    },
    {
      "usrn": "22401324",
      "street": "BURTONS RD"
    },
    {
      "usrn": "22405398",
      "street": "BUSH RD"
    },
    {
      "usrn": "22405399",
      "street": "BUSHWOOD RD"
    },
    {
      "usrn": "22407005",
      "street": "BUSHY PRK"
    },
    {
      "usrn": "22407070",
      "street": "BUSHY PRK"
    },
    {
      "usrn": "22401325",
      "street": "BUSHY PRK GARDENS"
    },
    {
      "usrn": "22407130",
      "street": "BUSHY PRK MEWS"
    },
    {
      "usrn": "22403336",
      "street": "BUSHY PRK RD"
    },
    {
      "usrn": "22403339",
      "street": "BUTE AV"
    },
    {
      "usrn": "22407059",
      "street": "BUTE GARDENS"
    },
    {
      "usrn": "22407159",
      "street": "BUTLER FARM CLS"
    },
    {
      "usrn": "22403340",
      "street": "BUTTERFIELD CLS"
    },
    {
      "usrn": "22401326",
      "street": "BUTTS CRESCENT"
    },
    {
      "usrn": "22404200",
      "street": "BUXTON RD"
    },
    {
      "usrn": "22406370",
      "street": "BYATT WALK"
    },
    {
      "usrn": "22403341",
      "street": "BYCHURCH END"
    },
    {
      "usrn": "22401327",
      "street": "BYE WAYS"
    },
    {
      "usrn": "22404201",
      "street": "BYFELD GARDENS"
    },
    {
      "usrn": "22401328",
      "street": "BYRON CLS"
    },
    {
      "usrn": "22403342",
      "street": "CADOGAN CLS"
    },
    {
      "usrn": "22406130",
      "street": "CAIRNGORM CLS"
    },
    {
      "usrn": "22401544",
      "street": "CALLINGTON MEWS"
    },
    {
      "usrn": "22401330",
      "street": "CAMAC RD"
    },
    {
      "usrn": "22403345",
      "street": "CAMBRIAN RD"
    },
    {
      "usrn": "22406122",
      "street": "CAMBRIDGE COTTAGES"
    },
    {
      "usrn": "22403346",
      "street": "CAMBRIDGE CRESCENT"
    },
    {
      "usrn": "22403395",
      "street": "CAMBRIDGE GARDENS"
    },
    {
      "usrn": "22403347",
      "street": "CAMBRIDGE PRK"
    },
    {
      "usrn": "22406191",
      "street": "CAMBRIDGE PRK FOOTPATH"
    },
    {
      "usrn": "20302070",
      "street": "CAMBRIDGE RD"
    },
    {
      "usrn": "22401333",
      "street": "CAMBRIDGE RD"
    },
    {
      "usrn": "22403348",
      "street": "CAMBRIDGE RD"
    },
    {
      "usrn": "22403349",
      "street": "CAMBRIDGE RD"
    },
    {
      "usrn": "22404204",
      "street": "CAMBRIDGE RD"
    },
    {
      "usrn": "22405403",
      "street": "CAMBRIDGE RD"
    },
    {
      "usrn": "22401335",
      "street": "CAMELLIA PLACE"
    },
    {
      "usrn": "22401336",
      "street": "CAMPBELL CLS"
    },
    {
      "usrn": "22401337",
      "street": "CAMPBELL RD"
    },
    {
      "usrn": "22406374",
      "street": "CAMPBELL RD"
    },
    {
      "usrn": "22407173",
      "street": "CANBERRA PLACE"
    },
    {
      "usrn": "22406927",
      "street": "CANDLER MEWS"
    },
    {
      "usrn": "22406737",
      "street": "CANFORD PLACE"
    },
    {
      "usrn": "22407190",
      "street": "CANHAM GARDENS"
    },
    {
      "usrn": "22401339",
      "street": "CANNON CLS"
    },
    {
      "usrn": "22403351",
      "street": "CARDIGAN RD"
    },
    {
      "usrn": "22404208",
      "street": "CARDIGAN RD"
    },
    {
      "usrn": "22401342",
      "street": "CARDINALS WALK"
    },
    {
      "usrn": "22407134",
      "street": "CARISBROOKE CLS"
    },
    {
      "usrn": "22407188",
      "street": "CARLILE PLACE"
    },
    {
      "usrn": "22401343",
      "street": "CARLISLE RD"
    },
    {
      "usrn": "22404211",
      "street": "CARLTON RD"
    },
    {
      "usrn": "22407151",
      "street": "CARMEL WAY"
    },
    {
      "usrn": "22405415",
      "street": "CARRINGTON RD"
    },
    {
      "usrn": "22406740",
      "street": "CARTWRIGHT WAY"
    },
    {
      "usrn": "22403353",
      "street": "CASSILIS RD"
    },
    {
      "usrn": "22404217",
      "street": "CASTELNAU"
    },
    {
      "usrn": "22406375",
      "street": "CASTELNAU GARDENS"
    },
    {
      "usrn": "22406193",
      "street": "CASTELNAU PLACE"
    },
    {
      "usrn": "22406195",
      "street": "CASTELNAU ROW"
    },
    {
      "usrn": "22403354",
      "street": "CASTLE YARD"
    },
    {
      "usrn": "22405418",
      "street": "CASTLEGATE"
    },
    {
      "usrn": "22406763",
      "street": "CATHERINE DRIVE"
    },
    {
      "usrn": "22403355",
      "street": "CAVE RD"
    },
    {
      "usrn": "8400925",
      "street": "CAVENDISH SQUARE"
    },
    {
      "usrn": "22401348",
      "street": "CEDAR AV"
    },
    {
      "usrn": "22101284",
      "street": "CEDAR CT"
    },
    {
      "usrn": "22403356",
      "street": "CEDAR HEIGHTS"
    },
    {
      "usrn": "22403357",
      "street": "CEDAR RD"
    },
    {
      "usrn": "22405422",
      "street": "CEDAR TERR"
    },
    {
      "usrn": "22400107",
      "street": "CEDARS RD"
    },
    {
      "usrn": "22404222",
      "street": "CEDARS RD"
    },
    {
      "usrn": "22403358",
      "street": "CHADWICK CLS"
    },
    {
      "usrn": "22407140",
      "street": "CHALMERS WAY"
    },
    {
      "usrn": "22400782",
      "street": "CHANDLER CLS"
    },
    {
      "usrn": "22403359",
      "street": "CHAPEL RD"
    },
    {
      "usrn": "22401352",
      "street": "CHAPTER WAY"
    },
    {
      "usrn": "22404234",
      "street": "CHARLES ST"
    },
    {
      "usrn": "22406922",
      "street": "CHARLESWORTH PLACE"
    },
    {
      "usrn": "22407124",
      "street": "CHARLEVILLE MEWS"
    },
    {
      "usrn": "22404236",
      "street": "CHARLOTTE RD"
    },
    {
      "usrn": "22406690",
      "street": "CHARLOTTE SQUARE"
    },
    {
      "usrn": "21604497",
      "street": "CHARTERHOUSE MEWS"
    },
    {
      "usrn": "22401354",
      "street": "CHASE GARDENS"
    },
    {
      "usrn": "22403360",
      "street": "CHATSWORTH PLACE"
    },
    {
      "usrn": "22405428",
      "street": "CHAUCER AV"
    },
    {
      "usrn": "22401355",
      "street": "CHEESEMAN CLS"
    },
    {
      "usrn": "22401356",
      "street": "CHELSEA CLS"
    },
    {
      "usrn": "22403361",
      "street": "CHELTENHAM AV"
    },
    {
      "usrn": "22405430",
      "street": "CHELWOOD GARDENS"
    },
    {
      "usrn": "22406764",
      "street": "CHERTSEY CT"
    },
    {
      "usrn": "22406590",
      "street": "CHERTSEY RD"
    },
    {
      "usrn": "22401360",
      "street": "CHESTER AV"
    },
    {
      "usrn": "22403368",
      "street": "CHESTER AV"
    },
    {
      "usrn": "22406376",
      "street": "CHESTER CLS"
    },
    {
      "usrn": "8400031",
      "street": "CHESTER CLS"
    },
    {
      "usrn": "8400032",
      "street": "CHESTER MEWS"
    },
    {
      "usrn": "22401361",
      "street": "CHESTNUT AV"
    },
    {
      "usrn": "22404250",
      "street": "CHESTNUT AV"
    },
    {
      "usrn": "22407158",
      "street": "CHESTNUT AV"
    },
    {
      "usrn": "22404409",
      "street": "CHESTNUT MEWS"
    },
    {
      "usrn": "21800240",
      "street": "CHESTNUT RD"
    },
    {
      "usrn": "22403370",
      "street": "CHESTNUT RD"
    },
    {
      "usrn": "22401363",
      "street": "CHEYNE AV"
    },
    {
      "usrn": "22401364",
      "street": "CHICHESTER CLS"
    },
    {
      "usrn": "22403372",
      "street": "CHILLINGWORTH GARDENS"
    },
    {
      "usrn": "22405440",
      "street": "CHILTON RD"
    },
    {
      "usrn": "22407082",
      "street": "CHILVERS CLS"
    },
    {
      "usrn": "22403373",
      "street": "CHISHOLM RD"
    },
    {
      "usrn": "22403374",
      "street": "CHISLEHURST RD"
    },
    {
      "usrn": "21500254",
      "street": "CHISWICK VILLAGE"
    },
    {
      "usrn": "22406161",
      "street": "CHOLMONDELEY WALK"
    },
    {
      "usrn": "22403375",
      "street": "CHRISTCHURCH AV"
    },
    {
      "usrn": "21900335",
      "street": "CHRISTCHURCH RD"
    },
    {
      "usrn": "22101404",
      "street": "CHRISTCHURCH RD"
    },
    {
      "usrn": "22402731",
      "street": "CHRISTCHURCH RD"
    },
    {
      "usrn": "22403377",
      "street": "CHUDLEIGH RD"
    },
    {
      "usrn": "22404261",
      "street": "CHURCH AV"
    },
    {
      "usrn": "22406598",
      "street": "CHURCH CT"
    },
    {
      "usrn": "22400125",
      "street": "CHURCH GROVE"
    },
    {
      "usrn": "22403379",
      "street": "CHURCH LANE"
    },
    {
      "usrn": "22403380",
      "street": "CHURCH LANE"
    },
    {
      "usrn": "22406206",
      "street": "CHURCH PATH"
    },
    {
      "usrn": "20200825",
      "street": "CHURCH RD"
    },
    {
      "usrn": "20500027",
      "street": "CHURCH RD"
    },
    {
      "usrn": "21106105",
      "street": "CHURCH RD"
    },
    {
      "usrn": "22200141",
      "street": "CHURCH RD"
    },
    {
      "usrn": "22403381",
      "street": "CHURCH RD"
    },
    {
      "usrn": "22403382",
      "street": "CHURCH RD"
    },
    {
      "usrn": "22404264",
      "street": "CHURCH RD"
    },
    {
      "usrn": "22405449",
      "street": "CHURCH RD"
    },
    {
      "usrn": "22400792",
      "street": "CHURCH ST"
    },
    {
      "usrn": "22403384",
      "street": "CHURCH ST"
    },
    {
      "usrn": "22403385",
      "street": "CHURCH TERR"
    },
    {
      "usrn": "20900238",
      "street": "CHURCH WALK"
    },
    {
      "usrn": "22406597",
      "street": "CHURCH WALK"
    },
    {
      "usrn": "22406671",
      "street": "CHURCH WALK"
    },
    {
      "usrn": "22401373",
      "street": "CHURCHVIEW RD"
    },
    {
      "usrn": "22402735",
      "street": "CLARE LAWN AV"
    },
    {
      "usrn": "22403386",
      "street": "CLAREMONT RD"
    },
    {
      "usrn": "22403387",
      "street": "CLAREMONT RD"
    },
    {
      "usrn": "22403388",
      "street": "CLARENCE RD"
    },
    {
      "usrn": "22405456",
      "street": "CLARENCE RD"
    },
    {
      "usrn": "21800255",
      "street": "CLARENCE ST"
    },
    {
      "usrn": "22405457",
      "street": "CLARENCE ST"
    },
    {
      "usrn": "22401374",
      "street": "CLARENDON CRESCENT"
    },
    {
      "usrn": "22404269",
      "street": "CLAVERING AV"
    },
    {
      "usrn": "22403389",
      "street": "CLAVERING CLS"
    },
    {
      "usrn": "22403390",
      "street": "CLEVEDON RD"
    },
    {
      "usrn": "22401375",
      "street": "CLEVELAND AV"
    },
    {
      "usrn": "22404274",
      "street": "CLEVELAND GARDENS"
    },
    {
      "usrn": "22404275",
      "street": "CLEVELAND RD"
    },
    {
      "usrn": "22403391",
      "street": "CLEVES RD"
    },
    {
      "usrn": "22401376",
      "street": "CLEVES WAY"
    },
    {
      "usrn": "22403392",
      "street": "CLIFDEN RD"
    },
    {
      "usrn": "22404277",
      "street": "CLIFFORD AV"
    },
    {
      "usrn": "22405471",
      "street": "CLIFFORD AV"
    },
    {
      "usrn": "22403393",
      "street": "CLIFFORD RD"
    },
    {
      "usrn": "21800260",
      "street": "CLIFTON RD"
    },
    {
      "usrn": "22403394",
      "street": "CLIFTON RD"
    },
    {
      "usrn": "22403396",
      "street": "CLIVE RD"
    },
    {
      "usrn": "22406697",
      "street": "CLOISTER CLS"
    },
    {
      "usrn": "22403398",
      "street": "CLONMEL RD"
    },
    {
      "usrn": "22405477",
      "street": "CLYDESDALE GARDENS"
    },
    {
      "usrn": "22401381",
      "street": "COBBETT RD"
    },
    {
      "usrn": "22403400",
      "street": "COLE PRK GARDENS"
    },
    {
      "usrn": "22403402",
      "street": "COLE PRK RD"
    },
    {
      "usrn": "22407083",
      "street": "COLE PRK VIEW"
    },
    {
      "usrn": "22403404",
      "street": "COLE RD"
    },
    {
      "usrn": "22403405",
      "street": "COLESHILL RD"
    },
    {
      "usrn": "22401382",
      "street": "COLLEGE CLS"
    },
    {
      "usrn": "22401383",
      "street": "COLLINGWOOD CLS"
    },
    {
      "usrn": "22403406",
      "street": "COLNE RD"
    },
    {
      "usrn": "22401384",
      "street": "COLONIAL AV"
    },
    {
      "usrn": "22200495",
      "street": "COLSTON RD"
    },
    {
      "usrn": "22404291",
      "street": "COLSTON RD"
    },
    {
      "usrn": "22403408",
      "street": "CONIFERS CLS"
    },
    {
      "usrn": "22404299",
      "street": "CONISTON CLS"
    },
    {
      "usrn": "22401385",
      "street": "CONISTON RD"
    },
    {
      "usrn": "22404300",
      "street": "CONNAUGHT AV"
    },
    {
      "usrn": "22828500",
      "street": "CONNAUGHT AV"
    },
    {
      "usrn": "22401387",
      "street": "CONNAUGHT RD"
    },
    {
      "usrn": "22403410",
      "street": "CONNAUGHT RD"
    },
    {
      "usrn": "22401390",
      "street": "CONSTANCE RD"
    },
    {
      "usrn": "22401392",
      "street": "CONWAY RD"
    },
    {
      "usrn": "22406149",
      "street": "CONWAY WALK"
    },
    {
      "usrn": "22401394",
      "street": "COOMBE CRESCENT"
    },
    {
      "usrn": "22401395",
      "street": "COOMBE RD"
    },
    {
      "usrn": "22403411",
      "street": "COPTHALL GARDENS"
    },
    {
      "usrn": "22407135",
      "street": "CORFE CLS"
    },
    {
      "usrn": "22403412",
      "street": "CORNWALL RD"
    },
    {
      "usrn": "22407181",
      "street": "CORSELLIS SQUARE"
    },
    {
      "usrn": "22401396",
      "street": "COTSWOLD RD"
    },
    {
      "usrn": "22403416",
      "street": "COURTLANDS"
    },
    {
      "usrn": "22401402",
      "street": "COURTLANDS AV"
    },
    {
      "usrn": "22405488",
      "street": "COURTLANDS AV"
    },
    {
      "usrn": "22405489",
      "street": "COVAL GARDENS"
    },
    {
      "usrn": "22405490",
      "street": "COVAL LANE"
    },
    {
      "usrn": "22406216",
      "street": "COVAL PASSAGE"
    },
    {
      "usrn": "22405491",
      "street": "COVAL RD"
    },
    {
      "usrn": "22404312",
      "street": "COWLEY RD"
    },
    {
      "usrn": "22403417",
      "street": "COWPER RD"
    },
    {
      "usrn": "22403418",
      "street": "CRAIG RD"
    },
    {
      "usrn": "22401404",
      "street": "CRANBROOK DRIVE"
    },
    {
      "usrn": "8100153",
      "street": "CRANE CT"
    },
    {
      "usrn": "22401405",
      "street": "CRANE PRK RD"
    },
    {
      "usrn": "22403420",
      "street": "CRANE RD"
    },
    {
      "usrn": "22401406",
      "street": "CRANE WAY"
    },
    {
      "usrn": "22407084",
      "street": "CRANEBANK MEWS"
    },
    {
      "usrn": "22403421",
      "street": "CRANEFORD CLS"
    },
    {
      "usrn": "22403422",
      "street": "CRANEFORD WAY"
    },
    {
      "usrn": "22401409",
      "street": "CRANMER RD"
    },
    {
      "usrn": "22403426",
      "street": "CRESSWELL RD"
    },
    {
      "usrn": "22407167",
      "street": "CRICKET LANE"
    },
    {
      "usrn": "22406634",
      "street": "CRIEFF CT"
    },
    {
      "usrn": "22403427",
      "street": "CROFT WAY"
    },
    {
      "usrn": "22404324",
      "street": "CROMWELL PLACE"
    },
    {
      "usrn": "22403428",
      "street": "CROMWELL RD"
    },
    {
      "usrn": "22403429",
      "street": "CROSS DEEP"
    },
    {
      "usrn": "22403430",
      "street": "CROSS DEEP GARDENS"
    },
    {
      "usrn": "22401419",
      "street": "CROSS ST"
    },
    {
      "usrn": "22406806",
      "street": "CROSS ST"
    },
    {
      "usrn": "22403432",
      "street": "CROWN RD"
    },
    {
      "usrn": "22405496",
      "street": "CROWN TERR"
    },
    {
      "usrn": "22406788",
      "street": "CT CLS"
    },
    {
      "usrn": "22403415",
      "street": "CT WAY"
    },
    {
      "usrn": "22403433",
      "street": "CUMBERLAND CLS"
    },
    {
      "usrn": "20600490",
      "street": "CUMBERLAND RD"
    },
    {
      "usrn": "22404328",
      "street": "CUMBERLAND RD"
    },
    {
      "usrn": "22405500",
      "street": "CUMBERLAND RD"
    },
    {
      "usrn": "22401420",
      "street": "CURTIS RD"
    },
    {
      "usrn": "22403434",
      "street": "CUSACK CLS"
    },
    {
      "usrn": "22401421",
      "street": "CYCLAMEN CLS"
    },
    {
      "usrn": "22401423",
      "street": "CYPRESS AV"
    },
    {
      "usrn": "22406731",
      "street": "DAFFODIL PLACE"
    },
    {
      "usrn": "22405502",
      "street": "DANCER RD"
    },
    {
      "usrn": "22406929",
      "street": "DANIEL CLS"
    },
    {
      "usrn": "22405503",
      "street": "DARELL RD"
    },
    {
      "usrn": "22407006",
      "street": "DAUBENEY PLACE"
    },
    {
      "usrn": "22403436",
      "street": "DAVENPORT CLS"
    },
    {
      "usrn": "22406150",
      "street": "DEACONS WALK"
    },
    {
      "usrn": "22401427",
      "street": "DEAN RD"
    },
    {
      "usrn": "22405508",
      "street": "DEANHILL RD"
    },
    {
      "usrn": "22405511",
      "street": "DEE RD"
    },
    {
      "usrn": "22406933",
      "street": "DEERHURST CRESCENT"
    },
    {
      "usrn": "22405513",
      "street": "DEFOE AV"
    },
    {
      "usrn": "22407071",
      "street": "DELLS CLS"
    },
    {
      "usrn": "22403440",
      "street": "DENBIGH GARDENS"
    },
    {
      "usrn": "22401431",
      "street": "DENEHURST GARDENS"
    },
    {
      "usrn": "22405515",
      "street": "DENEHURST GARDENS"
    },
    {
      "usrn": "22401433",
      "street": "DENMARK RD"
    },
    {
      "usrn": "22401434",
      "street": "DENNING CLS"
    },
    {
      "usrn": "22403442",
      "street": "DENTON RD"
    },
    {
      "usrn": "22405516",
      "street": "DERBY RD"
    },
    {
      "usrn": "22401435",
      "street": "DERWENT RD"
    },
    {
      "usrn": "22406743",
      "street": "DEVEREUX LANE"
    },
    {
      "usrn": "22401436",
      "street": "DEVON AV"
    },
    {
      "usrn": "22403443",
      "street": "DEVONCROFT GARDENS"
    },
    {
      "usrn": "21001266",
      "street": "DEVONPORT MEWS"
    },
    {
      "usrn": "22403444",
      "street": "DICKENS CLS"
    },
    {
      "usrn": "22403446",
      "street": "DOONE CLS"
    },
    {
      "usrn": "22406642",
      "street": "DORA JORDAN RD"
    },
    {
      "usrn": "22403447",
      "street": "DORCHESTER MEWS"
    },
    {
      "usrn": "22401440",
      "street": "DORSET WAY"
    },
    {
      "usrn": "22400823",
      "street": "DOUAI GROVE"
    },
    {
      "usrn": "22406924",
      "street": "DOVECOTE GARDENS"
    },
    {
      "usrn": "22403448",
      "street": "DOWN RD"
    },
    {
      "usrn": "22403449",
      "street": "DOWNES CLS"
    },
    {
      "usrn": "22403450",
      "street": "DOWNSIDE"
    },
    {
      "usrn": "22406811",
      "street": "DRUMMOND PLACE"
    },
    {
      "usrn": "22406744",
      "street": "DRUMMONDS PLACE"
    },
    {
      "usrn": "22406151",
      "street": "DUCKS WALK"
    },
    {
      "usrn": "22405525",
      "street": "DUDLEY RD"
    },
    {
      "usrn": "22401442",
      "street": "DUKE OF CAMBRIDGE CLS"
    },
    {
      "usrn": "22403451",
      "street": "DUKE ST"
    },
    {
      "usrn": "22403452",
      "street": "DUKES AV"
    },
    {
      "usrn": "22401443",
      "street": "DUKES CLS"
    },
    {
      "usrn": "22207537",
      "street": "DUKES CT"
    },
    {
      "usrn": "22405527",
      "street": "DUNCAN RD"
    },
    {
      "usrn": "22401444",
      "street": "DUNLEARY CLS"
    },
    {
      "usrn": "22405528",
      "street": "DUNSTABLE RD"
    },
    {
      "usrn": "22404377",
      "street": "DYERS LANE"
    },
    {
      "usrn": "22403455",
      "street": "DYNEVOR RD"
    },
    {
      "usrn": "22404378",
      "street": "EARL RD"
    },
    {
      "usrn": "22402798",
      "street": "EAST SHEEN AV"
    },
    {
      "usrn": "22401447",
      "street": "EASTBANK RD"
    },
    {
      "usrn": "22404383",
      "street": "EASTBOURNE GARDENS"
    },
    {
      "usrn": "8401171",
      "street": "EATON GATE"
    },
    {
      "usrn": "8400821",
      "street": "EATON SQUARE"
    },
    {
      "usrn": "22401449",
      "street": "EDGAR RD"
    },
    {
      "usrn": "21000298",
      "street": "EDITH VILLAS"
    },
    {
      "usrn": "22401450",
      "street": "EDWARD CLS"
    },
    {
      "usrn": "22401451",
      "street": "EDWARD RD"
    },
    {
      "usrn": "22403460",
      "street": "EDWIN RD"
    },
    {
      "usrn": "22407085",
      "street": "EEL PIE ISLAND"
    },
    {
      "usrn": "22403461",
      "street": "EGERTON RD"
    },
    {
      "usrn": "22404396",
      "street": "ELEANOR GROVE"
    },
    {
      "usrn": "22403462",
      "street": "ELFIN GROVE"
    },
    {
      "usrn": "22405539",
      "street": "ELIZABETH COTTAGES"
    },
    {
      "usrn": "22403463",
      "street": "ELLERAY RD"
    },
    {
      "usrn": "22403464",
      "street": "ELLERKER GARDENS"
    },
    {
      "usrn": "22401455",
      "street": "ELLERMAN AV"
    },
    {
      "usrn": "22403465",
      "street": "ELLESMERE RD"
    },
    {
      "usrn": "22901453",
      "street": "ELLISFIELD DRIVE"
    },
    {
      "usrn": "22404405",
      "street": "ELLISON RD"
    },
    {
      "usrn": "22404406",
      "street": "ELM BANK GARDENS"
    },
    {
      "usrn": "22401456",
      "street": "ELM CLS"
    },
    {
      "usrn": "22404407",
      "street": "ELM GROVE RD"
    },
    {
      "usrn": "21900513",
      "street": "ELM PRK"
    },
    {
      "usrn": "22404408",
      "street": "ELM RD"
    },
    {
      "usrn": "22406610",
      "street": "ELMERS DRIVE"
    },
    {
      "usrn": "22403468",
      "street": "ELMFIELD AV"
    },
    {
      "usrn": "22401458",
      "street": "ELMSLEIGH RD"
    },
    {
      "usrn": "22403469",
      "street": "ELMTREE RD"
    },
    {
      "usrn": "22405542",
      "street": "ELSINORE WAY"
    },
    {
      "usrn": "22406131",
      "street": "ELTON CLS"
    },
    {
      "usrn": "22406934",
      "street": "EMANUEL DRIVE"
    },
    {
      "usrn": "22406152",
      "street": "EMBLETON WALK"
    },
    {
      "usrn": "22402807",
      "street": "ENMORE GARDENS"
    },
    {
      "usrn": "22405547",
      "street": "ENNERDALE RD"
    },
    {
      "usrn": "22403470",
      "street": "ENTERPRISE WAY"
    },
    {
      "usrn": "22403471",
      "street": "ERNCROFT WAY"
    },
    {
      "usrn": "22403472",
      "street": "ETON ST"
    },
    {
      "usrn": "22401463",
      "street": "EVELYN CLS"
    },
    {
      "usrn": "22405553",
      "street": "EVELYN GARDENS"
    },
    {
      "usrn": "22403473",
      "street": "EVELYN RD"
    },
    {
      "usrn": "22405554",
      "street": "EVELYN RD"
    },
    {
      "usrn": "22405555",
      "street": "EVELYN TERR"
    },
    {
      "usrn": "22404430",
      "street": "EVERDON RD"
    },
    {
      "usrn": "22405556",
      "street": "EVERSFIELD RD"
    },
    {
      "usrn": "22403474",
      "street": "FAIRFAX RD"
    },
    {
      "usrn": "22401466",
      "street": "FAIRFIELD AV"
    },
    {
      "usrn": "22403476",
      "street": "FAIRLAWNS"
    },
    {
      "usrn": "22403477",
      "street": "FAIRWAYS"
    },
    {
      "usrn": "22401468",
      "street": "FALCON RD"
    },
    {
      "usrn": "22403466",
      "street": "FALLOW PLACE"
    },
    {
      "usrn": "22406728",
      "street": "FALSTAFF MEWS"
    },
    {
      "usrn": "22403478",
      "street": "FANSHAWE RD"
    },
    {
      "usrn": "22401470",
      "street": "FARM RD"
    },
    {
      "usrn": "22401471",
      "street": "FEARNLEY CRESCENT"
    },
    {
      "usrn": "22403479",
      "street": "FELLBROOK"
    },
    {
      "usrn": "22407027",
      "street": "FEN LANE"
    },
    {
      "usrn": "22404452",
      "street": "FERRY LANE"
    },
    {
      "usrn": "22405560",
      "street": "FERRY LANE"
    },
    {
      "usrn": "22403481",
      "street": "FERRY RD"
    },
    {
      "usrn": "22403482",
      "street": "FERRY RD"
    },
    {
      "usrn": "22404453",
      "street": "FERRY RD"
    },
    {
      "usrn": "22403483",
      "street": "FERRYMOOR"
    },
    {
      "usrn": "22403484",
      "street": "FIELD LANE"
    },
    {
      "usrn": "22403485",
      "street": "FIELDEND"
    },
    {
      "usrn": "22401477",
      "street": "FIELDING AV"
    },
    {
      "usrn": "22406925",
      "street": "FIELDING MEWS"
    },
    {
      "usrn": "22402817",
      "street": "FIFE RD"
    },
    {
      "usrn": "22401478",
      "street": "FIFTH CROSS RD"
    },
    {
      "usrn": "22404461",
      "street": "FIRS AV"
    },
    {
      "usrn": "22404462",
      "street": "FIRST AV"
    },
    {
      "usrn": "22403486",
      "street": "FIRST CROSS RD"
    },
    {
      "usrn": "22403487",
      "street": "FISHERMAN CLS"
    },
    {
      "usrn": "22401481",
      "street": "FITZ WYGRAM CLS"
    },
    {
      "usrn": "22404466",
      "street": "FITZGERALD AV"
    },
    {
      "usrn": "22404467",
      "street": "FITZGERALD RD"
    },
    {
      "usrn": "22405564",
      "street": "FITZWILLIAM AV"
    },
    {
      "usrn": "22403488",
      "street": "FLOOD LANE"
    },
    {
      "usrn": "22403284",
      "street": "FLORENCE CLS"
    },
    {
      "usrn": "22407184",
      "street": "FLOYER CLS"
    },
    {
      "usrn": "22405566",
      "street": "FOREST RD"
    },
    {
      "usrn": "22407165",
      "street": "FORGE LANE"
    },
    {
      "usrn": "22401485",
      "street": "FORTESCUE AV"
    },
    {
      "usrn": "22404074",
      "street": "FOUNDRY MEWS"
    },
    {
      "usrn": "22401489",
      "street": "FOURTH CROSS RD"
    },
    {
      "usrn": "22406408",
      "street": "FOXTON MEWS"
    },
    {
      "usrn": "22403490",
      "street": "FRIARS LANE"
    },
    {
      "usrn": "22406162",
      "street": "FRIARS STILE PLACE"
    },
    {
      "usrn": "22403491",
      "street": "FRIARS STILE RD"
    },
    {
      "usrn": "22401494",
      "street": "FULMER CLS"
    },
    {
      "usrn": "22401495",
      "street": "FULWELL PRK AV"
    },
    {
      "usrn": "22403492",
      "street": "FULWELL RD"
    },
    {
      "usrn": "22403493",
      "street": "FULWOOD GARDENS"
    },
    {
      "usrn": "22405568",
      "street": "GAINSBOROUGH RD"
    },
    {
      "usrn": "22404489",
      "street": "GALATA RD"
    },
    {
      "usrn": "22401499",
      "street": "GALE CLS"
    },
    {
      "usrn": "22406941",
      "street": "GANDER GREEN CRESCENT"
    },
    {
      "usrn": "22401500",
      "street": "GARDEN CLS"
    },
    {
      "usrn": "22405569",
      "street": "GARDEN RD"
    },
    {
      "usrn": "22403495",
      "street": "GARFIELD RD"
    },
    {
      "usrn": "22403496",
      "street": "GARRICK CLS"
    },
    {
      "usrn": "22405570",
      "street": "GARRICK RD"
    },
    {
      "usrn": "13703516",
      "street": "GARRICKS AIT"
    },
    {
      "usrn": "22401501",
      "street": "GARSIDE CLS"
    },
    {
      "usrn": "22403499",
      "street": "GARTHSIDE"
    },
    {
      "usrn": "22405571",
      "street": "GASTON BELL CLS"
    },
    {
      "usrn": "22403501",
      "street": "GEORGE ST"
    },
    {
      "usrn": "22401502",
      "street": "GERARD AV"
    },
    {
      "usrn": "22404495",
      "street": "GERARD RD"
    },
    {
      "usrn": "22407086",
      "street": "GIBSON MEWS"
    },
    {
      "usrn": "22401944",
      "street": "GILKES LANE"
    },
    {
      "usrn": "22404497",
      "street": "GILPIN AV"
    },
    {
      "usrn": "22401503",
      "street": "GILPIN CRESCENT"
    },
    {
      "usrn": "22404498",
      "street": "GIPSY LANE"
    },
    {
      "usrn": "22401504",
      "street": "GLADIOLI CLS"
    },
    {
      "usrn": "22401506",
      "street": "GLADSTONE AV"
    },
    {
      "usrn": "22400262",
      "street": "GLAMORGAN RD"
    },
    {
      "usrn": "22401507",
      "street": "GLASBROOK AV"
    },
    {
      "usrn": "20017760",
      "street": "GLEBE RD"
    },
    {
      "usrn": "22404504",
      "street": "GLEBE RD"
    },
    {
      "usrn": "22403506",
      "street": "GLEBE SIDE"
    },
    {
      "usrn": "22401508",
      "street": "GLEBE WAY"
    },
    {
      "usrn": "22404509",
      "street": "GLENDOWER GARDENS"
    },
    {
      "usrn": "22404510",
      "street": "GLENDOWER RD"
    },
    {
      "usrn": "22406935",
      "street": "GLENMILL"
    },
    {
      "usrn": "22404511",
      "street": "GLENTHAM GARDENS"
    },
    {
      "usrn": "22404512",
      "street": "GLENTHAM RD"
    },
    {
      "usrn": "22405577",
      "street": "GLOUCESTER CT"
    },
    {
      "usrn": "22401511",
      "street": "GLOUCESTER RD"
    },
    {
      "usrn": "22401512",
      "street": "GLOUCESTER RD"
    },
    {
      "usrn": "22403507",
      "street": "GLOUCESTER RD"
    },
    {
      "usrn": "22405578",
      "street": "GLOUCESTER RD"
    },
    {
      "usrn": "8400410",
      "street": "GLOUCESTER TERR"
    },
    {
      "usrn": "22406812",
      "street": "GLOXINIA WALK"
    },
    {
      "usrn": "22406378",
      "street": "GODDING PATH"
    },
    {
      "usrn": "22401513",
      "street": "GODFREY AV"
    },
    {
      "usrn": "21590281",
      "street": "GODFREY WAY"
    },
    {
      "usrn": "22403508",
      "street": "GODSTONE RD"
    },
    {
      "usrn": "22406600",
      "street": "GOLDEN CT"
    },
    {
      "usrn": "22401515",
      "street": "GOLF SIDE"
    },
    {
      "usrn": "22403509",
      "street": "GOMER GARDENS"
    },
    {
      "usrn": "22403510",
      "street": "GOMER PLACE"
    },
    {
      "usrn": "22403511",
      "street": "GORDON AV"
    },
    {
      "usrn": "22404522",
      "street": "GORDON AV"
    },
    {
      "usrn": "22405582",
      "street": "GORDON RD"
    },
    {
      "usrn": "22401516",
      "street": "GOSTLING RD"
    },
    {
      "usrn": "22401517",
      "street": "GOTHIC RD"
    },
    {
      "usrn": "22403512",
      "street": "GOULD RD"
    },
    {
      "usrn": "13700614",
      "street": "GRABURN WAY"
    },
    {
      "usrn": "22405584",
      "street": "GRAEMESDYKE AV"
    },
    {
      "usrn": "22406221",
      "street": "GRAEMSDYKE FOOTPATH"
    },
    {
      "usrn": "22401518",
      "street": "GRAFTON CLS"
    },
    {
      "usrn": "22401519",
      "street": "GRAHAM RD"
    },
    {
      "usrn": "22407033",
      "street": "GRAND PARADE"
    },
    {
      "usrn": "22403513",
      "street": "GRANGE AV"
    },
    {
      "usrn": "22201429",
      "street": "GRANGE RD"
    },
    {
      "usrn": "22404527",
      "street": "GRANGE RD"
    },
    {
      "usrn": "22401522",
      "street": "GRASMERE AV"
    },
    {
      "usrn": "22403514",
      "street": "GRAVEL RD"
    },
    {
      "usrn": "22406154",
      "street": "GREEN WALK"
    },
    {
      "usrn": "22407123",
      "street": "GREENLINK WALK"
    },
    {
      "usrn": "22401529",
      "street": "GREENWOOD LANE"
    },
    {
      "usrn": "22405602",
      "street": "GRENA GARDENS"
    },
    {
      "usrn": "22405603",
      "street": "GRENA RD"
    },
    {
      "usrn": "22401530",
      "street": "GRENVILLE MEWS"
    },
    {
      "usrn": "22401531",
      "street": "GRESHAM RD"
    },
    {
      "usrn": "22403515",
      "street": "GREVILLE CLS"
    },
    {
      "usrn": "22403516",
      "street": "GREVILLE RD"
    },
    {
      "usrn": "22403517",
      "street": "GRIMWOOD RD"
    },
    {
      "usrn": "22406147",
      "street": "GROGAN CLS"
    },
    {
      "usrn": "22403518",
      "street": "GROSVENOR AV"
    },
    {
      "usrn": "22404552",
      "street": "GROSVENOR AV"
    },
    {
      "usrn": "22404553",
      "street": "GROSVENOR GARDENS"
    },
    {
      "usrn": "21500522",
      "street": "GROSVENOR RD"
    },
    {
      "usrn": "22403520",
      "street": "GROSVENOR RD"
    },
    {
      "usrn": "22403521",
      "street": "GROSVENOR RD"
    },
    {
      "usrn": "22403522",
      "street": "GROTTO RD"
    },
    {
      "usrn": "22403523",
      "street": "GROVE AV"
    },
    {
      "usrn": "22403524",
      "street": "GROVE GARDENS"
    },
    {
      "usrn": "22401533",
      "street": "GROVE RD"
    },
    {
      "usrn": "22403525",
      "street": "GROVE RD"
    },
    {
      "usrn": "22404561",
      "street": "GROVE RD"
    },
    {
      "usrn": "22403526",
      "street": "GROVE TERR"
    },
    {
      "usrn": "22406119",
      "street": "GROVEWOOD"
    },
    {
      "usrn": "22403527",
      "street": "HAGGARD RD"
    },
    {
      "usrn": "22406686",
      "street": "HALCYON CLS"
    },
    {
      "usrn": "22403528",
      "street": "HALFORD RD"
    },
    {
      "usrn": "22403529",
      "street": "HALIBURTON RD"
    },
    {
      "usrn": "22407072",
      "street": "HALIFAX CLS"
    },
    {
      "usrn": "22401536",
      "street": "HALL FARM DRIVE"
    },
    {
      "usrn": "22902194",
      "street": "HALLAM RD"
    },
    {
      "usrn": "22403530",
      "street": "HAM AVENUES"
    },
    {
      "usrn": "22406127",
      "street": "HAM CLS"
    },
    {
      "usrn": "22403531",
      "street": "HAM COMMON"
    },
    {
      "usrn": "22403532",
      "street": "HAM FARM RD"
    },
    {
      "usrn": "22406427",
      "street": "HAM GATE AV"
    },
    {
      "usrn": "22403534",
      "street": "HAM RIDINGS"
    },
    {
      "usrn": "22403535",
      "street": "HAM ST"
    },
    {
      "usrn": "22407142",
      "street": "HAMILTON CLS"
    },
    {
      "usrn": "22403536",
      "street": "HAMILTON RD"
    },
    {
      "usrn": "21001178",
      "street": "HAMMERSMITH BRIDGE"
    },
    {
      "usrn": "21000411",
      "street": "HAMMERSMITH RD"
    },
    {
      "usrn": "22400896",
      "street": "HAMMOND CLS"
    },
    {
      "usrn": "22407001",
      "street": "HAMPTON CT PALACE"
    },
    {
      "usrn": "22400288",
      "street": "HAMPTON CT RD"
    },
    {
      "usrn": "22406635",
      "street": "HAMPTON CT RD"
    },
    {
      "usrn": "22406593",
      "street": "HAMPTON CT WAY"
    },
    {
      "usrn": "22401543",
      "street": "HAMPTON RD"
    },
    {
      "usrn": "22403537",
      "street": "HAMPTON RD"
    },
    {
      "usrn": "22403538",
      "street": "HAMPTON RD"
    },
    {
      "usrn": "21500549",
      "street": "HAMPTON RD EAST"
    },
    {
      "usrn": "21500550",
      "street": "HAMPTON RD WEST"
    },
    {
      "usrn": "22405628",
      "street": "HANOVER CLS"
    },
    {
      "usrn": "22404582",
      "street": "HANSON CLS"
    },
    {
      "usrn": "21501254",
      "street": "HANWORTH RD"
    },
    {
      "usrn": "22401549",
      "street": "HANWORTH RD"
    },
    {
      "usrn": "22406585",
      "street": "HANWORTH RD"
    },
    {
      "usrn": "22403539",
      "street": "HARDWICKE RD"
    },
    {
      "usrn": "22403541",
      "street": "HARLEQUIN RD"
    },
    {
      "usrn": "22403542",
      "street": "HARROWDENE GARDENS"
    },
    {
      "usrn": "22403543",
      "street": "HARTINGTON RD"
    },
    {
      "usrn": "22401554",
      "street": "HARTLAND RD"
    },
    {
      "usrn": "22406942",
      "street": "HARVEY DRIVE"
    },
    {
      "usrn": "22401557",
      "street": "HARVEY RD"
    },
    {
      "usrn": "22401558",
      "street": "HASLEMERE CLS"
    },
    {
      "usrn": "22405640",
      "street": "HATHERLEY RD"
    },
    {
      "usrn": "22401559",
      "street": "HATHEROP RD"
    },
    {
      "usrn": "22405641",
      "street": "HAVERFIELD GARDENS"
    },
    {
      "usrn": "22403545",
      "street": "HAVERSHAM CLS"
    },
    {
      "usrn": "22403546",
      "street": "HAWKESLEY CLS"
    },
    {
      "usrn": "22403547",
      "street": "HAWKINS RD"
    },
    {
      "usrn": "22401560",
      "street": "HAWLEY CLS"
    },
    {
      "usrn": "22401561",
      "street": "HAWTHORN CLS"
    },
    {
      "usrn": "22403698",
      "street": "HAYDON CLS"
    },
    {
      "usrn": "22401563",
      "street": "HAZEL CLS"
    },
    {
      "usrn": "22406223",
      "street": "HAZEL LANE"
    },
    {
      "usrn": "22403549",
      "street": "HEADWAY CLS"
    },
    {
      "usrn": "22403550",
      "street": "HEATH GARDENS"
    },
    {
      "usrn": "22403551",
      "street": "HEATH RD"
    },
    {
      "usrn": "22403552",
      "street": "HEATHAM PRK"
    },
    {
      "usrn": "22403553",
      "street": "HEATHCOTE RD"
    },
    {
      "usrn": "20600863",
      "street": "HEATHCROFT"
    },
    {
      "usrn": "22400903",
      "street": "HEATHER CLS"
    },
    {
      "usrn": "22406380",
      "street": "HEATHER WALK"
    },
    {
      "usrn": "22403555",
      "street": "HEATHFIELD NORTH"
    },
    {
      "usrn": "22403556",
      "street": "HEATHFIELD SOUTH"
    },
    {
      "usrn": "22403557",
      "street": "HEATHLANDS CLS"
    },
    {
      "usrn": "22401572",
      "street": "HEATHSIDE"
    },
    {
      "usrn": "22401573",
      "street": "HEDLEY RD"
    },
    {
      "usrn": "22406850",
      "street": "HEIDEGGER CRESCENT"
    },
    {
      "usrn": "22400906",
      "street": "HEMMING CLS"
    },
    {
      "usrn": "20021800",
      "street": "HENDON LANE"
    },
    {
      "usrn": "22406412",
      "street": "HENLOW PLACE"
    },
    {
      "usrn": "22407073",
      "street": "HENRY PETERS DRIVE"
    },
    {
      "usrn": "22401576",
      "street": "HEREFORD GARDENS"
    },
    {
      "usrn": "22405654",
      "street": "HERON RD"
    },
    {
      "usrn": "22406720",
      "street": "HERON SQUARE"
    },
    {
      "usrn": "22404599",
      "street": "HERTFORD AV"
    },
    {
      "usrn": "20022120",
      "street": "HERTFORD RD"
    },
    {
      "usrn": "22405657",
      "street": "HESTER TERR"
    },
    {
      "usrn": "21500603",
      "street": "HIBERNIA RD"
    },
    {
      "usrn": "22406632",
      "street": "HIGGINS WALK"
    },
    {
      "usrn": "22405659",
      "street": "HIGH PRK AV"
    },
    {
      "usrn": "22405660",
      "street": "HIGH PRK RD"
    },
    {
      "usrn": "22201445",
      "street": "HIGH ST"
    },
    {
      "usrn": "22400303",
      "street": "HIGH ST"
    },
    {
      "usrn": "22401582",
      "street": "HIGH ST"
    },
    {
      "usrn": "22403558",
      "street": "HIGH ST"
    },
    {
      "usrn": "22406746",
      "street": "HIGH ST"
    },
    {
      "usrn": "22406747",
      "street": "HIGH ST"
    },
    {
      "usrn": "22845050",
      "street": "HIGH ST"
    },
    {
      "usrn": "31901152",
      "street": "HIGH ST"
    },
    {
      "usrn": "22400913",
      "street": "HILL FIELD RD"
    },
    {
      "usrn": "22406940",
      "street": "HILL HOUSE DRIVE"
    },
    {
      "usrn": "22403560",
      "street": "HILL RISE"
    },
    {
      "usrn": "22403561",
      "street": "HILL ST"
    },
    {
      "usrn": "22403562",
      "street": "HILL VIEW RD"
    },
    {
      "usrn": "22404602",
      "street": "HILLERSDON AV"
    },
    {
      "usrn": "22403563",
      "street": "HOBART PLACE"
    },
    {
      "usrn": "22400916",
      "street": "HOGARTH WAY"
    },
    {
      "usrn": "21700262",
      "street": "HOLBEIN PLACE"
    },
    {
      "usrn": "22406413",
      "street": "HOLBROOKE PLACE"
    },
    {
      "usrn": "22401585",
      "street": "HOLLES CLS"
    },
    {
      "usrn": "22403564",
      "street": "HOLLIES CLS"
    },
    {
      "usrn": "22401586",
      "street": "HOLLY BUSH LANE"
    },
    {
      "usrn": "22401588",
      "street": "HOLLY RD"
    },
    {
      "usrn": "22403565",
      "street": "HOLLY RD"
    },
    {
      "usrn": "22401589",
      "street": "HOLLYBANK CLS"
    },
    {
      "usrn": "22403567",
      "street": "HOLMES RD"
    },
    {
      "usrn": "22405665",
      "street": "HOLMESDALE AV"
    },
    {
      "usrn": "22403568",
      "street": "HOLMESDALE RD"
    },
    {
      "usrn": "22405666",
      "street": "HOLMESDALE RD"
    },
    {
      "usrn": "22401590",
      "street": "HOMEWOOD CLS"
    },
    {
      "usrn": "22402892",
      "street": "HOOD AV"
    },
    {
      "usrn": "22401591",
      "street": "HOSPITAL BRIDGE RD"
    },
    {
      "usrn": "22405669",
      "street": "HOUBLON RD"
    },
    {
      "usrn": "22401592",
      "street": "HOUGHTON CLS"
    },
    {
      "usrn": "22401597",
      "street": "HOUNSLOW RD"
    },
    {
      "usrn": "22401598",
      "street": "HOWARD CLS"
    },
    {
      "usrn": "22404627",
      "street": "HOWGATE RD"
    },
    {
      "usrn": "22404628",
      "street": "HOWSMAN RD"
    },
    {
      "usrn": "22407119",
      "street": "HOWSON TERR"
    },
    {
      "usrn": "22403570",
      "street": "HUNTERS CT"
    },
    {
      "usrn": "22403571",
      "street": "HUNTING GATE MEWS"
    },
    {
      "usrn": "13703502",
      "street": "HURST RD"
    },
    {
      "usrn": "22401600",
      "street": "HYACINTH CLS"
    },
    {
      "usrn": "22403572",
      "street": "HYDE RD"
    },
    {
      "usrn": "8401646",
      "street": "INVERNESS TERR"
    },
    {
      "usrn": "22406673",
      "street": "IRONMONGERS MEWS"
    },
    {
      "usrn": "22406943",
      "street": "ISABEL HILL CLS"
    },
    {
      "usrn": "21880197",
      "street": "ISABELLA PLACE"
    },
    {
      "usrn": "22407127",
      "street": "ISABELLA PLACE"
    },
    {
      "usrn": "22403573",
      "street": "IVYBRIDGE CLS"
    },
    {
      "usrn": "22407102",
      "street": "JAMES TERR"
    },
    {
      "usrn": "22401603",
      "street": "JEFFS CLS"
    },
    {
      "usrn": "22406698",
      "street": "JENNER PLACE"
    },
    {
      "usrn": "22401604",
      "street": "JILLIAN CLS"
    },
    {
      "usrn": "22405675",
      "street": "JOCELYN RD"
    },
    {
      "usrn": "22400934",
      "street": "JOHNSONS DRIVE"
    },
    {
      "usrn": "22407042",
      "street": "JONES WALK"
    },
    {
      "usrn": "22401605",
      "street": "JONQUIL GARDENS"
    },
    {
      "usrn": "22407087",
      "street": "JORDANS MEWS"
    },
    {
      "usrn": "22401606",
      "street": "JUBILEE AV"
    },
    {
      "usrn": "22406383",
      "street": "JUBILEE CLS"
    },
    {
      "usrn": "22406921",
      "street": "KEBLE PLACE"
    },
    {
      "usrn": "22403574",
      "street": "KEEPERS MEWS"
    },
    {
      "usrn": "22407114",
      "street": "KELSALL MEWS"
    },
    {
      "usrn": "22403576",
      "street": "KELVIN DRIVE"
    },
    {
      "usrn": "22400939",
      "street": "KEMPTON RD"
    },
    {
      "usrn": "22403577",
      "street": "KENDREY GARDENS"
    },
    {
      "usrn": "22403578",
      "street": "KENLEY RD"
    },
    {
      "usrn": "22405680",
      "street": "KENMORE CLS"
    },
    {
      "usrn": "22403579",
      "street": "KENT DRIVE"
    },
    {
      "usrn": "22405682",
      "street": "KENT RD"
    },
    {
      "usrn": "22404649",
      "street": "KENTWODE GREEN"
    },
    {
      "usrn": "22401608",
      "street": "KESWICK RD"
    },
    {
      "usrn": "22405685",
      "street": "KEW FOOT RD"
    },
    {
      "usrn": "22405686",
      "street": "KEW GARDENS RD"
    },
    {
      "usrn": "22405687",
      "street": "KEW GREEN"
    },
    {
      "usrn": "22406664",
      "street": "KEW MEADOW PATH"
    },
    {
      "usrn": "22405688",
      "street": "KEW RD"
    },
    {
      "usrn": "22406655",
      "street": "KEW RD"
    },
    {
      "usrn": "22404653",
      "street": "KILMINGTON RD"
    },
    {
      "usrn": "22403580",
      "street": "KILMOREY GARDENS"
    },
    {
      "usrn": "22403581",
      "street": "KILMOREY RD"
    },
    {
      "usrn": "22407171",
      "street": "KIMBER PLACE"
    },
    {
      "usrn": "22406753",
      "street": "KING EDWARD MEWS"
    },
    {
      "usrn": "22403582",
      "street": "KING EDWARDS GROVE"
    },
    {
      "usrn": "22403583",
      "street": "KING GEORGE SQUARE"
    },
    {
      "usrn": "22403584",
      "street": "KING ST"
    },
    {
      "usrn": "22403585",
      "street": "KING ST"
    },
    {
      "usrn": "31900061",
      "street": "KING ST"
    },
    {
      "usrn": "22407090",
      "street": "KING ST PARADE"
    },
    {
      "usrn": "22403588",
      "street": "KINGFISHER DRIVE"
    },
    {
      "usrn": "21900805",
      "street": "KINGS AV"
    },
    {
      "usrn": "22405692",
      "street": "KINGS FARM AV"
    },
    {
      "usrn": "21800550",
      "street": "KINGS RD"
    },
    {
      "usrn": "22401610",
      "street": "KINGS RD"
    },
    {
      "usrn": "22403586",
      "street": "KINGS RD"
    },
    {
      "usrn": "22403589",
      "street": "KINGS RD"
    },
    {
      "usrn": "22404656",
      "street": "KINGS RD"
    },
    {
      "usrn": "22406384",
      "street": "KINGS RIDE GATE"
    },
    {
      "usrn": "21800553",
      "street": "KINGSGATE RD"
    },
    {
      "usrn": "22403590",
      "street": "KINGSMEAD"
    },
    {
      "usrn": "22403591",
      "street": "KINGSMEAD CLS"
    },
    {
      "usrn": "22400330",
      "street": "KINGSTON BRIDGE"
    },
    {
      "usrn": "22407110",
      "street": "KINGSTON BRIDGE ROUNDABOUT"
    },
    {
      "usrn": "22406135",
      "street": "KINGSTON CLS"
    },
    {
      "usrn": "22403594",
      "street": "KINGSTON LANE"
    },
    {
      "usrn": "22403595",
      "street": "KINGSTON RD"
    },
    {
      "usrn": "22405697",
      "street": "KINGSWAY"
    },
    {
      "usrn": "22401612",
      "street": "KINGSWOOD AV"
    },
    {
      "usrn": "8400985",
      "street": "KINNERTON ST"
    },
    {
      "usrn": "22404668",
      "street": "KITSON RD"
    },
    {
      "usrn": "22401614",
      "street": "KNELLER RD"
    },
    {
      "usrn": "22407088",
      "street": "KNIGHTS PLACE"
    },
    {
      "usrn": "22403597",
      "street": "KNOWLE RD"
    },
    {
      "usrn": "22405470",
      "street": "KONSTANZ CLS"
    },
    {
      "usrn": "22406155",
      "street": "KREISEL WALK"
    },
    {
      "usrn": "22400951",
      "street": "LACEY DRIVE"
    },
    {
      "usrn": "22403599",
      "street": "LAKE GARDENS"
    },
    {
      "usrn": "22405700",
      "street": "LAMBERT AV"
    },
    {
      "usrn": "22403600",
      "street": "LAMMAS RD"
    },
    {
      "usrn": "22403602",
      "street": "LANCASTER COTTAGES"
    },
    {
      "usrn": "22403604",
      "street": "LANCASTER MEWS"
    },
    {
      "usrn": "22403606",
      "street": "LANCASTER PLACE"
    },
    {
      "usrn": "22403605",
      "street": "LANCASTER PRK"
    },
    {
      "usrn": "22405705",
      "street": "LANGDALE CLS"
    },
    {
      "usrn": "22404679",
      "street": "LANGDON PLACE"
    },
    {
      "usrn": "22407115",
      "street": "LANGDON PRK"
    },
    {
      "usrn": "22403607",
      "street": "LANGHAM GARDENS"
    },
    {
      "usrn": "22403608",
      "street": "LANGHAM HOUSE CLS"
    },
    {
      "usrn": "21501542",
      "street": "LANGHAM PLACE"
    },
    {
      "usrn": "22403609",
      "street": "LANGHAM RD"
    },
    {
      "usrn": "22406930",
      "street": "LANGHORN DRIVE"
    },
    {
      "usrn": "22401616",
      "street": "LANGRIDGE MEWS"
    },
    {
      "usrn": "22403610",
      "street": "LANGWOOD CHASE"
    },
    {
      "usrn": "22403611",
      "street": "LANSDOWNE CLS"
    },
    {
      "usrn": "22404684",
      "street": "LARCHES AV"
    },
    {
      "usrn": "22405708",
      "street": "LARKFIELD RD"
    },
    {
      "usrn": "22403612",
      "street": "LATCHMERE CLS"
    },
    {
      "usrn": "21800594",
      "street": "LATCHMERE LANE"
    },
    {
      "usrn": "22403613",
      "street": "LATCHMERE LANE"
    },
    {
      "usrn": "22403615",
      "street": "LATHAM CLS"
    },
    {
      "usrn": "22403616",
      "street": "LATHAM RD"
    },
    {
      "usrn": "22403617",
      "street": "LATIMER RD"
    },
    {
      "usrn": "22407138",
      "street": "LAUBIN CLS"
    },
    {
      "usrn": "22403618",
      "street": "LAUDERDALE DRIVE"
    },
    {
      "usrn": "22403619",
      "street": "LAUREL AV"
    },
    {
      "usrn": "22401619",
      "street": "LAUREL RD"
    },
    {
      "usrn": "22404690",
      "street": "LAUREL RD"
    },
    {
      "usrn": "22401587",
      "street": "LAVENDER MEWS"
    },
    {
      "usrn": "22405711",
      "street": "LAWN CRESCENT"
    },
    {
      "usrn": "22401620",
      "street": "LAWRENCE RD"
    },
    {
      "usrn": "22403620",
      "street": "LAWRENCE RD"
    },
    {
      "usrn": "22407043",
      "street": "LAYTON PLACE"
    },
    {
      "usrn": "22407089",
      "street": "LEA CLS"
    },
    {
      "usrn": "22403621",
      "street": "LEBANON PRK"
    },
    {
      "usrn": "22404694",
      "street": "LECONFIELD AV"
    },
    {
      "usrn": "22404697",
      "street": "LEINSTER AV"
    },
    {
      "usrn": "22405716",
      "street": "LENTON RISE"
    },
    {
      "usrn": "22407103",
      "street": "LEVETT SQUARE"
    },
    {
      "usrn": "21900869",
      "street": "LEWIN RD"
    },
    {
      "usrn": "22404701",
      "street": "LEWIN RD"
    },
    {
      "usrn": "22403622",
      "street": "LEWIS RD"
    },
    {
      "usrn": "22407120",
      "street": "LEXINGTON PLACE"
    },
    {
      "usrn": "22405718",
      "street": "LEYBORNE PRK"
    },
    {
      "usrn": "22401987",
      "street": "LIBRARY MEWS"
    },
    {
      "usrn": "22406385",
      "street": "LIBRARY WAY"
    },
    {
      "usrn": "22403623",
      "street": "LICHFIELD GARDENS"
    },
    {
      "usrn": "22401742",
      "street": "LICHFIELD LANE"
    },
    {
      "usrn": "22405720",
      "street": "LICHFIELD RD"
    },
    {
      "usrn": "22406815",
      "street": "LIFFORDS PLACE"
    },
    {
      "usrn": "22103903",
      "street": "LILIAN RD"
    },
    {
      "usrn": "22404705",
      "street": "LILLIAN RD"
    },
    {
      "usrn": "22403624",
      "street": "LIME GROVE"
    },
    {
      "usrn": "22404709",
      "street": "LIMES AV"
    },
    {
      "usrn": "22404710",
      "street": "LIMES FIELD RD"
    },
    {
      "usrn": "22401623",
      "street": "LINCOLN AV"
    },
    {
      "usrn": "22403625",
      "street": "LINDEN GROVE"
    },
    {
      "usrn": "22400961",
      "street": "LINDEN RD"
    },
    {
      "usrn": "22407044",
      "street": "LINDLEY PLACE"
    },
    {
      "usrn": "22401627",
      "street": "LINDSAY RD"
    },
    {
      "usrn": "22403626",
      "street": "LINDUM RD"
    },
    {
      "usrn": "22401701",
      "street": "LINEAR WALK"
    },
    {
      "usrn": "22403627",
      "street": "LINK WAY"
    },
    {
      "usrn": "22401628",
      "street": "LINKS VIEW RD"
    },
    {
      "usrn": "22403628",
      "street": "LION AV"
    },
    {
      "usrn": "22405726",
      "street": "LION GATE GARDENS"
    },
    {
      "usrn": "22403629",
      "street": "LION RD"
    },
    {
      "usrn": "22401630",
      "street": "LISBON AV"
    },
    {
      "usrn": "22403630",
      "street": "LITTLE FERRY RD"
    },
    {
      "usrn": "22406677",
      "street": "LITTLE GREEN"
    },
    {
      "usrn": "22403631",
      "street": "LITTLE QUEENS RD"
    },
    {
      "usrn": "22404714",
      "street": "LITTLE ST LEONARDS"
    },
    {
      "usrn": "22403633",
      "street": "LOCK RD"
    },
    {
      "usrn": "22403634",
      "street": "LOCKSMEADE RD"
    },
    {
      "usrn": "22406866",
      "street": "LODGE AV"
    },
    {
      "usrn": "22501542",
      "street": "LONDON BRIDGE ST"
    },
    {
      "usrn": "22403635",
      "street": "LONDON RD"
    },
    {
      "usrn": "22406228",
      "street": "LONG WALK"
    },
    {
      "usrn": "22403636",
      "street": "LONGFIELD DRIVE"
    },
    {
      "usrn": "22401632",
      "street": "LONGFORD CLS"
    },
    {
      "usrn": "22401633",
      "street": "LONGFORD RD"
    },
    {
      "usrn": "22405737",
      "street": "LONSDALE MEWS"
    },
    {
      "usrn": "21700934",
      "street": "LONSDALE RD"
    },
    {
      "usrn": "22306048",
      "street": "LONSDALE RD"
    },
    {
      "usrn": "22404716",
      "street": "LONSDALE RD"
    },
    {
      "usrn": "22403637",
      "street": "LORNE RD"
    },
    {
      "usrn": "22903039",
      "street": "LOUISVILLE RD"
    },
    {
      "usrn": "22403638",
      "street": "LOVELL RD"
    },
    {
      "usrn": "22404726",
      "street": "LOWTHER RD"
    },
    {
      "usrn": "22401635",
      "street": "LOXLEY RD"
    },
    {
      "usrn": "22407164",
      "street": "LUTHER MEWS"
    },
    {
      "usrn": "22403642",
      "street": "LUTHER RD"
    },
    {
      "usrn": "22406166",
      "street": "LWR GEORGE ST"
    },
    {
      "usrn": "22403639",
      "street": "LWR GROVE RD"
    },
    {
      "usrn": "21800623",
      "street": "LWR HAM RD"
    },
    {
      "usrn": "22405743",
      "street": "LWR MORTLAKE RD"
    },
    {
      "usrn": "22404723",
      "street": "LWR RICHMOND RD"
    },
    {
      "usrn": "22405744",
      "street": "LWR RICHMOND RD"
    },
    {
      "usrn": "22903046",
      "street": "LWR RICHMOND RD"
    },
    {
      "usrn": "22400970",
      "street": "LWR SUNBURY RD"
    },
    {
      "usrn": "22400390",
      "street": "LWR TEDDINGTON RD"
    },
    {
      "usrn": "22401638",
      "street": "LYNDHURST AV"
    },
    {
      "usrn": "22404734",
      "street": "LYRIC RD"
    },
    {
      "usrn": "22403643",
      "street": "MADDISON CLS"
    },
    {
      "usrn": "22404740",
      "street": "MADRID RD"
    },
    {
      "usrn": "22407157",
      "street": "MAGNA SQUARE"
    },
    {
      "usrn": "22403645",
      "street": "MAGUIRE DRIVE"
    },
    {
      "usrn": "22407060",
      "street": "MAIDS OF HONOUR ROW"
    },
    {
      "usrn": "22401640",
      "street": "MALLARD CLS"
    },
    {
      "usrn": "22406571",
      "street": "MALLARD PLACE"
    },
    {
      "usrn": "22406778",
      "street": "MALTHOUSE PASSAGE"
    },
    {
      "usrn": "22406937",
      "street": "MALTINGS CLS"
    },
    {
      "usrn": "22401643",
      "street": "MALVERN RD"
    },
    {
      "usrn": "22407045",
      "street": "MANNING PLACE"
    },
    {
      "usrn": "22401644",
      "street": "MANOEL RD"
    },
    {
      "usrn": "22401646",
      "street": "MANOR GARDENS"
    },
    {
      "usrn": "22405751",
      "street": "MANOR GARDENS"
    },
    {
      "usrn": "22405753",
      "street": "MANOR GROVE"
    },
    {
      "usrn": "22406681",
      "street": "MANOR PRK"
    },
    {
      "usrn": "22403649",
      "street": "MANOR RD"
    },
    {
      "usrn": "22405756",
      "street": "MANOR RD"
    },
    {
      "usrn": "22406804",
      "street": "MANOR RD"
    },
    {
      "usrn": "22401649",
      "street": "MAPLE CLS"
    },
    {
      "usrn": "22403650",
      "street": "MARBLE HILL CLS"
    },
    {
      "usrn": "22403651",
      "street": "MARBLE HILL GARDENS"
    },
    {
      "usrn": "22403652",
      "street": "MARCH RD"
    },
    {
      "usrn": "22403653",
      "street": "MARCHMONT RD"
    },
    {
      "usrn": "22407128",
      "street": "MARINA PLACE"
    },
    {
      "usrn": "22403654",
      "street": "MARINA WAY"
    },
    {
      "usrn": "22403655",
      "street": "MARINER GARDENS"
    },
    {
      "usrn": "22405763",
      "street": "MARKET RD"
    },
    {
      "usrn": "22401651",
      "street": "MARKHOLE CLS"
    },
    {
      "usrn": "22405764",
      "street": "MARKSBURY AV"
    },
    {
      "usrn": "22401653",
      "street": "MARLBOROUGH RD"
    },
    {
      "usrn": "22403656",
      "street": "MARLBOROUGH RD"
    },
    {
      "usrn": "22401654",
      "street": "MARLINGDENE CLS"
    },
    {
      "usrn": "22403657",
      "street": "MARLOW CRESCENT"
    },
    {
      "usrn": "22403658",
      "street": "MARSH FARM RD"
    },
    {
      "usrn": "22403659",
      "street": "MARSTON RD"
    },
    {
      "usrn": "22402958",
      "street": "MARTINDALE"
    },
    {
      "usrn": "22407136",
      "street": "MARTINEAU DRIVE"
    },
    {
      "usrn": "22403660",
      "street": "MARTINGALES CLS"
    },
    {
      "usrn": "22400985",
      "street": "MARY ROSE CLS"
    },
    {
      "usrn": "22407144",
      "street": "MARYLEBONE GARDENS"
    },
    {
      "usrn": "22406577",
      "street": "MARYS TERR"
    },
    {
      "usrn": "22401656",
      "street": "MASEFIELD RD"
    },
    {
      "usrn": "22400987",
      "street": "MASON CLS"
    },
    {
      "usrn": "22403662",
      "street": "MAY RD"
    },
    {
      "usrn": "22401659",
      "street": "MAYFAIR AV"
    },
    {
      "usrn": "22401660",
      "street": "MAYS RD"
    },
    {
      "usrn": "22405769",
      "street": "MAZE RD"
    },
    {
      "usrn": "22403663",
      "street": "MEAD RD"
    },
    {
      "usrn": "22403664",
      "street": "MEADLANDS DRIVE"
    },
    {
      "usrn": "22401662",
      "street": "MEADOW CLS"
    },
    {
      "usrn": "22403665",
      "street": "MEADOW CLS"
    },
    {
      "usrn": "22407091",
      "street": "MEADOWSIDE"
    },
    {
      "usrn": "22401664",
      "street": "MEADWAY"
    },
    {
      "usrn": "22404763",
      "street": "MEDCROFT GARDENS"
    },
    {
      "usrn": "22403666",
      "street": "MELBOURNE RD"
    },
    {
      "usrn": "22407046",
      "street": "MELLISS AV"
    },
    {
      "usrn": "22401665",
      "street": "MELROSE AV"
    },
    {
      "usrn": "22404769",
      "street": "MELROSE RD"
    },
    {
      "usrn": "22404771",
      "street": "MELVILLE RD"
    },
    {
      "usrn": "22404776",
      "street": "MEREDYTH RD"
    },
    {
      "usrn": "22403667",
      "street": "MEREWAY RD"
    },
    {
      "usrn": "22404778",
      "street": "MERTHYR TERR"
    },
    {
      "usrn": "22403519",
      "street": "MESSOM MEWS"
    },
    {
      "usrn": "22403668",
      "street": "MICHELHAM GARDENS"
    },
    {
      "usrn": "22406167",
      "street": "MICHELS ROW"
    },
    {
      "usrn": "22403669",
      "street": "MIDDLE LANE"
    },
    {
      "usrn": "22401668",
      "street": "MILL FARM CRESCENT"
    },
    {
      "usrn": "22404780",
      "street": "MILL HILL"
    },
    {
      "usrn": "22404781",
      "street": "MILL HILL RD"
    },
    {
      "usrn": "22401669",
      "street": "MILL RD"
    },
    {
      "usrn": "22401672",
      "street": "MILLFIELD RD"
    },
    {
      "usrn": "22401674",
      "street": "MILNER DRIVE"
    },
    {
      "usrn": "22401675",
      "street": "MILTON RD"
    },
    {
      "usrn": "22404788",
      "street": "MILTON RD"
    },
    {
      "usrn": "21800676",
      "street": "MINERVA RD"
    },
    {
      "usrn": "22406802",
      "street": "MODEL COTTAGES"
    },
    {
      "usrn": "22403671",
      "street": "MONMOUTH AV"
    },
    {
      "usrn": "22403672",
      "street": "MONROE DRIVE"
    },
    {
      "usrn": "22403673",
      "street": "MONTAGUE RD"
    },
    {
      "usrn": "22403674",
      "street": "MONTPELIER ROW"
    },
    {
      "usrn": "22401677",
      "street": "MONTROSE AV"
    },
    {
      "usrn": "22403675",
      "street": "MOOR MEAD RD"
    },
    {
      "usrn": "22404795",
      "street": "MOORE CLS"
    },
    {
      "usrn": "22401678",
      "street": "MOORLAND CLS"
    },
    {
      "usrn": "22401679",
      "street": "MORLAND CLS"
    },
    {
      "usrn": "22403677",
      "street": "MORLEY RD"
    },
    {
      "usrn": "22403678",
      "street": "MORNINGTON WALK"
    },
    {
      "usrn": "22401036",
      "street": "MORSHEAD YARD"
    },
    {
      "usrn": "22404798",
      "street": "MORTLAKE HIGH ST"
    },
    {
      "usrn": "22405784",
      "street": "MORTLAKE RD"
    },
    {
      "usrn": "22403679",
      "street": "MOUNT ARARAT RD"
    },
    {
      "usrn": "22406389",
      "street": "MOUNT MEWS"
    },
    {
      "usrn": "22403680",
      "street": "MOWBRAY RD"
    },
    {
      "usrn": "22404800",
      "street": "MUIRDOWN AV"
    },
    {
      "usrn": "22404803",
      "street": "MULLINS PATH"
    },
    {
      "usrn": "22403681",
      "street": "MUNSTER RD"
    },
    {
      "usrn": "21500779",
      "street": "MURRAY AV"
    },
    {
      "usrn": "22403682",
      "street": "MURRAY RD"
    },
    {
      "usrn": "22401684",
      "street": "MYRTLE RD"
    },
    {
      "usrn": "22403683",
      "street": "NAPOLEON RD"
    },
    {
      "usrn": "22404814",
      "street": "NASSAU RD"
    },
    {
      "usrn": "22406936",
      "street": "NATALIE MEWS"
    },
    {
      "usrn": "22406545",
      "street": "NELSON GARDENS"
    },
    {
      "usrn": "22401687",
      "street": "NELSON RD"
    },
    {
      "usrn": "22403684",
      "street": "NETHERTON RD"
    },
    {
      "usrn": "22403685",
      "street": "NEVILLE RD"
    },
    {
      "usrn": "22407010",
      "street": "NEW BROADWAY"
    },
    {
      "usrn": "22406643",
      "street": "NEW KELVIN AV PT OF NATIONAL PHYSICS LABORATORY"
    },
    {
      "usrn": "21000589",
      "street": "NEW KINGS RD"
    },
    {
      "usrn": "22403687",
      "street": "NEW RD"
    },
    {
      "usrn": "22401023",
      "street": "NEWFIELD CLS"
    },
    {
      "usrn": "22404821",
      "street": "NEWPORT RD"
    },
    {
      "usrn": "22403689",
      "street": "NEWRY RD"
    },
    {
      "usrn": "22406140",
      "street": "NICOL CLS"
    },
    {
      "usrn": "22403690",
      "street": "NIGHTINGALE LANE"
    },
    {
      "usrn": "22401693",
      "street": "NIGHTINGALE RD"
    },
    {
      "usrn": "22405798",
      "street": "NITON RD"
    },
    {
      "usrn": "22407146",
      "street": "NOEL SQUARE"
    },
    {
      "usrn": "22403691",
      "street": "NORCUTT RD"
    },
    {
      "usrn": "22403692",
      "street": "NORFOLK CLS"
    },
    {
      "usrn": "22403693",
      "street": "NORMAN AV"
    },
    {
      "usrn": "22403694",
      "street": "NORMANHURST DRIVE"
    },
    {
      "usrn": "22403695",
      "street": "NORMANSFIELD AV"
    },
    {
      "usrn": "22405799",
      "street": "NORTH AV"
    },
    {
      "usrn": "22403696",
      "street": "NORTH LANE"
    },
    {
      "usrn": "22403697",
      "street": "NORTH PLACE"
    },
    {
      "usrn": "22405802",
      "street": "NORTH RD"
    },
    {
      "usrn": "22404835",
      "street": "NORTH WORPLE WAY"
    },
    {
      "usrn": "22403699",
      "street": "NORTHCOTE RD"
    },
    {
      "usrn": "22406602",
      "street": "NORTHUMBERLAND PLACE"
    },
    {
      "usrn": "21800022",
      "street": "NORTHWEALD LANE"
    },
    {
      "usrn": "22406752",
      "street": "NORWOOD CLS"
    },
    {
      "usrn": "22404836",
      "street": "NOWELL RD"
    },
    {
      "usrn": "22407008",
      "street": "NURSERY GARDENS"
    },
    {
      "usrn": "22405811",
      "street": "NYLANDS AV"
    },
    {
      "usrn": "22401699",
      "street": "OAK AV"
    },
    {
      "usrn": "22403700",
      "street": "OAK LANE"
    },
    {
      "usrn": "22406938",
      "street": "OAKHURST CLS"
    },
    {
      "usrn": "22404837",
      "street": "OAKLANDS RD"
    },
    {
      "usrn": "22404840",
      "street": "OBSERVATORY RD"
    },
    {
      "usrn": "22406390",
      "street": "OCCUPATION RD"
    },
    {
      "usrn": "22400445",
      "street": "OLD BAKERY MEWS"
    },
    {
      "usrn": "22400444",
      "street": "OLD BRIDGE ST"
    },
    {
      "usrn": "22405818",
      "street": "OLD DEER PRK GARDENS"
    },
    {
      "usrn": "22405819",
      "street": "OLD DOCK CLS"
    },
    {
      "usrn": "22401702",
      "street": "OLD FARM RD"
    },
    {
      "usrn": "22406931",
      "street": "OLD HOUSE GARDENS"
    },
    {
      "usrn": "22406396",
      "street": "OLD LODGE PLACE"
    },
    {
      "usrn": "22401703",
      "street": "OLD MANOR DRIVE"
    },
    {
      "usrn": "22403701",
      "street": "OLD PALACE LANE"
    },
    {
      "usrn": "22406599",
      "street": "OLD PALACE TERR"
    },
    {
      "usrn": "22403703",
      "street": "OLD PALACE YARD"
    },
    {
      "usrn": "22407078",
      "street": "OLD STATION GARDENS"
    },
    {
      "usrn": "22401035",
      "street": "OLDFIELD RD"
    },
    {
      "usrn": "22403704",
      "street": "ONSLOW AV"
    },
    {
      "usrn": "22403705",
      "street": "ONSLOW RD"
    },
    {
      "usrn": "22401706",
      "street": "ORCHARD RD"
    },
    {
      "usrn": "22403707",
      "street": "ORCHARD RD"
    },
    {
      "usrn": "22405825",
      "street": "ORCHARD RD"
    },
    {
      "usrn": "22403706",
      "street": "ORCHARD RISE"
    },
    {
      "usrn": "22403708",
      "street": "ORFORD GARDENS"
    },
    {
      "usrn": "22406918",
      "street": "ORIEL DRIVE"
    },
    {
      "usrn": "22403709",
      "street": "ORLEANS RD"
    },
    {
      "usrn": "22401039",
      "street": "ORMOND AV"
    },
    {
      "usrn": "22406415",
      "street": "ORMOND AV"
    },
    {
      "usrn": "22401041",
      "street": "ORMOND CRESCENT"
    },
    {
      "usrn": "22401710",
      "street": "ORMOND DRIVE"
    },
    {
      "usrn": "22403710",
      "street": "ORMOND RD"
    },
    {
      "usrn": "22404846",
      "street": "ORMONDE RD"
    },
    {
      "usrn": "22401711",
      "street": "ORPWOOD CLS"
    },
    {
      "usrn": "22401713",
      "street": "OXFORD RD"
    },
    {
      "usrn": "22406796",
      "street": "PAGE CLS"
    },
    {
      "usrn": "22401716",
      "street": "PAGET CLS"
    },
    {
      "usrn": "22405839",
      "street": "PAGODA AV"
    },
    {
      "usrn": "22402993",
      "street": "PALEWELL COMMON DRIVE"
    },
    {
      "usrn": "22404852",
      "street": "PALEWELL PRK"
    },
    {
      "usrn": "22404855",
      "street": "PALMERS RD"
    },
    {
      "usrn": "22403713",
      "street": "PALMERSTON RD"
    },
    {
      "usrn": "22404856",
      "street": "PALMERSTON RD"
    },
    {
      "usrn": "22403714",
      "street": "PARADISE RD"
    },
    {
      "usrn": "22405762",
      "street": "PARISON CLS"
    },
    {
      "usrn": "22404866",
      "street": "PARKE RD"
    },
    {
      "usrn": "22404867",
      "street": "PARKFIELD AV"
    },
    {
      "usrn": "22402997",
      "street": "PARKLANDS CLS"
    },
    {
      "usrn": "21800754",
      "street": "PARKLEYS"
    },
    {
      "usrn": "22403727",
      "street": "PARKLEYS"
    },
    {
      "usrn": "22406758",
      "street": "PARKLEYS PARADE"
    },
    {
      "usrn": "22405848",
      "street": "PARKSHOT"
    },
    {
      "usrn": "22401730",
      "street": "PARKSIDE"
    },
    {
      "usrn": "22104995",
      "street": "PARKWAY"
    },
    {
      "usrn": "22406852",
      "street": "PARLIAMENT MEWS"
    },
    {
      "usrn": "22401732",
      "street": "PARRS PLACE"
    },
    {
      "usrn": "22401733",
      "street": "PARTRIDGE RD"
    },
    {
      "usrn": "22401734",
      "street": "PAULINE CRESCENT"
    },
    {
      "usrn": "22406601",
      "street": "PAVED CT"
    },
    {
      "usrn": "22406645",
      "street": "PAVILION RD"
    },
    {
      "usrn": "22405850",
      "street": "PAXTON CLS"
    },
    {
      "usrn": "22404871",
      "street": "PAYNESFIELD AV"
    },
    {
      "usrn": "22406757",
      "street": "PELDON CT"
    },
    {
      "usrn": "22401735",
      "street": "PEMBRIDGE AV"
    },
    {
      "usrn": "22405585",
      "street": "PEMBROKE GARDENS"
    },
    {
      "usrn": "22406745",
      "street": "PENNY FARTHING MEWS"
    },
    {
      "usrn": "22404877",
      "street": "PENRHYN CRESCENT"
    },
    {
      "usrn": "22405852",
      "street": "PENSFORD AV"
    },
    {
      "usrn": "22403008",
      "street": "PERCIVAL RD"
    },
    {
      "usrn": "22401739",
      "street": "PERCY RD"
    },
    {
      "usrn": "22401740",
      "street": "PERCY RD"
    },
    {
      "usrn": "22403728",
      "street": "PERRYFIELD WAY"
    },
    {
      "usrn": "22406680",
      "street": "PERSEVERANCE PLACE"
    },
    {
      "usrn": "22406641",
      "street": "PETAVEL RD"
    },
    {
      "usrn": "22403731",
      "street": "PETERSHAM CLS"
    },
    {
      "usrn": "22403729",
      "street": "PETERSHAM RD"
    },
    {
      "usrn": "22403730",
      "street": "PETERSHAM RD"
    },
    {
      "usrn": "22403732",
      "street": "PETERSHAM RD"
    },
    {
      "usrn": "22403733",
      "street": "PEVERIL DRIVE"
    },
    {
      "usrn": "22401746",
      "street": "PIGEON LANE"
    },
    {
      "usrn": "22401688",
      "street": "PINE TREE CLS"
    },
    {
      "usrn": "22403480",
      "street": "PINEWOOD GARDENS"
    },
    {
      "usrn": "22407009",
      "street": "PLATTS EYOT"
    },
    {
      "usrn": "22401059",
      "street": "PLEVNA RD"
    },
    {
      "usrn": "22407155",
      "street": "PLOUGH LANE"
    },
    {
      "usrn": "21901100",
      "street": "PLUMMER RD"
    },
    {
      "usrn": "22407137",
      "street": "POMEROY CLS"
    },
    {
      "usrn": "22403734",
      "street": "POND WAY"
    },
    {
      "usrn": "22407129",
      "street": "POOLEY DRIVE"
    },
    {
      "usrn": "22403735",
      "street": "POPES AV"
    },
    {
      "usrn": "22403736",
      "street": "POPES GROVE"
    },
    {
      "usrn": "22406719",
      "street": "POPLAR CT PARADE"
    },
    {
      "usrn": "22407062",
      "street": "PORTLAND TERR"
    },
    {
      "usrn": "22404893",
      "street": "PORTMAN AV"
    },
    {
      "usrn": "22401753",
      "street": "PORTUGAL GARDENS"
    },
    {
      "usrn": "22401754",
      "street": "POST LANE"
    },
    {
      "usrn": "22403737",
      "street": "POULETT GARDENS"
    },
    {
      "usrn": "22401927",
      "street": "POUPARTS PLACE"
    },
    {
      "usrn": "22401755",
      "street": "POWDER MILL LANE"
    },
    {
      "usrn": "22403738",
      "street": "POWERS CT"
    },
    {
      "usrn": "22407185",
      "street": "PRADO PATH"
    },
    {
      "usrn": "22403739",
      "street": "PRESTON CLS"
    },
    {
      "usrn": "22403740",
      "street": "PRESTON PLACE"
    },
    {
      "usrn": "22406143",
      "street": "PRICE WAY"
    },
    {
      "usrn": "22401353",
      "street": "PRIEST CLS"
    },
    {
      "usrn": "22404895",
      "street": "PRIESTS BRIDGE"
    },
    {
      "usrn": "22401756",
      "street": "PRINCES CLS"
    },
    {
      "usrn": "22403741",
      "street": "PRINCES RD"
    },
    {
      "usrn": "22404897",
      "street": "PRINCES RD"
    },
    {
      "usrn": "22405859",
      "street": "PRINCES RD"
    },
    {
      "usrn": "22405860",
      "street": "PRINCES RD"
    },
    {
      "usrn": "22403742",
      "street": "PRINCES ST"
    },
    {
      "usrn": "22403475",
      "street": "PRINTERS MEWS"
    },
    {
      "usrn": "22401064",
      "street": "PRIORY CLS"
    },
    {
      "usrn": "22401065",
      "street": "PRIORY GARDENS"
    },
    {
      "usrn": "22404899",
      "street": "PRIORY GARDENS"
    },
    {
      "usrn": "22401761",
      "street": "PRIORY RD"
    },
    {
      "usrn": "22405861",
      "street": "PRIORY RD"
    },
    {
      "usrn": "21500852",
      "street": "PRK AV"
    },
    {
      "usrn": "22404859",
      "street": "PRK AV"
    },
    {
      "usrn": "22401046",
      "street": "PRK CLS"
    },
    {
      "usrn": "22401719",
      "street": "PRK CRESCENT"
    },
    {
      "usrn": "22404861",
      "street": "PRK DRIVE"
    },
    {
      "usrn": "22402996",
      "street": "PRK GATE GARDENS"
    },
    {
      "usrn": "22403717",
      "street": "PRK HILL"
    },
    {
      "usrn": "22403718",
      "street": "PRK HOUSE GARDENS"
    },
    {
      "usrn": "22403719",
      "street": "PRK LANE"
    },
    {
      "usrn": "22405842",
      "street": "PRK LANE"
    },
    {
      "usrn": "22401720",
      "street": "PRK PLACE"
    },
    {
      "usrn": "21880043",
      "street": "PRK RD"
    },
    {
      "usrn": "22400459",
      "street": "PRK RD"
    },
    {
      "usrn": "22401724",
      "street": "PRK RD"
    },
    {
      "usrn": "22403720",
      "street": "PRK RD"
    },
    {
      "usrn": "22403721",
      "street": "PRK RD"
    },
    {
      "usrn": "22403722",
      "street": "PRK RD"
    },
    {
      "usrn": "22403724",
      "street": "PRK ST"
    },
    {
      "usrn": "22401764",
      "street": "PROSPECT CRESCENT"
    },
    {
      "usrn": "22403954",
      "street": "PULSFORD CLS"
    },
    {
      "usrn": "22403745",
      "street": "PYRLAND RD"
    },
    {
      "usrn": "22405864",
      "street": "QUADRANT RD"
    },
    {
      "usrn": "22401765",
      "street": "QUEEN ANNES CLS"
    },
    {
      "usrn": "22404921",
      "street": "QUEEN ELIZABETH WALK"
    },
    {
      "usrn": "22403752",
      "street": "QUEENS CRESCENT"
    },
    {
      "usrn": "20035620",
      "street": "QUEENS RD"
    },
    {
      "usrn": "22401767",
      "street": "QUEENS RD"
    },
    {
      "usrn": "22403748",
      "street": "QUEENS RD"
    },
    {
      "usrn": "22403749",
      "street": "QUEENS RD"
    },
    {
      "usrn": "22404925",
      "street": "QUEENS RD"
    },
    {
      "usrn": "22405868",
      "street": "QUEENS RD"
    },
    {
      "usrn": "22502028",
      "street": "QUEENS RD"
    },
    {
      "usrn": "31900099",
      "street": "QUEENS RD"
    },
    {
      "usrn": "22406685",
      "street": "QUEENS RIDE"
    },
    {
      "usrn": "22403747",
      "street": "QUEENS RISE"
    },
    {
      "usrn": "22401772",
      "street": "QUEENSWOOD AV"
    },
    {
      "usrn": "22406108",
      "street": "RADCLIFFE MEWS"
    },
    {
      "usrn": "22403754",
      "street": "RADNOR GARDENS"
    },
    {
      "usrn": "22403755",
      "street": "RADNOR RD"
    },
    {
      "usrn": "22406132",
      "street": "RAEBURN CLS"
    },
    {
      "usrn": "22405871",
      "street": "RAILSHEAD RD"
    },
    {
      "usrn": "22403757",
      "street": "RAILWAY APPROACH"
    },
    {
      "usrn": "22406243",
      "street": "RAILWAY PASSAGE"
    },
    {
      "usrn": "22403758",
      "street": "RAILWAY RD"
    },
    {
      "usrn": "22404932",
      "street": "RAILWAY SIDE"
    },
    {
      "usrn": "22405872",
      "street": "RALEIGH RD"
    },
    {
      "usrn": "22403759",
      "street": "RANDLE RD"
    },
    {
      "usrn": "21000670",
      "street": "RANELAGH AV"
    },
    {
      "usrn": "22404936",
      "street": "RANELAGH AV"
    },
    {
      "usrn": "22405873",
      "street": "RANELAGH DRIVE"
    },
    {
      "usrn": "22403762",
      "street": "RAVENSBOURNE RD"
    },
    {
      "usrn": "22406638",
      "street": "RAYLEIGH AV PT OF NATIONAL PHYSICS LARORATORY"
    },
    {
      "usrn": "22401778",
      "street": "RECTORY GROVE"
    },
    {
      "usrn": "22404952",
      "street": "RECTORY RD"
    },
    {
      "usrn": "22403764",
      "street": "RED LION ST"
    },
    {
      "usrn": "22401779",
      "street": "REDFERN AV"
    },
    {
      "usrn": "22401780",
      "street": "REDWAY DRIVE"
    },
    {
      "usrn": "22401781",
      "street": "REGENCY CLS"
    },
    {
      "usrn": "22406853",
      "street": "REGENCY WALK"
    },
    {
      "usrn": "22403766",
      "street": "RETREAT RD"
    },
    {
      "usrn": "22403767",
      "street": "REYNOLDS PLACE"
    },
    {
      "usrn": "22406561",
      "street": "RICHMOND BRIDGE"
    },
    {
      "usrn": "22403768",
      "street": "RICHMOND HILL"
    },
    {
      "usrn": "22406116",
      "street": "RICHMOND HILL CT"
    },
    {
      "usrn": "22406157",
      "street": "RICHMOND MEWS"
    },
    {
      "usrn": "22407092",
      "street": "RICHMOND PARADE"
    },
    {
      "usrn": "22407019",
      "street": "RICHMOND PRK"
    },
    {
      "usrn": "22407048",
      "street": "RICHMOND PRK"
    },
    {
      "usrn": "22403043",
      "street": "RICHMOND PRK RD"
    },
    {
      "usrn": "21500937",
      "street": "RICHMOND RD"
    },
    {
      "usrn": "21800806",
      "street": "RICHMOND RD"
    },
    {
      "usrn": "22403771",
      "street": "RICHMOND RD"
    },
    {
      "usrn": "22406817",
      "street": "RICHMOND RD"
    },
    {
      "usrn": "31900956",
      "street": "RICHMOND RD"
    },
    {
      "usrn": "22401783",
      "street": "RINGWOOD WAY"
    },
    {
      "usrn": "22404963",
      "street": "RIPLEY GARDENS"
    },
    {
      "usrn": "22401784",
      "street": "RIPLEY RD"
    },
    {
      "usrn": "22403772",
      "street": "RIVER LANE"
    },
    {
      "usrn": "22403773",
      "street": "RIVER REACH"
    },
    {
      "usrn": "13703662",
      "street": "RIVER THAMES MOLESEY"
    },
    {
      "usrn": "22401787",
      "street": "RIVER WAY"
    },
    {
      "usrn": "22403775",
      "street": "RIVERDALE GARDENS"
    },
    {
      "usrn": "22403776",
      "street": "RIVERDALE RD"
    },
    {
      "usrn": "22403777",
      "street": "RIVERMEAD CLS"
    },
    {
      "usrn": "22401786",
      "street": "RIVERMEADS AV"
    },
    {
      "usrn": "22403778",
      "street": "RIVERSIDE"
    },
    {
      "usrn": "22406657",
      "street": "RIVERSIDE"
    },
    {
      "usrn": "22407112",
      "street": "RIVERSIDE"
    },
    {
      "usrn": "22403779",
      "street": "RIVERSIDE DRIVE"
    },
    {
      "usrn": "22403774",
      "street": "RIVERVIEW GARDENS"
    },
    {
      "usrn": "22404968",
      "street": "RIVERVIEW GARDENS"
    },
    {
      "usrn": "22401789",
      "street": "ROBIN CLS"
    },
    {
      "usrn": "22404969",
      "street": "ROCK AV"
    },
    {
      "usrn": "22404973",
      "street": "ROCKS LANE"
    },
    {
      "usrn": "22401791",
      "street": "RODNEY RD"
    },
    {
      "usrn": "22403780",
      "street": "ROSEBANK CLS"
    },
    {
      "usrn": "22401798",
      "street": "ROSEBINE AV"
    },
    {
      "usrn": "22401799",
      "street": "ROSECROFT GARDENS"
    },
    {
      "usrn": "22405896",
      "street": "ROSEDALE RD"
    },
    {
      "usrn": "22401082",
      "street": "ROSEHILL"
    },
    {
      "usrn": "22403782",
      "street": "ROSELEIGH CLS"
    },
    {
      "usrn": "22406394",
      "street": "ROSEMARY GARDENS"
    },
    {
      "usrn": "22404980",
      "street": "ROSEMARY LANE"
    },
    {
      "usrn": "22403783",
      "street": "ROSEMONT RD"
    },
    {
      "usrn": "22407169",
      "street": "ROSETREE PLACE"
    },
    {
      "usrn": "22401802",
      "street": "ROSS RD"
    },
    {
      "usrn": "22404983",
      "street": "ROSSLYN AV"
    },
    {
      "usrn": "22403785",
      "street": "ROSSLYN RD"
    },
    {
      "usrn": "22405899",
      "street": "ROTHESAY AV"
    },
    {
      "usrn": "22403786",
      "street": "ROWNTREE RD"
    },
    {
      "usrn": "22401805",
      "street": "ROY GROVE"
    },
    {
      "usrn": "22407049",
      "street": "ROYAL BOTANIC GARDENS"
    },
    {
      "usrn": "22407003",
      "street": "ROYAL MEWS"
    },
    {
      "usrn": "22407156",
      "street": "ROYAL OAK MEWS"
    },
    {
      "usrn": "22407050",
      "street": "ROYAL PARADE"
    },
    {
      "usrn": "22401806",
      "street": "ROYAL RD"
    },
    {
      "usrn": "22403788",
      "street": "ROYSTON RD"
    },
    {
      "usrn": "22403789",
      "street": "RUGBY RD"
    },
    {
      "usrn": "22401807",
      "street": "RUMSEY CLS"
    },
    {
      "usrn": "22401808",
      "street": "RUNNYMEDE CLS"
    },
    {
      "usrn": "22401809",
      "street": "RUNNYMEDE GARDENS"
    },
    {
      "usrn": "22401810",
      "street": "RUNNYMEDE RD"
    },
    {
      "usrn": "22403790",
      "street": "RUSHMEAD"
    },
    {
      "usrn": "22405903",
      "street": "RUSKIN AV"
    },
    {
      "usrn": "22403791",
      "street": "RUSSELL GARDENS"
    },
    {
      "usrn": "22403792",
      "street": "RUSSELL RD"
    },
    {
      "usrn": "22406689",
      "street": "RUSSELL WALK"
    },
    {
      "usrn": "22405000",
      "street": "RUTLAND CLS"
    },
    {
      "usrn": "22403793",
      "street": "RUTLAND DRIVE"
    },
    {
      "usrn": "22401812",
      "street": "RUTLAND RD"
    },
    {
      "usrn": "22401813",
      "street": "RYDAL GARDENS"
    },
    {
      "usrn": "22403794",
      "street": "RYDE PLACE"
    },
    {
      "usrn": "22401814",
      "street": "RYECROFT AV"
    },
    {
      "usrn": "22406945",
      "street": "SADDLERS MEWS"
    },
    {
      "usrn": "13701232",
      "street": "SADLERS RIDE"
    },
    {
      "usrn": "22407026",
      "street": "SALAMANDER QUAY"
    },
    {
      "usrn": "22405907",
      "street": "SALISBURY RD"
    },
    {
      "usrn": "22401818",
      "street": "SANDERS CLS"
    },
    {
      "usrn": "22403795",
      "street": "SANDPITS RD"
    },
    {
      "usrn": "22407101",
      "street": "SANDRINGHAM MEWS"
    },
    {
      "usrn": "22400515",
      "street": "SANDY LANE"
    },
    {
      "usrn": "22403796",
      "street": "SANDY LANE"
    },
    {
      "usrn": "22403797",
      "street": "SANDY LANE"
    },
    {
      "usrn": "22405908",
      "street": "SANDYCOMBE RD"
    },
    {
      "usrn": "22403798",
      "street": "SANDYCOOMBE RD"
    },
    {
      "usrn": "22403799",
      "street": "SAVILLE RD"
    },
    {
      "usrn": "22406875",
      "street": "SAWYERS HILL"
    },
    {
      "usrn": "22407063",
      "street": "SAYERS WALK"
    },
    {
      "usrn": "22405011",
      "street": "SCARTH RD"
    },
    {
      "usrn": "22403801",
      "street": "SCHOOL HOUSE LANE"
    },
    {
      "usrn": "22400519",
      "street": "SCHOOL LANE"
    },
    {
      "usrn": "22400520",
      "street": "SCHOOL RD"
    },
    {
      "usrn": "22401822",
      "street": "SCHOOL RD"
    },
    {
      "usrn": "22401823",
      "street": "SCHOOL RD AV"
    },
    {
      "usrn": "22401928",
      "street": "SCHURLOCK PLACE"
    },
    {
      "usrn": "22401824",
      "street": "SCOTTS DRIVE"
    },
    {
      "usrn": "22401825",
      "street": "SEATON CLS"
    },
    {
      "usrn": "22401826",
      "street": "SEATON RD"
    },
    {
      "usrn": "22405013",
      "street": "SECOND AV"
    },
    {
      "usrn": "22403802",
      "street": "SECOND CROSS RD"
    },
    {
      "usrn": "22401829",
      "street": "SELKIRK RD"
    },
    {
      "usrn": "22405910",
      "street": "SELWYN AV"
    },
    {
      "usrn": "22403803",
      "street": "SEYMOUR GARDENS"
    },
    {
      "usrn": "22400527",
      "street": "SEYMOUR RD"
    },
    {
      "usrn": "22401831",
      "street": "SEYMOUR RD"
    },
    {
      "usrn": "22403804",
      "street": "SHACKLEGATE LANE"
    },
    {
      "usrn": "22406609",
      "street": "SHAEF WAY"
    },
    {
      "usrn": "22405912",
      "street": "SHAFTESBURY RD"
    },
    {
      "usrn": "22401833",
      "street": "SHAFTESBURY WAY"
    },
    {
      "usrn": "22405913",
      "street": "SHALSTONE RD"
    },
    {
      "usrn": "22407029",
      "street": "SHEEN COMMON"
    },
    {
      "usrn": "22403807",
      "street": "SHEEN COMMON DRIVE"
    },
    {
      "usrn": "22405915",
      "street": "SHEEN CT RD"
    },
    {
      "usrn": "22405018",
      "street": "SHEEN GATE GARDENS"
    },
    {
      "usrn": "22405019",
      "street": "SHEEN LANE"
    },
    {
      "usrn": "22405020",
      "street": "SHEEN LANE"
    },
    {
      "usrn": "22405916",
      "street": "SHEEN PRK"
    },
    {
      "usrn": "22405917",
      "street": "SHEEN RD"
    },
    {
      "usrn": "22403077",
      "street": "SHEEN WOOD"
    },
    {
      "usrn": "22405918",
      "street": "SHEENDALE RD"
    },
    {
      "usrn": "22406246",
      "street": "SHEENGATE MANSIONS PASSAGE"
    },
    {
      "usrn": "22407015",
      "street": "SHELBURNE DRIVE"
    },
    {
      "usrn": "22401104",
      "street": "SHERIDAN PLACE"
    },
    {
      "usrn": "22406865",
      "street": "SHERIDAN PLACE"
    },
    {
      "usrn": "22403809",
      "street": "SHERIDAN RD"
    },
    {
      "usrn": "22401837",
      "street": "SHERINGHAM AV"
    },
    {
      "usrn": "22403811",
      "street": "SHERLAND RD"
    },
    {
      "usrn": "22406377",
      "street": "SHERWOOD CLS"
    },
    {
      "usrn": "22401839",
      "street": "SHERWOOD RD"
    },
    {
      "usrn": "22405025",
      "street": "SHIP LANE"
    },
    {
      "usrn": "22406932",
      "street": "SHIRE MEWS"
    },
    {
      "usrn": "22401842",
      "street": "SHORE CLS"
    },
    {
      "usrn": "22401845",
      "street": "SHORT WAY"
    },
    {
      "usrn": "22405030",
      "street": "SHOTTFIELD AV"
    },
    {
      "usrn": "22405031",
      "street": "SHREWSBURY AV"
    },
    {
      "usrn": "22403814",
      "street": "SIDNEY RD"
    },
    {
      "usrn": "22403647",
      "street": "SILVER BIRCHES CLS"
    },
    {
      "usrn": "22401846",
      "street": "SIMPSON RD"
    },
    {
      "usrn": "22403815",
      "street": "SIMPSON RD"
    },
    {
      "usrn": "22403816",
      "street": "SION RD"
    },
    {
      "usrn": "22401847",
      "street": "SIXTH CROSS RD"
    },
    {
      "usrn": "21700496",
      "street": "SLOANE SQUARE"
    },
    {
      "usrn": "22401849",
      "street": "SNOWDROP CLS"
    },
    {
      "usrn": "22403817",
      "street": "SOMERSET GARDENS"
    },
    {
      "usrn": "22403818",
      "street": "SOMERSET RD"
    },
    {
      "usrn": "22405927",
      "street": "SOMERTON AV"
    },
    {
      "usrn": "22406920",
      "street": "SOMERVILLE AV"
    },
    {
      "usrn": "22401850",
      "street": "SONNING GARDENS"
    },
    {
      "usrn": "21800865",
      "street": "SOPWITH CLS"
    },
    {
      "usrn": "22405928",
      "street": "SOUTH AV"
    },
    {
      "usrn": "22401851",
      "street": "SOUTH CLS"
    },
    {
      "usrn": "21501029",
      "street": "SOUTH RD"
    },
    {
      "usrn": "22401853",
      "street": "SOUTH RD"
    },
    {
      "usrn": "22401854",
      "street": "SOUTH RD"
    },
    {
      "usrn": "22403820",
      "street": "SOUTH WESTERN RD"
    },
    {
      "usrn": "22405046",
      "street": "SOUTH WORPLE AV"
    },
    {
      "usrn": "22405047",
      "street": "SOUTH WORPLE WAY"
    },
    {
      "usrn": "22407172",
      "street": "SOUTHCOTT RD"
    },
    {
      "usrn": "22403821",
      "street": "SOUTHFIELD GARDENS"
    },
    {
      "usrn": "22407149",
      "street": "SOUTHMEAD GARDENS"
    },
    {
      "usrn": "22401859",
      "street": "SPARKS CLS"
    },
    {
      "usrn": "22401860",
      "street": "SPARROW CLS"
    },
    {
      "usrn": "22403094",
      "street": "SPENCER GARDENS"
    },
    {
      "usrn": "22403822",
      "street": "SPENCER RD"
    },
    {
      "usrn": "22401113",
      "street": "SPRING GROVE"
    },
    {
      "usrn": "22403823",
      "street": "SPRING GROVE RD"
    },
    {
      "usrn": "22407052",
      "street": "SPRING MEWS"
    },
    {
      "usrn": "21000747",
      "street": "SPRING VALE TERR"
    },
    {
      "usrn": "22401863",
      "street": "SPRINGFIELD AV"
    },
    {
      "usrn": "22401864",
      "street": "SPRINGFIELD RD"
    },
    {
      "usrn": "22403824",
      "street": "SPRINGFIELD RD"
    },
    {
      "usrn": "22403826",
      "street": "ST ALBANS GARDENS"
    },
    {
      "usrn": "22406244",
      "street": "ST ANNS PASSAGE"
    },
    {
      "usrn": "22406109",
      "street": "ST ANNS RD"
    },
    {
      "usrn": "8401225",
      "street": "ST ANNS ST"
    },
    {
      "usrn": "22406917",
      "street": "ST EDMUNDS SQUARE"
    },
    {
      "usrn": "22406769",
      "street": "ST GEORGES PLACE"
    },
    {
      "usrn": "22403829",
      "street": "ST GEORGES RD"
    },
    {
      "usrn": "22405942",
      "street": "ST GEORGES RD"
    },
    {
      "usrn": "22405064",
      "street": "ST HILDAS RD"
    },
    {
      "usrn": "22403831",
      "street": "ST JAMES COTTAGES"
    },
    {
      "usrn": "22401873",
      "street": "ST JAMESS AV"
    },
    {
      "usrn": "22401874",
      "street": "ST JAMESS RD"
    },
    {
      "usrn": "22405066",
      "street": "ST JOHNS GROVE"
    },
    {
      "usrn": "22405944",
      "street": "ST JOHNS GROVE"
    },
    {
      "usrn": "22400556",
      "street": "ST JOHNS RD"
    },
    {
      "usrn": "22405946",
      "street": "ST JOHNS RD"
    },
    {
      "usrn": "20601603",
      "street": "ST LEONARDS RD"
    },
    {
      "usrn": "22405067",
      "street": "ST LEONARDS RD"
    },
    {
      "usrn": "22701140",
      "street": "ST LEONARDS RD"
    },
    {
      "usrn": "22701141",
      "street": "ST LEONARDS ST"
    },
    {
      "usrn": "22403832",
      "street": "ST MARGARETS DRIVE"
    },
    {
      "usrn": "22403833",
      "street": "ST MARGARETS GROVE"
    },
    {
      "usrn": "22405949",
      "street": "ST MARGARETS RD"
    },
    {
      "usrn": "22403835",
      "street": "ST MARKS RD"
    },
    {
      "usrn": "22403836",
      "street": "ST MARYS AV"
    },
    {
      "usrn": "22405070",
      "street": "ST MARYS GROVE"
    },
    {
      "usrn": "22405954",
      "street": "ST MARYS GROVE"
    },
    {
      "usrn": "22406820",
      "street": "ST MARYS MEWS"
    },
    {
      "usrn": "22405961",
      "street": "ST PAULS RD"
    },
    {
      "usrn": "22403837",
      "street": "ST PETERS RD"
    },
    {
      "usrn": "22403838",
      "street": "ST STEPHENS GARDENS"
    },
    {
      "usrn": "22401877",
      "street": "ST VINCENT RD"
    },
    {
      "usrn": "22403839",
      "street": "ST WINIFREDS RD"
    },
    {
      "usrn": "22407133",
      "street": "STABLE MEWS"
    },
    {
      "usrn": "22407160",
      "street": "STABLEYARD MEWS"
    },
    {
      "usrn": "22406570",
      "street": "STAINES RD"
    },
    {
      "usrn": "37200859",
      "street": "STAINES RD EAST"
    },
    {
      "usrn": "22401881",
      "street": "STANBOROUGH CLS"
    },
    {
      "usrn": "22401882",
      "street": "STANFORD CLS"
    },
    {
      "usrn": "22403842",
      "street": "STANLEY GARDENS RD"
    },
    {
      "usrn": "22401883",
      "street": "STANLEY RD"
    },
    {
      "usrn": "22403843",
      "street": "STANLEY RD"
    },
    {
      "usrn": "22405963",
      "street": "STANLEY RD"
    },
    {
      "usrn": "22405966",
      "street": "STANMORE GARDENS"
    },
    {
      "usrn": "22405967",
      "street": "STANMORE RD"
    },
    {
      "usrn": "22406636",
      "street": "STANTON AV"
    },
    {
      "usrn": "22405091",
      "street": "STANTON RD"
    },
    {
      "usrn": "22406789",
      "street": "STARLING WALK"
    },
    {
      "usrn": "22403846",
      "street": "STATEN GARDENS"
    },
    {
      "usrn": "22401128",
      "street": "STATION APPROACH"
    },
    {
      "usrn": "22405968",
      "street": "STATION APPROACH"
    },
    {
      "usrn": "22407111",
      "street": "STATION APPROACH"
    },
    {
      "usrn": "22406750",
      "street": "STATION AV"
    },
    {
      "usrn": "22401130",
      "street": "STATION CLS"
    },
    {
      "usrn": "22405969",
      "street": "STATION PARADE"
    },
    {
      "usrn": "20704778",
      "street": "STATION RD"
    },
    {
      "usrn": "22400571",
      "street": "STATION RD"
    },
    {
      "usrn": "22401132",
      "street": "STATION RD"
    },
    {
      "usrn": "22403847",
      "street": "STATION RD"
    },
    {
      "usrn": "22403848",
      "street": "STATION RD"
    },
    {
      "usrn": "22405098",
      "street": "STATION RD"
    },
    {
      "usrn": "22403849",
      "street": "STATION YARD"
    },
    {
      "usrn": "22401888",
      "street": "STEPHENSON RD"
    },
    {
      "usrn": "22401889",
      "street": "STEVENS CLS"
    },
    {
      "usrn": "22401890",
      "street": "STEWART CLS"
    },
    {
      "usrn": "22405109",
      "street": "STILLINGFLEET RD"
    },
    {
      "usrn": "22401891",
      "street": "STIRLING RD"
    },
    {
      "usrn": "22407182",
      "street": "STOKES MEWS"
    },
    {
      "usrn": "22403113",
      "street": "STONEHILL CLS"
    },
    {
      "usrn": "22403114",
      "street": "STONEHILL RD"
    },
    {
      "usrn": "21000790",
      "street": "STONOR RD"
    },
    {
      "usrn": "22403851",
      "street": "STRAFFORD RD"
    },
    {
      "usrn": "22407126",
      "street": "STRAND DRIVE"
    },
    {
      "usrn": "22401893",
      "street": "STRATHEARN AV"
    },
    {
      "usrn": "22403852",
      "street": "STRATHMORE RD"
    },
    {
      "usrn": "22403853",
      "street": "STRAWBERRY HILL CLS"
    },
    {
      "usrn": "22406250",
      "street": "STRAWBERRY HILL FOOTPATH"
    },
    {
      "usrn": "22403854",
      "street": "STRAWBERRY HILL RD"
    },
    {
      "usrn": "22403855",
      "street": "STRAWBERRY VALE"
    },
    {
      "usrn": "22406792",
      "street": "STRAWBERRY VALE FOOTPATH"
    },
    {
      "usrn": "22403856",
      "street": "STRETTON RD"
    },
    {
      "usrn": "22403857",
      "street": "STUART GROVE"
    },
    {
      "usrn": "22403858",
      "street": "STUART RD"
    },
    {
      "usrn": "22403860",
      "street": "SUDBROOK GARDENS"
    },
    {
      "usrn": "22403861",
      "street": "SUDBROOK LANE"
    },
    {
      "usrn": "22405121",
      "street": "SUFFOLK RD"
    },
    {
      "usrn": "21501326",
      "street": "SUMMERWOOD RD"
    },
    {
      "usrn": "22406252",
      "street": "SUN ALLEY"
    },
    {
      "usrn": "22403120",
      "street": "SUNBURY AV"
    },
    {
      "usrn": "22406253",
      "street": "SUNBURY AV PASSAGE"
    },
    {
      "usrn": "22401897",
      "street": "SUNNYSIDE RD"
    },
    {
      "usrn": "22403863",
      "street": "SUSSEX CLS"
    },
    {
      "usrn": "22405128",
      "street": "SUTHERLAND GARDENS"
    },
    {
      "usrn": "22403864",
      "street": "SUTHERLAND GROVE"
    },
    {
      "usrn": "22407093",
      "street": "SWAN ISLAND"
    },
    {
      "usrn": "22405134",
      "street": "SWAN PLACE"
    },
    {
      "usrn": "22403865",
      "street": "SYCAMORE WAY"
    },
    {
      "usrn": "22403866",
      "street": "SYDNEY RD"
    },
    {
      "usrn": "22405985",
      "street": "SYDNEY RD"
    },
    {
      "usrn": "22407011",
      "street": "TAGGS ISLAND"
    },
    {
      "usrn": "22407177",
      "street": "TALBOT RD"
    },
    {
      "usrn": "22403868",
      "street": "TALMA GARDENS"
    },
    {
      "usrn": "22405991",
      "street": "TANGIER RD"
    },
    {
      "usrn": "22401907",
      "street": "TANGLEY PRK RD"
    },
    {
      "usrn": "22403870",
      "street": "TAYBEN AV"
    },
    {
      "usrn": "22405992",
      "street": "TAYLOR AV"
    },
    {
      "usrn": "22401909",
      "street": "TAYLOR CLS"
    },
    {
      "usrn": "22407074",
      "street": "TEDDINGTON LOCK"
    },
    {
      "usrn": "22403871",
      "street": "TEDDINGTON PRK"
    },
    {
      "usrn": "22403872",
      "street": "TEDDINGTON PRK RD"
    },
    {
      "usrn": "22401911",
      "street": "TELFORD RD"
    },
    {
      "usrn": "22401912",
      "street": "TEMPLAR PLACE"
    },
    {
      "usrn": "22405996",
      "street": "TEMPLE RD"
    },
    {
      "usrn": "22405144",
      "street": "TEMPLE SHEEN"
    },
    {
      "usrn": "22405997",
      "street": "TEMPLE SHEEN RD"
    },
    {
      "usrn": "22403873",
      "street": "TENNYSON AV"
    },
    {
      "usrn": "22405147",
      "street": "TERR GARDENS"
    },
    {
      "usrn": "22403874",
      "street": "TERR LANE"
    },
    {
      "usrn": "22407053",
      "street": "TERSHA ST"
    },
    {
      "usrn": "22405148",
      "street": "THAMES BANK"
    },
    {
      "usrn": "22401156",
      "street": "THAMES CLS"
    },
    {
      "usrn": "22401160",
      "street": "THAMES ST"
    },
    {
      "usrn": "22403875",
      "street": "THAMESGATE CLS"
    },
    {
      "usrn": "22403876",
      "street": "THAMESIDE"
    },
    {
      "usrn": "22401917",
      "street": "THE AV"
    },
    {
      "usrn": "22405999",
      "street": "THE AV"
    },
    {
      "usrn": "22406605",
      "street": "THE AV"
    },
    {
      "usrn": "22403878",
      "street": "THE BARONS"
    },
    {
      "usrn": "22406371",
      "street": "THE BROADWAY"
    },
    {
      "usrn": "22405153",
      "street": "THE BYEWAY"
    },
    {
      "usrn": "22403879",
      "street": "THE CAUSEWAY"
    },
    {
      "usrn": "22403880",
      "street": "THE CEDARS"
    },
    {
      "usrn": "22406001",
      "street": "THE CLS"
    },
    {
      "usrn": "22405154",
      "street": "THE CRESCENT"
    },
    {
      "usrn": "22405155",
      "street": "THE ELMS"
    },
    {
      "usrn": "22403881",
      "street": "THE EMBANKMENT"
    },
    {
      "usrn": "22401923",
      "street": "THE GARTH"
    },
    {
      "usrn": "22403882",
      "street": "THE GREEN"
    },
    {
      "usrn": "22406188",
      "street": "THE GREEN"
    },
    {
      "usrn": "22407030",
      "street": "THE GREEN"
    },
    {
      "usrn": "31900180",
      "street": "THE GREEN"
    },
    {
      "usrn": "31900708",
      "street": "THE GREEN"
    },
    {
      "usrn": "22403884",
      "street": "THE GROVE"
    },
    {
      "usrn": "22406005",
      "street": "THE HAVEN"
    },
    {
      "usrn": "22403885",
      "street": "THE HERMITAGE"
    },
    {
      "usrn": "22405156",
      "street": "THE HERMITAGE"
    },
    {
      "usrn": "22407162",
      "street": "THE HOLLIES"
    },
    {
      "usrn": "22403142",
      "street": "THE MALL"
    },
    {
      "usrn": "22403888",
      "street": "THE ORANGERY"
    },
    {
      "usrn": "22407096",
      "street": "THE PARADE"
    },
    {
      "usrn": "22406603",
      "street": "THE PASSAGE"
    },
    {
      "usrn": "22407118",
      "street": "THE POLEHAMPTONS"
    },
    {
      "usrn": "21590226",
      "street": "THE PROMENADE"
    },
    {
      "usrn": "22406165",
      "street": "THE QUADRANT"
    },
    {
      "usrn": "22405163",
      "street": "THE RETREAT"
    },
    {
      "usrn": "22401926",
      "street": "THE RIDGE"
    },
    {
      "usrn": "22403890",
      "street": "THE SHIRES"
    },
    {
      "usrn": "20704838",
      "street": "THE SPINNEY"
    },
    {
      "usrn": "22403891",
      "street": "THE SQUARE"
    },
    {
      "usrn": "22405165",
      "street": "THE TERR"
    },
    {
      "usrn": "22403892",
      "street": "THE VINEYARD"
    },
    {
      "usrn": "22403893",
      "street": "THE WARDROBE"
    },
    {
      "usrn": "22401929",
      "street": "THE WILDERNESS"
    },
    {
      "usrn": "22403894",
      "street": "THELMA GROVE"
    },
    {
      "usrn": "22407125",
      "street": "THETIS TERR"
    },
    {
      "usrn": "22401930",
      "street": "THIRD CROSS RD"
    },
    {
      "usrn": "22406011",
      "street": "THOMPSON AV"
    },
    {
      "usrn": "22406667",
      "street": "THORNE PASSAGE"
    },
    {
      "usrn": "22405167",
      "street": "THORNE ST"
    },
    {
      "usrn": "22405172",
      "street": "THORNTON RD"
    },
    {
      "usrn": "22403897",
      "street": "TIDEWAY CLS"
    },
    {
      "usrn": "22106300",
      "street": "TOLVERNE RD"
    },
    {
      "usrn": "22406783",
      "street": "TOPIARY SQUARE"
    },
    {
      "usrn": "22403898",
      "street": "TOWER RD"
    },
    {
      "usrn": "22406019",
      "street": "TOWER RISE"
    },
    {
      "usrn": "22403899",
      "street": "TOWERS PLACE"
    },
    {
      "usrn": "22406022",
      "street": "TOWNMEAD RD"
    },
    {
      "usrn": "22406023",
      "street": "TOWNSHEND RD"
    },
    {
      "usrn": "22406024",
      "street": "TOWNSHEND TERR"
    },
    {
      "usrn": "22106318",
      "street": "TOYNBEE RD"
    },
    {
      "usrn": "22401932",
      "street": "TRAFALGAR RD"
    },
    {
      "usrn": "22401933",
      "street": "TRANMERE RD"
    },
    {
      "usrn": "22403900",
      "street": "TREE CLS"
    },
    {
      "usrn": "22405178",
      "street": "TREEN AV"
    },
    {
      "usrn": "22405179",
      "street": "TREHERN RD"
    },
    {
      "usrn": "22406401",
      "street": "TREHERNE LODGE SERVICE RD"
    },
    {
      "usrn": "21901398",
      "street": "TREMADOC RD"
    },
    {
      "usrn": "22406854",
      "street": "TREMATON PLACE"
    },
    {
      "usrn": "22407075",
      "street": "TRINDER MEWS"
    },
    {
      "usrn": "22406258",
      "street": "TRINITY CHURCH PASSAGE"
    },
    {
      "usrn": "22405181",
      "street": "TRINITY CHURCH RD"
    },
    {
      "usrn": "22406259",
      "street": "TRINITY COTTAGES"
    },
    {
      "usrn": "22406028",
      "street": "TRINITY RD"
    },
    {
      "usrn": "22403902",
      "street": "TROWLOCK AV"
    },
    {
      "usrn": "22407076",
      "street": "TROWLOCK ISLAND"
    },
    {
      "usrn": "22403903",
      "street": "TROWLOCK WAY"
    },
    {
      "usrn": "22401934",
      "street": "TUDOR AV"
    },
    {
      "usrn": "21800983",
      "street": "TUDOR DRIVE"
    },
    {
      "usrn": "22403905",
      "street": "TUDOR GARDENS"
    },
    {
      "usrn": "22405183",
      "street": "TUDOR GARDENS"
    },
    {
      "usrn": "22401936",
      "street": "TUDOR RD"
    },
    {
      "usrn": "22401938",
      "street": "TULIP CLS"
    },
    {
      "usrn": "22401939",
      "street": "TURNER AV"
    },
    {
      "usrn": "21501137",
      "street": "TWICKENHAM RD"
    },
    {
      "usrn": "21501251",
      "street": "TWICKENHAM RD"
    },
    {
      "usrn": "22401942",
      "street": "TWICKENHAM RD"
    },
    {
      "usrn": "22403908",
      "street": "TWICKENHAM RD"
    },
    {
      "usrn": "22406562",
      "street": "TWICKENHAM RD"
    },
    {
      "usrn": "22401943",
      "street": "TWINING AV"
    },
    {
      "usrn": "22403911",
      "street": "UDNEY PRK RD"
    },
    {
      "usrn": "22405186",
      "street": "ULLSWATER RD"
    },
    {
      "usrn": "22406953",
      "street": "UNNAMED FOOTPATH 2 ELLERMAN AV TO CRANE PRK"
    },
    {
      "usrn": "22406949",
      "street": "UNNAMED FOOTPATH 2 GAINSBOROUGH RD TO TEMPLE RD"
    },
    {
      "usrn": "22406915",
      "street": "UNNAMED FOOTPATH ASHBURNHAM RD TO BREAMWATER GARDENS"
    },
    {
      "usrn": "22406442",
      "street": "UNNAMED FOOTPATH CLARENCE ST TO REAR OF 47 61 KEW RD"
    },
    {
      "usrn": "22406468",
      "street": "UNNAMED FOOTPATH COLE PRK RD TO LONDON RD"
    },
    {
      "usrn": "22406469",
      "street": "UNNAMED FOOTPATH COLE PRK RD TO MOORMEAD RD"
    },
    {
      "usrn": "22406499",
      "street": "UNNAMED FOOTPATH GRAFTON CLS TO MILL FARM CRESCENT"
    },
    {
      "usrn": "22404717",
      "street": "UNNAMED FOOTPATH LONSDALE RD TO HAMMERSMITH BRIDGE"
    },
    {
      "usrn": "22406910",
      "street": "UNNAMED FOOTPATH MEREWAY RD TO CRANEFORD WAY"
    },
    {
      "usrn": "22406500",
      "street": "UNNAMED FOOTPATH MILL RD TO PERCY RD"
    },
    {
      "usrn": "22406459",
      "street": "UNNAMED FOOTPATH PETERSHAM RD TO PETERSHAM MEADOWS"
    },
    {
      "usrn": "22406890",
      "street": "UNNAMED FOOTPATH REAR OF 6 44 DANCER RD"
    },
    {
      "usrn": "22406904",
      "street": "UNNAMED FOOTPATH REAR OF VICTORIA PLACE"
    },
    {
      "usrn": "22403770",
      "street": "UNNAMED FOOTPATH RIVER LANE TO BOROUGH BOUNDARY WITH KINGSTON"
    },
    {
      "usrn": "22406475",
      "street": "UNNAMED FOOTPATH SHAFTESBURY WAY TO STANLEY RD"
    },
    {
      "usrn": "22406625",
      "street": "UNNAMED FOOTPATH SHEEN RD TO SHEEN COMMON SHEEN RIDE GATE"
    },
    {
      "usrn": "22406484",
      "street": "UNNAMED RD ACCESS TO CAVENDISH HOUSE"
    },
    {
      "usrn": "22406782",
      "street": "UNNAMED RD ACCESS TO OBSERVATORY"
    },
    {
      "usrn": "22406781",
      "street": "UNNAMED RD ACCESS TO OLD BARNES CEMETERY"
    },
    {
      "usrn": "22406537",
      "street": "UNNAMED RD CYPRESS AV TO NELSON RD"
    },
    {
      "usrn": "22406869",
      "street": "UNNAMED RD FAIRFAX RD TO SCHOOL"
    },
    {
      "usrn": "22406546",
      "street": "UNNAMED RD FRONTING 395 403 NELSON RD"
    },
    {
      "usrn": "22406544",
      "street": "UNNAMED RD FRONTING MITRE HOTEL"
    },
    {
      "usrn": "22406892",
      "street": "UNNAMED RD HAMPTON CT PRK OWNED AND MAINTAINED BY ROYAL PARKS"
    },
    {
      "usrn": "22406535",
      "street": "UNNAMED RD REAR OF 115 123 HIGH ST WHITTON"
    },
    {
      "usrn": "22406533",
      "street": "UNNAMED RD REAR OF 157 165 ST MARGARETS RD"
    },
    {
      "usrn": "22406888",
      "street": "UNNAMED RD RICHMOND PRK HAM GATE TO PRK"
    },
    {
      "usrn": "22406881",
      "street": "UNNAMED RD RICHMOND PRK RICHMOND GATE TO KINGSTON GATE"
    },
    {
      "usrn": "22406883",
      "street": "UNNAMED RD RICHMOND PRK ROBIN HOOD GATE TO EAST SHEEN GATE"
    },
    {
      "usrn": "22406543",
      "street": "UNNAMED RD WHARF LANE TO 3 33 KING ST"
    },
    {
      "usrn": "22403912",
      "street": "UPLANDS CLS"
    },
    {
      "usrn": "22403913",
      "street": "UPPER GROTTO RD"
    },
    {
      "usrn": "22403914",
      "street": "UPPER HAM RD"
    },
    {
      "usrn": "22406768",
      "street": "UPPER RICHMOND RD"
    },
    {
      "usrn": "22905667",
      "street": "UPPER RICHMOND RD"
    },
    {
      "usrn": "22406036",
      "street": "UPPER RICHMOND RD WEST"
    },
    {
      "usrn": "22401189",
      "street": "UPPER SUNBURY RD"
    },
    {
      "usrn": "22400623",
      "street": "UPPER TEDDINGTON RD"
    },
    {
      "usrn": "22406573",
      "street": "UXBRIDGE RD"
    },
    {
      "usrn": "22407094",
      "street": "VALE CLS"
    },
    {
      "usrn": "22407100",
      "street": "VALERY PLACE"
    },
    {
      "usrn": "22406159",
      "street": "VALLEY MEWS"
    },
    {
      "usrn": "22403917",
      "street": "VANCOUVER RD"
    },
    {
      "usrn": "22407163",
      "street": "VANQUISH CLS"
    },
    {
      "usrn": "22407139",
      "street": "VARLEY DRIVE"
    },
    {
      "usrn": "22401191",
      "street": "VARNA RD"
    },
    {
      "usrn": "22405200",
      "street": "VARSITY ROW"
    },
    {
      "usrn": "22406142",
      "street": "VAUGHAN CLS"
    },
    {
      "usrn": "20801542",
      "street": "VERDUN RD"
    },
    {
      "usrn": "22405205",
      "street": "VERDUN RD"
    },
    {
      "usrn": "22405207",
      "street": "VERNON RD"
    },
    {
      "usrn": "22403169",
      "street": "VICARAGE DRIVE"
    },
    {
      "usrn": "22407035",
      "street": "VICARAGE GARDENS"
    },
    {
      "usrn": "22400629",
      "street": "VICARAGE RD"
    },
    {
      "usrn": "22401949",
      "street": "VICARAGE RD"
    },
    {
      "usrn": "22403170",
      "street": "VICARAGE RD"
    },
    {
      "usrn": "22403919",
      "street": "VICARAGE RD"
    },
    {
      "usrn": "22403920",
      "street": "VICARAGE RD"
    },
    {
      "usrn": "22403921",
      "street": "VICTOR RD"
    },
    {
      "usrn": "21501152",
      "street": "VICTORIA AV"
    },
    {
      "usrn": "22406040",
      "street": "VICTORIA COTTAGES"
    },
    {
      "usrn": "22407066",
      "street": "VICTORIA PARADE"
    },
    {
      "usrn": "22403922",
      "street": "VICTORIA PLACE"
    },
    {
      "usrn": "22403923",
      "street": "VICTORIA RD"
    },
    {
      "usrn": "22403924",
      "street": "VICTORIA RD"
    },
    {
      "usrn": "22405210",
      "street": "VICTORIA RD"
    },
    {
      "usrn": "22406041",
      "street": "VICTORIA VILLAS"
    },
    {
      "usrn": "22401952",
      "street": "VICTORS DRIVE"
    },
    {
      "usrn": "22401953",
      "street": "VILLIERS AV"
    },
    {
      "usrn": "22401954",
      "street": "VINCAM CLS"
    },
    {
      "usrn": "22401955",
      "street": "VINCENT ROW"
    },
    {
      "usrn": "22201652",
      "street": "VINE RD"
    },
    {
      "usrn": "22405212",
      "street": "VINE RD"
    },
    {
      "usrn": "22406261",
      "street": "VINEYARD PASSAGE"
    },
    {
      "usrn": "22405213",
      "street": "VINEYARD PATH"
    },
    {
      "usrn": "22400639",
      "street": "VINEYARD ROW"
    },
    {
      "usrn": "22403925",
      "street": "VIVIENNE CLS"
    },
    {
      "usrn": "22406765",
      "street": "VROW WALK"
    },
    {
      "usrn": "22403926",
      "street": "WADES LANE"
    },
    {
      "usrn": "22405259",
      "street": "WADHAM MEWS"
    },
    {
      "usrn": "22403927",
      "street": "WAKEFIELD RD"
    },
    {
      "usrn": "22405216",
      "street": "WALDECK RD"
    },
    {
      "usrn": "22406404",
      "street": "WALDECK TERR"
    },
    {
      "usrn": "22403928",
      "street": "WALDEGRAVE GARDENS"
    },
    {
      "usrn": "22403929",
      "street": "WALDEGRAVE PRK"
    },
    {
      "usrn": "22403930",
      "street": "WALDEGRAVE RD"
    },
    {
      "usrn": "22407147",
      "street": "WALDEGRAVE RD"
    },
    {
      "usrn": "22401958",
      "street": "WALKER CLS"
    },
    {
      "usrn": "22405219",
      "street": "WALLORTON GARDENS"
    },
    {
      "usrn": "22405220",
      "street": "WALNUT TREE CLS"
    },
    {
      "usrn": "22406048",
      "street": "WALPOLE AV"
    },
    {
      "usrn": "22403931",
      "street": "WALPOLE CRESCENT"
    },
    {
      "usrn": "22403932",
      "street": "WALPOLE GARDENS"
    },
    {
      "usrn": "22403933",
      "street": "WALPOLE PLACE"
    },
    {
      "usrn": "22403934",
      "street": "WALPOLE RD"
    },
    {
      "usrn": "22403935",
      "street": "WALPOLE RD"
    },
    {
      "usrn": "22401960",
      "street": "WARBURTON RD"
    },
    {
      "usrn": "22401202",
      "street": "WARFIELD RD"
    },
    {
      "usrn": "22406900",
      "street": "WARNER CLS"
    },
    {
      "usrn": "22406051",
      "street": "WARREN AV"
    },
    {
      "usrn": "22401961",
      "street": "WARREN RD"
    },
    {
      "usrn": "22403938",
      "street": "WARRINGTON RD"
    },
    {
      "usrn": "8400268",
      "street": "WARWICK AV"
    },
    {
      "usrn": "22401962",
      "street": "WARWICK CLS"
    },
    {
      "usrn": "22405225",
      "street": "WARWICK DRIVE"
    },
    {
      "usrn": "21700679",
      "street": "WARWICK GARDENS"
    },
    {
      "usrn": "22400647",
      "street": "WARWICK RD"
    },
    {
      "usrn": "22403939",
      "street": "WARWICK RD"
    },
    {
      "usrn": "22405228",
      "street": "WASHINGTON RD"
    },
    {
      "usrn": "22406121",
      "street": "WATCOMBE COTTAGES"
    },
    {
      "usrn": "22403940",
      "street": "WATER LANE"
    },
    {
      "usrn": "22403941",
      "street": "WATER LANE"
    },
    {
      "usrn": "22406908",
      "street": "WATERLOO PLACE"
    },
    {
      "usrn": "22403942",
      "street": "WATERMILL CLS"
    },
    {
      "usrn": "22405230",
      "street": "WATNEY RD"
    },
    {
      "usrn": "22403943",
      "street": "WATTS LANE"
    },
    {
      "usrn": "22401964",
      "street": "WAVERLEY AV"
    },
    {
      "usrn": "22403184",
      "street": "WAYSIDE"
    },
    {
      "usrn": "22403186",
      "street": "WELL LANE"
    },
    {
      "usrn": "22403945",
      "street": "WELLESLEY CRESCENT"
    },
    {
      "usrn": "22407095",
      "street": "WELLESLEY PARADE"
    },
    {
      "usrn": "22401965",
      "street": "WELLESLEY RD"
    },
    {
      "usrn": "22401967",
      "street": "WELLINGTON GARDENS"
    },
    {
      "usrn": "22406790",
      "street": "WELLINGTON RD"
    },
    {
      "usrn": "22406791",
      "street": "WELLINGTON RD"
    },
    {
      "usrn": "21501181",
      "street": "WELLINGTON RD SOUTH"
    },
    {
      "usrn": "22407121",
      "street": "WELLINGTON RD SOUTH"
    },
    {
      "usrn": "22403187",
      "street": "WELLSIDE GARDENS"
    },
    {
      "usrn": "22401206",
      "street": "WEMBLEY RD"
    },
    {
      "usrn": "22401970",
      "street": "WENSLEYDALE GARDENS"
    },
    {
      "usrn": "22401207",
      "street": "WENSLEYDALE RD"
    },
    {
      "usrn": "22406939",
      "street": "WEST CLS"
    },
    {
      "usrn": "22406061",
      "street": "WEST HALL RD"
    },
    {
      "usrn": "22406062",
      "street": "WEST PRK AV"
    },
    {
      "usrn": "22406063",
      "street": "WEST PRK RD"
    },
    {
      "usrn": "22406064",
      "street": "WEST SHEEN VALE"
    },
    {
      "usrn": "8100565",
      "street": "WEST SMITHFIELD"
    },
    {
      "usrn": "22406065",
      "street": "WEST TEMPLE SHEEN"
    },
    {
      "usrn": "22401972",
      "street": "WESTBANK RD"
    },
    {
      "usrn": "22401973",
      "street": "WESTBROOK AV"
    },
    {
      "usrn": "22406658",
      "street": "WESTERLEY WARE"
    },
    {
      "usrn": "22405245",
      "street": "WESTFIELDS"
    },
    {
      "usrn": "22405246",
      "street": "WESTFIELDS AV"
    },
    {
      "usrn": "22403948",
      "street": "WESTHAY GARDENS"
    },
    {
      "usrn": "22403949",
      "street": "WESTMINSTER CLS"
    },
    {
      "usrn": "22405248",
      "street": "WESTMORELAND RD"
    },
    {
      "usrn": "22403950",
      "street": "WESTMORLAND CLS"
    },
    {
      "usrn": "21901484",
      "street": "WESTOW HILL"
    },
    {
      "usrn": "22405252",
      "street": "WESTWOOD GARDENS"
    },
    {
      "usrn": "22405253",
      "street": "WESTWOOD RD"
    },
    {
      "usrn": "22407056",
      "street": "WHITCOME MEWS"
    },
    {
      "usrn": "21106111",
      "street": "WHITE HART LANE"
    },
    {
      "usrn": "22405257",
      "street": "WHITE HART LANE"
    },
    {
      "usrn": "22403952",
      "street": "WHITE HERON MEWS"
    },
    {
      "usrn": "22401975",
      "street": "WHITELEYS WAY"
    },
    {
      "usrn": "22403953",
      "street": "WHITTAKER AV"
    },
    {
      "usrn": "21501203",
      "street": "WHITTON DENE"
    },
    {
      "usrn": "22406575",
      "street": "WHITTON DENE"
    },
    {
      "usrn": "22401977",
      "street": "WHITTON MANOR RD"
    },
    {
      "usrn": "21501205",
      "street": "WHITTON RD"
    },
    {
      "usrn": "22403955",
      "street": "WHITTON RD"
    },
    {
      "usrn": "22401979",
      "street": "WHITTON WAYE"
    },
    {
      "usrn": "22401469",
      "street": "WHITWORTH PLACE"
    },
    {
      "usrn": "22403958",
      "street": "WICK RD"
    },
    {
      "usrn": "22407077",
      "street": "WIDEWING CLS"
    },
    {
      "usrn": "22407057",
      "street": "WIGGINS LANE"
    },
    {
      "usrn": "22401981",
      "street": "WILCOX RD"
    },
    {
      "usrn": "22405260",
      "street": "WILLIAMS LANE"
    },
    {
      "usrn": "22403961",
      "street": "WILLOUGHBY RD"
    },
    {
      "usrn": "22405261",
      "street": "WILLOW AV"
    },
    {
      "usrn": "22406125",
      "street": "WILLOW BANK"
    },
    {
      "usrn": "22406160",
      "street": "WILLOW COTTAGES"
    },
    {
      "usrn": "22906202",
      "street": "WILLOW FARM LANE"
    },
    {
      "usrn": "22401982",
      "street": "WILLOW WAY"
    },
    {
      "usrn": "22401983",
      "street": "WILLOWDENE CLS"
    },
    {
      "usrn": "22401984",
      "street": "WILLS CRESCENT"
    },
    {
      "usrn": "8400284",
      "street": "WILTON RD"
    },
    {
      "usrn": "22401985",
      "street": "WILTSHIRE GARDENS"
    },
    {
      "usrn": "22403964",
      "street": "WINCHENDON RD"
    },
    {
      "usrn": "22403966",
      "street": "WINCHESTER RD"
    },
    {
      "usrn": "22406081",
      "street": "WINDHAM RD"
    },
    {
      "usrn": "22401989",
      "street": "WINDLESHAM MEWS"
    },
    {
      "usrn": "22401988",
      "street": "WINDMILL RD"
    },
    {
      "usrn": "22403968",
      "street": "WINDSOR RD"
    },
    {
      "usrn": "22406084",
      "street": "WINDSOR RD"
    },
    {
      "usrn": "22401991",
      "street": "WINIFRED RD"
    },
    {
      "usrn": "22403971",
      "street": "WINTER BOX WALK"
    },
    {
      "usrn": "22400677",
      "street": "WOFFINGTON CLS"
    },
    {
      "usrn": "22401994",
      "street": "WOLSEY RD"
    },
    {
      "usrn": "22401997",
      "street": "WOODBINE CLS"
    },
    {
      "usrn": "22405281",
      "street": "WOODLANDS RD"
    },
    {
      "usrn": "22401998",
      "street": "WOODLAWN CRESCENT"
    },
    {
      "usrn": "22407122",
      "street": "WOODMAN MEWS"
    },
    {
      "usrn": "22403976",
      "street": "WOODVILLE CLS"
    },
    {
      "usrn": "22403977",
      "street": "WOODVILLE RD"
    },
    {
      "usrn": "22406267",
      "street": "WOODWARDS FOOTPATH"
    },
    {
      "usrn": "22402000",
      "street": "WORDSWORTH RD"
    },
    {
      "usrn": "22405287",
      "street": "WORPLE ST"
    },
    {
      "usrn": "22406093",
      "street": "WORPLE WAY"
    },
    {
      "usrn": "22407032",
      "street": "WRIGHTS WALK"
    },
    {
      "usrn": "22406738",
      "street": "WYATT DRIVE"
    },
    {
      "usrn": "22402004",
      "street": "WYNDHAM CRESCENT"
    },
    {
      "usrn": "22406633",
      "street": "YATES PATH"
    },
    {
      "usrn": "22403230",
      "street": "YORK AV"
    },
    {
      "usrn": "22403769",
      "street": "YORK HOUSE GARDENS"
    },
    {
      "usrn": "22403980",
      "street": "YORK RD"
    },
    {
      "usrn": "22403981",
      "street": "YORK RD"
    },
    {
      "usrn": "22403983",
      "street": "YORK ST"
    }
  ]
}
```
