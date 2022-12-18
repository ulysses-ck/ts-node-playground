# ts-node-playground-boilerplate

 A boilerplate to get started using TypeScript with linting, formatting and building features

## 🔨 Build with:

-   TypeScript
-   Node
-	SWC
-	Prettier
-   Eslint
-   SonarJS
-   ts-node
-   nodemon
-   husky

<!-- Installation -->
## Installation
1. Clone repo and rename directory
```
git clone https://github.com/ulysses-ck/ts-node-playground-boilerplate name-of-your-choice
```
2. Get into directory
```
cd name-of-your-choice
```
3. Install dependencies
```
pnpm install
```
<!-- Scripts -->
## Scripts
```
# generate dist directory with transpiled js
pnpm build

# remove dist directory in windows
pnpm clean-win

# remove dist directory in linux
pnpm clean

# init dev server
pnpm dev

# linting code with eslint
pnpm lint

# format code
pnpm prettier
```

## Eslint and prettier
If some of the rules are conflicting with prettier in formatting, run this command
```
npx eslint-config-prettier /path/to/script.ts
```


<!-- CONTRIBUTING -->

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## ⚠ License

Distributed under the GNU GPLv3 License. See `LICENSE` for more information.