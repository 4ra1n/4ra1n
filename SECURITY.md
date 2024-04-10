在 Java 安全领域获得的一些成果
- [OpenJDK 安全公告致谢（2023年1月）](https://openjdk.org/groups/vulnerability/advisories/2023-01-17)
- [OpenJDK 安全公告致谢（2023年7月）](https://openjdk.org/groups/vulnerability/advisories/2023-07-18)
- [Oracle 深度安全贡献者（2022年10月）](https://www.oracle.com/security-alerts/cpuoct2022.html)
- [Oracle 深度安全贡献者（2023年1月）](https://www.oracle.com/security-alerts/cpujan2023.html)
- [Oracle 深度安全贡献者（2023年4月）](https://www.oracle.com/security-alerts/cpuapr2023.html)
- [Oracle 深度安全贡献者（2023年7月）](https://www.oracle.com/security-alerts/cpujul2023.html)
- [Oracle 深度安全贡献者（2023年10月）](https://www.oracle.com/security-alerts/cpuoct2023.html)
- 向知名 SRC 报告重要产品 RCE 漏洞并确认获得赏金

为简化 CVE 漏洞类型仅分为两种
- 直接或间接可 RCE （RCE）
- 不可 RCE （其他）

我的 ID 主要有
- 4ra1n
- n1ar4
- Qing Xu
- emyiqing
- rg

| Index | Vendor |  Product | CVE-ID | Type |
| :-- | :----- |  :-----  | :----- | :--- |
| 001 | Apache | Log4j2 | [CVE-2021-45046](https://logging.apache.org/log4j/2.x/security.html) | RCE |
| 002 | Spring | Spring Framework | [CVE-2022-22950](https://tanzu.vmware.com/security/cve-2022-22950) | 其他 |
| 003 | Oracle | WebLogic | [CVE-2022-21441](https://www.oracle.com/security-alerts/cpuapr2022.html) | 其他 |
| 004 | Apache | Tomcat | [CVE-2022-29885](https://lists.apache.org/thread/2b4qmhbcyqvc7dyfpjyx54c03x65vhcv) | 其他 |
| 005 | Apache | Shiro | [CVE-2022-32532](https://lists.apache.org/thread/y8260dw8vbm99oq7zv6y3mzn5ovk90xh) | 其他 |
| 006 | Oracle | WebLogic | [CVE-2022-21557](https://www.oracle.com/security-alerts/cpujul2022.html) | 其他 |
| 007 | Oracle | WebLogic | [CVE-2022-21560](https://www.oracle.com/security-alerts/cpujul2022.html) | 其他 |
| 008 | Oracle | SOA Suite | [CVE-2022-21562](https://www.oracle.com/security-alerts/cpujul2022.html) | RCE |
| 009 | Oracle | WebLogic | [CVE-2022-21564](https://www.oracle.com/security-alerts/cpujul2022.html) | 其他 |
| 010 | Apache | SystemDS | [CVE-2022-26477](https://lists.apache.org/thread/r4x2d2r6d4zykdrrx6s2l4qbxgzws0z3) | 其他 |
| 011 | Apache | InLong | [CVE-2022-40955](https://lists.apache.org/thread/1bgg183v529xyyrjqvdwyst4w8vbh556) | RCE |
| 012 | Oracle | Siebel CRM | [CVE-2022-21598](https://www.oracle.com/security-alerts/cpuoct2022.html) | RCE |
| 013 | Oracle | WebLogic | [CVE-2022-21616](https://www.oracle.com/security-alerts/cpuoct2022.html) | 其他 |
| 014 | Oracle | SOA Suite | [CVE-2022-21622](https://www.oracle.com/security-alerts/cpuoct2022.html) | RCE |
| 015 | Oracle | EM | [CVE-2022-21623](https://www.oracle.com/security-alerts/cpuoct2022.html) | RCE |
| 016 | Apache | Causeway | [CVE-2022-42466](https://lists.apache.org/thread/83ftj5jgtv3mbm28w3trjyvd591jztrz) | 其他 |
| 017 | Apache | Batik | [CVE-2022-41704](https://lists.apache.org/thread/4ybxj4vk0vqoj1hwjmvqdhf780cqzh8p) | RCE |
| 018 | Apache | Batik | [CVE-2022-42890](https://lists.apache.org/thread/xrfth92gq7hz896l4fygjwq31yrn2xsz) | RCE |
| 019 | Apache | Linkis | [CVE-2022-39944](https://lists.apache.org/thread/rxytj48q17304snonjtyt5lnlw64gccc) | RCE |
| 020 | Apache | IoTDB | [CVE-2022-43766](https://lists.apache.org/thread/9pgpb82p5brooy41n8l5q0y9h33db2zn) | 其他 |
| 021 | Apache | Ambari | [CVE-2022-45855](https://lists.apache.org/thread/302c4hwfjy9lx63jrbhcdx948pxc54l1) | RCE |
| 022 | Apache | DolphinScheduler | [CVE-2022-45875](https://lists.apache.org/thread/r0wqzkjsoq17j6ww381kmpx3jjp9hb6r) | RCE |
| 023 | Apache | ManifoldCF | [CVE-2022-45910](https://lists.apache.org/thread/ps32gd7y5cqtzz73kszsdxkk63oxqnso) | 其他 |
| 024 | Oracle | BI Publisher | [CVE-2023-21832](https://www.oracle.com/security-alerts/cpujan2023.html) | RCE |
| 025 | Oracle | WebLogic | [CVE-2023-21839](https://www.oracle.com/security-alerts/cpujan2023.html) | RCE |
| 026 | Oracle | BI Publisher | [CVE-2023-21846](https://www.oracle.com/security-alerts/cpujan2023.html) | RCE |
| 027 | Apache | Kafka | [CVE-2023-25194](https://lists.apache.org/thread/rn8vn4d9dbxc6817c5wz1dhhoshp1s25) | RCE |
| 028 | Apache | Kerby | [CVE-2023-25613](https://lists.apache.org/thread/3kkn1sc2s0pjhxy96nwmyhv1sr79q1w6) | 其他 |
| 029 | Apache | StreamPark | [CVE-2022-45801](https://lists.apache.org/thread/xbkwwpkp3n2rs2wcxg8l26mhsftxwwr9) | 其他 | 
| 030 | Apache | Airflow | [CVE-2023-28706](https://lists.apache.org/thread/518bzfxql7zwnlpp7ktdjn9ndsfzpqk2) | RCE |
| 031 | Apache | Linkis | [CVE-2023-27603](https://lists.apache.org/thread/6n1vlvnyn441rm02zdqc0wnpckj8ltn8) | RCE |
| 032 | Apache | Linkis | [CVE-2023-29215](https://lists.apache.org/thread/o682wz1ggq491ybvjwokxvcdtnzo76ls) | RCE |
| 033 | Apache | Linkis | [CVE-2023-29216](https://lists.apache.org/thread/18vv0m32oy51nzk8tbz13qdl5569y55l) | RCE |
| 034 | Oracle | WebLogic | [CVE-2023-21931](https://www.oracle.com/security-alerts/cpuapr2023.html) | RCE |
| 035 | Oracle | WebLogic | [CVE-2023-21960](https://www.oracle.com/security-alerts/cpuapr2023.html) | 其他 |
| 036 | Oracle | WebLogic | [CVE-2023-21964](https://www.oracle.com/security-alerts/cpuapr2023.html) | 其他 |
| 037 | Oracle | WebLogic | [CVE-2023-21979](https://www.oracle.com/security-alerts/cpuapr2023.html) | RCE |
| 038 | Apache | Inlong | [CVE-2023-31058](https://www.cve.org/CVERecord?id=CVE-2023-31058) | RCE |
| 039 | Oracle | WebLogic | [CVE-2023-22031](https://www.oracle.com/security-alerts/cpujul2023.html) | 其他 |
| 040 | Apache | Inlong | [CVE-2023-34434](https://lists.apache.org/thread/7f1o71w5r732cspltmtdydn01gllf4jo) | 其他 |
| 041 | Apache | Felix | [CVE-2023-38435](https://lists.apache.org/thread/6qyroszcrwt5sjoxwhxfxb5nvtpr9th1) | 其他 |
| 042 | Apache | Helix | [CVE-2023-38647](https://lists.apache.org/thread/ozhkchy7ngy8zgjbbn6pfjjh0ppcqvb9) | RCE |
| 043 | Metabase | Metabase | [CVE-2023-37470](https://github.com/metabase/metabase/security/advisories/GHSA-p7w3-9m58-rq83) | RCE |
| 044 | Apache | Airflow | [CVE-2023-39553](https://lists.apache.org/thread/tjlwk10odmgcd0t48qpsoprlgny6tbv0) | 其他 |
| 045 | Oracle | WebLogic | [CVE-2023-22069](https://www.oracle.com/security-alerts/cpuoct2023.html) | RCE |
| 046 | Oracle | WebLogic | [CVE-2023-22086](https://www.oracle.com/security-alerts/cpuoct2023.html) | RCE |
| 047 | Oracle | WebLogic | [CVE-2023-22089](https://www.oracle.com/security-alerts/cpuoct2023.html) | RCE |
| 048 | Apache | Derby | [CVE-2022-46337](https://lists.apache.org/thread/q23kvvtoohgzwybxpwozmvvk17rp0td3) | 其他 |
| 049 | Apache | DolphinScheduler | [CVE-2023-49068](https://lists.apache.org/thread/jn6kr6mjdgtfgpxoq9j8q4pkfsq8zmpq) | 其他 |
| 050 | Apache | Solr | [CVE-2023-50298](https://solr.apache.org/security.html#cve-2023-50298-apache-solr-can-expose-zookeeper-credentials-via-streaming-expressions) | 其他 |
| 051 | Apahce | Dolphinscheduler | [CVE-2023-49109](https://lists.apache.org/thread/5b6yq2gov0fsy9x5dkvo8ws4rr45vkn8) | RCE |
| 052 | Apache | Dolphinscheduler | [CVE-2023-50270](https://www.cve.org/CVERecord?id=CVE-2023-50270) | 其他 |
| 053 | Apache | Dolphinscheduler | [CVE-2023-51770](https://lists.apache.org/thread/gpks573kn00ofxn7n9gkg6o47d03p5rw) | 其他 |
| 054 | Apache | Ambari | [CVE-2023-50379](https://lists.apache.org/thread/jglww6h6ngxpo1r6r5fx7ff7z29lnvv8) | RCE |
| 055 | Apache | Zeppelin | [CVE-2024-31864](https://lists.apache.org/thread/53fd4m8kpthxpwz6767gqx30tv99g2so) | RCE |
| 056 | Apache | Zeppelin | [CVE-2024-31867](https://lists.apache.org/thread/s4scw8bxdhrjs0kg0lhb68xqd8y9lrtf) | 其他 |
