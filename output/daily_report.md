# AutoNodes 每日报告

生成时间：2026-09-09 20:54:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83567 |
| 去重后节点数 | 22107 |
| TCP 可达数 | 3000 |
| 真测通过数 | 378 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22107 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 88.7 |
| geo | 1.4 |
| probe | 196.6 |
| real_test | 200.2 |
| tcp | 37.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 24 | 14 | 10 | 58.3% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 148 | 135 | 13 | 91.2% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 17 | 15 | 2 | 88.2% |
| vless | 257 | 195 | 62 | 75.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 21 |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 12 |
| 204:ProxyError | 9 |
| 204:ProxyConnectionError | 7 |
| cn-block:ClientOSError | 7 |
| speed:TimeoutError | 5 |
| speed:ClientOSError | 4 |
| 204:ClientOSError | 2 |
| geo:TimeoutError | 2 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5121 |
| ConnectionRefusedError | 861 |
| gaierror | 314 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.954 | prefer | 305 | 0.895 | 1527 |
| Surfboard-tg-mixed | 0.786 | prefer | 66 | 0.712 | 7393 |
| DeltaKronecker-all | 0.723 | prefer | 54 | 0.648 | 5187 |
| ermaozi | 0.555 | observe | 24 | 0.542 | 410 |
| mheidari-all | 0.474 | observe | 15 | 0.467 | 16196 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 147 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4795 |
| Epodonios-all | 0.255 | observe | 0 | None | 7839 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.467 | 7 | 8 | 15 |
| ermaozi | 0.542 | 13 | 11 | 24 |
| DeltaKronecker-all | 0.648 | 35 | 19 | 54 |
| Surfboard-tg-mixed | 0.712 | 47 | 19 | 66 |
| Au1rxx-base64 | 0.895 | 273 | 32 | 305 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16196 | yes | 4.5 | 0 |
| SoliSpirit-all | 8955 | yes | 2.07 | 0 |
| Epodonios-all | 7839 | yes | 5.26 | 0 |
| Surfboard-tg-mixed | 7393 | yes | 5.58 | 0 |
| barry-far-vless | 6253 | yes | 1.12 | 0 |
| Surfboard-tg-vless | 6033 | yes | 3.71 | 0 |
| DeltaKronecker-all | 5187 | yes | 4.62 | 0 |
| 10ium-ScrapeCategorize-Vless | 4795 | yes | 0.5 | 0 |
| mahdibland-V2RayAggregator | 4247 | yes | 3.05 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.87 | 0 |

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
| 204 | 30 |
| cn-block | 27 |
| geo | 24 |
| speed | 10 |
