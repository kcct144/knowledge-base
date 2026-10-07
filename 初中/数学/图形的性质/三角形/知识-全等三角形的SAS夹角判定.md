---
标题: 全等三角形的SAS夹角判定
别名: ["SAS", "边角边全等"]
前置: ["知识-全等三角形的对应顶点与刚性关系"]
---

## 讲解

### 是什么

两三角形有两边及这两边所夹的角分别对应相等，就全等，称SAS。夹角是两给定边的共同顶点处角，不是任意一角。长度对应及角对应均需明确。

### 怎么来的

一条已知边可先重合，另一给定边的长度和与它的夹角将第三顶点的位置确定在对应射线上；允许镜像翻折后便可完全重合。这解释为什么夹角能固定两边的开合，是教材基本全等判据。原AB=AC、BD=CE的共同顶点分别是B、C，夹角ABD=ACE由等腰底角得到，因此SAS直接推出AD=AE。原圆弧中点题比较BOP和COP，用半径OB=OC、公共OP与夹角BOP=POC，三项也恰为SAS。

### 什么时候能用

必须是两给定边之间的角；若给一个不夹在两边之间的角，一般SSA不保证唯一三角形，不能改叫SAS。共享边可提供一项相等但须写“公共边”。原D、E若重合导致某辅助三角形退化，先看目标直接成立，不对退化图机械应用判据。


本章同加FC补对应AC=DF，平行给两给边真实夹角；手拉手从相等整体共减DAC，得到BAD=CAE后才能用SAS。截长补短每一层的对应边及夹角分开核。SSA反例说明非夹角不能替夹角，即使元素总数同样三项。原书写顺序可按边、夹角、边列，不把待证对应量加入前提。

## 例题

### 弧中点连半径弦与直径直角多次勾股

> 来源ID Q18-18；第18章命题的证明；201-250/full.md 第1389–1401行。原答案与解析定位：201-250/full.md 第1403–1415行。

例7 如图, $AB$ 是 $\odot O$ 的直径, $P$ 是弧 $BC$ 的中点, $AB = 13$ , $AC = 5$ , 求 $PA$ 的长.

![](../命题与证明/图片/18-原图-c4773a324e31.webp)

![](../命题与证明/图片/18-原图-0dc806dd32c0.webp)

**原资料答案与解析：**

解析 连接 $PB, BC$ , 连接 $OP$ 交 $BC$ 于 $D$ .

∵ P 是弧 BC 的中点, ∴ $OP \perp BC, BD = CD.$

又∵ OA=OB, ∴ $OD=\frac{1}{2}AC=\frac{5}{2}$ . 又∵ $OP=\frac{1}{2}AB=\frac{13}{2}$ , ∴ PD=OP-OD=4.

∵ AB 是 ⊙O 的直径, ∴ $\angle ACB = 90^{\circ}$ . ∵ AB = 13, AC = 5,

$$
\therefore B C = \sqrt {A B ^ {2} - A C ^ {2}} = 1 2, \therefore B D = \frac {1}{2} B C = 6. \therefore P B = \sqrt {P D ^ {2} + B D ^ {2}} = 2 \sqrt {1 3}.
$$

∵ AB 是 $\odot O$ 的直径, ∴ $\angle APB = 90^{\circ}$ , ∴ $PA = \sqrt{AB^{2} - PB^{2}} = 3\sqrt{13}$ .

**展开解析（依据原详解补足理由与步骤）：**

先连PB、BC、OP并令OP交BC于D，原P在不含A的BC弧中点。等弧给BOP=POC，OB=OC、OP共同，由SAS得PB=PC；进一步△BPD与△CPD由SAS全等，故BD=CD，BDP=CDP，两角邻补所以均90°，OP⊥BC。O是AB中点、D是BC中点，△ABC中位线OD=AC/2=5/2；OP为半径=AB/2=13/2。原图O、D、P按序，PD=OP−OD=4。

AB为直径，ACB90°，BC²=13²−5²=144，BC=12，BD=6。在直角△PDB中PB²=PD²+BD²=16+36=52，PB=2√13。AB亦为直径，APB90°，PA²=AB²−PB²=169−52=117，PA=3√13。每次正根来自长度为正。三个不同直角分别来自直径、垂径和直径，不能把未画辅助线的斜段随意当直角边；PD差式依赖原弧中点与点序。

### 等腰底边对称点两种方法证明线段等

> 来源ID Q18-19；第18章命题的证明；201-250/full.md 第1425–1434行。原答案与解析定位：201-250/full.md 第1436–1471行。

例8 如图, 点 D, E 在 $\triangle ABC$ 的边 BC 上, AB = AC, BD = CE. 求证: AD = AE.

![](图片/18-原图-4c03d2bd73c9.webp)

**原资料答案与解析：**

证明 证法一:∵ AB=AC,∴ ∠B=∠C.又∵ BD=CE,∴ △ABD≌△ACE,∴ AD=AE.

证法二: 过点 A 作 $AF \perp BC$ ，垂足为 $F \therefore AB = AC, \therefore BF = CF.$

∵ BD=CE, ∴ BF-BD=CF-CE, 即 DF=EF. ∴ AF 垂直平分 DE, ∴ AD=AE.

(注:还可用等腰三角形的判定证明 AD=AE)

**展开解析（依据原详解补足理由与步骤）：**

法一：AB=AC使B=C（等腰底角），D、E均在BC且原B-D-E-C顺序，所以ABD=ACE；再有AB=AC、BD=CE，这两边及夹角对应相等，由SAS得△ABD≌△ACE，对应AD=AE。把对应顺序写为A↔A、B↔C、D↔E。

法二：过A作AF⊥BC，由等腰三角形三线合一F为BC中点，BF=CF。BD=CE且按原点序D、E在F两侧（可由等长两端段与D在E左侧推出），所以DF=BF−BD、EF=CF−CE，二者相等。AF垂直平分DE，点A到D、E距离相等，AD=AE；也可在直角△AFD、△AFE中AF共同、DF=EF、夹角90°，直接SAS全等得到AD=AE，不需未说明的垂平线定理。若D=E退化，目标直接成立，两个三角形的使用需单独看非退化情况。原提取此处混进其他两题辅助图，已按实际图对象重新归属，原证据不改。


### SAS原书同加FC与平行内错

> 来源ID Q20-08；第20章全等三角形；201-250/full.md 第2730–2744行。原答案与解析定位：201-250/full.md 第2732–2748行。

书写示例: 如图, 点 A、F、C、D 在一条直线上, $AB \parallel DE$ , AB = DE, AF = DC, 求证 $BC \parallel EF$ .

证明：∵ $AB \parallel DE, \therefore \angle A = \angle D, \because AF = DC, \therefore AC = DF,$

在 $\triangle ABC$ 和 $\triangle DEF$ 中， $\left\{\begin{aligned}AB&=DE,\\ \angle A&=\angle D,\\ AC&=DF,\end{aligned}\right.$ ②

![](图片/20-原图-72ac93a3b50d.webp)

**原资料答案与解析：**

证明：∵ $AB \parallel DE, \therefore \angle A = \angle D, \because AF = DC, \therefore AC = DF,$

在 $\triangle ABC$ 和 $\triangle DEF$ 中， $\left\{\begin{aligned}AB&=DE,\\ \angle A&=\angle D,\\ AC&=DF,\end{aligned}\right.$ ②

![](图片/20-原图-72ac93a3b50d.webp)

$$
\therefore \triangle A B C \cong \triangle D E F (\text { SAS }), \therefore \angle A C B = \angle D F E, \therefore B C / / E F.
$$

**展开解析（依据原详解补足理由与步骤）：**

原A-F-C-D按序，AF=DC，两边同加FC得AC=DF。AB∥DE、AD为截线，BAC=EDF；再有AB=DE，两边及夹角对应相等，△ABC≌△DEF（SAS）。得到ACB=DFE；它们为BC、EF被AD截的内错角，所以BC∥EF。先角判定全等，再由全等对应角判平行，不可先用待证BC∥EF来配角。

### 两个原直角全等引出另两对与CF等EF双证

> 来源ID Q20-12；第20章全等三角形；201-250/full.md 第2856–2860行。原答案与解析定位：201-250/full.md 第2861–2896行。

例1 如图, 已知 Rt△ABC≌Rt△ADE, ∠ABC = ∠ADE = 90°, 连接 CD、EB.

(1) 图中还有几对全等三角形？请你一一列举.  
(2) 求证: CF = EF.

**原资料答案与解析：**

解析（1）还有2对全等三角形. $\triangle ADC\cong \triangle ABE,\triangle CDF\cong \triangle EBF.$

(2) 证法一: $\because \mathrm{Rt} \triangle ABC \cong \mathrm{Rt} \triangle ADE, \therefore AC = AE, \angle CAB = \angle EAD, AB = AD,$

$$
\therefore \angle C A B - \angle D A B = \angle E A D - \angle D A B, \text { 即 } \angle C A D = \angle E A B, \therefore \triangle A C D \cong \triangle A E B (\mathrm{SAS}),
$$

$$
\therefore C D = E B, \angle A D C = \angle A B E. \text {又} \because \angle A D E = \angle A B C, \therefore \angle C D F = \angle E B F.
$$

$$
\text { 又 } \because \angle D F C = \angle B F E, \therefore \triangle C D F \cong \triangle E B F (\mathrm{AAS}), \therefore C F = E F.
$$

证法二: 连接 $AF$ . ∵ Rt△ABC ≅ Rt△ADE, ∴ AB = AD, BC = DE.

在 Rt△ABF 和 Rt△ADF 中, AF = AF, AB = AD, ∴ Rt△ABF ≅ Rt△ADF(HL),

$$
\therefore B F = D F. \text {   又   } \because B C = D E, \therefore B C - B F = D E - D F, \text {   即   } C F = E F.
$$

![](图片/20-原图-3ca8b9ea479f.webp)

**展开解析（依据原详解补足理由与步骤）：**

原Rt△ABC≌Rt△ADE，得AC=AE、AB=AD、BC=DE、CAB=EAD。原两整体角都含DAB，同减得CAD=EAB；所以△ACD与△AEB有两边及夹角对应等，SAS全等，CD=EB、ADC=ABE。原ADE=ABC90°，从ADC与ABE对应相等的整体中扣去90°，得CDF=EBF；DFC与BFE对顶，结合CD=EB得△CDF≌△EBF（AAS），故CF=EF。原除给定一对外还有这两对，三角形次序按对应可倒写。

原法二连AF，ABF、ADF的直角分别在B、D，AF共同斜边、AB=AD一腿，HL全等得BF=DF。原B-F-C、D-F-E点序与BC=DE，再同减相等小段BF/DF，得CF=BC−BF=DE−DF=EF。两方法的两组辅助三角形不同，均列真实条件，未用目标CF=EF作判据。

### 双等腰手拉手同减公共角造SAS

> 来源ID Q20-13；第20章全等三角形；201-250/full.md 第2910–2918行。原答案与解析定位：201-250/full.md 第2920–2922行。

例2 如图, $AB = AC$ , $AD = AE$ , $\angle BAC = \angle DAE$ . 求证: $\triangle ABD \cong \triangle ACE$ .

![](图片/20-原图-4910046162b1.webp)

**原资料答案与解析：**

证明 $\because \angle BAC = \angle DAE, \therefore \angle BAD = \angle EAC,$

在 $\triangle ABD$ 和 $\triangle ACE$ 中， $\left\{\begin{aligned}AB&=AC,\\ \angle BAD&=\angle EAC,\\ AD&=AE,\end{aligned}\right.$ $\therefore\triangle ABD\cong\triangle ACE(SAS).$

**展开解析（依据原详解补足理由与步骤）：**

原射线次序AB、AD、AC、AE，BAC=DAE，分别写BAC=BAD+DAC、DAE=DAC+CAE，共减DAC得BAD=CAE。再用AB=AC、AD=AE，两边及夹角，△ABD≌△ACE（SAS）。D不一定在BE的中点，只因图中D连到共顶点A不能加中点条件。模型的关键是两组同顶点等腰边以及相等旋转角，不是任意两个等腰都能连成这对全等。

### 截长补短原两证证明AB等AC加BD

> 来源ID Q20-16；第20章全等三角形；201-250/full.md 第3021–3033行。原答案与解析定位：201-250/full.md 第3035–3093行。

例5 如图, $AC \parallel BD$ , $AE$ 、 $BE$ 分别平分 $\angle CAB$ 和 $\angle DBA$ , $CD$ 过点 $E$ . 求证: $AB = AC + BD$ .

![](图片/20-原图-b170a511ab32.webp)

**原资料答案与解析：**

证明 证法一(截长法): 如图, 在线段 AB 上截取 AF = AC, 连接 EF.

![](图片/20-原图-82ce1155b9e2.webp)

∵ AE, BE 分别平分 $\angle CAB$ 和 $\angle DBA$ , ∴ $\angle 1 = \angle 2$ , $\angle 3 = \angle 4$ .

在 $\triangle ACE$ 和 $\triangle AFE$ 中， $\left\{\begin{aligned}AC&=AF,\\ \angle1&=\angle2,\therefore\triangle ACE\cong\triangle AFE(SAS),\therefore\angle5=\angle C.\\ AE&=AE,\end{aligned}\right.$

$\because AC \parallel BD, \therefore \angle C + \angle D = 180^{\circ}$ . 又 $\because \angle 5 + \angle 6 = 180^{\circ}, \therefore \angle 6 = \angle D.$

在 $\triangle EFB$ 和 $\triangle EDB$ 中， $\left\{\begin{aligned}\angle6&=\angle D,\\ \angle3&=\angle4,\\ BE&=BE,\end{aligned}\right.$

$\therefore \triangle EFB \cong \triangle EDB(AAS), \therefore FB = BD. \therefore AB = AF + FB = AC + BD.$

证法二(补短法):如图,延长AC到点G,使AG=AB,连接EG.

![](图片/20-原图-87f1fbc7d2c2.webp)

∵ AE, BE 分别平分 $\angle CAB$ 和 $\angle DBA$ , ∴ $\angle 1 = \angle 2$ , $\angle 3 = \angle 4$ .

在 $\triangle AEG$ 和 $\triangle AEB$ 中， $\left\{\begin{aligned}AG&=AB,\\ \angle1&=\angle2,\therefore\triangle AEG\cong\triangle AEB(SAS).\\ AE&=AE,\end{aligned}\right.$

$\therefore EG = BE, \angle G = \angle 3.$ 又 $\because \angle 3 = \angle 4, \therefore \angle G = \angle 4.$ $\because AC \parallel BD, \therefore \angle GCE = \angle D.$

在 $\triangle CEG$ 和 $\triangle DEB$ 中， $\left\{\begin{aligned}\angle GCE&=\angle D,\\ \angle G&=\angle4,\\ EG&=EB,\end{aligned}\right.$ $\therefore\triangle CEG\cong\triangle DEB(AAS),$

$\therefore CG=BD,\because AB=AG=AC+CG,\therefore AB=AC+BD.$

**展开解析（依据原详解补足理由与步骤）：**

先说明作图存在性，避免以目标倒推AC<AB：记A半角α、B半角β，AC∥BD用AB截得两整角互补，所以α+β90°；△ABE内角和给AEB90°。C-E-D共线，CEA+AEB+BED=180°，故CEA+BED90°，两个非退化小角均正，CEA<90°。在射线AB截AF=AC，用AE共同和A处平分夹角，△AFE≌△ACE（SAS），于是AEF=CEA<90°；EF落在直角AEB内部，交基线AB只能落A、B之间，所以AF<AB，合法截点F存在，也就独立证明AC<AB。

截长法：第一全等给AFE=ACE；AC∥BD且C-E-D共线给ACE+BDE180°；A-F-B共线给AFE+EFB180°，故EFB=BDE。同B处平分得EBF=EBD，BE共同，AAS使△EFB≌△EDB，得到FB=DB；AB=AF+FB=AC+BD。

补短法：已知AC<AB，沿AC延到G使AG=AB，连EG。AE共同、A处夹角平分、AG=AB，SAS给△AEG≌△AEB，EG=EB、AGE=ABE；B处平分使ABE=EBD，因此AGE=EBD。AC∥BD及C-E-D共线使GCE=BDE；两角及非夹边EG=EB，△CEG≌△DEB（AAS），得CG=DB。AG=AC+CG、AG=AB，故同样AB=AC+BD。两证原详解完整保留，补足等角加减和截点存在，不以示意长短当证据。

### 边6等腰直角截取等边全等转面积9

> 来源ID Q20-19；第20章全等三角形；201-250/full.md 第3168–3189行。原答案与解析定位：201-250/full.md 第3199–3205行。

例2 (2024 广东广州) 如图, 在 $\triangle ABC$ 中, $\angle A = 90^{\circ}$ , AB = AC = 6, D 为边 BC 的中点, 点 E, F 分别在边 AB, AC 上, AE = CF, 则四边形 AEDF 的面积为 ( )

![](图片/20-原图-59f2a8bc844e.webp)

A.18

B. $9\sqrt{2}$

C.9

D. $6\sqrt{2}$

**原资料答案与解析：**

例2 解析 连接 AD, 由题意得 $\angle DAE = \angle C = 45^{\circ}, AD = CD$ , 又 AE = CF, 所以 $\triangle DAE \cong \triangle DCF$ , 所以 $S_{四边形AEDF}=S_{\triangle DAE}+S_{\triangle DAF}=S_{\triangle DCF}+$

$$
S _ {\triangle D A F} = \frac {1}{2} S _ {\triangle A B C} = \frac {1}{2} \times \frac {1}{2} \times 6 \times 6 = 9.
$$

答案 C

**展开解析（依据原详解补足理由与步骤）：**

AB=AC6、A90°，原等腰直角，B=C45°。D为BC中点，等腰三线合一使AD⊥BC且平分A，DAE45°；斜边中点D到A、C等距，也可用△ADC两锐角均45°得到AD=CD。AE=CF，DAE=DCF45°，AD=CD，SAS使△DAE≌△DCF。目标AEDF由DAE、DAF两块构成，替DAE为DCF后成为ACD；AD中线分ABC为两等面积，面积=半×(6×6/2)=9。A18是整个ABC，错；B9√2把斜线长度误入面积，错；C9正确；D6√2是原斜边BC的长度数值，量纲和图形均不是所求面积，错。选C。边上E/F在端点时四边形可能退化，原按非退化图讨论全等，极端面积仍可按同底高直接核为9，不假装退化三角形满足通常判据。

## 易错

原ABD与ACE的角选B与C才是AB/BD、AC/CE的夹角；选A处某角未由已知证明，不能偷用。弧题半径与公共线段相等还需等弧给中央夹角。
