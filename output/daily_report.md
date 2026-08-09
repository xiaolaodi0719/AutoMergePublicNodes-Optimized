# AutoNodes 每日报告

生成时间：2026-08-09 07:07:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 82917 |
| 去重后节点数 | 23035 |
| TCP 可达数 | 3000 |
| 真测通过数 | 540 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23035 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 27.7 |
| geo | 1.4 |
| probe | 57.2 |
| real_test | 118.8 |
| tcp | 34.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 149 | 142 | 7 | 95.3% |
| socks | 3 | 3 | 0 | 100.0% |
| trojan | 133 | 128 | 5 | 96.2% |
| vless | 358 | 220 | 138 | 61.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 54 |
| 204:TimeoutError | 21 |
| speed:ClientOSError | 18 |
| speed:TimeoutError | 15 |
| geo:ClientOSError | 13 |
| cn-block:TimeoutError | 11 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 4 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4772 |
| ConnectionRefusedError | 791 |
| gaierror | 284 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.994 | prefer | 401 | 0.93 | 1640 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.836 | prefer | 84 | 0.762 | 6537 |
| mheidari-all | 0.616 | observe | 136 | 0.537 | 17626 |
| tg-oneclickvpnkeys | 0.318 | observe | 2 | 1.0 | 171 |
| nscl5-all | 0.315 | observe | 1 | 1.0 | 1506 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5505 |
| Epodonios-all | 0.255 | observe | 0 | None | 7052 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.229 | 45 | 0.133 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.133 | 6 | 39 | 45 |
| mheidari-all | 0.537 | 73 | 63 | 136 |
| Surfboard-tg-mixed | 0.762 | 64 | 20 | 84 |
| Au1rxx-base64 | 0.93 | 373 | 28 | 401 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17626 | yes | 3.52 | 0 |
| SoliSpirit-all | 7616 | yes | 1.62 | 0 |
| Epodonios-all | 7052 | yes | 2.1 | 0 |
| Surfboard-tg-mixed | 6537 | yes | 3.95 | 0 |
| barry-far-vless | 5569 | yes | 2.21 | 0 |
| 10ium-ScrapeCategorize-Vless | 5505 | yes | 1.23 | 0 |
| Surfboard-tg-vless | 5295 | yes | 2.85 | 0 |
| mahdibland-V2RayAggregator | 5130 | yes | 2.18 | 0 |
| DeltaKronecker-all | 4998 | yes | 4.72 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.04 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 68 |
| 204 | 34 |
| speed | 33 |
| cn-block | 17 |
