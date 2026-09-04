# AutoNodes 每日报告

生成时间：2026-09-04 11:02:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83808 |
| 去重后节点数 | 23398 |
| TCP 可达数 | 3000 |
| 真测通过数 | 589 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23398 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 43.4 |
| geo | 1.4 |
| probe | 88.9 |
| real_test | 127.2 |
| tcp | 37.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 160 | 148 | 12 | 92.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 38 | 26 | 12 | 68.4% |
| vless | 460 | 371 | 89 | 80.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 22 |
| geo:ClientOSError | 19 |
| speed:TimeoutError | 17 |
| cn-block:TimeoutError | 17 |
| cn-block:ClientOSError | 12 |
| 204:TimeoutError | 11 |
| speed:ClientOSError | 8 |
| 204:ProxyError | 4 |
| geo:ProxyError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4906 |
| ConnectionRefusedError | 885 |
| gaierror | 319 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| Au1rxx-base64 | 0.945 | prefer | 367 | 0.877 | 1736 |
| Surfboard-tg-mixed | 0.922 | prefer | 156 | 0.846 | 7244 |
| mheidari-all | 0.828 | prefer | 129 | 0.752 | 15923 |
| DeltaKronecker-all | 0.561 | observe | 25 | 0.48 | 7089 |
| tg-oneclickvpnkeys | 0.443 | observe | 5 | 1.0 | 87 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4810 |
| Epodonios-all | 0.255 | observe | 0 | None | 7763 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7993 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.48 | 12 | 13 | 25 |
| mheidari-all | 0.752 | 97 | 32 | 129 |
| Surfboard-tg-mixed | 0.846 | 132 | 24 | 156 |
| Au1rxx-base64 | 0.877 | 322 | 45 | 367 |
| tg-oneclickvpnkeys | 1.0 | 5 | 0 | 5 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15923 | yes | 4.74 | 0 |
| SoliSpirit-all | 7993 | yes | 3.9 | 0 |
| Epodonios-all | 7763 | yes | 2.99 | 0 |
| Surfboard-tg-mixed | 7244 | yes | 3.74 | 0 |
| DeltaKronecker-all | 7089 | yes | 4.5 | 0 |
| barry-far-vless | 6426 | yes | 1.91 | 0 |
| Surfboard-tg-vless | 6120 | yes | 3.93 | 0 |
| 10ium-ScrapeCategorize-Vless | 4810 | yes | 2.09 | 0 |
| mahdibland-V2RayAggregator | 4123 | yes | 0.5 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.2 | 0 |

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
| geo | 44 |
| cn-block | 30 |
| speed | 25 |
| 204 | 17 |
