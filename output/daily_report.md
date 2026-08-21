# AutoNodes 每日报告

生成时间：2026-08-21 18:49:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 93362 |
| 去重后节点数 | 23312 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1165 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23312 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 35.5 |
| geo | 0.6 |
| probe | 69.0 |
| real_test | 216.9 |
| tcp | 38.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 111 | 111 | 0 | 100.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 151 | 136 | 15 | 90.1% |
| socks | 8 | 5 | 3 | 62.5% |
| trojan | 627 | 624 | 3 | 99.5% |
| vless | 357 | 268 | 89 | 75.1% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 37 |
| geo:TimeoutError | 17 |
| 204:TimeoutError | 12 |
| cn-block:TimeoutError | 11 |
| speed:TimeoutError | 10 |
| 204:ProxyError | 8 |
| speed:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5192 |
| ConnectionRefusedError | 925 |
| gaierror | 432 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 687 | 0.985 | 1933 |
| zhangkai | 0.997 | prefer | 111 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.921 | prefer | 80 | 0.85 | 6488 |
| mheidari-all | 0.866 | prefer | 385 | 0.787 | 21956 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 3031 |
| roosterkid-openproxylist-v2ray | 0.317 | observe | 2 | 1.0 | 150 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 177 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5148 |
| Epodonios-all | 0.255 | observe | 0 | None | 7155 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3988 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.208 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.143 | 1 | 6 | 7 |
| mheidari-all | 0.787 | 303 | 82 | 385 |
| Surfboard-tg-mixed | 0.85 | 68 | 12 | 80 |
| Au1rxx-base64 | 0.985 | 677 | 10 | 687 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| roosterkid-openproxylist-v2ray | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 111 | 0 | 111 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21956 | yes | 5.11 | 0 |
| SoliSpirit-all | 7163 | yes | 4.82 | 0 |
| Epodonios-all | 7155 | yes | 5.59 | 0 |
| Surfboard-tg-mixed | 6488 | yes | 3.29 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.72 | 0 |
| barry-far-vless | 5535 | yes | 3.08 | 0 |
| Surfboard-tg-vless | 5287 | yes | 4.11 | 0 |
| 10ium-ScrapeCategorize-Vless | 5148 | yes | 3.31 | 0 |
| DeltaKronecker-all | 4433 | yes | 5.68 | 0 |
| mahdibland-V2RayAggregator | 4091 | yes | 2.85 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 55 |
| 204 | 23 |
| cn-block | 18 |
| speed | 16 |
