# AutoNodes 每日报告

生成时间：2026-08-10 07:54:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 87298 |
| 去重后节点数 | 24721 |
| TCP 可达数 | 3000 |
| 真测通过数 | 469 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24721 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 31.6 |
| geo | 0.9 |
| probe | 60.7 |
| real_test | 109.6 |
| tcp | 34.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 24 | 22 | 2 | 91.7% |
| shadowsocks | 156 | 145 | 11 | 92.9% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 140 | 120 | 20 | 85.7% |
| vless | 299 | 158 | 141 | 52.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 45 |
| geo:TimeoutError | 38 |
| 204:TimeoutError | 27 |
| geo:ClientOSError | 16 |
| 204:ProxyError | 16 |
| speed:ClientOSError | 13 |
| cn-block:TimeoutError | 12 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4079 |
| ConnectionRefusedError | 830 |
| gaierror | 417 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Au1rxx-base64 | 0.886 | prefer | 440 | 0.818 | 1742 |
| Surfboard-tg-mixed | 0.716 | prefer | 105 | 0.638 | 6647 |
| DeltaKronecker-all | 0.439 | observe | 37 | 0.351 | 5881 |
| nscl5-all | 0.313 | observe | 1 | 1.0 | 1442 |
| mheidari-all | 0.289 | observe | 41 | 0.195 | 20373 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7338 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3994 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7807 |

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
| mheidari-all | 0.195 | 8 | 33 | 41 |
| DeltaKronecker-all | 0.351 | 13 | 24 | 37 |
| Surfboard-tg-mixed | 0.638 | 67 | 38 | 105 |
| Au1rxx-base64 | 0.818 | 360 | 80 | 440 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20373 | yes | 4.55 | 0 |
| SoliSpirit-all | 7807 | yes | 4.31 | 0 |
| Epodonios-all | 7338 | yes | 2.85 | 0 |
| Surfboard-tg-mixed | 6647 | yes | 3.95 | 0 |
| DeltaKronecker-all | 5881 | yes | 4.7 | 0 |
| barry-far-vless | 5713 | yes | 1.25 | 0 |
| Surfboard-tg-vless | 5394 | yes | 5.31 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 2.63 | 0 |
| mahdibland-V2RayAggregator | 5191 | yes | 2.94 | 0 |
| MatinGhanbari-all-sub | 3994 | yes | 1.32 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 58 |
| geo | 54 |
| 204 | 48 |
| cn-block | 15 |
