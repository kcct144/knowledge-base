---
标题: 直角三角形的HL斜边直角边判定
别名: ["HL", "斜边直角边全等"]
前置: ["知识-全等三角形的SSS三边判定", "知识-勾股定理"]
---

## 讲解

### 是什么

两个直角三角形，斜边与一条直角边分别对应相等，则全等，简记HL。必须先确认两个90°，斜边是各自直角的对边。两直角边对应相等也能用SAS，不是只有HL能证直角全等。

### 怎么来的

设两斜边均h、对应一腿均a，另一腿长b、b′正。勾股给b²=h²−a²、b′²=h²−a²，所以b²=b′²；正长度取同一正根，b=b′。三边现在对应相等，用SSS得到全等。HL看似一般SSA的形式，却多了直角条件，使第三边长度能被勾股唯一补出；这正是不能把它推广到任意三角形的原因。原书写例先从ABC90°与邻补得CBF90°，再确认AE/CF为斜边、AB/CB为腿。

### 什么时候能用

先写Rt或明示两个三角形直角位置，再列h、a两项。共享斜边AF是同一条线段，原双证题可用；已给边若其实两腿，选SAS夹角90°或其他合法判据，不能把任一边称斜边。h>a>0是非退化存在条件，原h=a会另一腿0。

## 例题

### HL原书先证明两个直角再列斜边和腿

> 来源ID Q20-11；第20章全等三角形；201-250/full.md 第2797–2810行。原答案与解析定位：201-250/full.md 第2799–2816行。

书写示例:如图,在 $\triangle ABC$ 中, $AB=CB,\angle ABC=90^{\circ},F$ 为AB延长线上一点,点E在BC上,且AE=CF.求证 $\triangle ABE\cong\triangle CBF$ .

证明：∵ $\angle ABC = 90^{\circ}$ , $\angle ABC + \angle CBF = 180^{\circ}$ ,
∴ $\angle CBF = 90^{\circ}$ .

![](图片/20-原图-df4d8e78b20f.webp)

**原资料答案与解析：**

证明：∵ $\angle ABC = 90^{\circ}$ , $\angle ABC + \angle CBF = 180^{\circ}$ ,
∴ $\angle CBF = 90^{\circ}$ .

![](图片/20-原图-df4d8e78b20f.webp)

在 Rt△ABE 和 Rt△CBF 中， $\left\{\begin{aligned}AE&=CF,\\ AB&=CB,\end{aligned}\right.$

$$
\therefore \mathrm{Rt} \triangle A B E \cong \mathrm{Rt} \triangle C B F (\mathrm{HL}).
$$

**展开解析（依据原详解补足理由与步骤）：**

ABC90°，F在AB反向延长线上，CBF=180°−ABC=90°，所以ABE与CBF确为两个直角三角形。AE、CF分别是其斜边，原给AE=CF；AB、CB为对应一条直角边，原给AB=CB。由HL得Rt△ABE≌Rt△CBF。不能只看两边等便用HL，首先必须核两个直角和哪边是斜边。

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

### 四种原角平分作图痕迹逐个全等或平行核

> 来源ID Q20-32；第20章全等三角形；201-250/full.md 第3717–3733行。原答案与解析定位：201-250/full.md 第3703–3705行。

例2（2024 山东烟台）某班开展“用直尺和圆规作角平分线”的探究活动,各组展示作图痕迹如下,其中射线 OP 为 $\angle AOB$ 的平分线的有()

![](图片/20-原图-a88c92a44660.webp)

A.1 个

![](图片/20-原图-517b782fc659.webp)

B.2 个

![](图片/20-原图-80fd3345f249.webp)

C.3 个

![](图片/20-原图-0bee1c210fa7.webp)

D.4 个

**原资料答案与解析：**

例2 解析 第一个图是尺规作已知角的平分线的常规方法;第二个图,通过多次证三角形全等,可推出 $\angle COP=\angle DOP$ ,故 $OP$ 平分 $\angle AOB$ ;第三个图,由作图知 $CP\parallel OB,\triangle OCP$ 是等腰三角形,可推出 $\angle COP=\angle BOP$ ,故 $OP$ 平分 $\angle AOB$ ;第四个图,由等腰三角形三线合一可推出 $OP$ 平分 $\angle AOB$ .

答案 D

**展开解析（依据原详解补足理由与步骤）：**

原四图均有效，选D4个；A1个、B2个、C3个都漏掉有效的另一构造。

图1同圆OC=OD、两等半径弧CP=DP、OP公共，SSS使OCP与ODP全等，COP=DOP。

图2两组同圆给OA=OB、OC=OD，原虚线AD、BC交P。△OAD与△OBC两边夹角SAS全等，得OAD=OBC、ODA=OCB。AC=OA−OC=OB−OD=BD，两端角经同线补角对应相等，ASA给△ACP≌△BDP，故CP=DP；再OC=OD、OP公共，SSS给△OCP≌△ODP，目标半角等。

图3复制的相应等角给CP∥OB，原以C圆心过O/P弧给CO=CP，因此OCP等腰，COP=CPO；OP截两平行线给CPO=BOP，等量代换得COP=BOP。

图4原OC=OD为等腰OCD，两弧确定OP⊥CD，P位于CD上（核原直角与作图痕迹）。等腰顶点的高与角平分线合一，COP=DOP；也可在两直角三角OCP、ODP用等斜边OC=OD及公共直角边OP，HL全等。每图使用其自己的等半径、平行或垂直条件，不能统一声称全都只是第一种常规画法。

### 原SSA与AAA两组反例图明确缺失判据

> 来源ID Q20-33；第20章全等三角形；201-250/full.md 第2698–2702；2820–2824行。原答案与解析定位：201-250/full.md 第2698–2702行；201-250/full.md 第2820–2824行。

“边边角”（或“SSA”）：两边和其中一边的对角分别相等的两个三角形全等. （×）

解读：如图，在 $\triangle ABP$ 和 $\triangle ACP$ 中， $\angle A = \angle A, AP = AP, BP = CP$ ，满足“SSA”，但它们不全等.

![](图片/20-原图-5ae4c7da24cc.webp)

“角角角”（或 “AAA”）：三个角分别相等的两个三角形全等. （×）

解读：如图，在 $\triangle ABC$ 和 $\triangle ADE$ 中， $\angle A = \angle A, \angle ADE = \angle B, \angle AED = \angle C$ ，满足 “AAA”，但它们不全等（形状相同但大小不相等）.

![](图片/20-原图-25a9a1227049.webp)

**原资料答案与解析：**

“边边角”（或“SSA”）：两边和其中一边的对角分别相等的两个三角形全等. （×）

解读：如图，在 $\triangle ABP$ 和 $\triangle ACP$ 中， $\angle A = \angle A, AP = AP, BP = CP$ ，满足“SSA”，但它们不全等.

![](图片/20-原图-5ae4c7da24cc.webp)

“角角角”（或 “AAA”）：三个角分别相等的两个三角形全等. （×）

解读：如图，在 $\triangle ABC$ 和 $\triangle ADE$ 中， $\angle A = \angle A, \angle ADE = \angle B, \angle AED = \angle C$ ，满足 “AAA”，但它们不全等（形状相同但大小不相等）.

![](图片/20-原图-25a9a1227049.webp)

**展开解析（依据原详解补足理由与步骤）：**

原SSA图ABP与ACP共有AP及A角，BP=CP，但给定角A不夹在已给AP、BP之间，另一侧交点B、C可在同一射线上不同位置，不能固定第三边，原两三角不全等。原AAA图ABC与ADE三个对应角等，却一个是另一个放大或缩小，边未等，不能全等。原后段AAA图另接完整原文，结论只是相似或缺尺寸，不新增数值反例。直角三角形若等的是斜边与一腿，可以用HL；这是一组额外直角前提，不能当一般SSA合法。

## 易错

原只有两边一对非夹角、且无直角，仍属不保证全等的SSA。原第二证AF公共斜边，AB=AD一腿，得BF=DF后才作差CF=EF。
