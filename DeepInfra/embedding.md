```shell
curl "https://api.deepinfra.com/v1/openai/embeddings" \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer $DEEPINFRA_API_KEY" \
  -d '{
    "input": "The food was delicious and the waiter...",
    "model": "BAAI/bge-base-en-v1.5",
    "encoding_format": "float"
  }'
```

```shell
{"object":"list","model":"BAAI/bge-base-en-v1.5","usage":{"prompt_tokens":12,"total_tokens":12}, "data": [{"index": 0, "object": "embedding", "embedding": [-0.04759955033659935, -0.00554089667275548, 0.01872076652944088, -0.025672724470496178, 0.06591437757015228, 0.010764837265014648, -0.017667103558778763, 0.05037336051464081, -0.0014907341683283448, -0.015081332065165043, 0.017558956518769264, -0.01384044624865055, -0.008849958889186382, 0.020852291956543922, 0.003478036494925618, 0.008818683214485645, 0.07426325976848602, -0.031206903979182243, 0.039376843720674515, -0.03780442103743553, -0.022693736478686333, -0.01475651003420353, -0.011191106401383877, 0.012695509940385818, -0.014381601475179195, -0.022319236770272255, -0.007750328630208969, 0.02497246116399765, -0.03108079731464386, -0.04473147541284561, 0.050228942185640335, 0.031221900135278702, -0.01369540300220251, -0.030721787363290787, -0.012819446623325348, -0.00921497493982315, 0.04743942618370056, -0.010366947390139103, -0.03255416080355644, 0.03777903690934181, -0.005254733841866255, 0.008755276910960674, 0.024079622700810432, 0.04153095558285713, -0.04423364996910095, -0.007175879552960396, -0.015770643949508667, 0.03576071187853813, -0.016569649800658226, -0.0018155407160520554, 0.004344535060226917, -0.007239295169711113, 0.07205359637737274, -0.010945316404104233, -0.008941294625401497, 0.04299387335777283, -0.050608422607183456, -0.005793577525764704, 0.004561338108032942, -0.027548013255000114, -0.022598015144467354, -0.00045214008423499763, 0.022013211622834206, -0.0672312006354332, 0.009924071840941906, 0.01580832339823246, 0.011621860787272453, 0.0259843897074461, 0.02691769227385521, 0.03359067440032959, 0.00797499343752861, -0.03868037462234497, -0.031183509156107903, 0.019592557102441788, -0.05681535601615906, -0.07434073835611343, 0.0011230399832129478, 0.008702450431883335, -0.045035410672426224, 0.03968806564807892, -0.06158185005187988, -0.06362949311733246, 0.017657730728387833, 0.029419921338558197, -0.0011176365660503507, -0.007516937330365181, 0.02798079140484333, -0.0034311639610677958, 0.0058946022763848305, 0.02818501740694046, -0.05795001983642578, -0.00023800080816727132, -0.0032843747176229954, 0.04347175732254982, -0.03299379721283913, 0.004499856848269701, 0.0020928578451275826, 0.031837787479162216, 0.01768082194030285, 0.013835322111845016, -0.032499734312295914, -0.028856554999947548, 0.004020234569907188, 0.01578182727098465, -0.08078835904598236, -0.018862547352910042, -0.006230535451322794, 0.0015026251785457134, 0.032872479408979416, 0.03333105146884918, -0.011176015250384808, -0.03395119681954384, -0.06383253633975983, 0.07395053654909134, -0.05008867010474205, 0.05286584794521332, 0.03379949927330017, -0.01899423450231552, -0.017224537208676338, -0.11624472588300705, 0.054111529141664505, 0.011225353926420212, -0.009598051197826862, 0.04292919859290123, 0.032172419130802155, -0.060600463300943375, -0.028779296204447746, 0.019749809056520462, 0.05747659131884575, 0.002447892911732197, 0.04641018435359001, 0.09123492985963821, 0.005769695155322552, -0.0394013412296772, -0.03419661894440651, 0.02122805267572403, 0.02970105968415737, -0.028421899303793907, -0.010552898049354553, -0.04432081803679466, 0.015102994628250599, 0.02430088445544243, -0.016986671835184097, 0.018751049414277077, 0.023311972618103027, 0.01696859300136566, 0.04407071694731712, -0.037208639085292816, 0.058596283197402954, 0.011859129182994366, 0.018504777923226357, 0.01751037873327732, -0.018193025141954422, -0.005545374006032944, 0.03720271587371826, 0.008804007433354855, -0.031098395586013794, 0.013051860965788364, -0.07918998599052429, 0.031132012605667114, 0.04168297350406647, 0.058315131813287735, 0.009175051003694534, -0.023976996541023254, 0.024138014763593674, 0.04356468468904495, 0.008251143619418144, 0.03858855366706848, -0.014661631546914577, 0.05153097212314606, -0.043194159865379333, 0.014836549758911133, -0.024666154757142067, 0.007301982492208481, -0.059119902551174164, 0.06108413264155388, 0.08099176734685898, -0.03347574174404144, 0.025090936571359634, 0.005890791770070791, -0.04535447806119919, 0.042302895337343216, 0.0810544341802597, 0.050101105123758316, -0.00428487965837121, -0.013756580650806427, 0.031099889427423477, 0.027085160836577415, -0.03997020423412323, -0.031400490552186966, -0.06847253441810608, -0.04284725710749626, -0.04169478639960289, -0.03636329248547554, 0.0028136889450252056, -0.01647203229367733, -0.021729331463575363, 0.012299707159399986, 0.07123399525880814, -0.0023450616281479597, -0.06787299364805222, 0.034754086285829544, 0.007357186637818813, -0.05197770893573761, 0.00486717838793993, 0.007873051799833775, 0.0513143390417099, -0.0107053741812706, -0.02921903505921364, 0.03673198074102402, -0.0382714718580246, 0.021072935312986374, 0.037470847368240356, -0.009733322076499462, 0.026559332385659218, 0.02391294576227665, 0.05383022502064705, -0.05197420343756676, 0.011326884850859642, -0.03382079675793648, 0.06909611821174622, 0.015110988169908524, 0.0121927410364151, 0.02968003787100315, 0.01067151315510273, 0.09140853583812714, 0.03621482476592064, -0.022442568093538284, -0.025395605713129044, 0.02706506848335266, -0.045868128538131714, -0.023089271038770676, -0.0029997793026268482, 0.011279393918812275, 0.0170233603566885, 0.014151441864669323, 0.014966808259487152, 0.00814950093626976, 0.037059031426906586, -0.04307299479842186, 0.01613491214811802, 0.026317808777093887, -0.02414916269481182, 0.030147774145007133, 0.0054006087593734264, -0.006691578309983015, 0.02050015889108181, 0.054699115455150604, 0.010831774212419987, -0.047577694058418274, 0.02301553636789322, -0.03028084896504879, 0.011328037828207016, -0.02096155844628811, 0.006231687497347593, -0.07262975722551346, -0.04039507359266281, -0.023235242813825607, 0.034719884395599365, 0.04564468562602997, -0.015370320528745651, 0.014739536680281162, 0.017720689997076988, 0.03320308402180672, -0.011256762780249119, -0.020832384005188942, -0.03778628632426262, -0.04414886608719826, 0.023101650178432465, 0.04318498447537422, 0.012411494739353657, 0.008688967674970627, -0.015914330258965492, 0.037767671048641205, -0.015472576022148132, -0.026996605098247528, -0.00846753641963005, -0.02059420384466648, 0.02445506490767002, -0.051397453993558884, 0.02487664669752121, 0.05400575324892998, -0.027448439970612526, -0.034342240542173386, 0.022032270208001137, -0.05509824678301811, -0.05845493823289871, -0.02482718788087368, -0.07879748940467834, 0.031120339408516884, 0.012069405056536198, -0.0107091860845685, 0.0044305105693638325, -0.06543932110071182, 0.01946474425494671, -0.0478147529065609, -0.009205462411046028, 0.010480309836566448, 0.07082992792129517, 0.0035826051607728004, 0.011187435127794743, 0.017299681901931763, 0.05636635050177574, 0.02607438527047634, 0.014513485133647919, -0.07950815558433533, 0.03761400282382965, -0.0396910198032856, -0.2290845811367035, 0.043091222643852234, 0.06521541625261307, -0.0015351593028753996, -0.036867961287498474, -8.305395567731466e-06, 0.0366322360932827, -0.011384229175746441, 0.004584672395139933, 0.029127318412065506, -0.05047501623630524, -0.04450862482190132, -0.03176115080714226, 0.03947758302092552, 0.025071630254387856, -0.0012986999936401844, -0.014789403416216373, -0.046049393713474274, 0.019429750740528107, 0.06592728942632675, 0.0010059428168460727, -0.08874941617250443, 0.005123719573020935, 0.003151749027892947, 0.07695939391851425, 0.02332449145615101, -0.041633155196905136, 0.02080090530216694, -0.06600896269083023, -0.032167624682188034, -0.018897129222750664, 0.005689495708793402, 0.054515063762664795, -0.0290997251868248, 0.014473788440227509, 0.034208204597234726, 0.014835076406598091, -0.10930986702442169, -0.015822770074009895, -0.020498858764767647, 0.013418213464319706, -0.04492128640413284, -0.021790090948343277, -0.014699898660182953, 0.0622219443321228, -0.0330304354429245, -0.02490628883242607, -0.06886278837919235, 0.030583404004573822, 0.043328650295734406, -0.0004052893491461873, -0.04014594852924347, -0.013335921801626682, -0.006465405225753784, -0.059758976101875305, 0.10705757141113281, -0.008064322173595428, 0.016765452921390533, -0.02602662891149521, 0.006792580708861351, -0.03408559784293175, 0.012377433478832245, -0.043281443417072296, 0.005050573498010635, 0.02068638987839222, 0.010240347124636173, 0.02494959905743599, -0.004110647365450859, -0.01055828295648098, 0.04193782061338425, 0.02818342112004757, -0.033518947660923004, -0.008096376433968544, -0.06381496042013168, -0.005946299061179161, -0.04126483574509621, -0.06593608856201172, -0.026202933862805367, 0.021105436608195305, -0.024941876530647278, 0.002549481811001897, -0.020758720114827156, 0.025718066841363907, -0.023596040904521942, 0.033521365374326706, 0.033376727253198624, -0.018122727051377296, 0.03006211295723915, -0.05623485520482063, -0.03344998136162758, 0.07920140027999878, -0.008795957081019878, 0.010152718052268028, 0.02482837252318859, -0.00743526266887784, 0.053549766540527344, -0.011784144677221775, 0.03143564611673355, 0.0006931734387762845, -0.004560134373605251, 0.007045709062367678, -0.03519585356116295, 0.0361914187669754, 0.035003021359443665, 0.01966327428817749, 0.004178847186267376, -0.05514099448919296, -0.01590120792388916, 0.04280891269445419, 0.018181269988417625, 0.02633451484143734, 0.009281978011131287, 0.030036654323339462, -0.06404341757297516, 0.030702069401741028, -0.03125590831041336, 0.029045460745692253, 0.005630986765027046, 0.003194740740582347, 0.04598822072148323, -0.03399154916405678, -0.010644623078405857, -0.03647406026721001, 0.05394073575735092, -0.0021359832026064396, -0.03251257911324501, 0.01735718920826912, 0.010802469216287136, -0.024179872125387192, 0.009833737276494503, 0.016078542917966843, -0.01707407645881176, 0.027022412046790123, 0.019043153151869774, 0.02825654111802578, 0.008161719888448715, 0.00463677104562521, -0.0806102529168129, -0.005218187812715769, 0.020308423787355423, 0.010113297961652279, 0.05878693610429764, -0.03354471176862717, 0.008064975962042809, -0.028455961495637894, -0.0070083970203995705, 0.013180690817534924, -0.011292587965726852, -0.020619098097085953, 0.022543910890817642, -0.012231080792844296, 0.038509491831064224, -0.006024663336575031, -0.03737682104110718, -0.015241560526192188, -0.04243886098265648, 0.025310993194580078, 0.00711235124617815, -0.026875600218772888, 0.012121068313717842, 0.027883553877472878, -0.08673574030399323, 0.005599886178970337, 0.026845648884773254, -0.023884208872914314, 0.04646819084882736, 0.004302474204450846, -0.044444456696510315, -0.006367211230099201, 0.05365336313843727, 0.01709792949259281, 0.04258947819471359, 0.01624326780438423, 0.003438043175265193, 0.024844443425536156, -0.021566269919276237, -0.004697949159890413, 0.035524915903806686, -0.02896212600171566, -0.04223870113492012, 0.008999167010188103, 0.008299920707941055, -0.03307992219924927, 0.05301881209015846, 0.04853881895542145, -0.033278536051511765, -0.04177527874708176, -0.03400472179055214, 0.019794192165136337, -0.04144325852394104, -0.02741713635623455, 0.0011088812025263906, -0.01490277610719204, 0.03887353464961052, -0.04292038083076477, -0.05110130086541176, 0.013490459881722927, -0.011653563007712364, -0.031273528933525085, 0.013369069434702396, 0.040006496012210846, 0.02391219511628151, -0.002953244373202324, 0.002690511289983988, -0.005988837219774723, -0.043557628989219666, 0.0433029942214489, 0.008247291669249535, 0.02296476997435093, 0.053098395466804504, -0.04875873029232025, -0.010669095441699028, 0.016228308901190758, 0.016975583508610725, 0.017859729006886482, -0.03139650076627731, 0.010095945559442043, 0.012240549549460411, -0.013664057478308678, -0.017021488398313522, 0.0027291823644191027, -0.018805770203471184, -0.07550480961799622, -0.04659955948591232, 0.007912222295999527, 0.04876020550727844, -0.026088722050189972, -0.038634948432445526, 0.012122576124966145, -0.029405327513813972, 0.01632077805697918, -0.014567505568265915, 0.0096665620803833, 0.05082729458808899, -0.021282974630594254, -0.032770123332738876, -0.01815050281584263, -0.0343543142080307, -0.018050260841846466, 0.05278446152806282, 0.021374385803937912, -0.018769297748804092, -0.027199380099773407, -0.007256798911839724, 0.001534943119622767, 0.051228828728199005, -0.020400382578372955, -0.011083533987402916, -0.012084590271115303, 0.014738336205482483, -0.049280017614364624, 0.008400658145546913, 0.025305956602096558, -0.033467721194028854, 0.007935612462460995, -0.038171906024217606, 0.012237067334353924, 0.018691984936594963, -0.01981755532324314, -0.00430638249963522, 0.0019326454494148493, 0.05770551413297653, -0.0026319120079278946, 0.020342933014035225, 0.059969495981931686, 0.051750775426626205, 0.03996773436665535, -0.009471075609326363, -0.0002609844377730042, -0.019867008551955223, 0.0344122014939785, -0.049656640738248825, -0.03163120895624161, 0.028313426300883293, 0.049445830285549164, 0.007917643524706364, -0.02732783928513527, -0.0303275678306818, 0.044548727571964264, -0.10204964131116867, -0.005302958190441132, -0.003779617603868246, -0.03804453834891319, -0.03486161306500435, -0.05021420493721962, -0.04041466489434242, -0.006122289225459099, 0.0010199001990258694, -0.04249463975429535, 0.08631686866283417, -0.01159930694848299, 0.040602993220090866, 0.083124078810215, 0.004538607783615589, 0.04277592524886131, -0.0629405677318573, 0.06836865097284317, 0.03572427108883858, -0.0741543099284172, 0.02685513347387314, -0.05543820559978485, -0.03044271655380726, 0.011914284899830818, -0.01833117939531803, -0.0004773198743350804, 0.04714800417423248, 0.002042564796283841, -0.06756752729415894, -0.05199483036994934, -0.011401240713894367, -0.027571136131882668, -0.04518847540020943, 0.061462655663490295, -0.013344901613891125, -0.037233952432870865, -0.03488106280565262, 0.012883956544101238, -0.022109121084213257, -0.03240162134170532, 0.017887098714709282, 0.0386863574385643, -0.04440458491444588, 0.02704412117600441, 0.01193564385175705, 0.025535227730870247, 0.007254986558109522, -0.0451652929186821, 0.014533260837197304, -0.026739412918686867, 0.04449496790766716, -0.007193895056843758, 0.06354226171970367, 0.019437119364738464, 0.004581366200000048, -0.013386333361268044, -0.024349959567189217, 0.01401157770305872, -0.010804051533341408, -0.005111485254019499, -0.0013727350160479546, 0.0014057159423828125, 0.004896922968327999, -0.042245253920555115, 0.05475512519478798, 0.06957358866930008, 0.0019472342683002353, 0.034801214933395386, 0.02324187010526657, 0.04301666468381882, 0.023109521716833115, -0.014967137947678566, 0.007690994068980217, 0.019252732396125793, -0.048083629459142685, 0.04882542043924332, -0.034681882709264755, -0.08062976598739624, -0.04196515679359436, -0.05345011502504349, 0.06481663137674332, -0.0032388009130954742, 0.02978537231683731, 0.08568540215492249, -0.02832171320915222, 0.015714259818196297, -0.00032568033202551305, 0.004357883706688881, -0.029371775686740875, -0.010250425897538662, -0.008949149399995804, 0.0025941217318177223, -0.028442485257983208, -0.0030903141014277935, 0.0023428460117429495, 0.05459023267030716, 0.02183651365339756, 0.026264613494277, -0.057826440781354904, 0.03646345064043999, 0.04221084713935852, 0.03655456751585007, 0.0060383533127605915, -0.034583039581775665, -0.02198336087167263, -0.0006138908793218434, -0.02503802441060543, -0.03295034170150757, 0.05362462252378464, -0.06627881526947021, -0.030435500666499138, 0.05449896305799484, -0.02696909010410309, 0.007819462567567825, -0.04976682364940643, -0.05265481397509575, -0.015607021749019623, 0.019002992659807205, 0.01640753261744976, -0.05349612981081009, -0.008981951512396336, 0.03782883659005165, 0.07055139541625977, -0.0013562345411628485, -0.0390937365591526, -0.020356904715299606, 0.03838887810707092, 0.003031640313565731, -0.010024593211710453, -0.07490511983633041, 0.016805006191134453, 0.006734206806868315, 0.002823613816872239, -0.028548717498779297, 0.04788176342844963, -0.03869585692882538, -0.016768746078014374, 0.010689240880310535, -0.007183756213635206, -0.0019889932591468096, -0.07959333062171936, -0.0591638945043087, -0.027543943375349045, 0.07420320808887482, 0.03740409016609192, -0.04196721687912941, 0.07141289860010147, -0.013999144546687603, 0.03368766978383064, -0.031115828081965446, 0.045747753232717514, -0.008335372433066368, 0.020619232207536697, 0.01723450794816017, -0.03983141481876373, -0.020021138712763786, -0.06586891412734985, 0.04724069684743881, -0.009393756277859211, -0.01219835877418518, -0.02976815402507782, 0.003247670829296112, 0.0019343766616657376, -0.002126135630533099, -0.0013261085841804743, -0.015424832701683044, 0.01552993431687355, -0.03956817835569382, 0.01614230126142502, -0.06252189725637436, -0.040920328348875046, 0.007177270483225584, -0.02240365743637085, -0.0022746108006685972, -0.01268687192350626, -0.033858124166727066, 0.011252808384597301, 0.0074368976056575775, -0.03152243420481682, 0.05237618833780289, 0.030100006610155106]}]}
```