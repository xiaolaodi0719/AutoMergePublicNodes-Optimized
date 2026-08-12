# AutoNodes 每日报告

生成时间：2026-08-12 07:44:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 88266 |
| 去重后节点数 | 23638 |
| TCP 可达数 | 3000 |
| 真测通过数 | 606 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23638 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 40.8 |
| geo | 1.2 |
| probe | 61.7 |
| real_test | 152.2 |
| tcp | 35.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 161 | 149 | 12 | 92.5% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 122 | 110 | 12 | 90.2% |
| vless | 495 | 198 | 297 | 40.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 98 |
| geo:ClientOSError | 91 |
| speed:TimeoutError | 50 |
| speed:ClientOSError | 33 |
| 204:ProxyError | 20 |
| cn-block:TimeoutError | 12 |
| 204:TimeoutError | 10 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4983 |
| ConnectionRefusedError | 793 |
| OSError | 226 |
| gaierror | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Au1rxx-base64 | 0.91 | prefer | 422 | 0.846 | 1632 |
| Surfboard-tg-mixed | 0.604 | observe | 103 | 0.524 | 5943 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 4568 |
| DeltaKronecker-all | 0.318 | observe | 17 | 0.235 | 4975 |
| mheidari-all | 0.313 | observe | 255 | 0.231 | 20330 |
| tg-shadowproxy66 | 0.312 | observe | 2 | 1.0 | 12 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5328 |
| Epodonios-all | 0.255 | observe | 0 | None | 6602 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.231 | 59 | 196 | 255 |
| DeltaKronecker-all | 0.235 | 4 | 13 | 17 |
| Surfboard-tg-mixed | 0.524 | 54 | 49 | 103 |
| Au1rxx-base64 | 0.846 | 357 | 65 | 422 |
| tg-shadowproxy66 | 1.0 | 2 | 0 | 2 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20330 | yes | 5.22 | 0 |
| SoliSpirit-all | 7652 | yes | 3.02 | 0 |
| Epodonios-all | 6602 | yes | 2.8 | 0 |
| Surfboard-tg-mixed | 5943 | yes | 3.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 5328 | yes | 1.61 | 0 |
| barry-far-vless | 5267 | yes | 1.79 | 0 |
| mahdibland-V2RayAggregator | 5196 | yes | 2.9 | 0 |
| DeltaKronecker-all | 4975 | yes | 5.42 | 0 |
| Surfboard-tg-vless | 4919 | yes | 4.51 | 0 |
| xiaoji235-airport-v2ray-all | 4568 | yes | 1.17 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 191 |
| speed | 86 |
| 204 | 33 |
| cn-block | 16 |
