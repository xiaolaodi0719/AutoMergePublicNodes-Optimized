# AutoNodes 每日报告

生成时间：2026-08-03 10:00:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 83372 |
| 去重后节点数 | 24502 |
| TCP 可达数 | 3000 |
| 真测通过数 | 597 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24502 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 35.4 |
| geo | 1.5 |
| probe | 61.4 |
| real_test | 154.4 |
| tcp | 37.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 143 | 143 | 0 | 100.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 142 | 125 | 17 | 88.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 29 | 24 | 5 | 82.8% |
| vless | 530 | 285 | 245 | 53.8% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 151 |
| speed:TimeoutError | 27 |
| cn-block:TimeoutError | 21 |
| 204:ProxyError | 17 |
| geo:ClientOSError | 14 |
| speed:ClientOSError | 13 |
| 204:TimeoutError | 11 |
| cn-block:ProxyError | 7 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4813 |
| ConnectionRefusedError | 768 |
| gaierror | 256 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 143 | 1.0 | 344 |
| Au1rxx-base64 | 0.812 | prefer | 543 | 0.748 | 1629 |
| mheidari-all | 0.426 | observe | 24 | 0.333 | 18806 |
| Surfboard-tg-mixed | 0.393 | observe | 94 | 0.309 | 5244 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 3833 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 54 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5285 |
| Epodonios-all | 0.255 | observe | 0 | None | 5831 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6567 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.241 | 60 | 0.15 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.15 | 9 | 51 | 60 |
| Surfboard-tg-mixed | 0.309 | 29 | 65 | 94 |
| mheidari-all | 0.333 | 8 | 16 | 24 |
| Au1rxx-base64 | 0.748 | 406 | 137 | 543 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 143 | 0 | 143 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18806 | yes | 4.7 | 0 |
| SoliSpirit-all | 6567 | yes | 3.49 | 0 |
| DeltaKronecker-all | 6205 | yes | 4.84 | 0 |
| Epodonios-all | 5831 | yes | 4.83 | 0 |
| 10ium-ScrapeCategorize-Vless | 5285 | yes | 0.67 | 0 |
| Surfboard-tg-mixed | 5244 | yes | 3.8 | 0 |
| mahdibland-V2RayAggregator | 5196 | yes | 2.88 | 0 |
| barry-far-vless | 4492 | yes | 1.69 | 0 |
| Surfboard-tg-vless | 4132 | yes | 4.02 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.44 | 0 |

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
| geo | 167 |
| speed | 41 |
| 204 | 33 |
| cn-block | 30 |
