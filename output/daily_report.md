# AutoNodes 每日报告

生成时间：2026-09-02 11:03:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82681 |
| 去重后节点数 | 23587 |
| TCP 可达数 | 3000 |
| 真测通过数 | 598 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23587 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 36.2 |
| geo | 1.4 |
| probe | 85.7 |
| real_test | 121.7 |
| tcp | 38.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 157 | 143 | 14 | 91.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 29 | 21 | 8 | 72.4% |
| vless | 505 | 391 | 114 | 77.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 26 |
| geo:ClientOSError | 23 |
| 204:TimeoutError | 23 |
| 204:ProxyError | 15 |
| geo:TimeoutError | 12 |
| speed:ClientOSError | 11 |
| 204:ClientOSError | 9 |
| speed:TimeoutError | 9 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4974 |
| ConnectionRefusedError | 899 |
| gaierror | 280 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| Au1rxx-base64 | 0.952 | prefer | 411 | 0.881 | 1826 |
| mheidari-all | 0.819 | prefer | 117 | 0.744 | 15813 |
| Surfboard-tg-mixed | 0.784 | prefer | 160 | 0.706 | 7112 |
| DeltaKronecker-all | 0.618 | observe | 24 | 0.542 | 7295 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 102 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 47 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4765 |
| Epodonios-all | 0.255 | observe | 0 | None | 7428 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.542 | 13 | 11 | 24 |
| Surfboard-tg-mixed | 0.706 | 113 | 47 | 160 |
| mheidari-all | 0.744 | 87 | 30 | 117 |
| Au1rxx-base64 | 0.881 | 362 | 49 | 411 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15813 | yes | 3.9 | 0 |
| SoliSpirit-all | 7727 | yes | 3.72 | 0 |
| Epodonios-all | 7428 | yes | 4.12 | 0 |
| DeltaKronecker-all | 7295 | yes | 5.48 | 0 |
| Surfboard-tg-mixed | 7112 | yes | 3.48 | 0 |
| barry-far-vless | 6070 | yes | 2.08 | 0 |
| Surfboard-tg-vless | 5992 | yes | 3.28 | 0 |
| 10ium-ScrapeCategorize-Vless | 4765 | yes | 2.26 | 0 |
| mahdibland-V2RayAggregator | 4066 | yes | 2.43 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 2.33 | 0 |

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
| 204 | 47 |
| geo | 36 |
| cn-block | 35 |
| speed | 20 |
