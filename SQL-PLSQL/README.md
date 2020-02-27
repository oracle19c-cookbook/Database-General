
## SQL-PL/SQL 

---

오라클 Database 12.2, 18c, 19c의 SQL 및 PL/SQL의 신기능을 정리하였습니다.

![](https://github.com/oracle19c-cookbook/Database-General/blob/master/SQL-PLSQL/SQL_NEW_FEATURES.jpg)

- Oracle 12.2에서 Data Validation 기능이 강화되어 Date형 및 숫자형 데이터의 구분이 가능해지고, 에러핸들링 기능이 강화되었습니다. 
- Oracle 18c에서 Live SQL 기능으로 웹상에서 간단한 SQL을 테스트 할 수 잇게 되었습니다. 또한 JSON 기능이 강화되었으며, Private Temporyray Table 기능으로 임시테이블을 사용 후 자동으로 삭제할 수 있게 되었습니다.  
- Oracle 19c 에서 LISTAGG 집계 함수에 DISTINCT를 사용할 수 있게 되어 중복 데이터를 제거할 수 있게 되었으며, JSON 데이터의 부분 업데이트도 가능해졌습니다. 

## Hands-On

#### Oracle 19c

- [LISTAGG DISTINCT](https://livesql.oracle.com/apex/livesql/file/content_HT1O85E4BHSBWN93G1B3M8SI2.html)
- [JSON Syntax 간편화](https://livesql.oracle.com/apex/livesql/file/content_HT1U9Z9IZB03YZOD77B6D5411.html)
- [JSON 문서 부분 업데이트](https://livesql.oracle.com/apex/livesql/file/content_HUB30QTK3RRR7J1EYJ8R35SPM.html)
- [JSON_serialize 함수](https://livesql.oracle.com/apex/livesql/file/content_HUIN1Y0MEMG4CLORXNX04I6C7.html)

#### Oracle 18c 

- [Oracle Live SQL 소개](https://www.oracle.com/database/technologies/olracle-live-sql.html)
- [JSON 기능향상](https://livesql.oracle.com/apex/livesql/file/content_GBSPKG60QQZG6I7MRLS1V5BPG.html)
- [Private Temporary Tables](https://livesql.oracle.com/apex/livesql/file/content_GAD3PVUCHINEPIQK4IKDXALT7.html)
- [SODA API for PL/SQL](https://livesql.oracle.com/apex/livesql/file/content_HR0J8BA2K99VZWT51TU1OCGJ4.html)

#### Oracle 12.2

- [Data Validation 기능](https://livesql.oracle.com/apex/livesql/file/tutorial_EDVE861IMHO1W3Q654ES9EQQW.html)
- [LISTAGG 함수에서 Long List 처리하기](https://livesql.oracle.com/apex/livesql/file/tutorial_EDVE861IDOIZGLUZMSW7Y8HYG.html)
- [PL/Scope로 코드에서 Commit과 Rollback 찾기](https://livesql.oracle.com/apex/livesql/file/content_E31RZEWUHFL8VR4FNXRFWL00A.html)
- [SQL/JSON 기능 향상](https://livesqla.oracle.com/apex/livesql/file/tutorial_EDVE861H6UF4Z20EV0RM4DK2G.html)


## 참고 자료

- 공식 매뉴얼
    - [Introduction to SQL](https://docs.oracle.com/en/database/oracle/oracle-database/19/cncpt/sql.html#GUID-CBD8FE77-BA6F-4241-A71C-2ADDDF43EA7F)
    - [12.2 SQL Language Reference](https://docs.oracle.com/en/database/oracle/oracle-database/12.2/sqlrf/index.html)
    - [18c SQL Language Reference](https://docs.oracle.com/en/database/oracle/oracle-database/18/sqlrf/index.html)
    - [19c SQL Language Reference](https://docs.oracle.com/en/database/oracle/oracle-database/19/sqlrf/index.html)
