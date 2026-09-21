# AutoNodes 每日报告

生成时间：2026-09-21 22:02:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 88299 |
| 去重后节点数 | 25177 |
| TCP 可达数 | 3000 |
| 真测通过数 | 535 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25177 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 86.3 |
| geo | 1.4 |
| probe | 242.3 |
| real_test | 238.2 |
| tcp | 42.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 37 | 22 | 15 | 59.5% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 162 | 150 | 12 | 92.6% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 24 | 21 | 3 | 87.5% |
| vless | 551 | 319 | 232 | 57.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 61 |
| geo:ClientOSError | 51 |
| geo:TimeoutError | 43 |
| speed:ClientOSError | 30 |
| 204:TimeoutError | 23 |
| cn-block:TimeoutError | 20 |
| 204:ProxyError | 13 |
| speed:TimeoutError | 11 |
| 204:ProxyConnectionError | 7 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5850 |
| ConnectionRefusedError | 920 |
| gaierror | 365 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.912 | prefer | 277 | 0.845 | 1752 |
| Surfboard-tg-mixed | 0.714 | prefer | 151 | 0.636 | 7121 |
| mheidari-all | 0.633 | observe | 327 | 0.554 | 20197 |
| ermaozi | 0.593 | observe | 36 | 0.583 | 350 |
| ermaozi-get_subscribe | 0.27 | observe | 1 | 1.0 | 377 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 138 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5290 |
| Epodonios-all | 0.255 | observe | 0 | None | 7717 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.554 | 181 | 146 | 327 |
| ermaozi | 0.583 | 21 | 15 | 36 |
| Surfboard-tg-mixed | 0.636 | 96 | 55 | 151 |
| Au1rxx-base64 | 0.845 | 234 | 43 | 277 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20197 | yes | 5.15 | 0 |
| SoliSpirit-all | 8749 | yes | 1.8 | 0 |
| Epodonios-all | 7717 | yes | 3.18 | 0 |
| Surfboard-tg-mixed | 7121 | yes | 3.5 | 0 |
| DeltaKronecker-all | 6181 | yes | 5.73 | 0 |
| barry-far-vless | 6075 | yes | 1.16 | 0 |
| Surfboard-tg-vless | 5672 | yes | 3.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 5290 | yes | 1.38 | 0 |
| mahdibland-V2RayAggregator | 4344 | yes | 2.87 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.46 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 95 |
| cn-block | 83 |
| 204 | 45 |
| speed | 41 |
