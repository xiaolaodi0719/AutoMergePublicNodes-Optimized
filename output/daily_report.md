# AutoNodes 每日报告

生成时间：2026-10-04 12:13:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 99561 |
| 去重后节点数 | 27370 |
| TCP 可达数 | 3000 |
| 真测通过数 | 420 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27370 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 74.1 |
| geo | 1.5 |
| probe | 217.4 |
| real_test | 180.1 |
| tcp | 46.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 2 | 2 | 50.0% |
| http | 23 | 22 | 1 | 95.7% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 150 | 131 | 19 | 87.3% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 79 | 74 | 5 | 93.7% |
| vless | 217 | 175 | 42 | 80.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 21 |
| 204:TimeoutError | 17 |
| 204:ProxyError | 10 |
| speed:TimeoutError | 6 |
| cn-block:ClientOSError | 5 |
| geo:TimeoutError | 4 |
| speed:ClientOSError | 3 |
| geo:ClientOSError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6333 |
| ConnectionRefusedError | 1118 |
| gaierror | 425 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.96 | prefer | 300 | 0.89 | 1816 |
| ermaozi | 0.946 | prefer | 23 | 0.957 | 646 |
| Surfboard-tg-mixed | 0.883 | prefer | 115 | 0.809 | 7269 |
| mheidari-all | 0.835 | prefer | 47 | 0.766 | 23332 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5173 |
| Epodonios-all | 0.255 | observe | 0 | None | 7796 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9804 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5821 |

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
| DeltaKronecker-all | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.766 | 36 | 11 | 47 |
| Surfboard-tg-mixed | 0.809 | 93 | 22 | 115 |
| Au1rxx-base64 | 0.89 | 267 | 33 | 300 |
| ermaozi | 0.957 | 22 | 1 | 23 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23332 | yes | 4.98 | 0 |
| SoliSpirit-all | 9804 | yes | 4.71 | 0 |
| Epodonios-all | 7796 | yes | 5.43 | 0 |
| Surfboard-tg-mixed | 7269 | yes | 3.78 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.71 | 0 |
| barry-far-vless | 6148 | yes | 3.04 | 0 |
| Surfboard-tg-vless | 5821 | yes | 3.34 | 0 |
| DeltaKronecker-all | 5267 | yes | 5.59 | 0 |
| 10ium-ScrapeCategorize-Vless | 5173 | yes | 2.6 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 2.79 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 29 |
| cn-block | 27 |
| speed | 10 |
| geo | 6 |
