# AutoNodes 每日报告

生成时间：2026-08-12 13:25:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 80139 |
| 去重后节点数 | 22314 |
| TCP 可达数 | 3000 |
| 真测通过数 | 554 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22314 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.3 |
| generate | 38.1 |
| geo | 1.4 |
| probe | 55.9 |
| real_test | 134.6 |
| tcp | 33.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 17 | 14 | 3 | 82.4% |
| shadowsocks | 159 | 138 | 21 | 86.8% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 124 | 114 | 10 | 91.9% |
| vless | 240 | 158 | 82 | 65.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 25 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 17 |
| geo:TimeoutError | 14 |
| 204:ProxyError | 12 |
| geo:ClientOSError | 9 |
| speed:ClientOSError | 9 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4711 |
| ConnectionRefusedError | 766 |
| gaierror | 193 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Au1rxx-base64 | 0.911 | prefer | 428 | 0.846 | 1660 |
| Surfboard-tg-mixed | 0.701 | prefer | 85 | 0.624 | 6099 |
| mheidari-all | 0.373 | observe | 5 | 0.6 | 16658 |
| DeltaKronecker-all | 0.372 | observe | 22 | 0.273 | 4975 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5328 |
| Epodonios-all | 0.255 | observe | 0 | None | 6671 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 8 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.273 | 6 | 16 | 22 |
| mheidari-all | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.624 | 53 | 32 | 85 |
| Au1rxx-base64 | 0.846 | 362 | 66 | 428 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16658 | yes | 4.05 | 0 |
| SoliSpirit-all | 7502 | yes | 1.43 | 0 |
| Epodonios-all | 6671 | yes | 2.55 | 0 |
| Surfboard-tg-mixed | 6099 | yes | 2.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 5328 | yes | 0.87 | 0 |
| barry-far-vless | 5264 | yes | 1.05 | 0 |
| mahdibland-V2RayAggregator | 5196 | yes | 4.3 | 0 |
| DeltaKronecker-all | 4975 | yes | 4.23 | 0 |
| Surfboard-tg-vless | 4929 | yes | 2.91 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.13 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 38 |
| speed | 34 |
| geo | 23 |
| cn-block | 22 |
