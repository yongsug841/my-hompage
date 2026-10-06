# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 프로젝트 개요

비즈니스/회사 소개용 홈페이지 프로젝트. Next.js 기반으로 제작하며 Vercel을 통해 배포한다.

## 기술 스택

- **Framework**: Next.js (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Deployment**: Vercel

## 주요 명령어

```bash
# 패키지 설치
npm install

# 개발 서버 실행 (http://localhost:3000)
npm run dev

# 프로덕션 빌드
npm run build

# 빌드 결과 실행
npm run start

# 린트 검사
npm run lint
```

## 프로젝트 구조 (예정)

```
my-hompage/
├── app/                # Next.js App Router 페이지
│   ├── layout.tsx      # 루트 레이아웃
│   └── page.tsx        # 메인 페이지
├── components/         # 재사용 가능한 UI 컴포넌트
├── public/             # 정적 파일 (이미지 등)
└── CLAUDE.md
```

## SEO 및 배포

- 네이버/구글 검색 등록을 위해 `metadata` 설정 필수 (`app/layout.tsx`)
- 사이트맵은 `app/sitemap.ts`로 자동 생성
- Vercel 배포 후 도메인 연결 및 검색엔진 등록 진행
