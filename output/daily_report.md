# AutoNodes 每日报告

生成时间：2026-09-03 03:56:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 83558 |
| 去重后节点数 | 23576 |
| TCP 可达数 | 3000 |
| 真测通过数 | 692 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23576 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 36.9 |
| geo | 1.4 |
| probe | 91.0 |
| real_test | 155.5 |
| tcp | 38.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 22 | 3 | 88.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 163 | 154 | 9 | 94.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 76 | 44 | 32 | 57.9% |
| vless | 692 | 449 | 243 | 64.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 120 |
| speed:TimeoutError | 60 |
| speed:ClientOSError | 41 |
| geo:ClientOSError | 24 |
| cn-block:TimeoutError | 16 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 5 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 4 |
| 204:ProxyConnectionError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5293 |
| ConnectionRefusedError | 902 |
| gaierror | 365 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | prefer | 372 | 0.909 | 1874 |
| Surfboard-tg-mixed | 0.867 | prefer | 209 | 0.789 | 7080 |
| zhangkai | 0.846 | prefer | 23 | 0.87 | 144 |
| mheidari-all | 0.557 | observe | 348 | 0.477 | 16261 |
| tg-oneclickvpnkeys | 0.316 | observe | 2 | 1.0 | 131 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4765 |
| Epodonios-all | 0.255 | observe | 0 | None | 7558 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7927 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5956 |

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
| downweight | DeltaKronecker-all | 0.151 | 26 | 0.038 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.038 | 1 | 25 | 26 |
| mheidari-all | 0.477 | 166 | 182 | 348 |
| Surfboard-tg-mixed | 0.789 | 165 | 44 | 209 |
| zhangkai | 0.87 | 20 | 3 | 23 |
| Au1rxx-base64 | 0.909 | 338 | 34 | 372 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16261 | yes | 4.31 | 0 |
| SoliSpirit-all | 7927 | yes | 4.57 | 0 |
| Epodonios-all | 7558 | yes | 6.03 | 0 |
| DeltaKronecker-all | 7295 | yes | 4.85 | 0 |
| Surfboard-tg-mixed | 7080 | yes | 4.55 | 0 |
| barry-far-vless | 6145 | yes | 4.3 | 0 |
| Surfboard-tg-vless | 5956 | yes | 3.84 | 0 |
| 10ium-ScrapeCategorize-Vless | 4765 | yes | 2.66 | 0 |
| mahdibland-V2RayAggregator | 4066 | yes | 3.26 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.45 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 144 |
| speed | 101 |
| cn-block | 25 |
| 204 | 20 |
