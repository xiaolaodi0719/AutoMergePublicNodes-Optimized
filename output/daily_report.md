# AutoNodes 每日报告

生成时间：2026-09-11 11:09:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 84388 |
| 去重后节点数 | 23243 |
| TCP 可达数 | 3000 |
| 真测通过数 | 426 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23243 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 79.3 |
| geo | 1.4 |
| probe | 284.7 |
| real_test | 309.0 |
| tcp | 40.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 42 | 34 | 8 | 81.0% |
| hysteria2 | 9 | 8 | 1 | 88.9% |
| shadowsocks | 156 | 144 | 12 | 92.3% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 33 | 21 | 12 | 63.6% |
| vless | 300 | 216 | 84 | 72.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 26 |
| 204:TimeoutError | 23 |
| speed:TimeoutError | 17 |
| 204:ProxyError | 15 |
| cn-block:TimeoutError | 15 |
| 204:ClientOSError | 7 |
| speed:ClientOSError | 6 |
| cn-block:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5311 |
| ConnectionRefusedError | 894 |
| gaierror | 518 |
| OSError | 28 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.933 | prefer | 274 | 0.865 | 1772 |
| DeltaKronecker-all | 0.823 | prefer | 33 | 0.758 | 6070 |
| ermaozi | 0.79 | prefer | 42 | 0.786 | 431 |
| Surfboard-tg-mixed | 0.756 | prefer | 137 | 0.679 | 7422 |
| mheidari-all | 0.724 | prefer | 57 | 0.649 | 15701 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 199 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4932 |
| Epodonios-all | 0.255 | observe | 0 | None | 7889 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8749 |

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
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.649 | 37 | 20 | 57 |
| Surfboard-tg-mixed | 0.679 | 93 | 44 | 137 |
| DeltaKronecker-all | 0.758 | 25 | 8 | 33 |
| ermaozi | 0.786 | 33 | 9 | 42 |
| Au1rxx-base64 | 0.865 | 237 | 37 | 274 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15701 | yes | 5.15 | 0 |
| SoliSpirit-all | 8749 | yes | 3.01 | 0 |
| Epodonios-all | 7889 | yes | 3.28 | 0 |
| Surfboard-tg-mixed | 7422 | yes | 3.7 | 0 |
| barry-far-vless | 6213 | yes | 2.71 | 0 |
| DeltaKronecker-all | 6070 | yes | 5.14 | 0 |
| Surfboard-tg-vless | 5995 | yes | 4.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 4932 | yes | 2.19 | 0 |
| mahdibland-V2RayAggregator | 4223 | yes | 0.47 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.27 | 0 |

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
| 204 | 46 |
| geo | 30 |
| speed | 23 |
| cn-block | 20 |
