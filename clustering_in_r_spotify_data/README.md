# Clustering in R

An example of clustering in R using a Spotify data set covering the following topics:
- EDA
- Internal validation
- External validation
- Interpretation of clustering results

Read the rendered HTML report [here](https://htmlpreview.github.io/?https://github.com/endaflynn198/r-resources/blob/main/clustering_in_r_spotify_data/clustering.html).

- Note: GitHub's HTML preview does not render the Latex equations correctly. To view the report correctly, you can clone the repository and open the HTML file in a browser.

You can also run the analysis yourself by cloning the repository and running the `clustering.qmd` file.

## Project Structure
```
📦clustering_in_r_spotify_data
 ┣ 📂clustering_files
 ┃ ┣ 📂various files required for rendering HTML report
 ┣ 📂data
 ┃ ┗ 📜data_spotify_songs.rda
 ┣ 📜clustering.html
 ┣ 📜clustering.qmd 
 ┗ 📜README.md
```

# Quarto
The analysis is written in Quarto, and demonstrates some of the functionality it provides which allows for more aesthetically pleasing and interactive reports. These include:
- Code options (e.g. `echo`, `eval`, `results`)
- Code folding
- Floating table of contents
- Tabsets for code and output