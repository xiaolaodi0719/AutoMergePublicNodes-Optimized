# AutoNodes 每日报告

生成时间：2026-08-13 19:13:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 80094 |
| 去重后节点数 | 22489 |
| TCP 可达数 | 3000 |
| 真测通过数 | 850 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22489 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 31.4 |
| geo | 1.1 |
| probe | 63.2 |
| real_test | 177.6 |
| tcp | 32.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 150 | 137 | 13 | 91.3% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 325 | 321 | 4 | 98.8% |
| vless | 307 | 239 | 68 | 77.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 23 |
| cn-block:TimeoutError | 16 |
| geo:TimeoutError | 14 |
| 204:ProxyError | 9 |
| 204:ClientOSError | 8 |
| geo:ClientOSError | 5 |
| speed:TimeoutError | 5 |
| speed:ClientOSError | 5 |
| cn-block:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4069 |
| ConnectionRefusedError | 807 |
| gaierror | 307 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Au1rxx-base64 | 0.998 | prefer | 616 | 0.933 | 1639 |
| mheidari-all | 0.88 | prefer | 113 | 0.805 | 16814 |
| Surfboard-tg-mixed | 0.756 | prefer | 66 | 0.682 | 6036 |
| DeltaKronecker-all | 0.684 | observe | 14 | 0.786 | 4878 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5203 |
| Epodonios-all | 0.255 | observe | 0 | None | 6692 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7502 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4739 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.128 | observe | 1 | 0.0 | 0 | 20 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.682 | 45 | 21 | 66 |
| DeltaKronecker-all | 0.786 | 11 | 3 | 14 |
| mheidari-all | 0.805 | 91 | 22 | 113 |
| Au1rxx-base64 | 0.933 | 575 | 41 | 616 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16814 | yes | 4.31 | 0 |
| SoliSpirit-all | 7502 | yes | 3.93 | 0 |
| Epodonios-all | 6692 | yes | 4.48 | 0 |
| Surfboard-tg-mixed | 6036 | yes | 3.56 | 0 |
| 10ium-ScrapeCategorize-Vless | 5203 | yes | 2.45 | 0 |
| mahdibland-V2RayAggregator | 5197 | yes | 2.33 | 0 |
| barry-far-vless | 5103 | yes | 1.51 | 0 |
| DeltaKronecker-all | 4878 | yes | 4.28 | 0 |
| Surfboard-tg-vless | 4739 | yes | 3.07 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.6 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 40 |
| geo | 19 |
| cn-block | 19 |
| speed | 10 |
