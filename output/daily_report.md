# AutoNodes 每日报告

生成时间：2026-09-03 11:02:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82568 |
| 去重后节点数 | 22928 |
| TCP 可达数 | 3000 |
| 真测通过数 | 513 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22928 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 44.1 |
| geo | 1.6 |
| probe | 82.7 |
| real_test | 115.8 |
| tcp | 37.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 114 | 108 | 6 | 94.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 40 | 26 | 14 | 65.0% |
| vless | 412 | 337 | 75 | 81.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 23 |
| 204:TimeoutError | 20 |
| geo:ClientOSError | 14 |
| geo:TimeoutError | 10 |
| 204:ProxyError | 8 |
| speed:TimeoutError | 5 |
| speed:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| 204:ProxyConnectionError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4715 |
| ConnectionRefusedError | 905 |
| gaierror | 324 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.974 | prefer | 312 | 0.907 | 1751 |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| mheidari-all | 0.868 | prefer | 111 | 0.793 | 16145 |
| Surfboard-tg-mixed | 0.815 | prefer | 160 | 0.738 | 7139 |
| DeltaKronecker-all | 0.287 | observe | 2 | 0.5 | 6335 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 87 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4671 |
| Epodonios-all | 0.255 | observe | 0 | None | 7527 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| DeltaKronecker-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.738 | 118 | 42 | 160 |
| mheidari-all | 0.793 | 88 | 23 | 111 |
| Au1rxx-base64 | 0.907 | 283 | 29 | 312 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16145 | yes | 4.7 | 0 |
| SoliSpirit-all | 8132 | yes | 4.49 | 0 |
| Epodonios-all | 7527 | yes | 3.17 | 0 |
| Surfboard-tg-mixed | 7139 | yes | 4.24 | 0 |
| DeltaKronecker-all | 6335 | yes | 4.84 | 0 |
| barry-far-vless | 6217 | yes | 2.8 | 0 |
| Surfboard-tg-vless | 6006 | yes | 3.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 4671 | yes | 3.03 | 0 |
| mahdibland-V2RayAggregator | 4081 | yes | 2.85 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.1 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 33 |
| cn-block | 28 |
| geo | 25 |
| speed | 10 |
