# AutoNodes 每日报告

生成时间：2026-10-08 23:19:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 98440 |
| 去重后节点数 | 27653 |
| TCP 可达数 | 3000 |
| 真测通过数 | 418 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27653 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 76.6 |
| geo | 1.5 |
| probe | 245.1 |
| real_test | 243.9 |
| tcp | 47.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 8 | 2 | 6 | 25.0% |
| http | 23 | 15 | 8 | 65.2% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 132 | 124 | 8 | 93.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 73 | 73 | 0 | 100.0% |
| vless | 227 | 190 | 37 | 83.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 13 |
| speed:TimeoutError | 9 |
| 204:ProxyConnectionError | 8 |
| 204:TimeoutError | 8 |
| cn-block:TimeoutError | 8 |
| geo:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6625 |
| ConnectionRefusedError | 1011 |
| gaierror | 393 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.976 | prefer | 326 | 0.905 | 1827 |
| mheidari-all | 0.933 | prefer | 73 | 0.863 | 23588 |
| Surfboard-tg-mixed | 0.913 | prefer | 40 | 0.85 | 7092 |
| zhangkai | 0.646 | observe | 23 | 0.652 | 144 |
| DeltaKronecker-all | 0.593 | observe | 7 | 1.0 | 5197 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5081 |
| Epodonios-all | 0.255 | observe | 0 | None | 7650 |
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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.205 | 8 | 0.25 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.25 | 2 | 6 | 8 |
| zhangkai | 0.652 | 15 | 8 | 23 |
| Surfboard-tg-mixed | 0.85 | 34 | 6 | 40 |
| mheidari-all | 0.863 | 63 | 10 | 73 |
| Au1rxx-base64 | 0.905 | 295 | 31 | 326 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 7 | 0 | 7 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23588 | yes | 6.85 | 0 |
| SoliSpirit-all | 9660 | yes | 2.48 | 0 |
| Epodonios-all | 7650 | yes | 3.92 | 0 |
| Surfboard-tg-mixed | 7092 | yes | 5.44 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.65 | 0 |
| barry-far-vless | 5923 | yes | 2.12 | 0 |
| Surfboard-tg-vless | 5580 | yes | 4.52 | 0 |
| DeltaKronecker-all | 5197 | yes | 7.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 5081 | yes | 0.78 | 0 |
| mahdibland-V2RayAggregator | 4362 | yes | 3.61 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 22 |
| 204 | 20 |
| cn-block | 13 |
| geo | 7 |
