# React Three.js Mind Map

Three.js를 사용하여 구현한 3D 마인드맵 데모 프로젝트입니다.

## 기능

- 3D 공간에서 마인드맵 노드 표시
- 노드 간 연결선 표시
- 다양한 색상의 노드 스타일링
- 마우스를 통한 3D 공간 탐색

## 기술 스택

- React
- TypeScript
- Three.js
- React Three Fiber
- Vite

## 시작하기

### 필수 조건

- Node.js 18.0.0 이상
- npm 9.0.0 이상

### 설치

```bash
# 저장소 클론
git clone https://github.com/yoophi/react-threejs-mindmap.git

# 프로젝트 디렉토리로 이동
cd react-threejs-mindmap

# 의존성 설치
npm install
```

### 개발 서버 실행

```bash
npm run dev
```

이제 브라우저에서 `http://localhost:5173`로 접속하여 애플리케이션을 확인할 수 있습니다.

## 라이선스

MIT License

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
