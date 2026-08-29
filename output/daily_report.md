# AutoNodes 每日报告

生成时间：2026-08-29 20:49:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 79290 |
| 去重后节点数 | 21340 |
| TCP 可达数 | 3000 |
| 真测通过数 | 642 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21340 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 47.8 |
| geo | 1.4 |
| probe | 62.9 |
| real_test | 147.9 |
| tcp | 34.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 168 | 155 | 13 | 92.3% |
| socks | 9 | 5 | 4 | 55.6% |
| trojan | 12 | 10 | 2 | 83.3% |
| vless | 524 | 423 | 101 | 80.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 34 |
| cn-block:TimeoutError | 22 |
| geo:TimeoutError | 14 |
| geo:ClientOSError | 12 |
| speed:ClientOSError | 10 |
| speed:TimeoutError | 9 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4576 |
| ConnectionRefusedError | 884 |
| gaierror | 440 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | prefer | 360 | 0.897 | 1753 |
| zhangkai | 0.926 | prefer | 23 | 0.957 | 144 |
| mheidari-all | 0.897 | prefer | 91 | 0.824 | 14908 |
| DeltaKronecker-all | 0.865 | prefer | 128 | 0.789 | 4926 |
| Surfboard-tg-mixed | 0.825 | prefer | 155 | 0.748 | 6924 |
| tg-oneclickvpnkeys | 0.364 | observe | 3 | 1.0 | 155 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4635 |
| Epodonios-all | 0.255 | observe | 0 | None | 7291 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.748 | 116 | 39 | 155 |
| DeltaKronecker-all | 0.789 | 101 | 27 | 128 |
| mheidari-all | 0.824 | 75 | 16 | 91 |
| Au1rxx-base64 | 0.897 | 323 | 37 | 360 |
| zhangkai | 0.957 | 22 | 1 | 23 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14908 | yes | 3.41 | 0 |
| SoliSpirit-all | 7802 | yes | 2.98 | 0 |
| Epodonios-all | 7291 | yes | 2.89 | 0 |
| Surfboard-tg-mixed | 6924 | yes | 1.27 | 0 |
| barry-far-vless | 5901 | yes | 2.18 | 0 |
| Surfboard-tg-vless | 5706 | yes | 2.59 | 0 |
| DeltaKronecker-all | 4926 | yes | 3.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 4635 | yes | 1.99 | 0 |
| mahdibland-V2RayAggregator | 4012 | yes | 0.91 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.23 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 44 |
| cn-block | 33 |
| geo | 26 |
| speed | 19 |
