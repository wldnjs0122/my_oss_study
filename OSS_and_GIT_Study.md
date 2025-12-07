Git과 GitHub 정리
1. Git
1-1. 개념

분산형 버전관리 시스템으로서, 코드의 역사를 기록하며 과거의 모든 순간을 보존하고,
여러 사람이 한 프로젝트를 건축해 나가도록 돕는 도구.

1-2. 구조

Working Directory

Staging Area

Local Repository

1-3. 주요 기능

변경 이력 추적

이전 버전 복원

브랜치 생성

브랜치 병합

병합 충돌 해결

태그를 통한 버전 기록

1-4. 주요 명령어

저장소 생성: git init

변경사항 올리기: git add

저장(커밋): git commit

상태 확인: git status

이력 확인: git log

브랜치 목록: git branch

브랜치 이동: git switch, git checkout

브랜치 생성: git checkout -b

병합: git merge

차이 비교: git diff

되돌리기: git reset, git revert

2. GitHub
2-1. 개념

Git으로 관리되는 저장소를 온라인에서 보관하고,
팀과 공동체가 협업할 수 있는 장을 제공하는 플랫폼.

2-2. 주요 기능

Issues: 해야 할 작업, 버그, 논의 기록

Labels: 이슈 분류

Milestones: 일정과 목표 관리

Projects: 작업 흐름 정리(칸반, 일정 관리)

Pull Requests: 코드 변경 제안, 리뷰, 병합

Wiki: 문서 저장 공간

Actions: 자동화(CI/CD)

Releases: 소프트웨어 버전 배포

2-3. 협업 기본 흐름

GitHub에서 원격 저장소 생성

팀원 초대 및 권한 설정

각자 브랜치로 기능 개발

작업 완료 후 Pull Request

리뷰와 토의

승인 후 병합

Issue, Project, Wiki를 활용하여 지속적 관리

3. Git과 GitHub의 관계
구분	Git	GitHub
성격	버전관리 도구	Git 저장소 플랫폼
위치	로컬 환경	온라인 환경
핵심기능	버전관리, 브랜치, 병합	협업, 리뷰, 문서, 일정
의존성	독립 실행 가능	Git을 기반으로 운영
4. Git 기본 사용 흐름

디렉터리 초기화: git init

변경사항 스테이징: git add .

버전 생성: git commit -m "메시지"

원격 저장소 등록: git remote add origin URL

코드 업로드: git push

최신 코드 내려받기: git pull
