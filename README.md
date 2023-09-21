# TypeScript

This repo includes all my projects while I am learning TypeScript.

> [!NOTE]
> All of my projects I applied while learning the TypeScript course .

# Setup

We'll eventually be installing TypeScript in individual project, but just to get up and running in simple environment, we're going to install TypeScript globally on our machine with the following command :

```cmd
npm i -g typescript
```

That should't take more than a few seconds. When it's done, run the following command :

```cmd
tsc -v
```

And you should get a version number as the output.

With that work done, let's create some files! Move into your `lectures` directory and create a `first-typescript` directory with a `javascript.js` file and a `typescript.js` file inside. Open it in VS Code.

```cmd
mkdir first-typescript
cd first-typescript
touch javascript.js
touch typescript.js
code .
```

Note the `.ts` file extension on the `typescript.ts` file - we'll see other typescript file extensions down the road, but this is the most common.

> [!IMPORTANT]
> We typically won't create JavaScript files in our TypeScript projects (even though it's totally valid to); we're just doing so here to enable us to compare JavaScript vs. TypeScript behavior in VS Code.

| No  | Lecture                                                                                                 |
| :-- | :------------------------------------------------------------------------------------------------------ |
| 0   | [First-TypeScript](https://github.com/hishamk1999/TypeScript-self-learning/tree/main/first-typescript). |

## License

MIT

**Free Software, Hell Yeah!**
