# AutoNodes 每日报告

生成时间：2026-10-17 10:36:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99304 |
| 去重后节点数 | 27773 |
| TCP 可达数 | 3000 |
| 真测通过数 | 443 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27773 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 81.4 |
| geo | 1.5 |
| probe | 347.3 |
| real_test | 279.8 |
| tcp | 49.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 53 | 30 | 23 | 56.6% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 159 | 145 | 14 | 91.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 65 | 39 | 26 | 60.0% |
| vless | 300 | 212 | 88 | 70.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 44 |
| 204:ProxyError | 28 |
| geo:ClientOSError | 18 |
| speed:ClientOSError | 16 |
| cn-block:TimeoutError | 15 |
| speed:TimeoutError | 14 |
| geo:TimeoutError | 10 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7181 |
| ConnectionRefusedError | 1044 |
| OSError | 236 |
| gaierror | 217 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.923 | prefer | 451 | 0.845 | 1994 |
| ermaozi | 0.607 | observe | 55 | 0.582 | 702 |
| Surfboard-tg-mixed | 0.493 | observe | 44 | 0.409 | 7171 |
| mheidari-all | 0.446 | observe | 8 | 0.625 | 23828 |
| ermaozi-get_subscribe | 0.279 | observe | 1 | 1.0 | 601 |
| DeltaKronecker-all | 0.259 | observe | 37 | 0.162 | 4999 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4986 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1994 |
| Epodonios-all | 0.255 | observe | 0 | None | 7611 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.162 | 6 | 31 | 37 |
| Surfboard-tg-mixed | 0.409 | 18 | 26 | 44 |
| ermaozi | 0.582 | 32 | 23 | 55 |
| mheidari-all | 0.625 | 5 | 3 | 8 |
| Au1rxx-base64 | 0.845 | 381 | 70 | 451 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23828 | yes | 3.0 | 0 |
| SoliSpirit-all | 9902 | yes | 2.97 | 0 |
| Epodonios-all | 7611 | yes | 3.29 | 0 |
| Surfboard-tg-mixed | 7171 | yes | 3.73 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.98 | 0 |
| barry-far-vless | 5842 | yes | 1.54 | 0 |
| Surfboard-tg-vless | 5617 | yes | 2.08 | 0 |
| DeltaKronecker-all | 4999 | yes | 3.71 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 2.49 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 1.89 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 76 |
| speed | 31 |
| geo | 28 |
| cn-block | 19 |
