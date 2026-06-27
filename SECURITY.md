## 关于

本页面记录一些安全相关的成果

- 一般 `credit` 是：4ra1n
- 部分 AI 发现漏洞 `credit` 是：4ra2n
- 部分 `credit` 是：Qing Xu

## 致谢信息

- [OpenJDK 安全公告致谢（2023年01月）](https://openjdk.org/groups/vulnerability/advisories/2023-01-17)
- [OpenJDK 安全公告致谢（2023年07月）](https://openjdk.org/groups/vulnerability/advisories/2023-07-18)
- [Oracle 深度安全贡献者（2022年10月）](https://www.oracle.com/security-alerts/cpuoct2022.html)
- [Oracle 深度安全贡献者（2023年01月）](https://www.oracle.com/security-alerts/cpujan2023.html)
- [Oracle 深度安全贡献者（2023年04月）](https://www.oracle.com/security-alerts/cpuapr2023.html)
- [Oracle 深度安全贡献者（2023年07月）](https://www.oracle.com/security-alerts/cpujul2023.html)
- [Oracle 深度安全贡献者（2023年10月）](https://www.oracle.com/security-alerts/cpuoct2023.html)
- [Oracle 深度安全贡献者（2026年01月）](https://www.oracle.com/security-alerts/cpujan2026.html)

## CVE

以下大部分是我独立发现的 `CVE` 漏洞，部分和朋友合作发现，感谢我的朋友们

> 只保留高价值产品或有意义的 `CVE` 编号，并不是所有编号，我删除了部分低价值记录

| Vendor |  Product | CVE-ID | Type | CVSS 3 (官方/NVD) |
| :----- |  :-----  | :----- | :--- | :--- |
| Apache | Log4j2 | [CVE-2021-45046](https://logging.apache.org/security.html#CVE-2021-45046) | RCE | 9.0 CRITICAL |
| Spring | Spring Framework | [CVE-2022-22950](https://spring.io/security/cve-2022-22950) | 拒绝服务 | 6.5 MEDIUM | 
| Oracle | WebLogic | [CVE-2022-21441](https://www.oracle.com/security-alerts/cpuapr2022.html) | 拒绝服务 | 7.5 HIGH |
| Apache | Tomcat | [CVE-2022-29885](https://lists.apache.org/thread/2b4qmhbcyqvc7dyfpjyx54c03x65vhcv) | 拒绝服务 | 7.5 HIGH |
| Apache | Shiro | [CVE-2022-32532](https://lists.apache.org/thread/y8260dw8vbm99oq7zv6y3mzn5ovk90xh) | 身份验证绕过 | 9.8 CRITICAL |
| Oracle | WebLogic | [CVE-2022-21557](https://www.oracle.com/security-alerts/cpujul2022.html) | RCE | 5.7 MEDIUM |
| Oracle | WebLogic | [CVE-2022-21560](https://www.oracle.com/security-alerts/cpujul2022.html) | 拒绝服务 | 5.3 MEDIUM | 
| Oracle | SOA Suite | [CVE-2022-21562](https://www.oracle.com/security-alerts/cpujul2022.html) | RCE | 7.5 HIGH |
| Oracle | WebLogic | [CVE-2022-21564](https://www.oracle.com/security-alerts/cpujul2022.html) | 拒绝服务 | 5.3 MEDIUM | 
| Oracle | Siebel CRM | [CVE-2022-21598](https://www.oracle.com/security-alerts/cpuoct2022.html) | RCE | 7.5 HIGH |
| Oracle | WebLogic | [CVE-2022-21616](https://www.oracle.com/security-alerts/cpuoct2022.html) | 拒绝服务 | 5.2 MEDIUM | 
| Oracle | SOA Suite | [CVE-2022-21622](https://www.oracle.com/security-alerts/cpuoct2022.html) | RCE | 7.5 HIGH |
| Oracle | Enterprise Manager | [CVE-2022-21623](https://www.oracle.com/security-alerts/cpuoct2022.html) | RCE | 7.5 HIGH |
| Apache | Causeway | [CVE-2022-42466](https://lists.apache.org/thread/m3qvks78moblh7q2nbbhc5mzy9ckcrcn) | 存储XSS | 6.1 MEDIUM |
| Apache | Batik | [CVE-2022-41704](https://lists.apache.org/thread/4ybxj4vk0vqoj1hwjmvqdhf780cqzh8p) | RCE | 7.5 HIGH |
| Apache | Batik | [CVE-2022-42890](https://lists.apache.org/thread/xrfth92gq7hz896l4fygjwq31yrn2xsz) | RCE | 7.5 HIGH |
| Apache | ManifoldCF | [CVE-2022-45910](https://lists.apache.org/thread/ps32gd7y5cqtzz73kszsdxkk63oxqnso) | 信息泄露 | 5.3 MEDIUM |
| Apache | DolphinScheduler | [CVE-2022-45875](https://lists.apache.org/thread/dj6xj1xv1x0sxm9mx1x7kvr2nb45n3w8) | RCE | 9.8 CRITICAL |
| Apache | DolphinScheduler | [CVE-2023-49109](https://lists.apache.org/thread/llnghrd72gbfhwh4tn68zvl1hzl9gxn6) | RCE | 9.8 CRITICAL |
| Oracle | BI Publisher | [CVE-2023-21832](https://www.oracle.com/security-alerts/cpujan2023.html) | RCE | 8.8 HIGH |
| Oracle | WebLogic | [CVE-2023-21839](https://www.oracle.com/security-alerts/cpujan2023.html) | RCE | 7.5 HIGH |
| Oracle | BI Publisher | [CVE-2023-21846](https://www.oracle.com/security-alerts/cpujan2023.html) | RCE | 8.8 HIGH |
| Apache | Kafka | [CVE-2023-25194](https://lists.apache.org/thread/rn8vn4d9dbxc6817c5wz1dhhoshp1s25) | RCE | 8.8 HIGH |
| Apache | Airflow | [CVE-2023-28706](https://lists.apache.org/thread/518bzfxql7zwnlpp7ktdjn9ndsfzpqk2) | RCE | 9.8 CRITICAL |
| Oracle | WebLogic | [CVE-2023-21931](https://www.oracle.com/security-alerts/cpuapr2023.html) | RCE | 7.5 HIGH |
| Oracle | WebLogic | [CVE-2023-21960](https://www.oracle.com/security-alerts/cpuapr2023.html) | 拒绝服务 | 5.6 MEDIUM |
| Oracle | WebLogic | [CVE-2023-21964](https://www.oracle.com/security-alerts/cpuapr2023.html) | 拒绝服务 | 7.5 HIGH |
| Oracle | WebLogic | [CVE-2023-21979](https://www.oracle.com/security-alerts/cpuapr2023.html) | RCE | 7.5 HIGH |
| Oracle | WebLogic | [CVE-2023-22031](https://www.oracle.com/security-alerts/cpujul2023.html) | 拒绝服务 | 4.4 MEDIUM |
| Apache | Airflow | [CVE-2023-39553](https://lists.apache.org/thread/tjlwk10odmgcd0t48qpsoprlgny6tbv0) | 文件读取 | 7.5 HIGH |
| Oracle | WebLogic | [CVE-2023-22069](https://www.oracle.com/security-alerts/cpuoct2023.html) | RCE | 9.8 CRITICAL |
| Oracle | WebLogic | [CVE-2023-22086](https://www.oracle.com/security-alerts/cpuoct2023.html) | RCE | 7.5 HIGH |
| Oracle | WebLogic | [CVE-2023-22089](https://www.oracle.com/security-alerts/cpuoct2023.html) | RCE | 9.8 CRITICAL |
| Apache | Helix | [CVE-2023-38647](https://lists.apache.org/thread/ozhkchy7ngy8zgjbbn6pfjjh0ppcqvb9) | RCE | 9.8 CRITICAL |
| Apache | Kerby | [CVE-2023-25613](https://lists.apache.org/thread/ymptwbossopmvqhowjo7cm7j6o2hwr2t) | 信息泄露 | 9.8 CRITICAL |
| Apache | Linkis | [CVE-2023-27603](https://lists.apache.org/thread/6ynotvjvvwyj6lsctfxt42x7wrtks1z2) | RCE | 9.8 CRITICAL |
| Apache | InLong | [CVE-2023-34434](https://lists.apache.org/thread/390fwst87m9tpmpgx73n61ypcvvvxd9j) | 文件读取 | 7.5 HIGH |
| Metabase | Metabase | [CVE-2023-37470](https://github.com/metabase/metabase/security/advisories/GHSA-p7w3-9m58-rq83) | RCE | 9.8 CRITICAL |
| Apache | Derby | [CVE-2022-46337](https://lists.apache.org/thread/q23kvvtoohgzwybxpwozmvvk17rp0td3) | 信息泄露 | 9.8 CRITICAL |
| Apache | Solr | [CVE-2023-50298](https://lists.apache.org/thread/lz0obpo1y4xh8xgnw2sylkpcqbs670vy) | 信息泄露 | 7.5 HIGH |
| Oracle | WebLogic | [CVE-2024-21006](https://www.oracle.com/security-alerts/cpuapr2024.html) | RCE | 7.5 HIGH |
| Apache | OFBiz | [CVE-2024-38856](https://lists.apache.org/thread/lmckgos5s5prfdqfctqskkqnpkcgdb06) | RCE | 9.8 CRITICAL |
| Oracle | FMW Installer | [CVE-2024-21190](https://www.oracle.com/security-alerts/cpuoct2024.html) | RCE | 7.5 HIGH |
| Apache | ZooKeeper | [CVE-2024-51504](https://lists.apache.org/thread/dgvx1vr8jy69d65lrsl357lqvmb4wfw6) | 身份验证绕过 | 9.1 CRITICAL |
| Apache | Ambari | [CVE-2024-51941](https://lists.apache.org/thread/91p3h18mn6dwx93k9fw8tyy37lpwd1y2) | RCE | 8.8 HIGH |
| Apache | Zeppelin | [CVE-2024-31867](https://lists.apache.org/thread/xfvzrm9btw2jmthfblx5qb2848f21gby) | 信息泄露 | 6.5 MEDIUM |
| Apache | Kafka | [CVE-2025-27817](https://lists.apache.org/thread/ok29h7h0l5hwpoq9v4nlfngvzz71ndvs) | 文件读取 | 7.5 HIGH |
| Apache | Kafka | [CVE-2025-27818](https://lists.apache.org/thread/zc9v12hb4kt2twzxqmhn5t1psp38vbsn) | RCE | 8.8 HIGH |
| Apache | Shiro | [CVE-2026-23901](https://lists.apache.org/thread/mm1jct9b86jvnh3y44tj22xvjtx3xhhh) | 时序侧信道 | 2.5 LOW |
| Apache | OpenMeetings | [CVE-2026-34020](https://lists.apache.org/thread/jn6qvcs8g0gv46oso0pb9fk3xvq9wz1h) | 信息泄露 | 7.5 HIGH |
| Apache | OpenMeetings | [CVE-2026-33266](https://lists.apache.org/thread/vrjg6o9c1nnmhn64vr316voph303lt4c) | 信息泄露 | 7.5 HIGH |
| Apache | OpenMeetings | [CVE-2026-33005](https://lists.apache.org/thread/d5mcsdvdm1yj62bk68rl5890lopf6w94) | 逻辑漏洞 | 4.3 MEDIUM |
| Oracle | MySQL | [CVE-2026-34317](https://www.oracle.com/security-alerts/cpuapr2026.html) | 拒绝服务 | 5.0 MEDIUM |
| Oracle | MySQL | [CVE-2026-34318](https://www.oracle.com/security-alerts/cpuapr2026.html) | 信息泄露 | 5.8 MEDIUM |
| Oracle | MySQL | [CVE-2026-34319](https://www.oracle.com/security-alerts/cpuapr2026.html) | 拒绝服务 | 5.0 MEDIUM |
| DataEase | DataEase | [CVE-2026-45534](https://github.com/dataease/dataease/security/advisories/GHSA-cv4c-8rpv-2x97) | RCE | HIGH |
| DataEase | DataEase | [CVE-2026-45532](https://github.com/dataease/dataease/security/advisories/GHSA-2mqc-w4hm-f3p9) | 路径遍历 | HIGH |
| DataEase | DataEase | [CVE-2026-45419](https://github.com/dataease/dataease/security/advisories/GHSA-83fh-fgh3-g9f9) | 任意文件写入 | HIGH |
| DataEase | DataEase | [CVE-2026-45417](https://github.com/dataease/dataease/security/advisories/GHSA-rg6c-r9mv-39fr) | SQL注入 | HIGH |
| Apache | ActiveMQ | [CVE-2026-42588](https://lists.apache.org/thread/8dw2wyojfkxhk45sqnbbqpswcxvh7zf7) | RCE | 8.1 HIGH |
| Apache | ActiveMQ | [CVE-2026-42253](https://lists.apache.org/thread/rh0nr6shwhgpyhg4xlrkslznc57m87xy) | 存储XSS | 6.1 MEDIUM |
| Apache | Calcite | [CVE-2026-46718](https://lists.apache.org/thread/qb3bdfd0n15tq73vz8y3x4bry0oswz3b) | RCE | 6.5 MEDIUM |
| Oracle | MySQL | [CVE-2026-46863](https://www.oracle.com/security-alerts/cspujun2026.html) | 拒绝服务 | 7.5 HIGH |
| Apache | Kvrocks | [CVE-2026-46751](https://lists.apache.org/thread/rwrb0sz8bdg665cx6jmgxzozwq8bppom) | 拒绝服务 | 5.1 MEDIUM |
| Apache | Kvrocks | [CVE-2026-41566](https://lists.apache.org/thread/njqjzkczgr17c9rdfbcfvxlqxtmpgxcg) | 逻辑漏洞 | 9.4 CRITICAL |

### 补充

我认为，只有官方发布的 `CVE` 安全公告才是 **有价值** 的 `CVE` 

而通过 `MITRE` 表单/邮件等方式自行申请的 `CVE` 编号 **不属于有价值** 的 `CVE`

我认为古法时代（2026 年以前）的成果，是真实技术的体现，在 `AI` 时代谁都可以容易地审出新漏洞

特例除外，仅绝大多数情况下
