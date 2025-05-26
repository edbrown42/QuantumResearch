## Software Configuration
-Install [Julia](https://julialang.org/downloads/)
-To integrate Julia with Jupyter Notebook, you need to install the Ijulia package
	To do this enter the following Julia commands in the Julia REPL (read-eval-print-loop), this is Julia's full-featured command-line built into Julia executable.
	`using Pkg`
	Then press enter. Then enter the following command
	`Pkg.add("IJulia")`
-For this Spectral Graph Analysis notebook we will need one additional package, before exiting the Julia REPL enter the following command
	`Pkg.add("Laplacians")`
-In VS Code download the [Julia extension](https://marketplace.visualstudio.com/items?itemName=julialang.language-julia)