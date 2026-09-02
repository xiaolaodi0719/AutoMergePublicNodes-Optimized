# AutoNodes 每日报告

生成时间：2026-09-02 20:55:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82593 |
| 去重后节点数 | 23713 |
| TCP 可达数 | 3000 |
| 真测通过数 | 554 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23713 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 36.2 |
| geo | 1.4 |
| probe | 83.6 |
| real_test | 121.8 |
| tcp | 37.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 132 | 118 | 14 | 89.4% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 37 | 36 | 1 | 97.3% |
| vless | 431 | 355 | 76 | 82.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 20 |
| geo:ClientOSError | 12 |
| cn-block:ClientOSError | 10 |
| 204:ProxyError | 9 |
| speed:TimeoutError | 6 |
| cn-block:ProxyError | 5 |
| speed:ClientOSError | 5 |
| 204:ClientOSError | 2 |
| geo:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4573 |
| ConnectionRefusedError | 928 |
| gaierror | 367 |
| OSError | 31 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.97 | prefer | 343 | 0.901 | 1798 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| mheidari-all | 0.88 | prefer | 118 | 0.805 | 15504 |
| Surfboard-tg-mixed | 0.85 | prefer | 150 | 0.773 | 7091 |
| DeltaKronecker-all | 0.629 | observe | 8 | 1.0 | 7295 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 131 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4765 |
| Epodonios-all | 0.255 | observe | 0 | None | 7530 |

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
| Surfboard-tg-mixed | 0.773 | 116 | 34 | 150 |
| mheidari-all | 0.805 | 95 | 23 | 118 |
| Au1rxx-base64 | 0.901 | 309 | 34 | 343 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 8 | 0 | 8 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15504 | yes | 4.63 | 0 |
| SoliSpirit-all | 7745 | yes | 3.68 | 0 |
| Epodonios-all | 7530 | yes | 4.83 | 0 |
| DeltaKronecker-all | 7295 | yes | 5.19 | 0 |
| Surfboard-tg-mixed | 7091 | yes | 3.66 | 0 |
| barry-far-vless | 6223 | yes | 2.44 | 0 |
| Surfboard-tg-vless | 6013 | yes | 3.36 | 0 |
| 10ium-ScrapeCategorize-Vless | 4765 | yes | 2.72 | 0 |
| mahdibland-V2RayAggregator | 4066 | yes | 0.53 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 2.52 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 35 |
| 204 | 32 |
| geo | 14 |
| speed | 11 |
