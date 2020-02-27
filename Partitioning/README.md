## Partitioning

---

오라클 Database 12.2, 18c, 19c의 Partitioning의 신기능을 정리하였습니다.

![](https://github.com/oracle19c-cookbook/Database-General/blob/master/Partitioning/PARTITION.jpg)

- Oracle 12.2에서 Automatic List Partitioning으로 자동화 기능이 추가되었고, Multi-column으로 List Partitioning이 가능해졌습니다. 또한 Read Only Partition 기능이 추가되었습니다.
- Oracle 18c에서 Partition Wise 기능이 강화되었습니다. SQL에 Disinct가 있으면 파티션 별로 Sort Unque가 발생하여 성능이 개선됩니다. 또한 Anaytic 함수의 경우에도 Partition Wise Operation이 가능해졌습니다.
- Oracle 19c에서 Hybrid Partition 기능으로 Cloud의 Object 스토리지 혹은 NAS 상의 Haddop File, SAM 파일로 파티셔닝이 가능해졌습니다.

## Hands-On

#### Oracle 19c

- [Hybrid Partitioned Table 관리하기](https://docs.oracle.com/en/database/oracle/oracle-database/19/tutorial-manage-partitions-in-hybrid-partitioned-tables/)

#### Oracle 18c 

- [Partition Wise Operations(외부링크)](https://antognini.ch/2018/05/partition-wise-operations-new-features-in-12c-and-18c/)

#### Oracle 12.2

- [Partitioning 신기능](https://livesql.oracle.com/apex/livesql/file/tutorial_EDVE861H5MO8DX16EGJ80HOTK.html)

## 참고 자료

- 공식 매뉴얼
    - [12.2 VLDB and Partitioning Guide](https://docs.oracle.com/en/database/oracle/oracle-database/12.2/vldbg/index.html)
    - [18c VLDB and Partitioning Guide](https://docs.oracle.com/en/database/oracle/oracle-database/18/vldbg/index.html)
    - [19c VLDB and Partitioning Guide](https://docs.oracle.com/en/database/oracle/oracle-database/19/vldbg/index.html)
    
- White Paper
    - [Oracle Partitioning - Extreme Data Management and Performance](https://www.oracle.com/technetwork/database/options/partitioning/partitioning-wp-12c-1896137.pdf)    
