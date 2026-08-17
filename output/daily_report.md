# AutoNodes 每日报告

生成时间：2026-08-17 18:53:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 80814 |
| 去重后节点数 | 22843 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1394 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22843 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 25.3 |
| geo | 0.9 |
| probe | 79.5 |
| real_test | 288.3 |
| tcp | 35.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 133 | 117 | 16 | 88.0% |
| socks | 6 | 1 | 5 | 16.7% |
| trojan | 819 | 813 | 6 | 99.3% |
| tuic | 1 | 1 | 0 | 100.0% |
| vless | 433 | 317 | 116 | 73.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 43 |
| 204:TimeoutError | 33 |
| cn-block:TimeoutError | 18 |
| speed:TimeoutError | 11 |
| geo:TimeoutError | 10 |
| speed:ClientOSError | 10 |
| 204:ProxyError | 9 |
| geo:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4692 |
| ConnectionRefusedError | 829 |
| gaierror | 320 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | prefer | 327 | 0.942 | 15619 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Au1rxx-base64 | 0.971 | prefer | 962 | 0.893 | 1983 |
| Surfboard-tg-mixed | 0.93 | prefer | 111 | 0.856 | 6228 |
| DeltaKronecker-all | 0.324 | observe | 8 | 0.375 | 6368 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 192 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5085 |
| Epodonios-all | 0.255 | observe | 0 | None | 6789 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3984 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.375 | 3 | 5 | 8 |
| Surfboard-tg-mixed | 0.856 | 95 | 16 | 111 |
| Au1rxx-base64 | 0.893 | 859 | 103 | 962 |
| mheidari-all | 0.942 | 308 | 19 | 327 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15619 | yes | 4.14 | 0 |
| Epodonios-all | 6789 | yes | 4.52 | 0 |
| SoliSpirit-all | 6707 | yes | 2.92 | 0 |
| DeltaKronecker-all | 6368 | yes | 4.34 | 0 |
| Surfboard-tg-mixed | 6228 | yes | 3.33 | 0 |
| barry-far-vless | 5131 | yes | 2.22 | 0 |
| 10ium-ScrapeCategorize-Vless | 5085 | yes | 2.26 | 0 |
| Surfboard-tg-vless | 4903 | yes | 4.34 | 0 |
| mahdibland-V2RayAggregator | 4027 | yes | 1.32 | 0 |
| MatinGhanbari-all-sub | 3984 | yes | 2.71 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 85 |
| cn-block | 22 |
| speed | 21 |
| geo | 15 |
