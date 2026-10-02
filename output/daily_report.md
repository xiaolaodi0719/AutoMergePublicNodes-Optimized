# AutoNodes 每日报告

生成时间：2026-10-02 12:21:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 97754 |
| 去重后节点数 | 26970 |
| TCP 可达数 | 3000 |
| 真测通过数 | 380 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26970 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 78.0 |
| geo | 1.3 |
| probe | 215.4 |
| real_test | 181.3 |
| tcp | 46.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 24 | 18 | 6 | 75.0% |
| hysteria2 | 21 | 21 | 0 | 100.0% |
| shadowsocks | 146 | 128 | 18 | 87.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 17 | 10 | 7 | 58.8% |
| vless | 264 | 201 | 63 | 76.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 26 |
| cn-block:TimeoutError | 23 |
| speed:ClientOSError | 12 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 6 |
| speed:TimeoutError | 6 |
| 204:ProxyConnectionError | 5 |
| geo:TimeoutError | 5 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6848 |
| ConnectionRefusedError | 1129 |
| gaierror | 336 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.904 | prefer | 286 | 0.839 | 1673 |
| mheidari-all | 0.863 | prefer | 44 | 0.795 | 23059 |
| Surfboard-tg-mixed | 0.821 | prefer | 114 | 0.746 | 7176 |
| ermaozi | 0.728 | prefer | 25 | 0.72 | 618 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Pawdroid | 0.255 | observe | 1 | 1.0 | 12 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5276 |
| Epodonios-all | 0.255 | observe | 0 | None | 7676 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9234 |

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
| DeltaKronecker-all | 0.0 | 0 | 4 | 4 |
| ermaozi | 0.72 | 18 | 7 | 25 |
| Surfboard-tg-mixed | 0.746 | 85 | 29 | 114 |
| mheidari-all | 0.795 | 35 | 9 | 44 |
| Au1rxx-base64 | 0.839 | 240 | 46 | 286 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| Pawdroid | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23059 | yes | 6.34 | 0 |
| SoliSpirit-all | 9234 | yes | 1.33 | 0 |
| Epodonios-all | 7676 | yes | 5.43 | 0 |
| Surfboard-tg-mixed | 7176 | yes | 6.72 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.95 | 0 |
| barry-far-vless | 6070 | yes | 0.6 | 0 |
| Surfboard-tg-vless | 5828 | yes | 3.61 | 0 |
| 10ium-ScrapeCategorize-Vless | 5276 | yes | 0.89 | 0 |
| DeltaKronecker-all | 4981 | yes | 6.23 | 0 |
| mahdibland-V2RayAggregator | 4310 | yes | 3.29 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 41 |
| cn-block | 30 |
| speed | 18 |
| geo | 7 |
