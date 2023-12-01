To reproduce the problem, run the following with Node.js `18.18.2` (works) and `18.19.0` (fails):

```shell
npm install
npx ts-node main.ts
```

The setup is also available as GitHub workflows:

https://github.com/mlenkeit/ts-node-repro/actions/workflows/repro.yml