# AutoNodes 每日报告

生成时间：2026-10-06 22:40:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 97769 |
| 去重后节点数 | 27067 |
| TCP 可达数 | 3000 |
| 真测通过数 | 526 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27067 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 73.8 |
| geo | 1.5 |
| probe | 181.4 |
| real_test | 178.1 |
| tcp | 45.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 46 | 21 | 25 | 45.7% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 161 | 155 | 6 | 96.3% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 110 | 105 | 5 | 95.5% |
| vless | 267 | 222 | 45 | 83.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 27 |
| cn-block:TimeoutError | 12 |
| 204:TimeoutError | 9 |
| geo:ClientOSError | 7 |
| cn-block:ClientOSError | 7 |
| speed:ClientOSError | 6 |
| speed:TimeoutError | 5 |
| geo:TimeoutError | 4 |
| geo:ProxyError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5982 |
| ConnectionRefusedError | 1017 |
| gaierror | 473 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 339 | 0.953 | 1829 |
| mheidari-all | 1.0 | prefer | 51 | 0.941 | 23303 |
| Surfboard-tg-mixed | 0.879 | prefer | 162 | 0.802 | 7055 |
| ermaozi | 0.487 | observe | 46 | 0.457 | 708 |
| ermaozi-get_subscribe | 0.279 | observe | 1 | 1.0 | 597 |
| DeltaKronecker-all | 0.263 | observe | 8 | 0.25 | 4889 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4990 |
| Epodonios-all | 0.255 | observe | 0 | None | 7604 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.25 | 2 | 6 | 8 |
| ermaozi | 0.457 | 21 | 25 | 46 |
| Surfboard-tg-mixed | 0.802 | 130 | 32 | 162 |
| mheidari-all | 0.941 | 48 | 3 | 51 |
| Au1rxx-base64 | 0.953 | 323 | 16 | 339 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23303 | yes | 6.1 | 0 |
| SoliSpirit-all | 9213 | yes | 2.16 | 0 |
| Epodonios-all | 7604 | yes | 3.36 | 0 |
| Surfboard-tg-mixed | 7055 | yes | 3.9 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.88 | 0 |
| barry-far-vless | 5954 | yes | 1.31 | 0 |
| Surfboard-tg-vless | 5593 | yes | 3.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 1.01 | 0 |
| DeltaKronecker-all | 4889 | yes | 5.33 | 0 |
| mahdibland-V2RayAggregator | 4373 | yes | 3.43 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 38 |
| cn-block | 20 |
| geo | 14 |
| speed | 11 |
