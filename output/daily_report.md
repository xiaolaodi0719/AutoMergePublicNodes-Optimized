# AutoNodes 每日报告

生成时间：2026-08-23 18:41:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77715 |
| 去重后节点数 | 21484 |
| TCP 可达数 | 3000 |
| 真测通过数 | 638 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21484 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 12.9 |
| generate | 50.4 |
| geo | 1.4 |
| probe | 57.6 |
| real_test | 149.0 |
| tcp | 35.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 21 | 17 | 4 | 81.0% |
| shadowsocks | 173 | 157 | 16 | 90.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 27 | 24 | 3 | 88.9% |
| vless | 409 | 324 | 85 | 79.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 27 |
| cn-block:TimeoutError | 23 |
| geo:TimeoutError | 17 |
| geo:ClientOSError | 15 |
| 204:ProxyError | 11 |
| speed:ClientOSError | 7 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 3 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4685 |
| ConnectionRefusedError | 844 |
| gaierror | 371 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| Au1rxx-base64 | 0.978 | prefer | 403 | 0.911 | 1729 |
| mheidari-all | 0.783 | prefer | 62 | 0.71 | 14516 |
| Surfboard-tg-mixed | 0.771 | prefer | 134 | 0.694 | 6307 |
| DeltaKronecker-all | 0.663 | observe | 34 | 0.588 | 5415 |
| nscl5-all | 0.298 | observe | 1 | 1.0 | 1082 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 177 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4989 |
| Epodonios-all | 0.255 | observe | 0 | None | 6871 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3988 |

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
| DeltaKronecker-all | 0.588 | 20 | 14 | 34 |
| Surfboard-tg-mixed | 0.694 | 93 | 41 | 134 |
| mheidari-all | 0.71 | 44 | 18 | 62 |
| Au1rxx-base64 | 0.911 | 367 | 36 | 403 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 112 | 0 | 112 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14516 | yes | 5.02 | 0 |
| SoliSpirit-all | 6995 | yes | 1.15 | 0 |
| Epodonios-all | 6871 | yes | 5.45 | 0 |
| Surfboard-tg-mixed | 6307 | yes | 5.22 | 0 |
| barry-far-vless | 5492 | yes | 0.73 | 0 |
| DeltaKronecker-all | 5415 | yes | 3.69 | 0 |
| Surfboard-tg-vless | 5215 | yes | 4.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 4989 | yes | 0.52 | 0 |
| mahdibland-V2RayAggregator | 4085 | yes | 3.0 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 0.82 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 38 |
| geo | 32 |
| cn-block | 30 |
| speed | 10 |
