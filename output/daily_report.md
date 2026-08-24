# AutoNodes 每日报告

生成时间：2026-08-24 13:03:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78546 |
| 去重后节点数 | 21951 |
| TCP 可达数 | 3000 |
| 真测通过数 | 558 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21951 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.7 |
| generate | 31.8 |
| geo | 1.3 |
| probe | 51.4 |
| real_test | 120.3 |
| tcp | 34.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 210 | 194 | 16 | 92.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 47 | 41 | 6 | 87.2% |
| vless | 372 | 276 | 96 | 74.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 23 |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 16 |
| 204:ProxyError | 15 |
| speed:TimeoutError | 13 |
| geo:ClientOSError | 11 |
| cn-block:ClientOSError | 8 |
| speed:ClientOSError | 6 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4665 |
| ConnectionRefusedError | 843 |
| gaierror | 373 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.936 | prefer | 361 | 0.873 | 1628 |
| zhangkai | 0.929 | prefer | 24 | 0.958 | 144 |
| DeltaKronecker-all | 0.843 | prefer | 57 | 0.772 | 5914 |
| mheidari-all | 0.83 | prefer | 86 | 0.756 | 14541 |
| Surfboard-tg-mixed | 0.821 | prefer | 145 | 0.745 | 6395 |
| nscl5-all | 0.352 | observe | 2 | 1.0 | 1008 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4899 |
| Epodonios-all | 0.255 | observe | 0 | None | 6919 |
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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.745 | 108 | 37 | 145 |
| mheidari-all | 0.756 | 65 | 21 | 86 |
| DeltaKronecker-all | 0.772 | 44 | 13 | 57 |
| Au1rxx-base64 | 0.873 | 315 | 46 | 361 |
| zhangkai | 0.958 | 23 | 1 | 24 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14541 | yes | 2.27 | 0 |
| SoliSpirit-all | 7302 | yes | 1.43 | 0 |
| Epodonios-all | 6919 | yes | 2.44 | 0 |
| Surfboard-tg-mixed | 6395 | yes | 1.79 | 0 |
| DeltaKronecker-all | 5914 | yes | 2.61 | 0 |
| barry-far-vless | 5633 | yes | 0.54 | 0 |
| Surfboard-tg-vless | 5345 | yes | 1.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 4899 | yes | 0.88 | 0 |
| mahdibland-V2RayAggregator | 4097 | yes | 1.46 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 0.92 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 35 |
| geo | 34 |
| cn-block | 31 |
| speed | 20 |
