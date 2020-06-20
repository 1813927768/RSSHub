---
pageClass: routes
---

# 大学通知

## MIT

### MIT graduateadmissions's all blogs

<Route author="LogicJake" example="/mit/graduateadmissions/index/all" path="/mit/graduateadmissions/index/all"/>

### MIT graduateadmissions's blogs by department

<Route author="LogicJake" example="/mit/graduateadmissions/department/eecs" path="/mit/graduateadmissions/department/:name" :paramsDesc="['department name which can be found in url']"/>

### MIT graduateadmissions's blogs by category

<Route author="LogicJake" example="/mit/graduateadmissions/category/beyond-the-lab" path="/mit/graduateadmissions/category/:name" :paramsDesc="['category name which can be found in url']"/>

## Polimi

### News

<Route author="exuanbo" example="/polimi/news" path="/polimi/news/:language?" :paramsDesc="['English language code en']" />

## 安徽工业大学

### 教务处

<Route author="Diffumist" example="/ahut/jwc" path="/ahut/jwc" />

### 学校要闻

<Route author="Diffumist" example="/ahut/news" path="/ahut/news" />

### 计算机学院公告

<Route author="Diffumist" example="/ahut/cstzgg" path="/ahut/cstzgg" />

## 安徽农业大学

### 计算机学院

<Route author="SimonHu-HN" example="/ahau/cs_news/xxtg" path="/ahau/cs_news/:type" :paramsDesc="['类型名']">

| 信息通告 | 新闻动态 |
| -------- | -------- |
| xxtg     | xwddyn   |

</Route>

### 教务处

<Route author="SimonHu-HN" example="/ahau/jwc/jwyw" path="/ahau/jwc/:type" :paramsDesc="['类型名']">

| 教务要闻 | 通知公告 |
| -------- | -------- |
| jwyw     | tzgg     |

</Route>

### 安农大官网新闻

<Route author="SimonHu-HN" example="/ahau/main/xnyw" path="/ahau/main/:type" :paramsDesc="['类型名']">

| 校内要闻 | 学院动态 |
| -------- | -------- |
| xnyw     | xydt     |

</Route>

## 安徽医科大学

### 研究生学院通知公告

<Route author="Origami404" example="/ahmu/news" path="/ahmu/news" />

## 北华航天工业学院

### 新闻

<Route author="SunShinenny" example="/nciae/news" path="/nciae/news" />

### 学术信息

<Route author="SunShinenny" example="/nciae/xsxx" path="/nciae/xsxx" />

### 通知公告

<Route author="SunShinenny" example="/nciae/tzgg" path="/nciae/tzgg" />

## 北京大学

### 信科公告通知

<Route author="Ir1d" example="/pku/eecs/0" path="/pku/eecs/:type" :paramsDesc="['分区 type, 可在网页 URL 中找到']">

| 全部 | 学院通知 | 人事通知 | 教务通知 | 学工通知 | 科研通知 | 财务通知 | 工会通知 | 院友通知 |
| ---- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 0    | 1        | 2        | 6        | 8        | 7        | 5        | 3        | 4        |

</Route>

### 每周一推 - 中国政治学研究中心

<Route author="vhxubo" example="/pku/rccp/mzyt" path="/pku/rccp/mzyt" />

### 生命科学学院近期讲座

<Route author="TPOB" example="/pku/cls/lecture" path="/pku/cls/lecture" />

### 北大未名 BBS 全站十大

<Route author="wooddance" example="/pku/bbs/hot" path="/pku/bbs/hot">

::: warning 注意

论坛部分帖子正文内容的获取需要用户登录后的 Cookie 值，详情见部署页面的配置模块。

:::

</Route>

## 北京航空航天大学

### 北京航空航天大学

<Route author="AlanDecode" example="/buaa/news/zonghe" path="/buaa/news/:type" :paramsDesc="['新闻版块']">

| 综合新闻 | 信息公告 | 学术文化     | 校园风采 | 科教在线 | 媒体北航 | 专题新闻 | 北航人物 |
| -------- | -------- | ------------ | -------- | -------- | -------- | -------- | -------- |
| zonghe   | gonggao  | xueshuwenhua | fengcai  | kejiao   | meiti    | zhuanti  | renwu    |

</Route>

## 北京科技大学天津学院

### 北京科技大学天津学院

<Route author="henbf" example="/ustb/tj/news/all" path="/ustb/tj/news/:type" :paramsDesc="['默认为 `all`']">

| 全部 | 学院新闻 | 学术活动 | 城市建设学院 | 信息工程学院 | 经济学院 | 管理学院 | 材料系 | 机械工程系 | 护理系 | 法律系 | 外语系 | 艺术系 |
| ---- | -------- | -------- | ------------ | ------------ | -------- | -------- | ------ | ---------- | ------ | ------ | ------ | ------ |
| all  | xyxw     | xshhd    | csjsxy       | xxgcxy       | jjx      | glxy     | clx    | jxgcx      | hlx    | flx    | wyx    | ysx    |

</Route>

## 北京理工大学

### 教务处通知

<Route author="sinofp" example="/bit/jwc" path="/bit/jwc" />

### 计院通知

<Route author="sinofp" example="/bit/cs" path="/bit/cs" />

## 北京林业大学

### 绿色新闻网

<Route author="markmingjie" example="/bjfu/news/lsyw" path="/bjfu/news/:type" :paramsDesc="['新闻栏目']">

| 绿色要闻 | 校园动态 | 教学科研 | 党建思政 | 一周排行 |
| -------- | -------- | -------- | -------- | -------- |
| lsyw     | xydt     | jxky     | djsz     | yzph     |

</Route>

### 研究生院培养动态

<Route author="markmingjie" example="/bjfu/grs" path="/bjfu/grs" />

### 科技处通知公告

<Route author="markmingjie" example="/bjfu/kjc" path="/bjfu/kjc" />

### 教务处通知公告

<Route author="markmingjie" example="/bjfu/jwc/jwkx" path="/bjfu/jwc/:type" :paramsDesc="['通知类别']">

| 教务快讯 | 考试信息 | 课程信息 | 教改动态 | 图片新闻 |
| -------- | -------- | -------- | -------- | -------- |
| jwkx     | ksxx     | kcxx     | jgdt     | tpxw     |

</Route>

## 北京邮电大学

### 硕士研究生招生通知

<Route author="ihewro" example="/bupt/yz/int" path="/bupt/yz/:type" :paramsDesc="['学院英文缩写']">

| 综合 | 信息与通信工程学院 | 电子工程学院 | 计算机学院 | 自动化学院 | 软件学院 | 数字媒体与设计艺术学院 | 网络空间安全学院 | 理学院 | 经济管理学院 | 人文学院 | 马克思主义学院 | 网络技术研究院 | 信息光子学与光通信研究院 |
| ---- | ------------------ | ------------ | ---------- | ---------- | -------- | ---------------------- | ---------------- | ------ | ------------ | -------- | -------------- | -------------- | ------------------------ |
| all  | sice               | see          | scs        | sa         | sse      | sdmda                  | scss             | sci    | sem          | sh       | mtri           | int            | ipoc                     |

</Route>

### 研究生院通知

<Route author="RicardoMing" example="/bupt/grs" path="/bupt/grs" />

### 信息门户

<Route author="RicardoMing wzekin" example="/bupt/portal" path="/bupt/portal" />

### 校园新闻

<Route author="wzekin" example="/bupt/news" path="/bupt/news" />

### BTBYR 趣味盒

<Route author="prnake" example="/bupt/funbox" path="/bupt/funbox" />
::: warning 注意

由于需要登陆 BTBYR 后的 Cookie 值，所以只能自建，并且部署和订阅端均需支持 IPV6 网络或使用镜像站点。

:::

## 常州大学

### 教务处

<Route author="richardchien" example="/cczu/jwc/1425" path="/cczu/jwc/:category?" :paramsDesc="['可选, 默认为 `all`']">

| 全部 | 通知公告 | 教务新闻 | 各类活动与系列讲座 | 本科教学工程 | 他山之石 | 信息快递 |
| ---- | -------- | -------- | ------------------ | ------------ | -------- | -------- |
| all  | 1425     | 1437     | 1485               | 1487         | 1442     | 1445     |

</Route>

### 新闻网

<Route author="richardchien" example="/cczu/news/6620" path="/cczu/news/:category?" :paramsDesc="['可选, 默认为 `all`']">

| 全部 | 常大要闻 | 校园快讯 | 媒体常大 | 时事热点 | 高教动态 | 网上橱窗 | 新媒常大 |
| ---- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| all  | 6620     | 6621     | 6687     | 6628     | 6629     | 6640     | 6645     |

</Route>

## 成都信息工程大学

### 成信新闻网

<Route author="kimika" example="/cuit/cxxww/1" path="/cuit/cxxww/:type?" :paramsDesc="['默认为 `1`']">

| 综合新闻 | 信息公告 | 焦点新闻 | 学术动态 | 工作交流 | 媒体成信 | 更名专题 | 文化活动 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 1        | 2        | 3        | 4        | 5        | 7        | 9        | 10       |

</Route>

## 大连大学

### 教务处信息

<Route author="SettingDust" example="/dlu/jiaowu/news" path="/dlu/jiaowu/news">
</Route>

## 大连工业大学

### 教务处新闻

<Route author="xu42" example="/dpu/jiaowu/news/2" path="/dpu/jiaowu/news/:type?" :paramsDesc="['默认为 `2`']">

| 新闻动态 | 通知公告 | 教务文件 |
| -------- | -------- | -------- |
| 2        | 3        | 4        |

</Route>

### 网络服务新闻

<Route author="xu42" example="/dpu/wlfw/news/2" path="/dpu/wlfw/news/:type?" :paramsDesc="['默认为 `1`']">

| 新闻动态 | 通知公告 |
| -------- | -------- |
| 1        | 2        |

</Route>

## 大连海事大学

### 新闻网

<Route author="arjenzhou" example="/dlmu/news/hdyw" path="/dlmu/news/:type" :paramsDesc="['默认为 `hdyw`']">

| 海大要闻 | 媒体海大 | 综合新闻 | 院系风采 | 海大校报 | 理论园地 | 海大讲坛 | 艺文荟萃 |
| :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|   hdyw   |   mthd   |   zhxw   |   yxfc   |   hdxb   |   llyd   |   hdjt   |   ywhc   |

</Route>

### 研究生院

#### 招生工作

<Route author="nczitzk" example="/dlmu/grs/zsgz/ssyjs" path="/dlmu/grs/zsgz/:type" :paramsDesc="['招生类别']">

| 博士研究生 | 硕士研究生 | 同等学力攻读硕士学位 | 港澳台地区招生 |
| :--------: | :--------: | :------------------: | :------------: |
|    bsyjs   |    ssyjs   |      tdxlgdssxw      |     gatdqzs    |

</Route>

## 电子科技大学

### 教务处

<Route author="achjqz" example="/uestc/jwc/student" path="/uestc/jwc/:type?" :paramsDesc="['默认为 `important`']">

| 重要公告  | 学生事务公告 | 教师事务公告 |
| --------- | ------------ | ------------ |
| important | student      | teacher      |

</Route>

### 新闻中心

<Route author="achjqz" example="/uestc/news/culture" path="/uestc/news/:type?" :paramsDesc="['默认为 `announcement`']">

| 学术    | 文化    | 公告         | 校内通知     |
| ------- | ------- | ------------ | ------------ |
| academy | culture | announcement | notification |

</Route>

### 计算机科学与工程学院

<Route author="talengu" example="/uestc/cs/ztlj*xskb" path="/uestc/cs/:type?" :paramsDesc="['默认为 `ztlj*xskb`']">

| 学院新闻   | 学生科    | 教务科    | 研管科    | 学术看板   |
| ---------- | --------- | --------- | --------- | ---------- |
| xwzx\*xyxw | tzgg\*xsk | tzgg\*jwk | tzgg\*ygk | ztlj\*xskb |

注 1: xwzx\*xyxw 对应 <http://www.scse.uestc.edu.cn/xwzx/xyxw.htm> ;
tzgg\*xsk 对应 <http://www.scse.uestc.edu.cn/tzgg/xsk.htm>

可自定义设置

注 2; 用 + 号来叠加 学生科 + 教务科 `/uestc/cs/ztlj*xskb+tzgg*jwk`

</Route>

### 自动化工程学院

<Route author="talengu" example="/uestc/auto/tzgg1" path="/uestc/news/:type?" :paramsDesc="['默认为 `tzgg1`']">

| 通知公告 | 学术看板 | 焦点新闻 | 综合新闻 |
| -------- | -------- | -------- | -------- |
| tzgg1    | xskb1    | jdxw     | zhxw1    |

注 1: tzgg1 对应 <http://www.auto.uestc.edu.cn/index/tzgg1.htm> ;
xskb1 对应 <http://www.auto.uestc.edu.cn/index/xskb1.htm>

可自定义设置

注 2: 用 + 号来叠加，通知公告 + 学术看板 `/uestc/auto/tzgg1+xskb1`

</Route>

## 东北大学

### 东北大学新闻网

<Route author="JeasonLau" example="/neu/news/ddyw" path="/neu/news/:type" :paramsDesc="['种类名']">

| 东大要闻 | 媒体东大 | 通知公告 | 新闻纵横 | 人才培养 | 学术科研 | 英文新闻 | 招生就业 | 考研出国 | 校园文学 | 校友风采 | 时事热点 | 教育前沿 | 文化体育 | 最新科技 |
| -------- | -------- | -------- | -------- | -------: | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| ddyw     | mtdd     | tzgg     | xwzh     |     rcpy | xsky     | 217      | zsjy     | kycg     | xywx     | xyfc     | ssrd     | jyqy     | whty     | zxkj     |

</Route>

## 东莞理工学院

### 教务处通知

<Route author="AnyMoe" example="/dgut/jwc/" path="/dgut/jwc/:type?" :paramsDesc="['默认为 `2`']">

| 教务公告 | 教学信息 |
| -------- | -------- |
| 1        | 2        |

</Route>

### 学工部动态

<Route author="AnyMoe" example="/dgut/xsc/" path="/dgut/xsc/:type?" :paramsDesc="['默认为 `2`']">

| 学工动态 | 通知公告 | 网上公示 |
| -------- | -------- | -------- |
| 1        | 2        | 4        |

</Route>

## 东南大学

### 信息科学与工程学院学术活动

<Route author="HenryQW" example="/seu/radio/academic" path="/seu/radio/academic"/>

### 研究生招生网通知公告

<Route author="Chingyat" example="/seu/yzb/1" path="/seu/yzb/:type" :paramsDesc="['1 为硕士招生, 2 为博士招生, 3 为港澳台及中外合作办学']"/>

### 东南大学计算机技术与工程学院

<Route author="LogicJake" example="/seu/cse/xyxw" path="/seu/cse/:type?" :paramsDesc="['分类名(默认为xyxw)']">

| 学院新闻 | 通知公告 | 教务信息 | 就业信息 | 学工事务 |
| -------- | -------- | -------- | -------- | -------- |
| xyxw     | tzgg     | jwxx     | jyxx     | xgsw     |

</Route>

## 广东工业大学

### 校内新闻网

<Route author="Jiangming1399" example="/gdut/news" path="/gdut/news"/>

## 广东海洋大学

### 广东海洋大学

<Route author="Xiaotouming" example="/gdoujwc" path="/gdoujwc"/>

## 广州大学

## 广州大学研招网通知公告

<Route author="sushengmao" example="/gzyjs" path="/gzyjs" />

## 桂林电子科技大学

### 新闻资讯

<Route author="cssxsh" example="/guet/xwzx/xykx" path="/guet/xwzx/:type" :paramsDesc="['资讯类型，如下表']">

| 桂电要闻 | 文明校园建设 | 桂电新闻 | 校园快讯 | 学院动态 | 媒体桂电 | 通知公告 | 招标公示 | 学术活动 |
| -------- | ------------ | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| gdyw     | wmxyjs       | gdxw     | xykx     | xydt     | mtgd     | tzgg     | zbgs     | xshd     |

注 1: 不要吐槽拼音缩写，缩写原本的 URL 构成就这样。

</Route>

## 桂林航天工业学院

### 新闻资讯

<Route author="wyml" example="/guat/news/ghyw" path="/guat/news/:type?" :paramsDesc="['资讯类型，如下表']">

| 桂航要闻 | 院部动态 | 通知公告 | 信息公开 | 桂航大讲堂 |
| -------- | -------- | -------- | -------- | ---------- |
| gdyw     | ybdt     | tzgg     | xxgk     | ghdjt      |

注 1: 不要吐槽拼音缩写，缩写原本的 URL 构成就这样。

</Route>

## 哈尔滨工程大学

### 本科生院工作通知

<Route author="XYenon" example="/heu/ugs/news/jwc/jxap" path="/heu/ugs/news/:author?/:category?" :paramsDesc="['发布部门, 默认为 `gztz`', '分类, 默认为 `all`']">

author 列表：

| 教务处 | 实践教学与交流处 | 教育评估处 | 专业建设处 | 国家大学生文化素质基地 | 教师教学发展中心 | 综合办公室 | 工作通知 |
| ------ | ---------------- | ---------- | ---------- | ---------------------- | ---------------- | ---------- | -------- |
| jwc    | sjjxyjlzx        | jypgc      | zyjsc      | gjdxswhszjd            | jsjxfzzx         | zhbgs      | gztz     |

category 列表：

`all` 为全部

教务处：

| 教学安排 | 考试管理 | 学籍管理 | 外语统考 | 成绩管理 |
| -------- | -------- | -------- | -------- | -------- |
| jxap     | ksgl     | xjgl     | wytk     | cjgl     |

实践教学与交流处：

| 实验教学 | 实验室建设 | 校外实习 | 学位论文 | 课程设计 | 创新创业 | 校际交流 |
| -------- | ---------- | -------- | -------- | -------- | -------- | -------- |
| syjx     | sysjs      | xwsx     | xwlw     | kcsj     | cxcy     | xjjl     |

教育评估处：

| 教学研究与教学成果 | 质量监控 |
| ------------------ | -------- |
| jxyjyjxcg          | zljk     |

专业建设处：

| 专业与教材建设 | 陈赓实验班 | 教学名师与优秀主讲教师 | 课程建设 | 双语教学 
