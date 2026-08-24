# AutoNodes 每日报告

生成时间：2026-08-24 18:52:29

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84125 |
| 去重后节点数 | 23818 |
| TCP 可达数 | 3000 |
| 真测通过数 | 590 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23818 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 32.7 |
| geo | 1.5 |
| probe | 58.6 |
| real_test | 126.0 |
| tcp | 37.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 202 | 185 | 17 | 91.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 45 | 39 | 6 | 86.7% |
| vless | 428 | 317 | 111 | 74.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 36 |
| 204:TimeoutError | 28 |
| cn-block:TimeoutError | 24 |
| geo:ClientOSError | 22 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| speed:ClientOSError | 5 |
| speed:TimeoutError | 4 |
| 204:ProxyError | 4 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4853 |
| ConnectionRefusedError | 918 |
| gaierror | 440 |
| OSError | 242 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.961 | prefer | 370 | 0.892 | 1779 |
| Surfboard-tg-mixed | 0.942 | prefer | 92 | 0.87 | 6457 |
| mheidari-all | 0.805 | prefer | 118 | 0.729 | 19577 |
| DeltaKronecker-all | 0.653 | observe | 122 | 0.574 | 5914 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4899 |
| Epodonios-all | 0.255 | observe | 0 | None | 6977 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7298 |

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
| DeltaKronecker-all | 0.574 | 70 | 52 | 122 |
| mheidari-all | 0.729 | 86 | 32 | 118 |
| Surfboard-tg-mixed | 0.87 | 80 | 12 | 92 |
| Au1rxx-base64 | 0.892 | 330 | 40 | 370 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19577 | yes | 4.41 | 0 |
| SoliSpirit-all | 7298 | yes | 4.53 | 0 |
| Epodonios-all | 6977 | yes | 5.37 | 0 |
| Surfboard-tg-mixed | 6457 | yes | 3.4 | 0 |
| DeltaKronecker-all | 5914 | yes | 4.51 | 0 |
| barry-far-vless | 5662 | yes | 2.71 | 0 |
| Surfboard-tg-vless | 5373 | yes | 1.67 | 0 |
| 10ium-ScrapeCategorize-Vless | 4899 | yes | 2.53 | 0 |
| mahdibland-V2RayAggregator | 4132 | yes | 1.23 | 0 |
| MatinGhanbari-all-sub | 3987 | yes | 2.31 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 60 |
| 204 | 37 |
| cn-block | 30 |
| speed | 10 |
