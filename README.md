# Next infinite re-render

- See [`index.tsx`](https://github.com/rbalicki2/next-infinite-render/blob/main/src/pages/index.tsx), where we throw a rejected promise
- console output

```
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
render home
# etc
```

# Installation

Next was originally set up with:

```
npx create-next-app@latest . \
  --ts --eslint --no-app --src-dir \
  --no-tailwind --import-alias "@/*"
```

also, corepack was disabled.
