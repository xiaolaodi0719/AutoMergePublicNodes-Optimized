# AutoNodes 每日报告

生成时间：2026-10-09 05:48:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 98040 |
| 去重后节点数 | 27748 |
| TCP 可达数 | 3000 |
| 真测通过数 | 502 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27748 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 86.5 |
| geo | 1.5 |
| probe | 402.0 |
| real_test | 566.4 |
| tcp | 47.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 1 | 4 | 20.0% |
| http | 49 | 32 | 17 | 65.3% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 162 | 151 | 11 | 93.2% |
| socks | 6 | 2 | 4 | 33.3% |
| trojan | 105 | 95 | 10 | 90.5% |
| vless | 504 | 197 | 307 | 39.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 166 |
| speed:TimeoutError | 60 |
| geo:ClientOSError | 30 |
| 204:ProxyError | 27 |
| speed:ClientOSError | 25 |
| cn-block:TimeoutError | 15 |
| 204:TimeoutError | 13 |
| 204:ProxyConnectionError | 8 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6587 |
| ConnectionRefusedError | 1009 |
| gaierror | 405 |
| OSError | 239 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.979 | prefer | 360 | 0.911 | 1761 |
| Surfboard-tg-mixed | 0.83 | prefer | 54 | 0.759 | 7069 |
| ermaozi-get_subscribe | 0.564 | observe | 48 | 0.542 | 607 |
| zhangkai | 0.555 | observe | 8 | 1.0 | 144 |
| DeltaKronecker-all | 0.376 | observe | 15 | 0.333 | 5197 |
| mheidari-all | 0.332 | observe | 367 | 0.251 | 23125 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5081 |
| Epodonios-all | 0.255 | observe | 0 | None | 7569 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.251 | 92 | 275 | 367 |
| DeltaKronecker-all | 0.333 | 5 | 10 | 15 |
| ermaozi-get_subscribe | 0.542 | 26 | 22 | 48 |
| Surfboard-tg-mixed | 0.759 | 41 | 13 | 54 |
| Au1rxx-base64 | 0.911 | 328 | 32 | 360 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 8 | 0 | 8 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23125 | yes | 7.24 | 0 |
| SoliSpirit-all | 9901 | yes | 5.94 | 0 |
| Epodonios-all | 7569 | yes | 5.56 | 0 |
| Surfboard-tg-mixed | 7069 | yes | 4.2 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.17 | 0 |
| barry-far-vless | 5823 | yes | 3.58 | 0 |
| Surfboard-tg-vless | 5581 | yes | 4.67 | 0 |
| DeltaKronecker-all | 5197 | yes | 5.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 5081 | yes | 2.26 | 0 |
| mahdibland-V2RayAggregator | 4362 | yes | 3.65 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 198 |
| speed | 85 |
| 204 | 52 |
| cn-block | 19 |
