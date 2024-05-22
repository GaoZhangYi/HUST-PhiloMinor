目录
Compound statements 复合陈述
	conjunction 和取
	negation 否定
	disjunction 析取
	conditional  条件
classifying statements 陈述的分类
陈述的关系
### 陈述
三段论：对象是词项terms
命题逻辑：对象是whole statements
构成逻辑语言——消除歧义
#### logical language
translate natural language to logical language 
则用==真值表==来直接判断有效性
#### 简单陈述
不包含其他陈述
不需要连接词就可以表达
#### Compound statements 复合陈述
##### negation 否定陈述
¬ P
##### conjunction 和取陈述
P∧Q 并且
其中一个命题是合取支
##### disjunction （相容的）析取陈述
P∨Q 或者
相容的析取陈述——可以同真→一般都是这个定义
不相容的——不能同真；两个都为真的时候复合陈述为假
##### conditional statements 条件陈述
P→Q if…then… 
P为前件antecedent；Q为后件consequent
只有P为真，但是Q为假的时候能否定掉这个条件陈述
既没有断言A 也没有断言B

命题逻辑的漏洞：前件和后件可以不相干，这毫无意义

命题逻辑 四个真值，四个连接符

| P | Q | ¬ P | P∧Q | P∨Q  | P→Q  |
| ---- | ---- | ---- | ---- | ---- | ---- |
| T | T | T | T | T | T |
| <font color="#ff0000">T</font> | <font color="#ff0000">F</font> | T | F | T | <font color="#ff0000">**F**</font> |
| F | T | F | F | T | T |
| F | F | F | F | F | T |
亚里士多德认为逻辑只需要研究必然性，即演绎逻辑
命题逻辑
### 陈述的分类（按照真值分类）
↓可以涵盖全部陈述
偶真式contingent: truth value **varies**
重言式tautology: truth value always true
A∨¬ A
矛盾式 self-contradictory: always false
A∧ ¬ A 
### 陈述的比较（陈述之间关系的分类）
equivalent 等值: they are both true or false in every possible circumstance
(A→B)  &  (¬B → ¬A)
contradictory 矛盾: they have opposite truth value in every possible circumstance
(A→B) & ( A ∧ ¬B) 
consistent 一致: 至少存在一种取值，使得两个陈述的值都为真
### 必要条件和充分条件
A是B的充分条件：如果A则B 只有B才A
A是B的必要条件：如果B则A  如果非A则非B
### 论证的真值表
练习….a lot
### 运用真值表方法判断有效性
如果前提为真时，结论都为真，则有效
不用管前提为假的情况
列表：P1，P2为T的那行，C是否为T
### 一些有效的论证形式
#### Disjunctive syllogism（析取论证）

#### Modus Ponens（肯定前件式）
#### Modus Tollens（否定后件式）
#### Hypothetical syllogism（假言论证）

#### Dilemma/No matter what（二难论证）
