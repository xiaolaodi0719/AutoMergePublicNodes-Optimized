# AutoNodes 每日报告

生成时间：2026-09-01 20:55:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 81580 |
| 去重后节点数 | 23552 |
| TCP 可达数 | 3000 |
| 真测通过数 | 662 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23552 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 37.4 |
| geo | 1.5 |
| probe | 84.0 |
| real_test | 136.9 |
| tcp | 36.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 19 | 4 | 82.6% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 169 | 157 | 12 | 92.9% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 30 | 25 | 5 | 83.3% |
| vless | 526 | 437 | 89 | 83.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 30 |
| 204:TimeoutError | 23 |
| cn-block:ClientOSError | 11 |
| speed:ClientOSError | 10 |
| 204:ProxyError | 10 |
| geo:ClientOSError | 9 |
| 204:ClientOSError | 6 |
| speed:TimeoutError | 5 |
| 204:ProxyConnectionError | 4 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4420 |
| ConnectionRefusedError | 903 |
| gaierror | 360 |
| OSError | 31 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | prefer | 419 | 0.9 | 1703 |
| mheidari-all | 0.915 | prefer | 119 | 0.84 | 15436 |
| DeltaKronecker-all | 0.874 | prefer | 32 | 0.812 | 7294 |
| Surfboard-tg-mixed | 0.857 | prefer | 177 | 0.78 | 6983 |
| zhangkai | 0.813 | prefer | 24 | 0.833 | 144 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4708 |
| Epodonios-all | 0.255 | observe | 0 | None | 7385 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7585 |

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
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.78 | 138 | 39 | 177 |
| DeltaKronecker-all | 0.812 | 26 | 6 | 32 |
| zhangkai | 0.833 | 20 | 4 | 24 |
| mheidari-all | 0.84 | 100 | 19 | 119 |
| Au1rxx-base64 | 0.9 | 377 | 42 | 419 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15436 | yes | 4.16 | 0 |
| SoliSpirit-all | 7585 | yes | 2.55 | 0 |
| Epodonios-all | 7385 | yes | 4.45 | 0 |
| DeltaKronecker-all | 7294 | yes | 4.33 | 0 |
| Surfboard-tg-mixed | 6983 | yes | 3.36 | 0 |
| barry-far-vless | 5987 | yes | 0.75 | 0 |
| Surfboard-tg-vless | 5851 | yes | 3.82 | 0 |
| 10ium-ScrapeCategorize-Vless | 4708 | yes | 1.02 | 0 |
| mahdibland-V2RayAggregator | 4159 | yes | 0.71 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.5 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 43 |
| cn-block | 43 |
| speed | 16 |
| geo | 10 |
