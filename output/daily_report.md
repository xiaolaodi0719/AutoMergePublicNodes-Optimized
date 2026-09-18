# AutoNodes 每日报告

生成时间：2026-09-18 16:20:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 83896 |
| 去重后节点数 | 23095 |
| TCP 可达数 | 3000 |
| 真测通过数 | 397 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23095 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 76.5 |
| geo | 1.4 |
| probe | 271.6 |
| real_test | 275.6 |
| tcp | 38.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 31 | 20 | 11 | 64.5% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 179 | 155 | 24 | 86.6% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 3 | 1 | 2 | 33.3% |
| vless | 307 | 206 | 101 | 67.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 34 |
| 204:TimeoutError | 20 |
| geo:TimeoutError | 17 |
| 204:ProxyError | 16 |
| cn-block:TimeoutError | 16 |
| speed:ClientOSError | 15 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 4 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5377 |
| ConnectionRefusedError | 816 |
| gaierror | 372 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.927 | prefer | 254 | 0.866 | 1596 |
| ermaozi | 0.813 | prefer | 23 | 0.826 | 325 |
| mheidari-all | 0.752 | prefer | 59 | 0.678 | 15758 |
| Surfboard-tg-mixed | 0.744 | prefer | 147 | 0.667 | 7397 |
| DeltaKronecker-all | 0.499 | observe | 41 | 0.415 | 6040 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4241 |
| Epodonios-all | 0.255 | observe | 0 | None | 7860 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8960 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5909 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.136 | 8 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.125 | 1 | 7 | 8 |
| DeltaKronecker-all | 0.415 | 17 | 24 | 41 |
| roosterkid-openproxylist-v2ray | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.667 | 98 | 49 | 147 |
| mheidari-all | 0.678 | 40 | 19 | 59 |
| ermaozi | 0.826 | 19 | 4 | 23 |
| Au1rxx-base64 | 0.866 | 220 | 34 | 254 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15758 | yes | 4.48 | 0 |
| SoliSpirit-all | 8960 | yes | 5.13 | 0 |
| Epodonios-all | 7860 | yes | 5.9 | 0 |
| Surfboard-tg-mixed | 7397 | yes | 4.07 | 0 |
| barry-far-vless | 6127 | yes | 2.9 | 0 |
| DeltaKronecker-all | 6040 | yes | 4.9 | 0 |
| Surfboard-tg-vless | 5909 | yes | 3.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 5076 | yes | 1.69 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 0.19 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.0 | 0 |

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
| 204 | 40 |
| cn-block | 27 |
| speed | 19 |
