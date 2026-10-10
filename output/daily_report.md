# AutoNodes 每日报告

生成时间：2026-10-10 05:29:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 97887 |
| 去重后节点数 | 27737 |
| TCP 可达数 | 3000 |
| 真测通过数 | 520 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27737 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 71.8 |
| geo | 1.5 |
| probe | 333.4 |
| real_test | 480.7 |
| tcp | 47.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 3 | 1 | 75.0% |
| http | 29 | 21 | 8 | 72.4% |
| hysteria2 | 26 | 25 | 1 | 96.2% |
| shadowsocks | 163 | 147 | 16 | 90.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 136 | 128 | 8 | 94.1% |
| vless | 399 | 192 | 207 | 48.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 104 |
| speed:TimeoutError | 37 |
| geo:ClientOSError | 26 |
| cn-block:TimeoutError | 20 |
| speed:ClientOSError | 15 |
| 204:ProxyError | 12 |
| 204:TimeoutError | 12 |
| cn-block:ClientOSError | 10 |
| cn-block:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48085: bind: address already in use | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6863 |
| ConnectionRefusedError | 1025 |
| gaierror | 305 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | prefer | 357 | 0.908 | 1786 |
| Surfboard-tg-mixed | 0.712 | prefer | 180 | 0.633 | 7155 |
| ermaozi-get_subscribe | 0.681 | observe | 27 | 0.667 | 653 |
| zhangkai | 0.483 | observe | 6 | 1.0 | 144 |
| mheidari-all | 0.373 | observe | 182 | 0.291 | 23395 |
| DeltaKronecker-all | 0.337 | observe | 7 | 0.429 | 5154 |
| ninja-vless | 0.327 | observe | 1 | 1.0 | 1791 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4984 |
| Epodonios-all | 0.255 | observe | 0 | None | 7634 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.291 | 53 | 129 | 182 |
| DeltaKronecker-all | 0.429 | 3 | 4 | 7 |
| Surfboard-tg-mixed | 0.633 | 114 | 66 | 180 |
| ermaozi-get_subscribe | 0.667 | 18 | 9 | 27 |
| Au1rxx-base64 | 0.908 | 324 | 33 | 357 |
| ninja-vless | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 6 | 0 | 6 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23395 | yes | 4.18 | 0 |
| SoliSpirit-all | 9590 | yes | 3.16 | 0 |
| Epodonios-all | 7634 | yes | 2.51 | 0 |
| Surfboard-tg-mixed | 7155 | yes | 4.92 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.42 | 0 |
| barry-far-vless | 5793 | yes | 0.69 | 0 |
| Surfboard-tg-vless | 5643 | yes | 2.8 | 0 |
| DeltaKronecker-all | 5154 | yes | 5.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 4984 | yes | 1.02 | 0 |
| mahdibland-V2RayAggregator | 4346 | yes | 2.04 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 131 |
| speed | 53 |
| cn-block | 32 |
| 204 | 25 |
| sing-box exited 1 | 1 |
