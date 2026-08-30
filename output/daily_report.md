# AutoNodes 每日报告

生成时间：2026-08-30 11:42:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79168 |
| 去重后节点数 | 21765 |
| TCP 可达数 | 3000 |
| 真测通过数 | 619 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21765 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 38.0 |
| geo | 1.5 |
| probe | 58.7 |
| real_test | 137.2 |
| tcp | 34.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 152 | 140 | 12 | 92.1% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 41 | 33 | 8 | 80.5% |
| vless | 489 | 402 | 87 | 82.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 27 |
| cn-block:TimeoutError | 23 |
| geo:ClientOSError | 15 |
| 204:ProxyError | 10 |
| speed:ClientOSError | 9 |
| geo:TimeoutError | 9 |
| cn-block:ProxyError | 5 |
| geo:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| speed:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:47024: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4574 |
| ConnectionRefusedError | 899 |
| gaierror | 347 |
| OSError | 25 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 347 | 0.945 | 1804 |
| zhangkai | 0.929 | prefer | 24 | 0.958 | 144 |
| Surfboard-tg-mixed | 0.833 | prefer | 172 | 0.756 | 6846 |
| DeltaKronecker-all | 0.813 | prefer | 174 | 0.736 | 5576 |
| mheidari-all | 0.624 | observe | 11 | 0.818 | 15081 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4762 |
| Epodonios-all | 0.255 | observe | 0 | None | 7251 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3991 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7584 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.736 | 128 | 46 | 174 |
| Surfboard-tg-mixed | 0.756 | 130 | 42 | 172 |
| mheidari-all | 0.818 | 9 | 2 | 11 |
| Au1rxx-base64 | 0.945 | 328 | 19 | 347 |
| zhangkai | 0.958 | 23 | 1 | 24 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15081 | yes | 4.57 | 0 |
| SoliSpirit-all | 7584 | yes | 4.72 | 0 |
| Epodonios-all | 7251 | yes | 4.84 | 0 |
| Surfboard-tg-mixed | 6846 | yes | 3.87 | 0 |
| barry-far-vless | 5864 | yes | 3.02 | 0 |
| Surfboard-tg-vless | 5683 | yes | 4.11 | 0 |
| DeltaKronecker-all | 5576 | yes | 5.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 4762 | yes | 3.23 | 0 |
| MatinGhanbari-all-sub | 3991 | yes | 3.78 | 0 |
| mahdibland-V2RayAggregator | 3949 | yes | 1.49 | 0 |

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
| 204 | 39 |
| cn-block | 31 |
| geo | 28 |
| speed | 12 |
| sing-box exited 1 | 1 |
