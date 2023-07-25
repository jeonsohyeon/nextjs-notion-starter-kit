# 소개

> nextjs-notion-starter-kit 를 사용해 만든 노션 포트폴리오 사이트입니다.

라이브 데모 [portfoli-jsh.vercel.app](https://portfolio-jsh.vercel.app)

- Deployed from the `blog` branch

[![Build Status](https://github.com/jeonsohyeon/nextjs-notion-starter-kit/actions/workflows/build.yml/badge.svg)](https://github.com/jeonsohyeon/nextjs-notion-starter-kit/actions/workflows/build.yml) [![Prettier Code Formatting](https://img.shields.io/badge/code_style-prettier-brightgreen.svg)](https://prettier.io)

## 사용된 기술

[react-notion-x](https://github.com/NotionX/react-notion-x)
[Next.js](https://nextjs.org/)
[Vercel](https://vercel.com)

## Features

## 설치

This project requires a recent version of Node.js (we recommend >= 16).

1. Fork / clone this repo
2. Change a few values in [site.config.ts](./site.config.ts)
3. `npm install`
4. `npm run dev` to test locally
5. `npm run deploy` to deploy to vercel 💪

`rootNotionPageId` 에 **public** 상태의 노션 페이지 아이디를 넣습니다.

## 스타일

기본으로 제공하는 스타일에 antd 라는 UI 라이브러리를 추가했습니다.

[antd](https://github.com/ant-design/ant-design)
