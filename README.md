# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm init svelte

# create a new project in my-app
npm init svelte my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.




# 열편집 : Column Selection Mode - ALT + SHIFT + DRAG

# svelte sample project 개발 세팅 시작
    0. 참조 동영상 : 
        https://www.youtube.com/watch?v=ydR_M0fw9Xc


    1. 프로젝트 생성 : npm init svelte svelte-movie
    2. 프로젝트 열기 : code .
    3. 모듈 의존성 파일 : C:\job\front-end\svelte\svelte-movie\package.json

        "@sveltejs/adapter-auto": "next",
        "@sveltejs/kit": "next",
        "eslint": "^8.12.0",
        "eslint-config-prettier": "^8.3.0",
        "eslint-plugin-svelte3": "^4.0.0",
        "prettier": "^2.5.1",
        "prettier-plugin-svelte": "^2.5.0",
        "svelte": "^3.44.0"   

    4. 모듈 설치 : npm install


        C:\job\front-end\svelte\svelte-movie>npm install

        > svelte-movie@0.0.1 prepare
        > svelte-kit sync


        up to date, audited 136 packages in 3s

        20 packages are looking for funding
        run `npm fund` for details       

        found 0 vulnerabilities

        C:\job\front-end\svelte\svelte-movie>

    5. 로컬 실행 : npm run dev

        C:\job\front-end\svelte\svelte-movie>npm run dev

        > svelte-movie@0.0.1 dev
        > svelte-kit dev


        SvelteKit v1.0.0-next.330

        network: not exposed
        local:   http://localhost:3000

        Use --host to expose server to other devices on this network

    6. 로컬 실행 크롬 확인 : 
        http://localhost:3000/


    7. 빌드 : npm run build

 
        C:\job\front-end\svelte\svelte-movie>npm run build

        > svelte-movie@0.0.1 build
        > svelte-kit build

        vite v2.9.9 building for production...
        ✓ 13 modules transformed.
        .svelte-kit/output/client/_app/manifest.json                    1.14 KiB
        .svelte-kit/output/client/_app/layout.svelte-25c4188e.js        0.53 KiB / gzip: 0.35 KiB
        .svelte-kit/output/client/_app/error.svelte-5657da7f.js         1.56 KiB / gzip: 0.75 KiB
        .svelte-kit/output/client/_app/pages/index.svelte-05fabf4d.js   0.80 KiB / gzip: 0.47 KiB
        .svelte-kit/output/client/_app/chunks/index-c3650d4a.js         6.84 KiB / gzip: 2.79 KiB
        .svelte-kit/output/client/_app/start-b7a68b43.js                23.13 KiB / gzip: 8.67 KiB
        vite v2.9.9 building SSR bundle for production...
        ✓ 11 modules transformed.
        Generated an empty chunk: "hooks"
        .svelte-kit/output/server/manifest.json                        1.09 KiB
        .svelte-kit/output/server/index.js                             75.58 KiB
        .svelte-kit/output/server/entries/fallbacks/layout.svelte.js   0.24 KiB
        .svelte-kit/output/server/entries/fallbacks/error.svelte.js    0.72 KiB
        .svelte-kit/output/server/entries/pages/index.svelte.js        0.32 KiB
        .svelte-kit/output/server/chunks/index-5f038599.js             2.31 KiB
        .svelte-kit/output/server/chunks/hooks-1c45ba0b.js             0.00 KiB

        Run npm run preview to preview your production build locally.

        > Using @sveltejs/adapter-auto
        Could not detect a supported production environment. See https://kit.svelte.dev/docs/adapters to learn how to configure your app to run on the platform of your choosing
        ✔ done

        C:\job\front-end\svelte\svelte-movie>


    8. 프로젝트 구조 

        C:\job\front-end\svelte\svelte-movie\src\routes\index.svelte



    9. 리포지토리 생성 및 로컬 프로젝트 푸시
        https://github.com/king-garlic/svelte-movie

        echo "# svelte-movie" >> README.md
        git init
        git add README.md
        git commit -m "first commit"
        git branch -M main
        git remote add origin https://github.com/king-garlic/svelte-movie.git
        git push -u origin main





    10. 
    11. 
    12. 
    13. 
    14. 
    15. 
    16. 
    17. 
    18. 
    19. 
    20. 
    21. 
    22. 
    23. 
    24. 
    25. 
    26. 
    27. 
    28. 
    29. 
    "# svelte-movie" 
