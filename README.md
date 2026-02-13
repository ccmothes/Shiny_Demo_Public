# Shiny Tutorial

A practical introduction to building web applications with R Shiny, demonstrating core concepts and interactive features through hands-on examples.

## Overview

This repository provides a tutorial for creating interactive web applications using the Shiny package in R. The tutorial covers fundamental Shiny concepts including UI design, server logic, reactive programming, and building complete interactive data visualizations.

## Repository Structure

```
.
├── data/               # Tutorial data files
│   └── *.RData        # Pre-processed datasets for examples
├── shiny_demo/        # Demo Shiny application files
├── www/               # Web assets (images, CSS, etc.)
├── shiny_demo.Rmd     # R Markdown source for tutorial
└── shiny_demo.md      # Rendered tutorial guide
```

## Getting Started

### Prerequisites

- R (version 4.0+)
- RStudio (recommended)
- Required R packages:
  ```r
  install.packages(c("shiny", "leaflet", "dplyr", "sf"))
  ```

## Tutorial Topics

This tutorial covers:

- **Shiny Basics**: Understanding UI and server components
- **Reactive Programming**: Building responsive applications
- **User Inputs**: Implementing interactive controls
- **Data Visualization**: Creating dynamic plots and outputs
- **Layout Design**: Structuring application interfaces
- **Deployment**: Best practices for sharing your apps

## Learning Path

1. Start with `shiny_demo.md` for conceptual understanding
2. Examine code in the `shiny_demo/` directory
3. Experiment by modifying existing examples
4. Build your own application using provided patterns

## Additional Resources

- [Official Shiny Documentation](https://shiny.rstudio.com/)
- [Shiny Gallery](https://shiny.rstudio.com/gallery/)
- [Mastering Shiny Book](https://mastering-shiny.org/)


## Author

**Dr. Caitlin Mothes**  
Research Scientist, CSU Geospatial Centroid
