## FROM

https://github.com/lemonhu/NER-BERT-pytorch

## Entity
三种类型实体：Person，Organization，Location，and Other
对应缩写标签：PER，ORG，LOC and O

## classifier
没有 pooler

直接将每个token输出经过classifier后输出每个类别的概率