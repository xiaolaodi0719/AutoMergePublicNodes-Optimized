# AutoNodes 每日报告

生成时间：2026-09-08 11:02:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 91310 |
| 去重后节点数 | 25270 |
| TCP 可达数 | 3000 |
| 真测通过数 | 556 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25270 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 35.4 |
| geo | 1.4 |
| probe | 87.9 |
| real_test | 122.3 |
| tcp | 42.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 70 | 67 | 3 | 95.7% |
| hysteria2 | 25 | 21 | 4 | 84.0% |
| shadowsocks | 176 | 157 | 19 | 89.2% |
| socks | 8 | 4 | 4 | 50.0% |
| trojan | 22 | 21 | 1 | 95.5% |
| vless | 381 | 281 | 100 | 73.8% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 25 |
| cn-block:ClientOSError | 23 |
| speed:TimeoutError | 22 |
| cn-block:TimeoutError | 20 |
| geo:ClientOSError | 14 |
| 204:ProxyError | 9 |
| speed:ClientOSError | 6 |
| 204:ClientOSError | 5 |
| geo:TimeoutError | 4 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5389 |
| ConnectionRefusedError | 982 |
| gaierror | 490 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.961 | prefer | 51 | 0.961 | 450 |
| Au1rxx-base64 | 0.944 | prefer | 317 | 0.877 | 1726 |
| ermaozi-get_subscribe | 0.907 | prefer | 18 | 1.0 | 470 |
| Surfboard-tg-mixed | 0.818 | prefer | 185 | 0.741 | 7431 |
| mheidari-all | 0.755 | prefer | 78 | 0.679 | 22334 |
| DeltaKronecker-all | 0.636 | observe | 34 | 0.559 | 6097 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4657 |
| Epodonios-all | 0.255 | observe | 0 | None | 7885 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.559 | 19 | 15 | 34 |
| mheidari-all | 0.679 | 53 | 25 | 78 |
| Surfboard-tg-mixed | 0.741 | 137 | 48 | 185 |
| Au1rxx-base64 | 0.877 | 278 | 39 | 317 |
| ermaozi | 0.961 | 49 | 2 | 51 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 18 | 0 | 18 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22334 | yes | 5.91 | 0 |
| SoliSpirit-all | 8811 | yes | 3.34 | 0 |
| Epodonios-all | 7885 | yes | 5.23 | 0 |
| Surfboard-tg-mixed | 7431 | yes | 4.54 | 0 |
| barry-far-vless | 6423 | yes | 2.63 | 0 |
| Surfboard-tg-vless | 6201 | yes | 3.94 | 0 |
| DeltaKronecker-all | 6097 | yes | 5.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 1.98 | 0 |
| mahdibland-V2RayAggregator | 4209 | yes | 0.73 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.39 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 44 |
| 204 | 40 |
| speed | 29 |
| geo | 18 |
