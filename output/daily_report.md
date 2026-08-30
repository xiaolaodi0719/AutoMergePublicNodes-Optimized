# AutoNodes 每日报告

生成时间：2026-08-30 04:49:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 86359 |
| 去重后节点数 | 21983 |
| TCP 可达数 | 3000 |
| 真测通过数 | 689 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21983 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 38.2 |
| geo | 1.4 |
| probe | 54.7 |
| real_test | 131.8 |
| tcp | 34.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 184 | 176 | 8 | 95.7% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 30 | 24 | 6 | 80.0% |
| vless | 590 | 437 | 153 | 74.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 42 |
| geo:ClientOSError | 40 |
| speed:TimeoutError | 31 |
| cn-block:TimeoutError | 20 |
| speed:ClientOSError | 13 |
| 204:ProxyError | 8 |
| 204:TimeoutError | 7 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4459 |
| ConnectionRefusedError | 906 |
| gaierror | 378 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 377 | 0.95 | 1825 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.96 | prefer | 73 | 0.89 | 6910 |
| DeltaKronecker-all | 0.846 | prefer | 92 | 0.772 | 4926 |
| mheidari-all | 0.668 | observe | 289 | 0.588 | 18105 |
| tg-oneclickvpnkeys | 0.318 | observe | 2 | 1.0 | 169 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4635 |
| Epodonios-all | 0.255 | observe | 0 | None | 7323 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3992 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7549 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.588 | 170 | 119 | 289 |
| DeltaKronecker-all | 0.772 | 71 | 21 | 92 |
| Surfboard-tg-mixed | 0.89 | 65 | 8 | 73 |
| Au1rxx-base64 | 0.95 | 358 | 19 | 377 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18105 | yes | 5.86 | 0 |
| SoliSpirit-all | 7549 | yes | 4.31 | 0 |
| Epodonios-all | 7323 | yes | 4.69 | 0 |
| Surfboard-tg-mixed | 6910 | yes | 4.28 | 0 |
| barry-far-vless | 5912 | yes | 2.87 | 0 |
| Surfboard-tg-vless | 5726 | yes | 3.93 | 0 |
| DeltaKronecker-all | 4926 | yes | 5.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 4635 | yes | 3.77 | 0 |
| nscl5-all | 4310 | yes | 3.02 | 0 |
| mahdibland-V2RayAggregator | 4012 | yes | 0.83 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 82 |
| speed | 45 |
| cn-block | 25 |
| 204 | 18 |
