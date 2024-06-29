# Choropleth Map Project

This project is a choropleth map that visualizes the educational attainment in the United States. It is built using HTML, CSS, JavaScript, D3.js, and jQuery. The map displays the percentage of adults age 25 and older with a bachelor's degree or higher for each county in the US.

## Live Demo

You can view the live demo of this project [here](https://stackblitz.com/edit/stackblitz-starters-fr8byy?file=README.md).

## User Stories

The project fulfills the following user stories:

1. My choropleth should have a title with a corresponding id="title".
2. My choropleth should have a description element with a corresponding id="description".
3. My choropleth should have counties with a corresponding class="county" that represent the data.
4. There should be at least 4 different fill colors used for the counties.
5. My counties should each have `data-fips` and `data-education` properties containing their corresponding fips and education values.
6. My choropleth should have a county for each provided data point.
7. The counties should have `data-fips` and `data-education` values that match the sample data.
8. My choropleth should have a legend with a corresponding id="legend".
9. There should be at least 4 different fill colors used for the legend.
10. I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
11. My tooltip should have a `data-education` property that corresponds to the `data-education` of the active area.

## Dataset

- **US Education Data**: [for_user_education.json](https://cdn.freecodecamp.org/testable-projects-fcc/data/choropleth_map/for_user_education.json)
- **US County Data**: [counties.json](https://cdn.freecodecamp.org/testable-projects-fcc/data/choropleth_map/counties.json)

## Technologies Used

- HTML
- CSS
- JavaScript
- D3.js
- jQuery

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/choropleth-map-project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd choropleth-map-project
   ```
3. Open `index.html` in your browser.

## Project Structure

- `index.html`: The main HTML file.
- `style.css`: The CSS file for styling.
- `script.js`: The JavaScript file containing D3.js and jQuery code.
- `README.md`: This file.

## Acknowledgments

- FreeCodeCamp for providing the project idea and datasets.
- D3.js community for the amazing data visualization library.

## Credits

- AJ Javadi
- **Contact Me:**
  - amirjavadi25@gmail.com
  - github.com/oshkoshbagoshh

## License

This project is licensed under the MIT License.
