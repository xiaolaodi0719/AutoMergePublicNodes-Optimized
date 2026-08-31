# AutoNodes 每日报告

生成时间：2026-08-31 13:18:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 79273 |
| 去重后节点数 | 22274 |
| TCP 可达数 | 3000 |
| 真测通过数 | 534 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22274 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 34.7 |
| geo | 1.4 |
| probe | 87.9 |
| real_test | 105.6 |
| tcp | 35.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 19 | 4 | 82.6% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 164 | 150 | 14 | 91.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 18 | 16 | 2 | 88.9% |
| vless | 388 | 329 | 59 | 84.8% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 14 |
| geo:ClientOSError | 12 |
| 204:ProxyError | 12 |
| speed:TimeoutError | 6 |
| 204:ProxyConnectionError | 5 |
| geo:TimeoutError | 4 |
| cn-block:ClientOSError | 4 |
| speed:ClientOSError | 4 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4751 |
| ConnectionRefusedError | 912 |
| gaierror | 364 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 306 | 0.948 | 1804 |
| Surfboard-tg-mixed | 0.877 | prefer | 175 | 0.8 | 6828 |
| mheidari-all | 0.851 | prefer | 68 | 0.779 | 14620 |
| DeltaKronecker-all | 0.824 | prefer | 41 | 0.756 | 5904 |
| zhangkai | 0.806 | prefer | 23 | 0.826 | 144 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4657 |
| Epodonios-all | 0.255 | observe | 0 | None | 7174 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7956 |

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
| DeltaKronecker-all | 0.756 | 31 | 10 | 41 |
| mheidari-all | 0.779 | 53 | 15 | 68 |
| Surfboard-tg-mixed | 0.8 | 140 | 35 | 175 |
| zhangkai | 0.826 | 19 | 4 | 23 |
| Au1rxx-base64 | 0.948 | 290 | 16 | 306 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14620 | yes | 4.76 | 0 |
| SoliSpirit-all | 7956 | yes | 2.84 | 0 |
| Epodonios-all | 7174 | yes | 3.23 | 0 |
| Surfboard-tg-mixed | 6828 | yes | 3.92 | 0 |
| DeltaKronecker-all | 5904 | yes | 4.91 | 0 |
| barry-far-vless | 5864 | yes | 1.41 | 0 |
| Surfboard-tg-vless | 5768 | yes | 3.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 1.91 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.43 | 0 |
| mahdibland-V2RayAggregator | 3987 | yes | 0.52 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 36 |
| cn-block | 18 |
| geo | 17 |
| speed | 10 |
