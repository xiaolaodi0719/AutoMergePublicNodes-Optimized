# AutoNodes 每日报告

生成时间：2026-09-23 16:41:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 97200 |
| 去重后节点数 | 26542 |
| TCP 可达数 | 3000 |
| 真测通过数 | 415 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26542 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 82.5 |
| geo | 1.5 |
| probe | 230.0 |
| real_test | 186.4 |
| tcp | 43.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 36 | 25 | 11 | 69.4% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 167 | 147 | 20 | 88.0% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 6 | 6 | 0 | 100.0% |
| vless | 355 | 221 | 134 | 62.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 42 |
| geo:ClientOSError | 31 |
| 204:TimeoutError | 31 |
| cn-block:TimeoutError | 22 |
| 204:ProxyError | 20 |
| speed:TimeoutError | 9 |
| speed:ClientOSError | 5 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6179 |
| ConnectionRefusedError | 960 |
| gaierror | 340 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.96 | prefer | 270 | 0.896 | 1665 |
| ermaozi | 0.793 | prefer | 30 | 0.8 | 291 |
| Surfboard-tg-mixed | 0.708 | prefer | 41 | 0.634 | 7138 |
| mheidari-all | 0.597 | observe | 234 | 0.517 | 22163 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 88 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5131 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 6471 |
| Epodonios-all | 0.255 | observe | 0 | None | 7512 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9407 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.141 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.143 | 1 | 6 | 7 |
| mheidari-all | 0.517 | 121 | 113 | 234 |
| Surfboard-tg-mixed | 0.634 | 26 | 15 | 41 |
| ermaozi | 0.8 | 24 | 6 | 30 |
| Au1rxx-base64 | 0.896 | 242 | 28 | 270 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22163 | yes | 4.14 | 0 |
| SoliSpirit-all | 9407 | yes | 2.59 | 0 |
| Epodonios-all | 7512 | yes | 5.38 | 0 |
| Surfboard-tg-mixed | 7138 | yes | 3.39 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.24 | 0 |
| DeltaKronecker-all | 6471 | yes | 3.85 | 0 |
| barry-far-vless | 6042 | yes | 0.9 | 0 |
| Surfboard-tg-vless | 5827 | yes | 3.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5131 | yes | 1.32 | 0 |
| mahdibland-V2RayAggregator | 4187 | yes | 2.03 | 0 |

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
| cn-block | 66 |
| 204 | 53 |
| geo | 35 |
| speed | 15 |
