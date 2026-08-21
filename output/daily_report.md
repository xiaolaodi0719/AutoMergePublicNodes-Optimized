# AutoNodes 每日报告

生成时间：2026-08-21 01:45:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 95323 |
| 去重后节点数 | 25208 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1235 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25208 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 26.6 |
| geo | 1.4 |
| probe | 74.7 |
| real_test | 232.4 |
| tcp | 40.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 111 | 111 | 0 | 100.0% |
| hysteria2 | 34 | 34 | 0 | 100.0% |
| shadowsocks | 212 | 206 | 6 | 97.2% |
| socks | 3 | 3 | 0 | 100.0% |
| trojan | 659 | 640 | 19 | 97.1% |
| vless | 559 | 239 | 320 | 42.8% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 131 |
| geo:ClientOSError | 101 |
| speed:TimeoutError | 71 |
| speed:ClientOSError | 19 |
| cn-block:TimeoutError | 9 |
| 204:TimeoutError | 8 |
| cn-block:ClientOSError | 2 |
| 204:ProxyError | 2 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5043 |
| ConnectionRefusedError | 960 |
| gaierror | 569 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 567 | 0.984 | 1663 |
| Surfboard-tg-mixed | 1.0 | prefer | 109 | 0.936 | 6412 |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| mheidari-all | 0.686 | observe | 750 | 0.607 | 21987 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 3031 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4958 |
| Epodonios-all | 0.255 | observe | 0 | None | 7184 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7304 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5053 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| roosterkid-openproxylist-v2ray | 0.133 | observe | 1 | 0.0 | 0 | 150 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.154 | 6 | 33 | 39 |
| mheidari-all | 0.607 | 455 | 295 | 750 |
| Surfboard-tg-mixed | 0.936 | 102 | 7 | 109 |
| Au1rxx-base64 | 0.984 | 558 | 9 | 567 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 112 | 0 | 112 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21987 | yes | 4.78 | 0 |
| SoliSpirit-all | 7304 | yes | 3.64 | 0 |
| Epodonios-all | 7184 | yes | 5.05 | 0 |
| DeltaKronecker-all | 6781 | yes | 5.59 | 0 |
| Surfboard-tg-mixed | 6412 | yes | 3.03 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 2.35 | 0 |
| barry-far-vless | 5451 | yes | 1.95 | 0 |
| Surfboard-tg-vless | 5053 | yes | 3.28 | 0 |
| 10ium-ScrapeCategorize-Vless | 4958 | yes | 1.77 | 0 |
| mahdibland-V2RayAggregator | 4586 | yes | 0.17 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 233 |
| speed | 91 |
| 204 | 11 |
| cn-block | 11 |
