# AutoNodes 每日报告

生成时间：2026-08-24 07:12:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 78696 |
| 去重后节点数 | 21961 |
| TCP 可达数 | 3000 |
| 真测通过数 | 718 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21961 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 36.7 |
| geo | 1.4 |
| probe | 55.6 |
| real_test | 156.1 |
| tcp | 34.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 206 | 196 | 10 | 95.1% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 75 | 63 | 12 | 84.0% |
| vless | 635 | 324 | 311 | 51.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 134 |
| geo:ClientOSError | 60 |
| speed:ClientOSError | 38 |
| 204:ProxyError | 31 |
| speed:TimeoutError | 26 |
| 204:TimeoutError | 17 |
| cn-block:TimeoutError | 17 |
| cn-block:ClientOSError | 8 |
| geo:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4884 |
| ConnectionRefusedError | 824 |
| gaierror | 204 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | prefer | 34 | 1.0 | 14629 |
| zhangkai | 0.988 | prefer | 113 | 0.991 | 144 |
| Au1rxx-base64 | 0.957 | prefer | 383 | 0.89 | 1718 |
| Surfboard-tg-mixed | 0.875 | prefer | 149 | 0.799 | 6484 |
| DeltaKronecker-all | 0.376 | observe | 370 | 0.295 | 5914 |
| nscl5-all | 0.352 | observe | 2 | 1.0 | 1008 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4899 |
| Epodonios-all | 0.255 | observe | 0 | None | 6867 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3988 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.295 | 109 | 261 | 370 |
| Surfboard-tg-mixed | 0.799 | 119 | 30 | 149 |
| Au1rxx-base64 | 0.89 | 341 | 42 | 383 |
| zhangkai | 0.991 | 112 | 1 | 113 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| mheidari-all | 1.0 | 34 | 0 | 34 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14629 | yes | 3.68 | 0 |
| SoliSpirit-all | 7231 | yes | 3.27 | 0 |
| Epodonios-all | 6867 | yes | 3.86 | 0 |
| Surfboard-tg-mixed | 6484 | yes | 3.19 | 0 |
| DeltaKronecker-all | 5914 | yes | 4.42 | 0 |
| barry-far-vless | 5530 | yes | 3.64 | 0 |
| Surfboard-tg-vless | 5385 | yes | 4.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 4899 | yes | 2.12 | 0 |
| mahdibland-V2RayAggregator | 4097 | yes | 0.95 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 2.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 196 |
| speed | 64 |
| 204 | 50 |
| cn-block | 26 |
