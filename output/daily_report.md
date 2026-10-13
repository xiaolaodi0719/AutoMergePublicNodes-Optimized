# AutoNodes 每日报告

生成时间：2026-10-13 22:39:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98441 |
| 去重后节点数 | 27354 |
| TCP 可达数 | 3000 |
| 真测通过数 | 444 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27354 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 97.8 |
| geo | 1.5 |
| probe | 239.1 |
| real_test | 279.8 |
| tcp | 47.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 25 | 16 | 9 | 64.0% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 125 | 118 | 7 | 94.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 101 | 100 | 1 | 99.0% |
| vless | 230 | 194 | 36 | 84.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 16 |
| 204:ProxyConnectionError | 9 |
| speed:ClientOSError | 7 |
| cn-block:ClientOSError | 7 |
| speed:TimeoutError | 4 |
| 204:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| 204:TimeoutError | 2 |
| speed:ProxyError | 2 |
| geo:ClientOSError | 2 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6836 |
| ConnectionRefusedError | 1053 |
| gaierror | 351 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | prefer | 60 | 0.967 | 23973 |
| Au1rxx-base64 | 0.973 | prefer | 352 | 0.903 | 1806 |
| Surfboard-tg-mixed | 0.945 | prefer | 50 | 0.88 | 7123 |
| zhangkai | 0.686 | observe | 23 | 0.696 | 144 |
| DeltaKronecker-all | 0.373 | observe | 5 | 0.6 | 5076 |
| ermaozi-get_subscribe | 0.314 | observe | 5 | 0.6 | 534 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5086 |
| Epodonios-all | 0.255 | observe | 0 | None | 7631 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.6 | 3 | 2 | 5 |
| DeltaKronecker-all | 0.6 | 3 | 2 | 5 |
| zhangkai | 0.696 | 16 | 7 | 23 |
| Surfboard-tg-mixed | 0.88 | 44 | 6 | 50 |
| Au1rxx-base64 | 0.903 | 318 | 34 | 352 |
| mheidari-all | 0.967 | 58 | 2 | 60 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23973 | yes | 6.23 | 0 |
| SoliSpirit-all | 9832 | yes | 3.46 | 0 |
| Epodonios-all | 7631 | yes | 4.62 | 0 |
| Surfboard-tg-mixed | 7123 | yes | 4.19 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.46 | 0 |
| barry-far-vless | 5929 | yes | 1.64 | 0 |
| Surfboard-tg-vless | 5683 | yes | 4.36 | 0 |
| 10ium-ScrapeCategorize-Vless | 5086 | yes | 1.83 | 0 |
| DeltaKronecker-all | 5076 | yes | 3.75 | 0 |
| mahdibland-V2RayAggregator | 4216 | yes | 2.74 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 25 |
| 204 | 14 |
| speed | 13 |
| geo | 3 |
