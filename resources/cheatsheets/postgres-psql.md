# 🐘 Postgres Apps

| 명령어 | 설명 |
|------|------|
| `$ sudo -u <username> -i` | 특정 사용자로 로그인합니다. <br> 기본 설치 시 생성되는 기본 사용자는 **postgres** |
| `$ createdb <dbname>` | 새로운 데이터베이스 생성 |
| `$ dropdb <dbname>` | 기존 데이터베이스 삭제 |
| `$ dropdb <dbname> && createdb <dbname>` | 데이터베이스 초기화(리셋) <br> (기존 DB 삭제 후 같은 이름으로 새로 생성) |

---

<br>

# 💻 psql (PostgreSQL 터미널 클라이언트)

| 명령어 | 설명 |
|------|------|
| `$ psql <dbname> [<username>]` | 지정한 DB에 연결하여 psql 실행 <br> (선택적으로 다른 사용자로 접속 가능) |
| `# \l` | 서버의 모든 DB 목록 표시 (이름, 소유자, 접근 권한 포함) |
| `# \c <dbname>` | 특정 DB로 접속(전환) |
| `# \dt` | 현재 DB의 모든 테이블 목록 표시 |
| `# \d <tablename>` | 지정한 테이블의 스키마(구조) 확인 |
| `# \q` | psql 종료 후 터미널로 복귀 |
