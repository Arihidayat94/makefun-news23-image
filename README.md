# Sum up 23 November's world news in one image

Entry for the make.fun bounty "Sum up 23 November's world news in one image"
($100, ends 25 November 2026).

The program copies the front-page image `entry.png` to the output directory
as `entry.png`. The image is a newspaper front page for Monday 23 November
2026: the COP31 climate summit collapses with no deal, Ukraine sinks a
Russian warship off Benghazi, Jensen Huang returns as Nvidia chief, three
more ships are struck in the Strait of Hormuz, and Russian missiles crash
inside Poland.

## Run

```sh
node main.ts
```

Outside the grader, `MAKEFUN_OUTPUT_DIR` stands in for `/output`:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see LICENSE.
