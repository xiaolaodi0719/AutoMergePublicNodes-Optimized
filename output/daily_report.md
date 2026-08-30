# AutoNodes 每日报告

生成时间：2026-08-30 16:29:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79920 |
| 去重后节点数 | 21856 |
| TCP 可达数 | 3000 |
| 真测通过数 | 583 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21856 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 41.6 |
| geo | 1.5 |
| probe | 56.8 |
| real_test | 145.0 |
| tcp | 35.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 151 | 134 | 17 | 88.7% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 31 | 24 | 7 | 77.4% |
| vless | 481 | 380 | 101 | 79.0% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 34 |
| geo:TimeoutError | 23 |
| cn-block:TimeoutError | 15 |
| geo:ClientOSError | 13 |
| 204:ProxyError | 13 |
| speed:ClientOSError | 11 |
| speed:TimeoutError | 8 |
| 204:ClientOSError | 7 |
| cn-block:ProxyError | 4 |
| cn-block:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4727 |
| ConnectionRefusedError | 883 |
| gaierror | 332 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.967 | prefer | 24 | 1.0 | 144 |
| Au1rxx-base64 | 0.955 | prefer | 339 | 0.885 | 1804 |
| DeltaKronecker-all | 0.814 | prefer | 175 | 0.737 | 5576 |
| Surfboard-tg-mixed | 0.812 | prefer | 162 | 0.735 | 7004 |
| mheidari-all | 0.699 | observe | 10 | 1.0 | 15115 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4762 |
| Epodonios-all | 0.255 | observe | 0 | None | 7409 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7601 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
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
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.735 | 119 | 43 | 162 |
| DeltaKronecker-all | 0.737 | 129 | 46 | 175 |
| Au1rxx-base64 | 0.885 | 300 | 39 | 339 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 10 | 0 | 10 |
| zhangkai | 1.0 | 24 | 0 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15115 | yes | 4.56 | 0 |
| SoliSpirit-all | 7601 | yes | 3.56 | 0 |
| Epodonios-all | 7409 | yes | 5.59 | 0 |
| Surfboard-tg-mixed | 7004 | yes | 4.19 | 0 |
| barry-far-vless | 6056 | yes | 2.12 | 0 |
| Surfboard-tg-vless | 5872 | yes | 3.95 | 0 |
| DeltaKronecker-all | 5576 | yes | 4.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 4762 | yes | 2.33 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.92 | 0 |
| mahdibland-V2RayAggregator | 3949 | yes | 1.43 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 54 |
| geo | 36 |
| cn-block | 20 |
| speed | 20 |
