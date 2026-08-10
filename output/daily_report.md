# AutoNodes 每日报告

生成时间：2026-08-10 19:07:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 84993 |
| 去重后节点数 | 24663 |
| TCP 可达数 | 3000 |
| 真测通过数 | 469 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24663 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 33.4 |
| geo | 1.5 |
| probe | 56.5 |
| real_test | 100.6 |
| tcp | 37.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 49 | 49 | 0 | 100.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 145 | 135 | 10 | 93.1% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 123 | 117 | 6 | 95.1% |
| vless | 233 | 144 | 89 | 61.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 29 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 15 |
| geo:ClientOSError | 13 |
| geo:TimeoutError | 10 |
| speed:TimeoutError | 10 |
| speed:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5123 |
| ConnectionRefusedError | 835 |
| OSError | 229 |
| gaierror | 218 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.983 | prefer | 49 | 1.0 | 67 |
| Au1rxx-base64 | 0.957 | prefer | 398 | 0.894 | 1614 |
| Surfboard-tg-mixed | 0.687 | observe | 59 | 0.61 | 6152 |
| DeltaKronecker-all | 0.47 | observe | 57 | 0.386 | 5881 |
| mheidari-all | 0.361 | observe | 10 | 0.4 | 20189 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 6803 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.386 | 22 | 35 | 57 |
| mheidari-all | 0.4 | 4 | 6 | 10 |
| Surfboard-tg-mixed | 0.61 | 36 | 23 | 59 |
| Au1rxx-base64 | 0.894 | 356 | 42 | 398 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 49 | 0 | 49 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20189 | yes | 4.58 | 0 |
| SoliSpirit-all | 7537 | yes | 3.21 | 0 |
| Epodonios-all | 6803 | yes | 2.77 | 0 |
| Surfboard-tg-mixed | 6152 | yes | 3.02 | 0 |
| DeltaKronecker-all | 5881 | yes | 4.01 | 0 |
| barry-far-vless | 5417 | yes | 2.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 2.65 | 0 |
| mahdibland-V2RayAggregator | 5191 | yes | 2.42 | 0 |
| Surfboard-tg-vless | 5085 | yes | 3.58 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 2.97 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 49 |
| geo | 23 |
| cn-block | 19 |
| speed | 15 |
