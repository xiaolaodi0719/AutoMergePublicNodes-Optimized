# AutoNodes 每日报告

生成时间：2026-08-31 04:53:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78971 |
| 去重后节点数 | 21904 |
| TCP 可达数 | 3000 |
| 真测通过数 | 657 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21904 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 26.8 |
| geo | 1.5 |
| probe | 89.0 |
| real_test | 151.8 |
| tcp | 34.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 23 | 1 | 95.8% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 147 | 142 | 5 | 96.6% |
| socks | 7 | 3 | 4 | 42.9% |
| trojan | 45 | 31 | 14 | 68.9% |
| vless | 687 | 437 | 250 | 63.6% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 109 |
| geo:ClientOSError | 53 |
| speed:TimeoutError | 24 |
| cn-block:TimeoutError | 22 |
| speed:ClientOSError | 21 |
| 204:TimeoutError | 20 |
| 204:ProxyError | 10 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| cn-block:ClientOSError | 4 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4841 |
| ConnectionRefusedError | 876 |
| gaierror | 315 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | prefer | 322 | 0.925 | 1804 |
| zhangkai | 0.967 | prefer | 24 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.787 | prefer | 220 | 0.709 | 6765 |
| mheidari-all | 0.594 | observe | 18 | 0.556 | 14559 |
| DeltaKronecker-all | 0.565 | observe | 342 | 0.485 | 5576 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 4762 |
| Epodonios-all | 0.335 | observe | 1 | 1.0 | 7271 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7850 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.485 | 166 | 176 | 342 |
| mheidari-all | 0.556 | 10 | 8 | 18 |
| Surfboard-tg-mixed | 0.709 | 156 | 64 | 220 |
| Au1rxx-base64 | 0.925 | 298 | 24 | 322 |
| Epodonios-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14559 | yes | 4.74 | 0 |
| SoliSpirit-all | 7850 | yes | 3.73 | 0 |
| Epodonios-all | 7271 | yes | 4.09 | 0 |
| Surfboard-tg-mixed | 6765 | yes | 3.92 | 0 |
| barry-far-vless | 5858 | yes | 3.03 | 0 |
| Surfboard-tg-vless | 5673 | yes | 3.5 | 0 |
| DeltaKronecker-all | 5576 | yes | 4.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 4762 | yes | 2.62 | 0 |
| mahdibland-V2RayAggregator | 4041 | yes | 0.75 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.8 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 163 |
| speed | 47 |
| 204 | 35 |
| cn-block | 30 |
