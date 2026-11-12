# Claude Pro 国内订阅怎么付款：官网 $20/月值不值？支付宝代充能开在自己账号上吗？充完还是 Free Plan 怎么查？（附全套餐对比）

Claude Pro 官方价 **$20/月**，年付一次付 $200，折合 $17/月。Anthropic 的支持地区名单里没有中国大陆、香港和澳门，台湾在名单内；网页订阅只收信用卡和借记卡，国内银联卡、支付宝在官网结算页用不了，国内发行的双币卡也经常被拒。

下面把国内订阅 Claude Pro 的几件事按决策顺序讲清：Pro、Max、Ultra 怎么选；没有海外卡时哪几条路走得通；代充为什么要求账号当前是 Free Plan；付完钱还显示 Free Plan 按什么顺序排查。

## 选购速览

> 大多数国内读者：先开 **Pro $20/月** 用一个月，够不够用一周就能看出来。
> 每天用 Claude Code 写几个小时代码：**Max $100/月**。
> 几乎全天挂着、5 小时窗口经常打满：**Ultra $200/月**。
> 拿不准就先买低一档。同一个账号升级，聊天记录和 Projects 都在。
> 👉 在账号星球查看 Claude Pro / Max 当前报价与开通方式

## 全套餐对比

官方定价页当前展示的档位是 Free、Pro、Max、Ultra，团队和企业另算。下表价格均为网页订阅的美元价，手机 App 内订阅由应用商店定价，可能不同。

| 套餐 | 官方价 | 计费周期 | 用量与权益（官方口径） | 开通入口 |
| --- | --- | --- | --- | --- |
| Free | $0 | — | 用量少；不含 Claude Code | [免费版说明与升级入口](https://accboyytbetw.acceboy.com/) |
| Pro | **$20/月**；年付 $200（折 $17/月） | 月付 / 年付 | 5 小时和每周额度各为基准 1x；含 Claude Code；可开 usage credits | [开通 Pro](https://accboyytbetw.acceboy.com/) |
| Max | **$100/月** | 月付 | 5 小时和每周额度各为 Pro 的 5 倍；含每月 $100 API credits；优先体验新功能 | [开通 Max](https://accboyytbetw.acceboy.com/) |
| Ultra | **$200/月** | 月付 | 每周额度为 Pro 的 10 倍；官方标注完成验证的账号没有 5 小时限制；含每月 $200 API credits | [开通 Ultra](https://accboyytbetw.acceboy.com/) |
| Team | $20/人/月（年付）或 $25/人/月（月付） | 月付 / 年付 | 2–150 人；含 Claude Code 和团队共享 API credits | [查看团队方案](https://accboyytbetw.acceboy.com/) |
| Enterprise | 按席位 + 按 API 价计的用量，联系销售 | — | 大型组织 | [咨询企业方案](https://accboyytbetw.acceboy.com/) |

Team 的高级席位是 $100/人/月（年付）或 $125/人/月（月付）。年付 Pro 比月付一年省 $40，但一次付清、中途不退；月付 $20 一个月，随时可以停。从 Pro 升 Max、Max 升 Ultra，官方按剩余账期比例补差价，立即生效；年付 Pro 升 Max 时，剩余年费多于 Max 价格的部分会变成账户余额，账单地址变了要先取消 Pro、等到期再订。

## 国内付款的三条路，按可行性排

**第一条：有支持地区发行的银行卡，直接在网页端订阅。** 付款走 Stripe，接受 Visa、Mastercard、AmEx。账单地址必须和发卡信息一致，邮编对不上 AVS 校验会失败。不要编造账单地址，既会拒付，也会给账号留下风险记录。

**第二条：外区 Apple ID 应用内订阅。** Claude iOS App 内可以直接升级 Pro，付款由 App Store 处理。App Store 搜不到 Claude，就需要一个支持地区（比如美国）的 Apple ID。缺点是步骤多、价格按当地商店算、订阅和退款都由 App Store 管理。

**第三条：代充。** 卖家替你付款，会员开在你自己的账号上，支付宝下单。账号还是你的，聊天记录、Projects 都在。这条路的细节放在后面单独讲。

官方礼品订阅曾经是一条正规路线：Pro / Max 用户可以为别人购买 1、3、6 或 12 个月的订阅，对方通过邮件兑换。但 2026 年 10 月下旬的复测显示赠送订阅已暂停购买，下单前以官网为准。

不建议碰来路不明的兑换码、共享账号和多人拼车。共享会带来登录设备指纹混乱、IP 不一致，Anthropic 识别得很快，轻则要求重新验证，重则封禁。

虚拟卡这条旧路也基本断了：WildCard 已于 2025 年 7 月停止发卡（之后改名 WildAI，不再发卡），近两年多家虚拟卡平台陆续停服，网上还在教你注册 WildCard 的教程已经过期。

另外提醒一句香港用户：香港卡被拒通常不是卡本身的问题。Stripe 的风控会同时比对发卡地、当前 IP 归属地和账单地址，三者不一致就容易判高风险；三者都是香港，又会因为香港不在支持地区被拦。关键是把发卡地、IP、账单地址对齐到同一个支持地区。

👉 [没有海外卡，可以在账号星球用支付宝下单，会员开在自己账号上](https://accboyytbetw.acceboy.com/)

## 三套账别搞混：订阅、API、Claude Code

这是国内用户最容易踩的坑，也是退款争议最多的地方。

Pro、Max、Ultra 是 claude.ai 的订阅，管网页、桌面端、手机 App 和 Claude Code 的用量。Claude API 在 console.anthropic.com 单独按 token 计费。Claude Code 可以走订阅额度，也可以走 API 额度。三套账分开算。

**Pro 不含 API 额度。** Max 和 Ultra 附带的每月 API credits 只能在 Console 用，不能用在 Claude 应用和 Claude Code 里。

在 console.anthropic.com 充钱不会让你变成 Pro，回到 claude.ai 还是显示 Free。会员要在 claude.ai 的设置里升级，两者互不相通。

额度按滚动 5 小时窗口重置，付费套餐另有每周上限，每周在账号固定的时间重置。网页、桌面、手机 App、Claude Code 共用同一份额度，官方没有公布具体条数，消耗多少取决于对话长短、用的模型、附件大小和推理强度。

额度用完后，Pro、Max、Ultra 都可以在 Settings → Usage 开启 usage credits，到上限后自动转成按量付费，按标准 API 价计费。可以设每月上限、预充金额、自动充值和提醒，费用和订阅费分开出账。Claude Code 里对应命令是 `/usage-credits`。手机 App 订阅的只能在网页版开启，还要先绑卡。不想多花钱就别开，开了记得设上限。

## 付了钱还是 Free Plan：按这个顺序查

官方账单 FAQ 给了两条原因：登录的邮箱和开通会员的邮箱不是同一个；付款方式失败导致账号被降级。

实际还常见三种：当前停留在 Team 空间里；手机上订阅后电脑没登录同一个账号；页面没刷新。

排查按这个顺序走：

1. 退出再重新登录，手机 App 也一样。
2. 用可能注册过的其他邮箱、其他登录方式（Google / 邮箱）各试一次。
3. 进 Settings → Billing 看最近一次付款状态，失败的话更新付款方式。
4. 切换回个人账户。
5. 手机上订阅的，电脑上登录同一个账号。

代充的订单直接找卖家处理，别自己重复下单。

## 代充怎么挑：六个判断点，两条硬限制

代充是“订阅代付”，卖家替你付款，会员开到你自己的账号上。账号、聊天记录、Projects 都还是你的。

**硬限制一：代充只支持当前是 Free Plan 的账号。** 账号已经开了 Pro、Max、Team，或者有未付账单，要先自己处理掉再下单，否则充不进去。

**硬限制二：代充开的会员不走你的卡，不会自动续费，也不能叠加充值更长时间。** Pro 本身就是按月自动续费，想要长期要么每月续，要么买平台的多月套餐、由平台按月续订。

挑平台看六点：

1. 价格是否正常。靠谱代充一般略高于官方美元价折算，明显低于官方价的要警惕。
2. 要不要账号密码。要密码、要转发验证码的不要碰。
3. 开通方式和速度。正规做法是卖家登录你自己的账号完成付款，或者给你一个官方付款链接。
4. 开通失败怎么退。
5. 掉订阅管不管。
6. 售后找不找得到真人。

价格参考：目前能核到的单商家实价是 Claude Pro 一个月 ¥159；另有服务商自述的市场区间为 Pro ¥165–¥249/月，两个口径不同，只作参考。账号星球的具体报价以站内商品页为准。它的品类很全，从外区 Apple ID 到各类会员都有，下单 Claude 时认准“开在自己账号上”的商品说明，不要成品号或共享位。

质保方面，同类代充商城的通行口径大致是：没开通成功可以重开或退款；开通后掉会员（订阅被撤销、变回 Free），在本期有效期内凭订单号补一个月；账号被封或停用不在质保范围、不退款，只协助申诉。账号星球的具体规则以站内售后说明为准，下单前问清。

代充和封号的关系也说清楚：代充开的是你自己账号上的正常订阅，账号被限制更多和使用习惯有关，比如频繁切换地区、多人共用、付款被撤销（低价单常见）。

👉 [下单前先看账号星球的售后说明，确认掉订阅和退款怎么处理](https://accboyytbetw.acceboy.com/)

## 报错速查

**unable to verify**（注册最常见）：IP 被识别为高风险，多为机房或代理。换住宅 IP，清空 Cookie 和 LocalStorage，换一个 Chrome Profile，等 30 分钟再试。

**region not supported / unavailable in your country**：确认 IP 出口在支持地区，不是香港、澳门；确认 DNS 同样在美国；清 Cookie 重新登录，让 Anthropic 重新判定地区。

**payment failed / card declined**：查卡内余额，要够 $20 加预授权 buffer；查账单地址邮编是否和卡一致；等 24 小时再试，避免触发 Stripe 短时多次失败的风控；换一张卡或换一个 BIN 段。

**There was an error logging you in**：关掉 VPN、禁用浏览器扩展、清缓存和 Cookie；仍然不行就看 status.claude.com 有没有故障公告。

**Due to unexpected capacity constraints**：全体用户同时请求过多导致的临时情况，不是你的额度问题，也不会出现在状态页上，等几分钟再试。Claude Code 里对应 `529 Overloaded`，可以用 `/model` 换个模型，不扣额度。

**Claude Code 提示要充 API 或 Credit balance is too low**：登录时选了 Anthropic Console 账号，或者环境变量里有 `ANTHROPIC_API_KEY`（官方说明这个变量优先于订阅）。在 Claude Code 里输入 `/login` 选 Claude 账号；有环境变量的先 `unset ANTHROPIC_API_KEY`（PowerShell 用 `Remove-Item Env:ANTHROPIC_API_KEY`），把 `~/.zshrc`、`~/.bashrc` 里的 export 行删掉，重开终端后 `/status` 确认当前用的是订阅。

**账号被停用（Account disabled）**：官方会在邮件里说明原因，常见的是违反使用政策。登录 claude.ai，点左下角头像 → Get help 申诉。能否恢复、是否退款以官方处理结果为准。

**Your message will exceed the length limit**：单次输入超过这个对话的上下文长度，缩短、分段发，或者新开对话。

## 防封就四件事

网络固定在同一地区，不频繁换国家；一个账号只自己用，不拼车；不短时间内反复注册换邮箱；重要对话和代码自己备份。Claude 对地区一致性的要求比 ChatGPT 高，尤其是付款环节，发卡地、IP、账单地址三者对不上就容易出问题。

## 最后怎么选

只需要网页和 App 聊天、偶尔用 Claude Code → **Pro $20/月**，先买一个月看会不会经常碰上限。
每天用 Claude Code 写几个小时代码、Pro 一周里好几天提示额度用完 → **Max $100/月**。
Max 还经常不够、几乎全天在用 → **Ultra $200/月**。
2–150 人的团队要共享额度和 API credits → **Team**。

下单前确认两件事：账号当前是不是 Free Plan（不是的话代充充不进去）；掉订阅和退款规则白纸黑字写在哪里。

👉 [到账号星球挑一个开在自己账号上的 Claude 会员方案](https://accboyytbetw.acceboy.com/)
