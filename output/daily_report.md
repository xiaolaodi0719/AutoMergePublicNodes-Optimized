# AutoNodes 每日报告

生成时间：2026-09-09 04:14:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 85797 |
| 去重后节点数 | 22922 |
| TCP 可达数 | 3000 |
| 真测通过数 | 505 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22922 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 80.9 |
| geo | 1.4 |
| probe | 262.1 |
| real_test | 374.0 |
| tcp | 39.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 51 | 30 | 21 | 58.8% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 170 | 155 | 15 | 91.2% |
| socks | 11 | 8 | 3 | 72.7% |
| trojan | 26 | 15 | 11 | 57.7% |
| vless | 492 | 285 | 207 | 57.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 67 |
| 204:ProxyError | 38 |
| geo:ClientOSError | 34 |
| speed:ClientOSError | 29 |
| speed:TimeoutError | 29 |
| cn-block:ClientOSError | 26 |
| cn-block:TimeoutError | 18 |
| 204:TimeoutError | 10 |
| 204:ClientOSError | 3 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5106 |
| ConnectionRefusedError | 879 |
| gaierror | 397 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.894 | prefer | 41 | 0.829 | 16648 |
| Au1rxx-base64 | 0.891 | prefer | 264 | 0.826 | 1690 |
| Surfboard-tg-mixed | 0.838 | prefer | 192 | 0.76 | 7520 |
| ermaozi | 0.629 | observe | 34 | 0.618 | 442 |
| ermaozi-get_subscribe | 0.572 | observe | 19 | 0.579 | 473 |
| DeltaKronecker-all | 0.433 | observe | 205 | 0.351 | 6097 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 176 |
| Epodonios-all | 0.255 | observe | 0 | None | 7969 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.351 | 72 | 133 | 205 |
| ermaozi-get_subscribe | 0.579 | 11 | 8 | 19 |
| ermaozi | 0.618 | 21 | 13 | 34 |
| Surfboard-tg-mixed | 0.76 | 146 | 46 | 192 |
| Au1rxx-base64 | 0.826 | 218 | 46 | 264 |
| mheidari-all | 0.829 | 34 | 7 | 41 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16648 | yes | 4.59 | 0 |
| SoliSpirit-all | 8963 | yes | 2.6 | 0 |
| Epodonios-all | 7969 | yes | 4.91 | 0 |
| Surfboard-tg-mixed | 7520 | yes | 3.45 | 0 |
| barry-far-vless | 6393 | yes | 0.68 | 0 |
| Surfboard-tg-vless | 6208 | yes | 3.93 | 0 |
| DeltaKronecker-all | 6097 | yes | 5.08 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 1.13 | 0 |
| mahdibland-V2RayAggregator | 4219 | yes | 3.06 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.75 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 101 |
| speed | 59 |
| 204 | 52 |
| cn-block | 45 |
