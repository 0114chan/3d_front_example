# 3D Front Example
<img width="618" alt="3d" src="https://github.com/user-attachments/assets/2d214041-d1ab-4a4c-a1b1-006c132641f5" />

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/pages/api-reference/create-next-app), featuring a 3D frontend animation built with Three.js and `@react-three/fiber`.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev


## WebGL 기반의 3D 그래픽을 브라우저에 렌더링 -> Three.js
## React와의 통합성을 높이기 위해 @react-three/fiber와 @react-three/drei라는 라이브러리를 활용

## <boxGeometry>와 <meshStandardMaterial>은 Three.js의 기본 객체로, 큐브의 형태와 색상을 정의

## @react-three/fiber : Three.js를 React 컴포넌트처럼 사용할 수 있게 래핑한 라이브러리. <Canvas>와 useFrame 훅
## @react-three/drei ;  @react-three/fiber에 추가적인 편의 기능을 제공하는 헬퍼 라이브러리. <OrbitControls>
## --> 마우스로 3D 객체를 조작할 수 있게 해주는 컨트롤러를 제공





