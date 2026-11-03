# scoop-bucket

[![Tests](https://github.com/jseook11/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/jseook11/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/jseook11/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/jseook11/scoop-bucket/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) bucket for [Nalmeok](https://github.com/jseook11/nalmeok), a desktop app that transcribes lecture audio into Markdown with Gemini.

## 설치 / Install

```pwsh
scoop bucket add nalmeok https://github.com/jseook11/scoop-bucket
scoop install nalmeok/nalmeok
```

시작 메뉴에 **Nalmeok**이 생겨요. 업데이트는 `scoop update nalmeok`, 제거는 `scoop uninstall nalmeok`이에요. 기록과 API 키는 `%APPDATA%\nalmeok`에 있어서 업데이트나 제거 뒤에도 남아요.

A **Nalmeok** shortcut is added to the Start menu. Update with `scoop update nalmeok`, remove with `scoop uninstall nalmeok`. History and API keys live in `%APPDATA%\nalmeok` and are kept.

새 버전은 Nalmeok GitHub 릴리스가 나오면 몇 시간 안에 자동으로 반영돼요.
