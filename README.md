# unhcRverse.r-universe.dev

More on R Universe here: [What is R-universe and why is it useful?](https://jeroen.github.io/runiverse2021/#55).

See also [R-universe is for everyone !](https://jeroen.github.io/runiverse2021)

A list of packages related to UNHCR Work! 

unhcRverse R packages = https://unhcRverse.r-universe.dev/builds


```{r}
#Enable this universe
options(repos = c(
    unhcrverse = 'https://unhcrverse-universe.dev',
    CRAN = 'https://cloud.r-project.org'))
# Install some packages
install.packages('unhcrverse')

```