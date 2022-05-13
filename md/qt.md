
## 毒经


#### 设置

```
玉简；
技能cd监控:篾片蛊/蛊虫狂暴 蛊虫献祭 灵蛊;

/cast 攻击
/fcast 幻击
/fcast 影滞
```

#### 篾片蛊

> 尻尾,无常,黯影,虫兽,桃僵,不鸣,嗜蛊,祭礼,啖灵,篾片蛊,荒息,蛇悉

```
/cast 凤凰蛊
/cast 攻击
/fcast 幻击
/cast 蛊虫献祭
/cast [buff:蛊虫献祭] 篾片蛊
/cast [tnobuff:蛇影|tbufftime:蛇影<2.7] 蛇影
/cast 百足
/cast 蝎心
/cast 蟾啸
```

```
/cast 凤凰蛊
/cast 攻击
/fcast 幻击
/cast 蛊虫献祭
/cast [buff:蛊虫献祭] 篾片蛊
/cast [tnobuff:蛇影|tbufftime:蛇影<2.7] 蛇影
/cast 百足
/cast 灵蛊
/cast 蝎心
```


#### 蛊虫狂暴

> 尻尾,无常,黯影,虫兽,桃僵,不鸣,嗜蛊,祭礼,啖灵,蛊虫狂暴,荒息,蛇悉

```
/cast 凤凰蛊
/cast 蛊虫献祭
/cast 蛊虫狂暴
/cast 攻击
/fcast 幻击
/cast [tnobuff:蛇影|tbufftime:蛇影<2.7] 蛇影
/cast 百足
/cast 蝎心

/cast 蟾啸

/cast [mana<0.6] 灵蛊
```

```
/cast 凤凰蛊
/cast 蛊虫狂暴
/cast 蛊虫献祭
/fcast 攻击
/fcast 幻击
/cast [tnobuff:蛇影|tbufftime:蛇影<2.7] 蛇影
/cast 灵蛊
/cast 百足
/cast 蝎心
/cast 蟾啸
```





## 洗髓


#### 设置
```
技能cd监控:狮子吼 弘法 舍身;
```

#### 辅助


> 执迷不返,大明,抢珠式,归去来棍,禅语,立地成佛,天龙音,明王身,明心,轮回诀,独觉,舍身弘法

```
/cast [noskill:18623] 大狮子吼
/cast [qidian>2&bufftime:禅语>4|tnobuff:立地成佛] 立地成佛
/cast [qidian<2&tbuff:立地成佛<3|tbufftime:立地成佛<3] 擒龙诀
```


#### 承伤


> 执迷不返,大明,抢珠式,归去来棍,生缘,涅果,不畏,明王身,贞护,轮回诀,禅慧,舍身弘法


```
/cast [buff:大明&qidian>2] 罗汉金身
/cast [qidian>2] 韦陀献杵
/cast [nearby_enemy>1] 横扫六合1
/cast 大狮子吼
/cast [skill:17745] 般若诀
/cast 普渡四方
```