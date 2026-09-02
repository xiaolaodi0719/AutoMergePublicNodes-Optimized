# AutoNodes 每日报告

生成时间：2026-09-02 03:58:03

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82051 |
| 去重后节点数 | 23604 |
| TCP 可达数 | 3000 |
| 真测通过数 | 759 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23604 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 41.9 |
| geo | 1.6 |
| probe | 88.6 |
| real_test | 205.1 |
| tcp | 39.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 21 | 20 | 1 | 95.2% |
| hysteria2 | 8 | 7 | 1 | 87.5% |
| shadowsocks | 180 | 173 | 7 | 96.1% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 64 | 41 | 23 | 64.1% |
| vless | 943 | 513 | 430 | 54.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 208 |
| geo:ClientOSError | 72 |
| speed:ClientOSError | 69 |
| speed:TimeoutError | 58 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 13 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 3 |
| 204:ProxyConnectionError | 1 |
| speed:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5848 |
| ConnectionRefusedError | 876 |
| gaierror | 74 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.97 | prefer | 429 | 0.902 | 1736 |
| Surfboard-tg-mixed | 0.935 | prefer | 74 | 0.865 | 6990 |
| zhangkai | 0.922 | prefer | 22 | 0.955 | 144 |
| mheidari-all | 0.742 | prefer | 238 | 0.664 | 15712 |
| DeltaKronecker-all | 0.364 | observe | 455 | 0.284 | 7294 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4708 |
| Epodonios-all | 0.255 | observe | 0 | None | 7407 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7631 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5850 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.284 | 129 | 326 | 455 |
| mheidari-all | 0.664 | 158 | 80 | 238 |
| Surfboard-tg-mixed | 0.865 | 64 | 10 | 74 |
| Au1rxx-base64 | 0.902 | 387 | 42 | 429 |
| zhangkai | 0.955 | 21 | 1 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15712 | yes | 5.83 | 0 |
| SoliSpirit-all | 7631 | yes | 2.84 | 0 |
| Epodonios-all | 7407 | yes | 6.21 | 0 |
| DeltaKronecker-all | 7294 | yes | 4.91 | 0 |
| Surfboard-tg-mixed | 6990 | yes | 4.81 | 0 |
| barry-far-vless | 6027 | yes | 2.16 | 0 |
| Surfboard-tg-vless | 5850 | yes | 3.36 | 0 |
| 10ium-ScrapeCategorize-Vless | 4708 | yes | 2.58 | 0 |
| mahdibland-V2RayAggregator | 4159 | yes | 1.52 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 280 |
| speed | 128 |
| cn-block | 28 |
| 204 | 27 |
