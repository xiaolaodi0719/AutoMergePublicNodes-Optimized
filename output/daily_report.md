# AutoNodes 每日报告

生成时间：2026-08-25 18:50:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78004 |
| 去重后节点数 | 22568 |
| TCP 可达数 | 3000 |
| 真测通过数 | 584 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22568 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 40.8 |
| geo | 1.4 |
| probe | 58.3 |
| real_test | 139.8 |
| tcp | 35.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 23 | 23 | 0 | 100.0% |
| shadowsocks | 179 | 164 | 15 | 91.6% |
| socks | 11 | 9 | 2 | 81.8% |
| trojan | 36 | 35 | 1 | 97.2% |
| vless | 450 | 328 | 122 | 72.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 49 |
| 204:TimeoutError | 23 |
| geo:TimeoutError | 20 |
| 204:ProxyError | 12 |
| cn-block:TimeoutError | 11 |
| geo:ClientOSError | 8 |
| speed:ClientOSError | 8 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4557 |
| ConnectionRefusedError | 875 |
| gaierror | 413 |
| OSError | 27 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.915 | prefer | 424 | 0.856 | 1502 |
| DeltaKronecker-all | 0.871 | prefer | 41 | 0.805 | 6340 |
| Surfboard-tg-mixed | 0.781 | prefer | 152 | 0.704 | 6487 |
| mheidari-all | 0.774 | prefer | 83 | 0.699 | 14446 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| Epodonios-all | 0.255 | observe | 0 | None | 6936 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7007 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5327 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.699 | 58 | 25 | 83 |
| Surfboard-tg-mixed | 0.704 | 107 | 45 | 152 |
| DeltaKronecker-all | 0.805 | 33 | 8 | 41 |
| Au1rxx-base64 | 0.856 | 363 | 61 | 424 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14446 | yes | 4.31 | 0 |
| SoliSpirit-all | 7007 | yes | 2.52 | 0 |
| Epodonios-all | 6936 | yes | 4.5 | 0 |
| Surfboard-tg-mixed | 6487 | yes | 3.21 | 0 |
| DeltaKronecker-all | 6340 | yes | 4.58 | 0 |
| barry-far-vless | 5601 | yes | 1.3 | 0 |
| Surfboard-tg-vless | 5327 | yes | 3.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 1.01 | 0 |
| mahdibland-V2RayAggregator | 4119 | yes | 2.68 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.09 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 58 |
| 204 | 36 |
| geo | 28 |
| cn-block | 18 |
