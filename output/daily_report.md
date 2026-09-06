# AutoNodes 每日报告

生成时间：2026-09-06 04:00:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 97417 |
| 去重后节点数 | 25568 |
| TCP 可达数 | 3000 |
| 真测通过数 | 634 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25568 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 36.9 |
| geo | 1.5 |
| probe | 94.2 |
| real_test | 175.0 |
| tcp | 41.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 28 | 28 | 0 | 100.0% |
| hysteria2 | 27 | 17 | 10 | 63.0% |
| shadowsocks | 181 | 174 | 7 | 96.1% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 27 | 18 | 9 | 66.7% |
| vless | 873 | 392 | 481 | 44.9% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 189 |
| geo:ClientOSError | 82 |
| cn-block:ClientOSError | 78 |
| speed:TimeoutError | 56 |
| speed:ClientOSError | 38 |
| cn-block:TimeoutError | 19 |
| 204:TimeoutError | 17 |
| 204:ProxyConnectionError | 15 |
| 204:ProxyError | 12 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5670 |
| ConnectionRefusedError | 1047 |
| gaierror | 449 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| Au1rxx-base64 | 0.939 | prefer | 318 | 0.868 | 1827 |
| Surfboard-tg-mixed | 0.851 | prefer | 203 | 0.773 | 7381 |
| tg-oneclickvpnkeys | 0.482 | observe | 6 | 1.0 | 132 |
| mheidari-all | 0.372 | observe | 583 | 0.292 | 22409 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6965 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4887 |
| Epodonios-all | 0.255 | observe | 0 | None | 7876 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.208 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.143 | 1 | 6 | 7 |
| mheidari-all | 0.292 | 170 | 413 | 583 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.773 | 157 | 46 | 203 |
| Au1rxx-base64 | 0.868 | 276 | 42 | 318 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 6 | 0 | 6 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22409 | yes | 5.75 | 0 |
| SoliSpirit-all | 8608 | yes | 4.71 | 0 |
| Epodonios-all | 7876 | yes | 5.08 | 0 |
| Surfboard-tg-mixed | 7381 | yes | 3.49 | 0 |
| xiaoji235-airport-v2ray-all | 6965 | yes | 3.24 | 0 |
| barry-far-vless | 6398 | yes | 2.25 | 0 |
| DeltaKronecker-all | 6212 | yes | 6.23 | 0 |
| Surfboard-tg-vless | 6075 | yes | 3.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 4887 | yes | 2.72 | 0 |
| mahdibland-V2RayAggregator | 4087 | yes | 0.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 272 |
| cn-block | 98 |
| speed | 94 |
| 204 | 46 |
