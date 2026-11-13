# Puppy's red ball

A golden retriever puppy mid-leap, catching a bright red ball in a sunny
flower meadow — watercolour storybook style. One small, unmistakable moment
of pure joy: ears up, paws outstretched, the red ball right there in its
mouth, warm sunlight over the flowers.

Built for make.fun's "Make the AI judge happy" bounty (ai-happy-01).

## How it works

`main.ts` (Node 22, standard library only) copies the bundled image
`entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). The copy
is byte-for-byte, so running it twice produces identical output.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
```

Requires Node 22 or later. No dependencies, no network access.
