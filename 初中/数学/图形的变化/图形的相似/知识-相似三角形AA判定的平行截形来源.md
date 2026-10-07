---
标题: 相似三角形AA判定的平行截形来源
别名: ["两角判相似", "AA相似"]
前置: ["知识-相似三角形的对应角与边比", "知识-三角形内角和定理"]
---

## 讲解

### 是什么

两组三角形角分别相等，第三角由内角和也相等，可以判相似，称AA。须是不同的两组角，不是同一角以两种名称重复写。相似关系用顶点顺序表达对应，先配角，再写边比。

共有角、对顶角、平行同位/内错角、直角与等角的余角是常见入口。

### 怎么来的

设两三角A/A′、B/B′分别等。在较大的三角两边截取一条边长与小形对应边相等，作平行于第三边的截线；由平行角得到截下小三角与目标小形的ASA全等，而它又是原大三角的平行截形，边比由截线比例给出。因此原两个三角不仅角同，也三边同比。先用平行截形建同比，再用角边角保证形状一致，是AA成立的理由。若哪条边较长不固定，可以交换两图进行同一构造。

### 什么时候能用

母子模型中斜边高制造两个直角，另共有一锐角，AA成立；折矩形一线三直角先用平角同减得到第二组角等再判。仅一个共有角不够，等腰附条件可补第二角。

## 例题

### 两中线中位线找A与X两对并按附角再找两对

> 来源ID Q26-16；第26章相似；301-350/full.md 第2059–2062行。原答案与解析定位：301-350/full.md 第2064–2074行。

例5 (A型、X型)如图,在 $\triangle ABC$ 中,两条中线BE,CD相交于点O.

(1) 写出图中两对相似的三角形.  
(2) 若 $\angle BOD = \angle A$ ，写出与(1)中不同的两对相似三角形.

![](图片/26-原图-8c9ae4ffe645.webp)

**原资料答案与解析：**

解析 (1) $\because BE, CD$ 是 $\triangle ABC$ 的两条中线, $\therefore DE$ 是 $\triangle ABC$ 的中位线, $\therefore DE \parallel BC$ ,

$$
\therefore \triangle A B C \sim \triangle A D E, \triangle B O C \sim \triangle E O D.
$$

(2) 当 $\angle BOD = \angle A$ 时, $\because \angle OBD = \angle ABE, \therefore \triangle OBD \sim \triangle ABE.$

$$
\because \angle C O E = \angle B O D = \angle A, \angle O C E = \angle A C D, \therefore \triangle O C E \sim \triangle A C D.
$$

**展开解析（依据原详解补足理由与步骤）：**

(1)BE/CD为中线，E/D分别是AC/AB中点，DE为中位线，DE∥BC。由共有A角和一对平行角，△ABC∽△ADE；由O处对顶角与平行角，△BOC∽△EOD。(2)新增∠BOD=∠A时，OB与BE共线、BD与BA共线，∠OBD=∠ABE，配新增角得△OBD∽△ABE。∠COE=∠BOD为对顶角，且∠OCE=∠ACD，得到△OCE∽△ACD。每一对各写两角来源，不能因共用O就认所有小三角相似。

### 矩形折A到DC上的M用三直角补角证明NDM与MCB相似

> 来源ID Q26-17；第26章相似；301-350/full.md 第2076–2084行。原答案与解析定位：301-350/full.md 第2086–2092行。

例6 (一线三等角型)在综合与实践课上,老师组织同学们以“矩形的折叠”为主题开展数学活动.有一张矩形纸片ABCD如图所示,点N在边AD上,现将矩形折叠,折痕为BN,点A对应的点记为点M,若点M恰好落在边DC上,求证:△NDM∽△MCB.

![](图片/26-原图-45df607c537b.webp)

**原资料答案与解析：**

证明 ∵ 四边形 ABCD 是矩形, ∴ $\angle A = \angle D = \angle C = 90^{\circ}$ .

由折叠的性质可知 $\angle NMB = \angle A = 90^{\circ}$ ，∴ $\angle D = \angle NMB = \angle C.$

$$
\because \angle N M D + \angle D + \angle M N D = 1 8 0 ^ {\circ}, \angle N M D + \angle N M B + \angle B M C = 1 8 0 ^ {\circ}, \therefore \angle M N D = \angle B M C, \therefore \triangle N D M \sim \triangle M C B.
$$

**展开解析（依据原详解补足理由与步骤）：**

矩形D/C均90°，折A到M保持∠NMB=∠A90°。原D-M-C共线，平角给∠NMD+90°+∠BMC=180°；△NDM内角和给∠NMD+90°+∠MND=180°。同减NMD与90，MND=BMC。再D=C90°，AA得△NDM∽△MCB。折叠保证右角但不保证两三角对应边等长，所以结论是相似，不随意升为全等。

### 等边交叉六十用余角相等AA证AE平方等BE乘PE

> 来源ID Q26-20；第26章相似；301-350/full.md 第2170–2183行。原答案与解析定位：301-350/full.md 第2185–2185行。

例9 如图,在等边三角形 ABC 的边 AC, BC 上各取一点 E, F, 连接 AF, BE, 相交于点 P, $\angle BPF = 60^{\circ}$ . 求证: $AE^{2} = BE \cdot PE$ .

![](图片/26-原图-9ee758c81ffb.webp)

**原资料答案与解析：**

证明 $\because \triangle ABC$ 为等边三角形, $\therefore \angle BAC = 60^{\circ}, \therefore \angle BAP + \angle EAP = 60^{\circ}, \because \angle BPF = 60^{\circ}, \therefore \angle BAP + \angle ABE = 60^{\circ}, \therefore \angle EAP = \angle ABE$ , 又 $\because \angle AEP = \angle AEB, \therefore \triangle AEP \sim \triangle BEA, \therefore \frac{PE}{AE} = \frac{AE}{BE}, \therefore AE^{2} = BE \cdot PE.$

**展开解析（依据原详解补足理由与步骤）：**

等边ABC使BAC60，故BAP+EAP=60。P在AF上且P-F与P-A反向，BPF60是△ABP的外角，BAP+ABE=60。两式同减BAP得EAP=ABE。E-P-B按序，AEP与AEB同角；AA得△AEP∽△BEA。按对应P↔A、A↔B、E↔E，PE/AE=AE/BE，乘正数AE·BE得AE²=BE·PE。不要把两端平方项当作任意同一边拼出；比例必须从这套对应顺序来。

### 添相似条件按ADE对ACB的交换顺序

> 来源ID Q26-21；第26章相似；301-350/full.md 第2224–2226行。原答案与解析定位：301-350/full.md 第2201–2203行。

例1 (2024 山东滨州) 如图, 在 $\triangle ABC$ 中, 点 $D, E$ 分别在边 $AB, AC$ 上. 添加一个条件使 $\triangle ADE \sim \triangle ACB$ , 则这个条件可以是 \_\_\_\_. (写出一种情况即可)

![](图片/26-原图-346d8d68e0c4.webp)

**原资料答案与解析：**

例1 解析 $\because \angle DAE = \angle CAB$ ， $\therefore$ 添加条件 $\angle ADE = \angle C$ 或 $\angle AED = \angle B$ 或 $AD: AC = AE: AB$ ，均可判定 $\triangle ADE \sim \triangle ACB$ .

答案 $\angle ADE = \angle C$ （答案不唯一）

**展开解析（依据原详解补足理由与步骤）：**

共有A角相等，但指定△ADE∽△ACB表示D↔C、E↔B。可添加ADE=C；则两角等AA相似。也可添加AED=B；或AD/AC=AE/AB，等A夹角两邻边比例，SAS相似。题只需一种，可写ADE=C；不随意写DE∥BC，因为平行通常给ADE∽ABC而不是已指定的ACB交换顺序。

### 镜中楼顶眼高一点六镜距一点五楼距二十求21点3

> 来源ID Q26-25；第26章相似；301-350/full.md 第2395–2403行。原答案与解析定位：301-350/full.md 第2405–2423行。

例1 如图,小明为了测量楼房MN的高度,在离N点20 m的A处放了一个平面镜(平面镜的厚度忽略不计),小明从A处沿NA方向走到C点,正好从镜中看到楼顶M点,若AC=1.5 m,小明眼睛离地面的高度BC为1.6 m,则楼房MN的高度约为\_\_\_\_(结果保留小数点后一位).

![](图片/26-原图-5111363ab7b3.webp)

**原资料答案与解析：**

解析：光线的反射角等于入射角，且等角的余角相等，

$$
\begin{array}{l} \therefore \angle B A C = \angle M A N. \because B C \perp C N, \\ M N \perp C N, \therefore \angle B C A = \angle M N A = \\ 9 0 ^ {\circ}, \therefore \triangle B C A \sim \triangle M N A. \end{array}
$$

$$
\therefore \frac {B C}{M N} = \frac {A C}{A N}, \text { 即 } \frac {1 . 6}{M N} = \frac {1 . 5}{2 0}.
$$

$$
\therefore M N = 1. 6 \times 2 0 \div 1. 5 \approx 2 1. 3 (\mathrm{m}).
$$

$$
\therefore \text {   楼房   } M N \text {   的高度约为   } 2 1. 3 \mathrm{m}.
$$

答案 $21.3\mathrm{m}$

**展开解析（依据原详解补足理由与步骤）：**

水平镜放A，反射角等入射角是光学原理；两光线与地面所夹角为这两法线角的余角，也相等。眼高BC和楼MN均垂直同一水平地面，C/N两角90°，AA得△BCA∽△MNA。BC/MN=AC/AN，1.6/MN=1.5/20，乘20MN得32=1.5MN，除1.5得MN=64/3≈21.3 m。采用眼睛高度1.6不是随意人体全高，镜若不水平、地面不同高度需另建模。

### 河岸X型两直角与对顶角一百一十比五十五求104

> 来源ID Q26-28；第26章相似；301-350/full.md 第2495–2507行。原答案与解析定位：301-350/full.md 第2509–2513行。

例2 如图,为了估算河的宽度,我们可以在河对岸的岸边选定一个目标,记为点A,再在河的另一边选定点B和点C,使 $AB\perp BC$ ,BC与河岸平行,再选定点E,使 $EC\perp BC$ ,用视线确定BC和AE的交点D.此时如果测得BD=110m,CD=55m,EC=52m,求河的宽度AB.

![](图片/26-原图-92f76ed528d2.webp)

**原资料答案与解析：**

解析 $\because AB\perp BC,EC\perp BC,\therefore \angle ABD = \angle ECD = 90^{\circ}$ ，又 $\because \angle ADB = \angle EDC,\therefore \triangle ABD\sim \triangle ECD,$

$\therefore \frac{AB}{EC}=\frac{BD}{CD}$ ，即 $\frac{AB}{52}=\frac{110}{55}$ ，解得AB=104.

∴ 河的宽度 AB 为 104 m.

**展开解析（依据原详解补足理由与步骤）：**

AB⊥BC、EC⊥BC，两三角B/C90°；D为两直线交点，ADB=EDC对顶角等，AA得△ABD∽△ECD。对应AB/EC=BD/CD，AB/52=110/55=2，AB104 m。图示B-D-C序，BD与CD分别两小三角底边，不把BC165误代任何一侧。垂直两岸与水平基线确保所得AB代表河宽。

### 斜边高母子三角三相似与一线三角原模型证明

> 来源ID Q26-39；第26章相似；301-350/full.md 第1788–1810行。原答案与解析定位：301-350/full.md 第1788–1810行。

# 2. 常见的基本图形

![](图片/26-原图-c5a5042ffa64.webp)  
图①

![](图片/26-原图-ed24bf8edda9.webp)  
图②

![](图片/26-原图-450d9f25a6c3.webp)  
图③

![](图片/26-原图-47e32284d230.webp)  
图④

![](图片/26-原图-029d02dfc827.webp)  
图⑤

![](图片/26-原图-5673d361fde7.webp)  
图⑥

图①和图②分别为“A型”图和“X型”图,条件是 $DE \parallel BC$ ,基本结论是 $\triangle ADE \sim \triangle ABC$ ;图③④是图①的变形图;图⑤是图②的变形图.

图⑥是“母子型”图,条件是 CD 为直角 $\triangle ABC$ 斜边上的高,基本结论是 $\triangle ACD \sim \triangle ABC \sim \triangle CBD$ .

**原资料答案与解析：**

# 2. 常见的基本图形

![](图片/26-原图-c5a5042ffa64.webp)  
图①

![](图片/26-原图-ed24bf8edda9.webp)  
图②

![](图片/26-原图-450d9f25a6c3.webp)  
图③

![](图片/26-原图-47e32284d230.webp)  
图④

![](图片/26-原图-029d02dfc827.webp)  
图⑤

![](图片/26-原图-5673d361fde7.webp)  
图⑥

图①和图②分别为“A型”图和“X型”图,条件是 $DE \parallel BC$ ,基本结论是 $\triangle ADE \sim \triangle ABC$ ;图③④是图①的变形图;图⑤是图②的变形图.

图⑥是“母子型”图,条件是 CD 为直角 $\triangle ABC$ 斜边上的高,基本结论是 $\triangle ACD \sim \triangle ABC \sim \triangle CBD$ .

**展开解析（依据原详解补足理由与步骤）：**

斜边高模型：ABC在C直角、CD⊥AB。ACD与ABC共有A角且D/C均90°，AA相似；CBD与ABC共有B角且D/C均90°，也相似；故三个三角按正确对应角顺序相似。进一步由AC/AB=AD/AC得AC²=AB·AD，由BC/AB=BD/BC得BC²=AB·BD，由AD/CD=CD/BD得CD²=AD·BD。这些乘积来自明确对应，不是所有共斜边的小三角都可用。原图只给模型，无独立数值题，不编题补空。

## 易错

图形像A/X不是证据，必须标两组角来自哪条已知。
