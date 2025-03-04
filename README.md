# zero
CLI for simple numerical operations using Go and Cobra

Using JetBrains guide [here](https://www.jetbrains.com/guide/go/tutorials/cli-apps-go-cobra/what_is_cli/)

[Go CLI docs](https://go.dev/solutions/clis)

To pass negative numbers as arguments use `--` (otherwise the negative sign is intrepreted as indicating a flag)
```bash
./zero mul -- -5 -3
Multiplication of -5 and -3 = 15.000000.
```