# AutoNodes 每日报告

生成时间：2026-08-11 13:20:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84566 |
| 去重后节点数 | 24401 |
| TCP 可达数 | 3000 |
| 真测通过数 | 527 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24401 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 28.5 |
| geo | 1.3 |
| probe | 50.1 |
| real_test | 121.9 |
| tcp | 35.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 156 | 141 | 15 | 90.4% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 121 | 118 | 3 | 97.5% |
| vless | 197 | 122 | 75 | 61.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 26 |
| geo:ClientOSError | 16 |
| 204:TimeoutError | 16 |
| speed:ClientOSError | 13 |
| geo:TimeoutError | 6 |
| 204:ProxyError | 6 |
| cn-block:TimeoutError | 5 |
| geo:ProxyError | 2 |
| speed:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4304 |
| ConnectionRefusedError | 831 |
| gaierror | 387 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Au1rxx-base64 | 0.903 | prefer | 392 | 0.844 | 1501 |
| Surfboard-tg-mixed | 0.784 | prefer | 79 | 0.709 | 6195 |
| mheidari-all | 0.543 | observe | 13 | 0.615 | 20194 |
| DeltaKronecker-all | 0.324 | observe | 8 | 0.375 | 5522 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5419 |
| Epodonios-all | 0.255 | observe | 0 | None | 6769 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7602 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| 10ium-HighSpeed | 0.161 | observe | 1 | 0.0 | 0 | 839 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.375 | 3 | 5 | 8 |
| mheidari-all | 0.615 | 8 | 5 | 13 |
| Surfboard-tg-mixed | 0.709 | 56 | 23 | 79 |
| Au1rxx-base64 | 0.844 | 331 | 61 | 392 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20194 | yes | 4.61 | 0 |
| SoliSpirit-all | 7602 | yes | 3.71 | 0 |
| Epodonios-all | 6769 | yes | 3.03 | 0 |
| Surfboard-tg-mixed | 6195 | yes | 3.49 | 0 |
| DeltaKronecker-all | 5522 | yes | 5.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 5419 | yes | 1.46 | 0 |
| barry-far-vless | 5245 | yes | 1.21 | 0 |
| mahdibland-V2RayAggregator | 5209 | yes | 2.64 | 0 |
| Surfboard-tg-vless | 5048 | yes | 3.22 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.55 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 41 |
| geo | 24 |
| 204 | 24 |
| cn-block | 7 |
