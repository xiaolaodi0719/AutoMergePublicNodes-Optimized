# AutoNodes 每日报告

生成时间：2026-10-03 11:32:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98931 |
| 去重后节点数 | 27239 |
| TCP 可达数 | 3000 |
| 真测通过数 | 362 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27239 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 82.3 |
| geo | 1.3 |
| probe | 223.2 |
| real_test | 179.4 |
| tcp | 47.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 24 | 13 | 11 | 54.2% |
| hysteria2 | 17 | 14 | 3 | 82.4% |
| shadowsocks | 158 | 135 | 23 | 85.4% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 32 | 28 | 4 | 87.5% |
| vless | 219 | 169 | 50 | 77.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 20 |
| speed:TimeoutError | 12 |
| 204:ProxyConnectionError | 10 |
| geo:TimeoutError | 9 |
| 204:ProxyError | 5 |
| speed:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6751 |
| ConnectionRefusedError | 1155 |
| gaierror | 368 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.938 | prefer | 241 | 0.871 | 1754 |
| Surfboard-tg-mixed | 0.811 | prefer | 117 | 0.735 | 7251 |
| mheidari-all | 0.809 | prefer | 57 | 0.737 | 23264 |
| ermaozi | 0.564 | observe | 24 | 0.542 | 645 |
| DeltaKronecker-all | 0.53 | observe | 10 | 0.7 | 5207 |
| ermaozi-get_subscribe | 0.332 | observe | 2 | 1.0 | 516 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5192 |
| Epodonios-all | 0.255 | observe | 0 | None | 7748 |

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
| ermaozi | 0.542 | 13 | 11 | 24 |
| DeltaKronecker-all | 0.7 | 7 | 3 | 10 |
| Surfboard-tg-mixed | 0.735 | 86 | 31 | 117 |
| mheidari-all | 0.737 | 42 | 15 | 57 |
| Au1rxx-base64 | 0.871 | 210 | 31 | 241 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23264 | yes | 6.62 | 0 |
| SoliSpirit-all | 9363 | yes | 2.79 | 0 |
| Epodonios-all | 7748 | yes | 4.78 | 0 |
| Surfboard-tg-mixed | 7251 | yes | 5.11 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.08 | 0 |
| barry-far-vless | 6206 | yes | 1.28 | 0 |
| Surfboard-tg-vless | 5966 | yes | 4.46 | 0 |
| DeltaKronecker-all | 5207 | yes | 4.83 | 0 |
| 10ium-ScrapeCategorize-Vless | 5192 | yes | 0.46 | 0 |
| mahdibland-V2RayAggregator | 4335 | yes | 3.06 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 41 |
| cn-block | 25 |
| speed | 15 |
| geo | 11 |
