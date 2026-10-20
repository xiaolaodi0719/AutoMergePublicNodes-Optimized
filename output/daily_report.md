# AutoNodes 每日报告

生成时间：2026-10-20 16:47:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 94292 |
| 去重后节点数 | 26495 |
| TCP 可达数 | 3000 |
| 真测通过数 | 293 |
| verified 输出数 | 293 |
| global 输出数 | 300 |
| all 输出数 | 26495 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 89.9 |
| geo | 1.5 |
| probe | 235.4 |
| real_test | 175.0 |
| tcp | 45.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 32 | 12 | 20 | 37.5% |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 126 | 117 | 9 | 92.9% |
| socks | 4 | 0 | 4 | 0.0% |
| trojan | 25 | 21 | 4 | 84.0% |
| vless | 174 | 133 | 41 | 76.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyConnectionError | 17 |
| 204:TimeoutError | 13 |
| speed:TimeoutError | 12 |
| speed:ClientOSError | 11 |
| cn-block:TimeoutError | 11 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 3 |
| geo:ClientOSError | 2 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6561 |
| ConnectionRefusedError | 1061 |
| gaierror | 281 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.911 | prefer | 250 | 0.86 | 1348 |
| mheidari-all | 0.88 | prefer | 43 | 0.814 | 23236 |
| Surfboard-tg-mixed | 0.785 | prefer | 42 | 0.714 | 6911 |
| zhangkai | 0.401 | observe | 23 | 0.391 | 31 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 79 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |
| Epodonios-all | 0.255 | observe | 0 | None | 7384 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10086 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5515 |

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
| downweight | ermaozi-get_subscribe | 0.2 | 8 | 0.25 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.25 | 1 | 3 | 4 |
| ermaozi-get_subscribe | 0.25 | 2 | 6 | 8 |
| zhangkai | 0.391 | 9 | 14 | 23 |
| Surfboard-tg-mixed | 0.714 | 30 | 12 | 42 |
| mheidari-all | 0.814 | 35 | 8 | 43 |
| Au1rxx-base64 | 0.86 | 215 | 35 | 250 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23236 | yes | 5.51 | 0 |
| SoliSpirit-all | 10086 | yes | 5.53 | 0 |
| Epodonios-all | 7384 | yes | 6.01 | 0 |
| Surfboard-tg-mixed | 6911 | yes | 5.81 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.52 | 0 |
| barry-far-vless | 5732 | yes | 3.89 | 0 |
| Surfboard-tg-vless | 5515 | yes | 3.55 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 2.9 | 0 |
| mahdibland-V2RayAggregator | 4278 | yes | 1.03 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 4.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 37 |
| speed | 23 |
| cn-block | 15 |
| geo | 4 |
