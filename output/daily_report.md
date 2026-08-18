# AutoNodes 每日报告

生成时间：2026-08-18 01:33:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 80389 |
| 去重后节点数 | 22945 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1290 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22945 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 27.5 |
| geo | 1.4 |
| probe | 68.3 |
| real_test | 212.3 |
| tcp | 35.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 36 | 33 | 3 | 91.7% |
| shadowsocks | 170 | 166 | 4 | 97.6% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 821 | 808 | 13 | 98.4% |
| tuic | 1 | 1 | 0 | 100.0% |
| vless | 314 | 147 | 167 | 46.8% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 74 |
| speed:TimeoutError | 42 |
| geo:ClientOSError | 23 |
| speed:ClientOSError | 20 |
| cn-block:TimeoutError | 9 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 5 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4682 |
| ConnectionRefusedError | 939 |
| gaierror | 303 |
| OSError | 25 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 526 | 0.966 | 1475 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| mheidari-all | 0.941 | prefer | 669 | 0.862 | 16056 |
| Surfboard-tg-mixed | 0.747 | prefer | 94 | 0.67 | 6128 |
| DeltaKronecker-all | 0.297 | observe | 58 | 0.207 | 6368 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 179 |
| Pawdroid | 0.256 | observe | 1 | 1.0 | 20 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5085 |
| Epodonios-all | 0.255 | observe | 0 | None | 6777 |

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
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.207 | 12 | 46 | 58 |
| Surfboard-tg-mixed | 0.67 | 63 | 31 | 94 |
| mheidari-all | 0.862 | 577 | 92 | 669 |
| Au1rxx-base64 | 0.966 | 508 | 18 | 526 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Pawdroid | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16056 | yes | 3.84 | 0 |
| SoliSpirit-all | 6971 | yes | 2.45 | 0 |
| Epodonios-all | 6777 | yes | 2.49 | 0 |
| DeltaKronecker-all | 6368 | yes | 4.22 | 0 |
| Surfboard-tg-mixed | 6128 | yes | 2.85 | 0 |
| barry-far-vless | 5128 | yes | 1.63 | 0 |
| 10ium-ScrapeCategorize-Vless | 5085 | yes | 1.47 | 0 |
| Surfboard-tg-vless | 4797 | yes | 3.0 | 0 |
| mahdibland-V2RayAggregator | 4027 | yes | 1.8 | 0 |
| MatinGhanbari-all-sub | 3986 | yes | 1.7 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 97 |
| speed | 62 |
| 204 | 15 |
| cn-block | 15 |
