# AutoNodes 每日报告

生成时间：2026-09-25 21:28:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 97258 |
| 去重后节点数 | 26464 |
| TCP 可达数 | 3000 |
| 真测通过数 | 381 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26464 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 79.6 |
| geo | 1.4 |
| probe | 189.6 |
| real_test | 151.7 |
| tcp | 43.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 30 | 18 | 12 | 60.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 146 | 128 | 18 | 87.7% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 11 | 9 | 2 | 81.8% |
| vless | 240 | 202 | 38 | 84.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 17 |
| 204:ProxyError | 14 |
| 204:TimeoutError | 12 |
| 204:ProxyConnectionError | 6 |
| speed:ClientOSError | 5 |
| speed:TimeoutError | 5 |
| cn-block:ClientOSError | 3 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 2 |
| geo:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5802 |
| ConnectionRefusedError | 968 |
| gaierror | 384 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.967 | prefer | 69 | 0.899 | 22345 |
| Au1rxx-base64 | 0.955 | prefer | 237 | 0.89 | 1701 |
| DeltaKronecker-all | 0.892 | prefer | 46 | 0.826 | 5452 |
| Surfboard-tg-mixed | 0.809 | prefer | 68 | 0.735 | 7370 |
| ermaozi | 0.593 | observe | 29 | 0.586 | 304 |
| ermaozi-get_subscribe | 0.324 | observe | 2 | 1.0 | 314 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 69 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5293 |
| Epodonios-all | 0.255 | observe | 0 | None | 7740 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.586 | 17 | 12 | 29 |
| Surfboard-tg-mixed | 0.735 | 50 | 18 | 68 |
| DeltaKronecker-all | 0.826 | 38 | 8 | 46 |
| Au1rxx-base64 | 0.89 | 211 | 26 | 237 |
| mheidari-all | 0.899 | 62 | 7 | 69 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22345 | yes | 6.6 | 0 |
| SoliSpirit-all | 9253 | yes | 2.36 | 0 |
| Epodonios-all | 7740 | yes | 3.33 | 0 |
| Surfboard-tg-mixed | 7370 | yes | 5.83 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.99 | 0 |
| barry-far-vless | 6190 | yes | 1.23 | 0 |
| Surfboard-tg-vless | 5959 | yes | 3.9 | 0 |
| DeltaKronecker-all | 5452 | yes | 5.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 5293 | yes | 0.7 | 0 |
| mahdibland-V2RayAggregator | 4304 | yes | 3.06 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 34 |
| cn-block | 22 |
| speed | 12 |
| geo | 5 |
