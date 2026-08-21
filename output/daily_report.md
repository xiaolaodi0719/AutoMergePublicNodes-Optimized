# AutoNodes 每日报告

生成时间：2026-08-21 13:02:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 95230 |
| 去重后节点数 | 24848 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1143 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24848 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 36.4 |
| geo | 1.1 |
| probe | 61.2 |
| real_test | 195.7 |
| tcp | 40.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 111 | 111 | 0 | 100.0% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 181 | 159 | 22 | 87.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 639 | 627 | 12 | 98.1% |
| vless | 319 | 223 | 96 | 69.9% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 45 |
| geo:TimeoutError | 20 |
| 204:TimeoutError | 17 |
| cn-block:TimeoutError | 13 |
| speed:TimeoutError | 12 |
| speed:ClientOSError | 9 |
| 204:ClientOSError | 8 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5395 |
| ConnectionRefusedError | 942 |
| gaierror | 416 |
| OSError | 225 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 713 | 0.966 | 1897 |
| zhangkai | 0.997 | prefer | 110 | 1.0 | 144 |
| mheidari-all | 0.845 | prefer | 338 | 0.766 | 22031 |
| Surfboard-tg-mixed | 0.835 | prefer | 104 | 0.76 | 6419 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 3031 |
| DeltaKronecker-all | 0.324 | observe | 8 | 0.375 | 6250 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 192 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5148 |
| Epodonios-all | 0.255 | observe | 0 | None | 7104 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3985 |

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
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.375 | 3 | 5 | 8 |
| Surfboard-tg-mixed | 0.76 | 79 | 25 | 104 |
| mheidari-all | 0.766 | 259 | 79 | 338 |
| Au1rxx-base64 | 0.966 | 689 | 24 | 713 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 110 | 0 | 110 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22031 | yes | 4.05 | 0 |
| SoliSpirit-all | 7205 | yes | 1.48 | 0 |
| Epodonios-all | 7104 | yes | 4.49 | 0 |
| Surfboard-tg-mixed | 6419 | yes | 2.59 | 0 |
| DeltaKronecker-all | 6250 | yes | 3.07 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.1 | 0 |
| barry-far-vless | 5444 | yes | 0.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 5148 | yes | 1.26 | 0 |
| Surfboard-tg-vless | 5125 | yes | 2.45 | 0 |
| mahdibland-V2RayAggregator | 4647 | yes | 1.95 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 65 |
| 204 | 32 |
| speed | 21 |
| cn-block | 16 |
