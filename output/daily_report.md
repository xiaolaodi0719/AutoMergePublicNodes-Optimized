# AutoNodes 每日报告

生成时间：2026-09-06 20:19:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94324 |
| 去重后节点数 | 24687 |
| TCP 可达数 | 3000 |
| 真测通过数 | 549 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24687 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 42.8 |
| geo | 1.4 |
| probe | 81.1 |
| real_test | 137.0 |
| tcp | 41.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 3 | 3 | 50.0% |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 173 | 148 | 25 | 85.5% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 31 | 25 | 6 | 80.6% |
| vless | 450 | 326 | 124 | 72.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 49 |
| geo:ClientOSError | 34 |
| 204:TimeoutError | 23 |
| cn-block:TimeoutError | 19 |
| speed:ClientOSError | 8 |
| 204:ProxyError | 7 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 5 |
| geo:TimeoutError | 4 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5526 |
| ConnectionRefusedError | 1005 |
| gaierror | 357 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.975 | prefer | 310 | 0.903 | 1862 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.793 | prefer | 186 | 0.715 | 7274 |
| mheidari-all | 0.675 | observe | 183 | 0.596 | 21188 |
| tg-oneclickvpnkeys | 0.298 | observe | 5 | 0.6 | 134 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4791 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 5856 |
| Epodonios-all | 0.255 | observe | 0 | None | 7817 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8616 |

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
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.596 | 109 | 74 | 183 |
| tg-oneclickvpnkeys | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.715 | 133 | 53 | 186 |
| Au1rxx-base64 | 0.903 | 280 | 30 | 310 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21188 | yes | 3.9 | 0 |
| SoliSpirit-all | 8616 | yes | 3.67 | 0 |
| Epodonios-all | 7817 | yes | 2.68 | 0 |
| Surfboard-tg-mixed | 7274 | yes | 1.27 | 0 |
| barry-far-vless | 6306 | yes | 2.36 | 0 |
| Surfboard-tg-vless | 6019 | yes | 3.25 | 0 |
| DeltaKronecker-all | 5856 | yes | 4.32 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 2.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 4791 | yes | 2.5 | 0 |
| mahdibland-V2RayAggregator | 4138 | yes | 0.6 | 0 |

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
| cn-block | 73 |
| geo | 40 |
| 204 | 35 |
| speed | 15 |
