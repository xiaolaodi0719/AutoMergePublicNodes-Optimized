# AutoNodes 每日报告

生成时间：2026-10-19 12:51:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 95095 |
| 去重后节点数 | 26228 |
| TCP 可达数 | 3000 |
| 真测通过数 | 361 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26228 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 93.1 |
| geo | 1.5 |
| probe | 243.5 |
| real_test | 222.8 |
| tcp | 44.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 18 | 9 | 9 | 50.0% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 156 | 131 | 25 | 84.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 31 | 22 | 9 | 71.0% |
| vless | 252 | 182 | 70 | 72.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 24 |
| geo:ClientOSError | 18 |
| cn-block:TimeoutError | 17 |
| 204:ProxyError | 15 |
| speed:ClientOSError | 14 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| geo:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6438 |
| ConnectionRefusedError | 1051 |
| gaierror | 282 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.885 | prefer | 374 | 0.818 | 1717 |
| Surfboard-tg-mixed | 0.647 | observe | 58 | 0.569 | 6948 |
| zhangkai | 0.555 | observe | 8 | 1.0 | 144 |
| mheidari-all | 0.501 | observe | 18 | 0.444 | 23446 |
| ermaozi | 0.441 | observe | 5 | 1.0 | 42 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4940 |
| Epodonios-all | 0.255 | observe | 0 | None | 7331 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10132 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5438 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.133 | 10 | 0.1 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.1 | 1 | 9 | 10 |
| mheidari-all | 0.444 | 8 | 10 | 18 |
| Surfboard-tg-mixed | 0.569 | 33 | 25 | 58 |
| Au1rxx-base64 | 0.818 | 306 | 68 | 374 |
| ermaozi | 1.0 | 5 | 0 | 5 |
| zhangkai | 1.0 | 8 | 0 | 8 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23446 | yes | 4.22 | 0 |
| SoliSpirit-all | 10132 | yes | 2.81 | 0 |
| Epodonios-all | 7331 | yes | 4.84 | 0 |
| Surfboard-tg-mixed | 6948 | yes | 2.68 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.29 | 0 |
| barry-far-vless | 5622 | yes | 1.19 | 0 |
| Surfboard-tg-vless | 5438 | yes | 3.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 4940 | yes | 1.02 | 0 |
| mahdibland-V2RayAggregator | 4314 | yes | 2.4 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.88 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 44 |
| geo | 25 |
| cn-block | 23 |
| speed | 22 |
