# AutoNodes 每日报告

生成时间：2026-10-14 21:38:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 98750 |
| 去重后节点数 | 27376 |
| TCP 可达数 | 3000 |
| 真测通过数 | 381 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27376 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 73.8 |
| geo | 1.5 |
| probe | 286.8 |
| real_test | 228.9 |
| tcp | 47.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 20 | 3 | 87.0% |
| hysteria2 | 7 | 7 | 0 | 100.0% |
| shadowsocks | 133 | 121 | 12 | 91.0% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 41 | 39 | 2 | 95.1% |
| vless | 245 | 192 | 53 | 78.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 17 |
| 204:ProxyConnectionError | 13 |
| speed:ClientOSError | 10 |
| 204:TimeoutError | 9 |
| speed:TimeoutError | 9 |
| geo:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| 204:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6821 |
| ConnectionRefusedError | 1050 |
| gaierror | 360 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.933 | prefer | 32 | 0.875 | 7197 |
| mheidari-all | 0.926 | prefer | 89 | 0.854 | 23828 |
| Au1rxx-base64 | 0.916 | prefer | 303 | 0.848 | 1761 |
| zhangkai | 0.846 | prefer | 23 | 0.87 | 144 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5125 |
| Epodonios-all | 0.255 | observe | 0 | None | 7716 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10189 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5754 |
| barry-far-vless | 0.255 | observe | 0 | None | 5978 |

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
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 3 | 3 |
| Au1rxx-base64 | 0.848 | 257 | 46 | 303 |
| mheidari-all | 0.854 | 76 | 13 | 89 |
| zhangkai | 0.87 | 20 | 3 | 23 |
| Surfboard-tg-mixed | 0.875 | 28 | 4 | 32 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23828 | yes | 5.73 | 0 |
| SoliSpirit-all | 10189 | yes | 4.95 | 0 |
| Epodonios-all | 7716 | yes | 6.52 | 0 |
| Surfboard-tg-mixed | 7197 | yes | 5.11 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.67 | 0 |
| barry-far-vless | 5978 | yes | 1.73 | 0 |
| Surfboard-tg-vless | 5754 | yes | 1.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 5125 | yes | 0.64 | 0 |
| DeltaKronecker-all | 4803 | yes | 6.03 | 0 |
| mahdibland-V2RayAggregator | 4271 | yes | 1.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 28 |
| cn-block | 20 |
| speed | 19 |
| geo | 5 |
