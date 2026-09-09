# AutoNodes 每日报告

生成时间：2026-09-09 16:29:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 84876 |
| 去重后节点数 | 22035 |
| TCP 可达数 | 3000 |
| 真测通过数 | 496 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22035 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 83.2 |
| geo | 1.5 |
| probe | 265.0 |
| real_test | 270.4 |
| tcp | 37.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 34 | 21 | 13 | 61.8% |
| hysteria2 | 24 | 21 | 3 | 87.5% |
| shadowsocks | 171 | 156 | 15 | 91.2% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 23 | 15 | 8 | 65.2% |
| vless | 381 | 282 | 99 | 74.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 46 |
| 204:TimeoutError | 21 |
| 204:ProxyError | 18 |
| cn-block:TimeoutError | 15 |
| cn-block:ClientOSError | 10 |
| speed:ClientOSError | 5 |
| speed:TimeoutError | 5 |
| geo:TimeoutError | 5 |
| 204:ProxyConnectionError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4952 |
| ConnectionRefusedError | 892 |
| gaierror | 377 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.978 | prefer | 273 | 0.916 | 1634 |
| DeltaKronecker-all | 0.822 | prefer | 60 | 0.75 | 5187 |
| Surfboard-tg-mixed | 0.796 | prefer | 146 | 0.719 | 7428 |
| ermaozi | 0.731 | prefer | 26 | 0.731 | 410 |
| mheidari-all | 0.692 | observe | 119 | 0.613 | 16618 |
| tg-oneclickvpnkeys | 0.319 | observe | 2 | 1.0 | 205 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4795 |
| Epodonios-all | 0.255 | observe | 0 | None | 7926 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9327 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.2 | 8 | 0.25 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.25 | 2 | 6 | 8 |
| mheidari-all | 0.613 | 73 | 46 | 119 |
| Surfboard-tg-mixed | 0.719 | 105 | 41 | 146 |
| ermaozi | 0.731 | 19 | 7 | 26 |
| DeltaKronecker-all | 0.75 | 45 | 15 | 60 |
| Au1rxx-base64 | 0.916 | 250 | 23 | 273 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16618 | yes | 5.0 | 0 |
| SoliSpirit-all | 9327 | yes | 3.69 | 0 |
| Epodonios-all | 7926 | yes | 5.73 | 0 |
| Surfboard-tg-mixed | 7428 | yes | 3.85 | 0 |
| barry-far-vless | 6336 | yes | 1.01 | 0 |
| Surfboard-tg-vless | 6118 | yes | 3.59 | 0 |
| DeltaKronecker-all | 5187 | yes | 4.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 4795 | yes | 4.4 | 0 |
| mahdibland-V2RayAggregator | 4219 | yes | 0.69 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.09 | 0 |

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
| geo | 54 |
| 204 | 46 |
| cn-block | 28 |
| speed | 11 |
