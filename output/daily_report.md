# AutoNodes 每日报告

生成时间：2026-08-10 13:23:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 86587 |
| 去重后节点数 | 24769 |
| TCP 可达数 | 3000 |
| 真测通过数 | 510 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24769 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 37.6 |
| geo | 1.0 |
| probe | 50.7 |
| real_test | 110.2 |
| tcp | 36.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 151 | 140 | 11 | 92.7% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 133 | 119 | 14 | 89.5% |
| vless | 274 | 207 | 67 | 75.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 17 |
| speed:TimeoutError | 15 |
| geo:ClientOSError | 14 |
| speed:ClientOSError | 8 |
| geo:TimeoutError | 8 |
| 204:ProxyError | 6 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4947 |
| ConnectionRefusedError | 836 |
| gaierror | 292 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.991 | prefer | 435 | 0.926 | 1668 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.742 | prefer | 69 | 0.667 | 6388 |
| DeltaKronecker-all | 0.559 | observe | 69 | 0.478 | 5881 |
| mheidari-all | 0.418 | observe | 10 | 0.5 | 20526 |
| tg-oneclickvpnkeys | 0.316 | observe | 2 | 1.0 | 122 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7165 |
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
| DeltaKronecker-all | 0.478 | 33 | 36 | 69 |
| mheidari-all | 0.5 | 5 | 5 | 10 |
| Surfboard-tg-mixed | 0.667 | 46 | 23 | 69 |
| Au1rxx-base64 | 0.926 | 403 | 32 | 435 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20526 | yes | 4.11 | 0 |
| SoliSpirit-all | 7747 | yes | 2.13 | 0 |
| Epodonios-all | 7165 | yes | 2.23 | 0 |
| Surfboard-tg-mixed | 6388 | yes | 2.69 | 0 |
| DeltaKronecker-all | 5881 | yes | 3.94 | 0 |
| barry-far-vless | 5695 | yes | 1.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 1.41 | 0 |
| Surfboard-tg-vless | 5219 | yes | 3.31 | 0 |
| mahdibland-V2RayAggregator | 5191 | yes | 2.46 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.63 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 29 |
| geo | 24 |
| speed | 23 |
| cn-block | 20 |
