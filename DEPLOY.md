# Vercel 배포

이 저장소의 `docs/` 가 https://myutils-mac.vercel.app 로 배포됩니다 (설정: vercel.json).

- GitHub 연동이 되어 있으면 main 에 푸시할 때 Vercel 이 자동으로 배포합니다.
  2026-09-17 저장소를 naggingmachine 계정으로 옮기면서 연동이 끊겼습니다. Vercel 대시보드 →
  프로젝트 myutils-mac → Settings → Git 에서 이 저장소를 다시 연결하면 자동 배포가 살아납니다.
- 연동이 없어도 소스 저장소의 `scripts/sync-site.sh <버전>` 이 푸시 뒤 `vercel deploy --prod` 로 배포합니다
  (이 클론에서 `vercel link --project myutils-mac` 을 한 번 해 두어야 합니다).
