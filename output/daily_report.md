# AutoNodes 每日报告

生成时间：2026-10-14 04:31:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 98590 |
| 去重后节点数 | 27420 |
| TCP 可达数 | 3000 |
| 真测通过数 | 437 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27420 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 89.8 |
| geo | 1.7 |
| probe | 258.9 |
| real_test | 352.7 |
| tcp | 47.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 42 | 13 | 29 | 31.0% |
| hysteria2 | 7 | 6 | 1 | 85.7% |
| shadowsocks | 145 | 134 | 11 | 92.4% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 85 | 78 | 7 | 91.8% |
| vless | 357 | 199 | 158 | 55.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 78 |
| 204:ProxyError | 23 |
| geo:ClientOSError | 22 |
| speed:ClientOSError | 20 |
| cn-block:TimeoutError | 19 |
| 204:ProxyConnectionError | 14 |
| 204:TimeoutError | 11 |
| speed:TimeoutError | 11 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6865 |
| ConnectionRefusedError | 1044 |
| gaierror | 280 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.946 | prefer | 326 | 0.877 | 1771 |
| Surfboard-tg-mixed | 0.899 | prefer | 70 | 0.829 | 7113 |
| mheidari-all | 0.457 | observe | 189 | 0.376 | 24076 |
| DeltaKronecker-all | 0.397 | observe | 12 | 0.417 | 5076 |
| ermaozi-get_subscribe | 0.349 | observe | 38 | 0.316 | 598 |
| zhangkai | 0.311 | observe | 8 | 0.5 | 144 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5086 |
| Epodonios-all | 0.255 | observe | 0 | None | 7613 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.316 | 12 | 26 | 38 |
| mheidari-all | 0.376 | 71 | 118 | 189 |
| DeltaKronecker-all | 0.417 | 5 | 7 | 12 |
| zhangkai | 0.5 | 4 | 4 | 8 |
| Surfboard-tg-mixed | 0.829 | 58 | 12 | 70 |
| Au1rxx-base64 | 0.877 | 286 | 40 | 326 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24076 | yes | 7.84 | 0 |
| SoliSpirit-all | 9825 | yes | 2.99 | 0 |
| Epodonios-all | 7613 | yes | 7.13 | 0 |
| Surfboard-tg-mixed | 7113 | yes | 4.37 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.83 | 0 |
| barry-far-vless | 5866 | yes | 0.57 | 0 |
| Surfboard-tg-vless | 5621 | yes | 6.07 | 0 |
| 10ium-ScrapeCategorize-Vless | 5086 | yes | 1.12 | 0 |
| DeltaKronecker-all | 5076 | yes | 5.57 | 0 |
| mahdibland-V2RayAggregator | 4216 | yes | 3.65 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 100 |
| 204 | 49 |
| speed | 32 |
| cn-block | 27 |
