# AutoNodes 每日报告

生成时间：2026-09-28 13:35:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 96149 |
| 去重后节点数 | 26789 |
| TCP 可达数 | 3000 |
| 真测通过数 | 430 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26789 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 75.8 |
| geo | 1.5 |
| probe | 279.3 |
| real_test | 204.1 |
| tcp | 44.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 51 | 26 | 25 | 51.0% |
| hysteria2 | 25 | 22 | 3 | 88.0% |
| shadowsocks | 168 | 148 | 20 | 88.1% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 26 | 25 | 1 | 96.2% |
| vless | 287 | 207 | 80 | 72.1% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 25 |
| 204:TimeoutError | 21 |
| speed:ClientOSError | 20 |
| 204:ProxyError | 18 |
| speed:TimeoutError | 16 |
| 204:ProxyConnectionError | 12 |
| geo:TimeoutError | 11 |
| cn-block:ClientOSError | 4 |
| geo:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6067 |
| ConnectionRefusedError | 963 |
| gaierror | 362 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.927 | prefer | 57 | 0.86 | 22474 |
| Au1rxx-base64 | 0.881 | prefer | 304 | 0.816 | 1677 |
| Surfboard-tg-mixed | 0.801 | prefer | 127 | 0.724 | 7046 |
| ermaozi | 0.569 | observe | 52 | 0.558 | 344 |
| DeltaKronecker-all | 0.543 | observe | 13 | 0.615 | 5428 |
| tg-oneclickvpnkeys | 0.315 | observe | 2 | 1.0 | 94 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5326 |
| Epodonios-all | 0.255 | observe | 0 | None | 7414 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.161 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| ermaozi | 0.558 | 29 | 23 | 52 |
| DeltaKronecker-all | 0.615 | 8 | 5 | 13 |
| Surfboard-tg-mixed | 0.724 | 92 | 35 | 127 |
| Au1rxx-base64 | 0.816 | 248 | 56 | 304 |
| mheidari-all | 0.86 | 49 | 8 | 57 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22474 | yes | 5.71 | 0 |
| SoliSpirit-all | 9420 | yes | 3.96 | 0 |
| Epodonios-all | 7414 | yes | 6.67 | 0 |
| Surfboard-tg-mixed | 7046 | yes | 4.41 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.99 | 0 |
| barry-far-vless | 5752 | yes | 1.01 | 0 |
| Surfboard-tg-vless | 5638 | yes | 3.85 | 0 |
| DeltaKronecker-all | 5428 | yes | 5.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 5326 | yes | 0.55 | 0 |
| mahdibland-V2RayAggregator | 4185 | yes | 0.26 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 53 |
| speed | 36 |
| cn-block | 30 |
| geo | 14 |
