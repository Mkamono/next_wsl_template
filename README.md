# Item
Qiita [【備忘録】Next.js開発環境をDockerで構築(WSL2)](https://qiita.com/KMNMKT/items/4837f123b30bcf7003c7)
# Usage
- Open this repository using devcontainer.
- Create your project
    ```bash
    npx create-next-app
    ```
- Copy `next.config.js`
    ```bash
    cp -f my-app/next.config.js {your-project-dir}/next.config.js
    ```
- Start your project
    ```bash
    cd {your-project-dir}
    yarn dev
    ```
- Remove template (Optional)
    ```bash
    cd ..
    rm -rf my-app
    ```
