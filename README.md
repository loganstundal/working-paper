# working-paper
A quarto template to quickly set up a new working paper directory.

To use run the following from shell:

```sh
mkdir ~/Documents/new-paper-dir
cd ~/Documents/new-paper-dir
quarto use template loganstundal/working-paper
quarto render --to pdf
```

To produce the paper edit the associated numbered quarto documents (05-abstract, 10-introduction, ...).
