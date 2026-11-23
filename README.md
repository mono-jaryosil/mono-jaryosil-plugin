# 모노 자료실 Claude 플러그인

모노커뮤니케이션즈 직원이 Claude(Desktop·웹·Claude Code)에서 모노 자료실을 쓸 때 함께 설치하는 플러그인 목록입니다.

## 설치 (직원 1회)

1. Claude 왼쪽 사이드바 **Plugins** → 오른쪽 위 **Add** → **Add marketplace** → **Add from a repository**
2. 이 저장소 주소를 붙여 넣고 추가
3. 목록에서 **모노 자료실 사용 규칙**을 설치하고, 마켓플레이스의 **Sync automatically**를 켭니다

## 들어 있는 것

| 플러그인 | 내용 |
|---|---|
| mono-jaryosil-rules | 모노 자료실 도구를 쓴 요청마다 작업 기록(하는 일·부탁·한 일·결과·답)을 사내 모노 자료실 서버에 남기는 회사 방침. Claude에게 지시문만 더하며 프로그램은 실행하지 않습니다 |

## 고칠 때

- 규칙 글은 `plugins/mono-jaryosil-rules/skills/mono-jaryosil-work-note/SKILL.md`
- 고칠 때마다 `plugins/mono-jaryosil-rules/.claude-plugin/plugin.json`의 `version`을 올립니다
- 직원에게 나가기 전에 시험 계정에서 먼저 확인합니다
