# AutoNodes 每日报告

生成时间：2026-10-18 15:51:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 98080 |
| 去重后节点数 | 27710 |
| TCP 可达数 | 3000 |
| 真测通过数 | 384 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27710 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 87.6 |
| geo | 1.5 |
| probe | 320.4 |
| real_test | 249.0 |
| tcp | 48.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 35 | 22 | 13 | 62.9% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 144 | 121 | 23 | 84.0% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 43 | 34 | 9 | 79.1% |
| vless | 293 | 192 | 101 | 65.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 43 |
| cn-block:TimeoutError | 22 |
| 204:ProxyError | 15 |
| geo:ClientOSError | 15 |
| 204:ProxyConnectionError | 13 |
| speed:TimeoutError | 12 |
| speed:ClientOSError | 11 |
| geo:TimeoutError | 7 |
| geo:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6899 |
| ConnectionRefusedError | 1059 |
| gaierror | 383 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.85 | prefer | 345 | 0.783 | 1729 |
| mheidari-all | 0.802 | prefer | 34 | 0.735 | 23775 |
| Surfboard-tg-mixed | 0.667 | observe | 102 | 0.588 | 7095 |
| ermaozi | 0.657 | observe | 36 | 0.639 | 639 |
| DeltaKronecker-all | 0.407 | observe | 11 | 0.455 | 4750 |
| Epodonios-all | 0.287 | observe | 2 | 0.5 | 7485 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10058 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5602 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.455 | 5 | 6 | 11 |
| Epodonios-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.588 | 60 | 42 | 102 |
| ermaozi | 0.639 | 23 | 13 | 36 |
| mheidari-all | 0.735 | 25 | 9 | 34 |
| Au1rxx-base64 | 0.783 | 270 | 75 | 345 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23775 | yes | 6.32 | 0 |
| SoliSpirit-all | 10058 | yes | 5.78 | 0 |
| Epodonios-all | 7485 | yes | 6.55 | 0 |
| Surfboard-tg-mixed | 7095 | yes | 4.4 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 4.34 | 0 |
| barry-far-vless | 5815 | yes | 3.33 | 0 |
| Surfboard-tg-vless | 5602 | yes | 4.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 2.85 | 0 |
| DeltaKronecker-all | 4750 | yes | 7.26 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 1.35 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 74 |
| geo | 26 |
| cn-block | 25 |
| speed | 23 |
