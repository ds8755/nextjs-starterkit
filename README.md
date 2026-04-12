# Claude Next.js Starter Kit

빠르게 시작할 수 있는 모던 웹 개발 스타터킷입니다.

## 🚀 기술 스택

- **Next.js 15** - App Router와 Turbopack 지원
- **TypeScript** - 완전한 타입 안정성
- **TailwindCSS v4** - 설정 파일 없이 CSS 기반 커스터마이징
- **shadcn/ui** - 접근성 있는 UI 컴포넌트 라이브러리
- **lucide-react** - 아름다운 SVG 아이콘
- **next-themes** - 다크모드 지원

## 📦 포함된 컴포넌트

- `Button` - 다양한 variant와 size 옵션
- `Card` - 콘텐츠 컨테이너
- `Input` - 폼 입력 필드
- `Badge` - 라벨과 태그
- `Separator` - 시각적 구분선
- `Header` - 상단 네비게이션
- `ThemeToggle` - 다크모드 토글

## 🎯 빠른 시작

### 설치

```bash
npm install
```

### 개발 서버 실행

```bash
npm run dev
```

브라우저에서 [http://localhost:3000](http://localhost:3000)으로 접속하세요.

### 프로덕션 빌드

```bash
npm run build
npm start
```

## 📁 프로젝트 구조

```
claude-nextjs-starterkit/
├── app/                    # Next.js App Router
│   ├── layout.tsx          # 루트 레이아웃
│   ├── page.tsx            # 메인 페이지
│   └── globals.css         # TailwindCSS v4 설정
├── components/
│   ├── ui/                 # shadcn/ui 컴포넌트
│   ├── layout/             # 레이아웃 컴포넌트
│   └── theme-toggle.tsx    # 다크모드 토글
├── lib/
│   └── utils.ts            # 유틸리티 함수
├── hooks/
│   └── use-theme.ts        # 테마 훅
├── public/                 # 정적 파일
├── components.json         # shadcn/ui 설정
├── tsconfig.json           # TypeScript 설정
├── next.config.ts          # Next.js 설정
├── postcss.config.mjs      # PostCSS 설정
└── package.json            # 프로젝트 의존성
```

## 🎨 TailwindCSS v4 CSS-based 설정

이 프로젝트는 TailwindCSS v4의 새로운 CSS-based 설정을 사용합니다:

```css
/* app/globals.css */
@import "tailwindcss";

@theme {
  --color-primary: oklch(0.205 0 0);
  /* ... 더 많은 테마 변수 */
}
```

`tailwind.config.js` 파일이 필요하지 않습니다!

## 🌓 다크모드

`next-themes`를 사용하여 자동으로 다크모드를 지원합니다. 사용자의 시스템 설정을 자동으로 감지합니다.

## 📝 shadcn/ui 컴포넌트 추가

새로운 컴포넌트를 추가하려면 `npx shadcn` CLI를 사용하세요:

```bash
npx shadcn-ui@latest add [component-name]
```

예:

```bash
npx shadcn-ui@latest add dialog
npx shadcn-ui@latest add form
```

## ✨ 주요 특징

- ✅ TypeScript 지원
- ✅ 반응형 디자인
- ✅ 다크모드 지원
- ✅ SEO 최적화 메타데이터
- ✅ 빠른 개발 서버 (Turbopack)
- ✅ ESLint 설정
- ✅ 완전한 타입 안정성

## 🔧 사용 가능한 스크립트

| 스크립트 | 설명 |
|---------|------|
| `npm run dev` | 개발 서버 실행 (Turbopack) |
| `npm run build` | 프로덕션 빌드 |
| `npm start` | 빌드된 앱 실행 |
| `npm run lint` | ESLint 실행 |

## 📚 유용한 링크

- [Next.js 공식 문서](https://nextjs.org)
- [TailwindCSS v4 가이드](https://tailwindcss.com/docs)
- [shadcn/ui 컴포넌트](https://ui.shadcn.com)
- [lucide-react 아이콘](https://lucide.dev)

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 있습니다.
