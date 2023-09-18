# Gibbonacci

Gibbonacci is an idle/incremental game about you getting bunch of monkeys to check numbers
for you to find all that belong to Fibonacci sequence.

Why?

Only you know the answer to that...

**NOTE:** This is a port to WebXDC, check the original Gibbonacci game
[here](https://github.com/MartinTale/gibbonacci)

## Developing

### Installing Dependencies

After cloning this repo, install dependecies:

```
pnpm i
```

### Checking the code format

```
pnpm check
```

### Testing the app in the browser

To test your work in your browser (with hot reloading!) while developing:

```
pnpm dev-mini
# Alternatively to test in a more advanced WebXDC emulator:
pnpm dev
```

### Building

To package the WebXDC file:

```
pnpm build
```

The resulting optimized `.xdc` file is saved in `dist-xdc/` folder.

### Releasing

To automatically build and create a new GitHub release with the `.xdc` file:

```
git tag v1.0.1
git push origin v1.0.1
```

## Credits

Notes from the original project:

> Everything (almost), including art, design, music, sound, and game was created by me - [Martin Tale](https://martintale.com/)
>
> -   Social and GUI icons from respective platforms and https://iconmonstr.com/
> -   Moon, Gorilla and Banana icons by [Delapouite](http://delapouite.com) under CC BY 3.0;
> -   Monkey and Turd icon by [Lorc](http://lorcblog.blogspot.com) under CC BY 3.0;
