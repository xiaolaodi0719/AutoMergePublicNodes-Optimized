# AutoNodes 每日报告

生成时间：2026-09-02 16:24:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 82564 |
| 去重后节点数 | 23518 |
| TCP 可达数 | 3000 |
| 真测通过数 | 573 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23518 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 36.4 |
| geo | 1.5 |
| probe | 87.7 |
| real_test | 120.7 |
| tcp | 38.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 22 | 2 | 91.7% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 154 | 135 | 19 | 87.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 23 | 21 | 2 | 91.3% |
| vless | 455 | 379 | 76 | 83.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 19 |
| geo:ClientOSError | 16 |
| cn-block:ClientOSError | 14 |
| 204:ProxyError | 11 |
| 204:TimeoutError | 10 |
| speed:TimeoutError | 8 |
| speed:ClientOSError | 7 |
| 204:ClientOSError | 5 |
| 204:ProxyConnectionError | 4 |
| geo:TimeoutError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5067 |
| ConnectionRefusedError | 908 |
| gaierror | 332 |
| OSError | 24 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.97 | prefer | 349 | 0.903 | 1741 |
| mheidari-all | 0.949 | prefer | 120 | 0.875 | 15532 |
| zhangkai | 0.886 | prefer | 23 | 0.913 | 144 |
| Surfboard-tg-mixed | 0.808 | prefer | 156 | 0.731 | 7112 |
| DeltaKronecker-all | 0.776 | prefer | 21 | 0.714 | 7295 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 103 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4765 |
| Epodonios-all | 0.255 | observe | 0 | None | 7553 |

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
| DeltaKronecker-all | 0.714 | 15 | 6 | 21 |
| Surfboard-tg-mixed | 0.731 | 114 | 42 | 156 |
| mheidari-all | 0.875 | 105 | 15 | 120 |
| Au1rxx-base64 | 0.903 | 315 | 34 | 349 |
| zhangkai | 0.913 | 21 | 2 | 23 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15532 | yes | 5.09 | 0 |
| SoliSpirit-all | 7794 | yes | 3.13 | 0 |
| Epodonios-all | 7553 | yes | 5.31 | 0 |
| DeltaKronecker-all | 7295 | yes | 5.32 | 0 |
| Surfboard-tg-mixed | 7112 | yes | 4.33 | 0 |
| barry-far-vless | 6200 | yes | 2.33 | 0 |
| Surfboard-tg-vless | 5992 | yes | 4.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 4765 | yes | 2.12 | 0 |
| mahdibland-V2RayAggregator | 4066 | yes | 1.57 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.9 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 34 |
| 204 | 30 |
| geo | 21 |
| speed | 16 |
