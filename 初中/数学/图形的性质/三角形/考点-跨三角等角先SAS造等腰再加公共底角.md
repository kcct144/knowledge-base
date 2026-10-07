---
标题: 跨三角等角先SAS造等腰再加公共底角
别名: ["全等配等腰求角相等"]
前置: []
知识: ["知识-全等三角形的SAS夹角判定", "知识-等腰三角形的等边等角与底边中线高线"]
---

## 讲解

### 判据

目标两角在不同三角形，给AB=AE、B=E、BC=DE，先SAS移边。

### 流程

1.ABC/AED列两边及夹角SAS，得AC=AD和ACB=ADE。2.同一ACD用等边对角ACD=ADC。3.按图目标分成ACB+ACD与ADE+ADC，两对对应角相加。4.每次等角在明确三角形中成立，不按相似五边形外观猜。

## 例题

### 两跨三角先SAS再等腰公共底角相加

> 来源ID Q21-11；第21章等腰三角形；201-250/full.md 第4150–4150行。原答案与解析定位：201-250/full.md 第4152–4166行。

例3 如图, 已知 $AB = AE$ , $\angle B = \angle E$ , $BC = DE$ , 求证: $\angle BCD = \angle EDC$ .

**原资料答案与解析：**

证明 在 $\triangle ABC$ 和 $\triangle AED$ 中， $\left\{ \begin{array}{l} AB = AE, \\ \angle B = \angle E, \therefore \triangle ABC \cong \triangle AED, \therefore AC = AD, \angle ACB = \angle ADE. \\ BC = DE, \end{array} \right.$

![](图片/21-原图-fae8351886b1.webp)

$\therefore \angle ACD = \angle ADC \therefore \angle ACD + \angle ACB = \angle ADC + \angle ADE$ 即 $\angle BCD = \angle EDC.$

**展开解析（依据原详解补足理由与步骤）：**

ABC与AED中AB=AE、B=E为给边夹角、BC=ED，SAS全等得AC=AD与ACB=ADE。ACD中AC=AD，等边对等角使ACD=ADC。原目标BCD= BCA+ACD，EDC=EDA+ADC，两对等角相加得到目标相等。原角不在同一三角形，不能直接说“等腰”省掉第一层跨三角SAS。

## 易错

原表格全等结论挤在前提中，先列完整条件再给结论。若射线次序换了，角可能相减。
