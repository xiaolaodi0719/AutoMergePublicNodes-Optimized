# AutoNodes 每日报告

生成时间：2026-07-25 08:18:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78921 |
| 去重后节点数 | 22393 |
| TCP 可达数 | 3000 |
| 真测通过数 | 749 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22393 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 36.5 |
| geo | 1.4 |
| probe | 63.2 |
| real_test | 180.3 |
| tcp | 31.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 35 | 1 | 97.2% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 18 | 11 | 7 | 61.1% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 607 | 575 | 32 | 94.7% |
| vless | 367 | 121 | 246 | 33.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 135 |
| speed:ClientOSError | 51 |
| cn-block:TimeoutError | 25 |
| geo:ClientOSError | 22 |
| 204:ProxyError | 17 |
| speed:TimeoutError | 12 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4057 |
| ConnectionRefusedError | 690 |
| gaierror | 369 |
| OSError | 218 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.95 | prefer | 36 | 0.972 | 61 |
| DeltaKronecker-all | 0.88 | prefer | 208 | 0.803 | 5838 |
| mheidari-all | 0.825 | prefer | 499 | 0.745 | 17378 |
| Surfboard-tg-mixed | 0.666 | observe | 283 | 0.587 | 5473 |
| Au1rxx-base64 | 0.566 | observe | 8 | 1.0 | 432 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4879 |
| Epodonios-all | 0.255 | observe | 0 | None | 6614 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6346 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.587 | 166 | 117 | 283 |
| mheidari-all | 0.745 | 372 | 127 | 499 |
| DeltaKronecker-all | 0.803 | 167 | 41 | 208 |
| zhangkai | 0.972 | 35 | 1 | 36 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| Au1rxx-base64 | 1.0 | 8 | 0 | 8 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17378 | yes | 3.1 | 0 |
| Epodonios-all | 6614 | yes | 3.27 | 0 |
| SoliSpirit-all | 6346 | yes | 3.04 | 0 |
| DeltaKronecker-all | 5838 | yes | 3.35 | 0 |
| Surfboard-tg-mixed | 5473 | yes | 2.05 | 0 |
| mahdibland-V2RayAggregator | 5009 | yes | 1.51 | 0 |
| barry-far-vless | 4927 | yes | 1.92 | 0 |
| 10ium-ScrapeCategorize-Vless | 4879 | yes | 2.12 | 0 |
| Surfboard-tg-vless | 4256 | yes | 1.9 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 1.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 160 |
| speed | 65 |
| cn-block | 33 |
| 204 | 29 |
