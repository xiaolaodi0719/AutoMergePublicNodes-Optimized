# AutoNodes 每日报告

生成时间：2026-09-19 04:13:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 82098 |
| 去重后节点数 | 23215 |
| TCP 可达数 | 3000 |
| 真测通过数 | 576 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23215 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 85.6 |
| geo | 1.4 |
| probe | 277.9 |
| real_test | 296.4 |
| tcp | 37.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 62 | 41 | 21 | 66.1% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 193 | 185 | 8 | 95.9% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 48 | 33 | 15 | 68.8% |
| vless | 495 | 299 | 196 | 60.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 79 |
| speed:TimeoutError | 46 |
| geo:ClientOSError | 32 |
| 204:ProxyError | 28 |
| cn-block:TimeoutError | 18 |
| speed:ClientOSError | 16 |
| cn-block:ClientOSError | 10 |
| 204:TimeoutError | 5 |
| 204:ProxyConnectionError | 3 |
| cn-block:ProxyError | 3 |
| geo:parse | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5239 |
| ConnectionRefusedError | 821 |
| gaierror | 472 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.963 | prefer | 313 | 0.898 | 1702 |
| ermaozi | 0.759 | prefer | 49 | 0.755 | 358 |
| Surfboard-tg-mixed | 0.756 | prefer | 254 | 0.677 | 7266 |
| roosterkid-openproxylist-v2ray | 0.555 | observe | 8 | 1.0 | 150 |
| mheidari-all | 0.521 | observe | 109 | 0.44 | 13937 |
| DeltaKronecker-all | 0.483 | observe | 65 | 0.4 | 6040 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4241 |
| Epodonios-all | 0.255 | observe | 0 | None | 7793 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8930 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.227 | 12 | 0.25 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 3 | 3 |
| ermaozi-get_subscribe | 0.25 | 3 | 9 | 12 |
| DeltaKronecker-all | 0.4 | 26 | 39 | 65 |
| mheidari-all | 0.44 | 48 | 61 | 109 |
| Surfboard-tg-mixed | 0.677 | 172 | 82 | 254 |
| ermaozi | 0.755 | 37 | 12 | 49 |
| Au1rxx-base64 | 0.898 | 281 | 32 | 313 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 13937 | yes | 6.27 | 0 |
| SoliSpirit-all | 8930 | yes | 1.92 | 0 |
| Epodonios-all | 7793 | yes | 3.26 | 0 |
| Surfboard-tg-mixed | 7266 | yes | 4.34 | 0 |
| barry-far-vless | 6112 | yes | 1.51 | 0 |
| DeltaKronecker-all | 6040 | yes | 5.1 | 0 |
| Surfboard-tg-vless | 5822 | yes | 3.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 5076 | yes | 0.96 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 0.7 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.05 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 112 |
| speed | 62 |
| 204 | 36 |
| cn-block | 31 |
