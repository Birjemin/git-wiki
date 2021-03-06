# 技术管理课-朱赟

## 简介

### 职场分身术：从给出答案到引导

面对同事的提问，确定什么时候适合直接给出答案，什么时候适合给出线索，让对方自己找答案。

```
场景：一味的给出答案，不仅不利于对方的成长，也影响自己的工作效率，学会引导对方去寻找答案以及原因，减少对方的依赖。
```

### Bug引发事故，该不该追究责任？

1. 追究责任，但不是惩罚。搞清什么场景下什么样的bug引发了什么样的错误，做好善后工作，并且思考如何避免下次犯同样的错误；
2. 对事不对人。改善流程、改进制度、避免相同的错误；
3. 反复问为什么，从根本上发现问题。从根本上发现问题，解决问题，避免只看到问题表象，而忽略内在的缺陷（bug的暴露可能只是冰山一角，更深层次的原因会是啥）；
4. 员工关系的建立。相互信任，互帮互助；

```
场景：解决问题，bug引发的问题是第一关键，应先挽回损失，避免恶性循环追究责任。分析原因，规范流程，bug的发生往往会暴露系统的不完善、预警系统不完善、数据的备份等一系列问题。
```

### 每个工程师都应该了解的：A/B测试

1. 回收数据，让产品更加完善;
2. 永远不要过分相信你的直觉；
3. 实验样本的数量和分配很重要；
4. 分析的维度尽可能全面；
5. 其他组的改动对A/B测试产生的影响；
6. 比较值得去是必须是收敛的，而不是发散的；
7. 数据埋点；
8. 形成一个流程，或者设计一个工具；
9. 试图给每个结果一个合理的解释；
10. 必要的时候重新设计实验；
11. 不同客户端分开进行试验；
12. 总结；

### 如何帮助团队成员成长

1. 帮助团队成员迅速成长（已经达到下一个级别的标准，并在这个水准上稳定地保持了一段时间）
2. 明确的分解和布置任务
3. 建立有效的合作关系

Question:
* 怎样做能够让员工进步到更高层次？
* 他的潜力在哪，哪些地方是可以培养和挖掘的？
* 怎么帮助员工改进他与组内组外同事的关系，让他有机会更好地发挥他的长处？
* 怎样尽早的发现他的错误和缺点，并帮助他认识和改进，而不是在错误变成后果后去追究责任。
* 怎么样帮助他在不擅长的领域建立信心？
* 怎样帮助他学会处理各种压力和矛盾？

Doing:
*  和自己对话，避免静态的眼光去看待别人的能力
* 把自己有这种心态时的表现和内心的一些想法写出来
* 在遇到类似的情况，停一下，想一想是不是自己可以有所改变
* 诚恳的告诉组员希望帮助他成长，多交流并听取对方的想法

### 当我们给别人提意见时，要注意些什么？

1. 是否合适提意见（逆心理）
2. 放低姿态，讲究合适的时机
3. 正向反馈（夸奖永远大于批评）

### 每个工程师都应该了解的：聊聊幂等

一个操作如果多次任意执行所产生的影响，均与一次执行的影响相同。(用户对于同一操作发起的一次请求或者多次请求的结果是一致的，不会因为多次点击而产生了副作用。)
幂等令牌（标识同一个请求）、确保唯一性（避免同一个请求一定不会被处理两次）。

```
场景：支付、购物车库存，消息队列消费。。。
```

### 当别人给我们提意见时，该如何应对？

对问题进行复盘，做到团队的信息保持一致。

Doing:
* 尽量排除情绪以及偏见对我们的干扰；
* 假定对方是善意的，尽可能以感激的心态去听取意见；
* 了解意见的具体细节，把关注点放在对方的出发点，以及对方希望我们改进的地方；
* 对意见里的信息进行分类和过滤，思考一下：哪些是误解，哪些是自己的不足，哪些是自己可以通过沟通去改变的，哪些是自己需要尝试改进的；

### 说说硅谷公司中的一对一沟通

1. 项目进展
2. 生活和家庭状况如何
3. 有啥学习目标
4. 工作中的阻力
5. 生活或者工作中的焦虑
6. 一些精彩的创意和不成熟的想法

Doing:
* 找一个合适谈话的场所，保证隐蔽性和安全感；
* 彼此百分百的专注，不会被打断；
* 要有一定程度的眼神交流，专注倾听和思考；
* 不会受到批判性的反馈；
* 有一定程度上的交互；
* 所有的对话，保证对话内容不会被传播出去；

### 每个工程师都应该了解的：大数据时代的算法

1. 一个合格的程序员，必须掌握算法。（！！！）
2. 算法导论必须要懂啊。
3. 编程时用到的更多是算法思想，而不是写具体的算法。

### 项目延期了，作为负责人该怎么办？

1. 建立一定的流程。包括计划制定流程和计划跟进流程，跟进项目进度。（规范流程，减少隐患）
2. 在项目计划中，有明确的优先级，知道哪些任务是非做不可的；哪些任务是别的任务所依赖的，需要提前完成的等等。（给重点问题重点关注）
3. 制作一个共享的项目状态表，让团队成员可以一眼就看清楚项目进展，并保持该图标的更新。（实时跟进）
4. 不要漏掉任何一个人。（团队参与感）
5. 提供一个有效的反馈渠道。任何人在任何时候对项目又担心或者质疑，确保他可以通过有效的途径让你第一时间知道他的担心。

Result：

```
如果做了这些还是延期了，那说明计划不合理，需要尽早和上级沟通，了解延迟的原因，以及自己做出的努力，还需要哪些资源或者做出什么样的调整才有可能赶上预计期限，获取相应的帮助和支持。
```

### 管理和被管理：期望值差异

1. 增加对彼此的了解。
2. 每一段时间进行一次关于期望值的深度对话。
3. 持续跟进，设置检查点。

```
场景：充分沟通和了解对方的意图；确定肯定对方目前的工作和付出，表明其重要性；梳理业务；设置挑战目标。离职的原因千千万，追根揭底无非是钱没到位，或者心累了。
```

### 每个工程师都应该了解的：数据库知识

dba请开始你的表演~~（事物，缓存，主从机制）

### 管理者在进行工作分配时，会考虑哪些问题？（important）

1. 建立参考基线。（第三方评价，个人履历，该员工做过的项目或产品衡量他的能力，别人的评论）
2. 问对问题比正确答案更重要。（把任务交到员工手里之前，要和他进行充分的沟通。告诉他任务的详细情形，看他会问出什么样的问题，提出哪些想法）
3. 工期估算。（估算完成任务的工期是分配任务中必不可少的环节。你可以让接受任务的员工试着去估算：需要多久完成，大概什么时候完成，需要什么样的资源等）
4. 是否具有执行力。
5. 后期维护是否尽职尽责。（自觉地维护产品，有没有责任感，会不会推卸责任）

Attention:
* 如何面对职场新人？（悉心指导，发掘潜力）
* 针对不同类型的员工分配不同类型工作（扬长避短）
* 分解大任务，首现指定一个团队负责人，由团队内部决定任务的分配。
* 具有挑战性的任务？

### 硅谷人到底忙不忙？

<b>管理者要思考如何最大程度地帮助组员成长，充分利用这种选择和自由。</b>愿意全身心投入工作的，可以分配一些重要的有挑战的新项目给他；愿意尝试不同技术的，多给一些预研和前瞻性的任务；更乐意享受生活的，可以把线上稳定业务的改进和迭代交给他做。在尊重他们选择的前提下，双方保持一致的期望值。你会惊奇地发现，忙不忙，已经不重要了，重要的是，他们的工作会更出色地完成。

### 每个工程师都应该了解的：系统拆分

1. 创业初期的代码现状：（一个代码库，部署上线不灵活，发布频繁）
2. 分模块（rpc，如何无缝修改接口？）

Attention:
* 测试会变得异常复杂
* 与接口相关的改动需要大量的协调
* 报错的处理（将报错通过接口暴露出，便于追寻错误发生在哪一个服务中）
* 日志的完整性（统一规范，统一收集，便于查找）
* 超时设置
* 关于代码的自由度（设置代码规范，服务管理规范）

Qestion:
如何去判断系统是不是到了必须进行拆分和服务化的临界点？

```
业务量是否足够大；开发人员经验是否能胜任；拆分不可逆
```

### 技术人员如何建立个人影响力？

1. 存在感：你的意见别人会认真听。（对别人的尊重，真诚相待）
2. 说服力：当别人和你意见不同的时候，能有效地让对方真的明白你的出发点，虽然不一定百分之百的采纳，但会认可你的观点。（找出对方不认可的地方，反复讨论，达成一致）
3. 谈判力：双方共同完成一个项目，让职责划分尽可能公平，对双方都有利。（逻辑清晰，动的适度取舍）
4. 协调力：多方合作的时候，你能起到桥梁的作用，促进多方更好地沟通。（培养多方沟通协调能力）
5. 鼓舞力。

### 管理者不用亲力亲为：关键是什么？

1. 让对方明确目标，知道最终想要达到的结果是什么，对这个任务完成的期望值是怎样的。
2. 制定一个计划，并保持跟进。（适当参与探讨，给出建议或者线索，确保没有大的阻碍阻止他取得关键性进展）
3. 给出反馈，尤其是正面的反馈。（给出客观的反馈，不必在细节上有太多意见，如果对方在方向上或者优先级等问题上偏离了你的预期，及时沟通和纠正，让项目走上正轨）

### 每个工程师都应该了解的：API的设计和实现

restful api

1. 保证API 100% restful
2. 在请求和响应中，应该尽可能的保持参数的结构化
3. 认证和安全的考虑
4. API本身应该和客户端无关
5. 尽可能让API的幂等的

API框架的选型：
1. 对访问权限的统一控制
2. 自动测试的支持
3. 对请求和相应的格式，以及序列化合反序列化的支持
4. 对日志和日志过滤的支持
5. 对自动文档生成的支持
6. 对架构以及性能的影响

设计的平衡
1. 自由总是相对的
2. api设计的适度（满足业务、便于扩展）
3. 可维护性和效率
4. 是否采用AOP(面对切面编程)

### 硅谷面试：那些你应该知道的事儿

### 项目管理中的三个技巧

1. 做项目计划的时候，要对多个项目进行细分重组
2. 工期估算
3. 实时跟踪，并准备好B计划

细分重组因素：
1. 先评估能力，再分配任务，每个人的能力要和任务的难度匹配
2. 每个人任务完成所需时间要尽量平等，也就是要达到一种负载平衡
3. 每个人得到的任务里，挑战有意思的工作和脏活累活的比例要大致相等
4. 每个人任务理由足够的挑战，能够帮助其成长，又不至于太难而让其望而生畏而产生挫败感
5. 不同人的人物之间如果有依赖性，在分配任务时要安排合理的顺序，确保不会有人被别的人或事阻塞
6. 每个人的任务里都应该有一个主题，就好像故事有一条主线。

### 每个工程师都应该了解的：中美在支付技术和大环境下的差异

### 不要做微观管理者

1. 给出指导性的建议和准则，是否需要更多的指导
2. 鼓励组员创新和独立完成
3. 调整跟进的粒度
4. 沟通的重要性

### 如何处理工作中的人际关系？

礼貌和尊重！
1. 首先，对于自己的上下级，保持开放的心态和愿意沟通的态度十分重要(无法避免)
2. 其次，在交往过程中，尽可能对别人的分享、工作、交流持一种积极、友善和鼓励的态度
3. 加入一些有利于自己成长的社交圈子
4. 适当的寻找帮助
5. 对于别人的意见要尽可能认真对待
6. 不背后议论别人，待人坦诚

### 编程语言漫谈

语言无界，重要的是思想

### 兼容并包的领导方式

多样化的员工，多样化的工作形式，多样化的相处方式，产品的多样化

特征：
1. 坚定地承诺
2. 谦卑的勇气
3. 正确的认知
4. 开放的心态
5. 高情商
6. 合作的意愿

### 如何做自己的职场规划？

Q:
1. 你的个人价值观是什么，最在意什么？
2. 你的长期愿景是什么？
3. 为了达到目标，你需要哪些技能和经验？
4. 你的优势和长处是什么？

A:

```
知道自己想要什么，知道自己现在的差距是什么
多和leader沟通
让计划可执行可追踪，适时调整计划
```

### 小议java语言

### 如何激发团队人员的责任心

Q:
1. 明确责任制，尽可能通过规则来明确和规范与责任心、责任感相关的事情。
2. 让责任制变得有效，而不是形同虚设。
3. 尽可能的让团队成员充满归属感，进而激发他们的责任心。

A:
工程师不仅仅写代码，他们会参与产品和设计的评论，负责自己的模块架构设计，编写代码实现，然后测试上线。最后还要负责产品的改进和Bug修复。
让员工具有归属感才能避免离职。。。

### 说说硅谷互联网公司的开发流程

1. OKR的设立
2. 主项目及其子项目的确立
3. 每个子项目的生命周期
4. 主项目的生命周期
5. 收尾、维护、复盘

备注：
需要共同制定一个合乎公司需求的开发规范，不能一概而论

### 编程马拉松

### 工程师、产品经理、数据工程师是如何一起工作的？

### 硅谷人如何做code review

### 技术人员的犯错成本

1. 所有关于公司公关层面的事都不是小事
2. 人事变动的宣布一定要谨慎
3. 关于技术或业务问题，如果你不确定，就不要随便给答案
4. 技术失误导致错误的产品决定

### 如何从错误中成长？

1. 伸展错误。尝试去做能力之外挑战的时候，因为自身能力或其他条件的束缚，做得够好而犯的错
2. 无知错误。
3. 粗心错误。
4. 高风险错误。主动去做事情，但是风险很高，是否犯错不受自己的控制

Doing:
1. 为了避免伸展错误，尽可能地提供一些的培训机制
2. 为了避免无知错误，要做好信息的透明和共享
3. 为了避免粗心错误，设置一定的复盘机制
4. 为了避免高风险错误，所有的决定尽可能都有一个备选方案 

### 理解和建立自己的工作弹性

焦虑是正常哒

1. 正确面对自己的焦虑，正面面对压力
2. 意识到反刍的危害，走出思维的误区，打造自己的弹性能力
3. 多认识积极向上的人，保持乐观的心态
4. 构建自己的弹性能力

### 如何对更多的工作说“不“

1. 分清事情的轻重缓急。有些紧急的事情和优先级高的事情很难拒绝
2. 正确评估自己的能力和时间资源

### 成长不是顿悟，而是练习

keep learning！

## 参考
1. [https://segmentfault.com/a/1190000012377139](https://segmentfault.com/a/1190000012377139)

2. 