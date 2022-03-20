# Data Visualization Using Seaborn

*Seaborn* is a Python data visualization library based on Matplotlib. In this project, I explore Seaborn. I discuss Seaborn API overview, its functionality, setting Seaborn aesthetic parameters and colour palette. I discuss different distributions, various plot types and multi-plot grids with seaborn.  

## Types of plots:

1. Relational plots
A) relplot - Figure-level interface for drawing relational plots onto a FacetGrid.

B) scatterplot - Draw a scatter plot with possibility of several semantic groupings.

C) lineplot - Draw a line plot with possibility of several semantic groupings.

2. Distribution plots

A) displot - Figure-level interface for drawing distribution plots onto a FacetGrid.

B) histplot - Plot univariate or bivariate histograms to show distributions of datasets.

C) kdeplot - Plot univariate or bivariate distributions using kernel density estimation.

D) ecdfplot - Plot empirical cumulative distribution functions.

E) rugplot - Plot marginal distributions by drawing ticks along the x and y axes.

F) distplot - DEPRECATED: Flexibly plot a univariate distribution of observations.

3. Categorical plots
A) catplot - Figure-level interface for drawing categorical plots onto a FacetGrid.

B) stripplot - Draw a scatterplot where one variable is categorical.

C) swarmplot - Draw a categorical scatterplot with non-overlapping points.

D) boxplot - Draw a box plot to show distributions with respect to categories.

E) violinplot - Draw a combination of boxplot and kernel density estimate.

F) boxenplot - Draw an enhanced box plot for larger datasets.

G) pointplot - Show point estimates and confidence intervals using scatter plot glyphs.

H) barplot - Show point estimates and confidence intervals as rectangular bars.

I) countplot - Show the counts of observations in each categorical bin using bars.

4. Regression plots
A) lmplot - Plot data and regression model fits across a FacetGrid.

B) regplot - Plot data and a linear regression model fit.

C) residplot - Plot the residuals of a linear regression.

5. Matrix plots
A) heatmap - Plot rectangular data as a color-encoded matrix.

B) clustermap - Plot a matrix dataset as a hierarchically-clustered heatmap.

6. Multi-plot grids

6.1. Facet grids

A) FacetGrid - Multi-plot grid for plotting conditional relationships.

6.2. Pair grids

A) pairplot - Plot pairwise relationships in a dataset.

B) PairGrid - Subplot grid for plotting pairwise relationships in a dataset.

6.3. Joint grids
A) jointplot - Draw a plot of two variables with bivariate and univariate graphs.

B) JointGrid - Grid for drawing a bivariate plot with marginal univariate plots.

7. Themeing
A) set_theme - Set aspects of the visual theme for all matplotlib and seaborn plots.

B) axes_style - Get the parameters that control the general style of the plots.

C) set_style - Set the parameters that control the general style of the plots.

D) plotting_context - Get the parameters that control the scaling of plot elements.

E) set_context - Set the parameters that control the scaling of plot elements.

F) set_color_codes - Change how matplotlib color shorthands are interpreted.

G) reset_defaults - Restore all RC params to default settings.

H) reset_orig - Restore all RC params to original settings (respects custom rc).

I) set - Alias for set_theme(), which is the preferred interface.

8. Color palettes
A) set_palette - Set the matplotlib color cycle using a seaborn palette.

B) color_palette - Return a list of colors or continuous colormap defining a palette.

C) husl_palette - Get a set of evenly spaced colors in HUSL hue space.

D) hls_palette - Get a set of evenly spaced colors in HLS hue space.

E) cubehelix_palette - Make a sequential palette from the cubehelix system.

F) dark_palette - Make a sequential palette that blends from dark to color.

H) light_palette - Make a sequential palette that blends from light to color.

I) diverging_palette - Make a diverging palette between two HUSL colors.

J) blend_palette - Make a palette that blends between a list of colors.

K) xkcd_palette - Make a palette with color names from the xkcd color survey.

L) crayon_palette - Make a palette with color names from Crayola crayons.

M) mpl_palette - Return discrete colors from a matplotlib palette.

10. Palette widgets
A) choose_colorbrewer_palette - Select a palette from the ColorBrewer set.

B) choose_cubehelix_palette - Launch an interactive widget to create a sequential cubehelix palette.

C) choose_light_palette - Launch an interactive widget to create a light sequential palette.

D) choose_dark_palette - Launch an interactive widget to create a dark sequential palette.

E) choose_diverging_palette - Launch an interactive widget to choose a diverging color palette.


## 37. Summary

I offer a high-level overview of Seaborn and related plots in this project.

Seaborn is discussed and compared to Matplotlib. I give an overview of the Seaborn API and explore its features. I go over how to set a plot's aesthetic parameters as well as color schemes.

Then I go over different types of Seaborn plots. I use the distplot() function to plot a univariate distribution. The histogram and kernel density estimation plots are next discussed. I use the jointplot() method to plot bivariate distributions and discuss the Seaborn scatter draw.

I use the pairplot() function to illustrate pairwise relationships. Then I use a Seaborn strip plot and a swarm plot to visualize categorical data. I use a Seaborn box plot and a violin plot to visualize the distribution of observations. The statistical estimations are measured using the Seaborn bar and point plots.

I use the Seaborn reg plot and lm plot to display the linear relationships between variables. I use the Seaborn resid plot to visualize the residuals. Seaborn's heat map and cluster map are discussed. Then I talk with Seaborn about multi-plot grids. Facet grid, pair grid, and joint grid are all discussed.

===============================================================================

## 38. References

The Seaborn plots and galleries in this project are taken from the following websites:-

1.	Seaborn official documentation (https://seaborn.pydata.org/)

2.  Seaborn API Reference (https://seaborn.pydata.org/api.html)







