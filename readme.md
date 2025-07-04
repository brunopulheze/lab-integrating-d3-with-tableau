![IronHack_Logo](https://user-images.githubusercontent.com/92721547/180665853-e52e3369-9973-4c1e-8d88-1ecef1eb8e9e.png)

# LAB | D3 Integration with Tableau

## Exercise 1

Using the `UNSPSC Codes dataset`, follow the instructions seen in the lesson to build your first Tableau Extension with D3.js.

**Dataset:** Download from https://catalog.data.gov/dataset/unspsc-codes

> In case the above didnt work, you may try this [Link](https://catalog.data.gov/dataset/unspsc-codes-93778) or use `data-unspsc-codes.csv` in the `dataset` folder. 

**Requirements:**
- Create two worksheets as demonstrated in class
- Set up the hierarchical table view with proper field arrangement
- Apply "Segment Name" filter across all worksheets
- Build a dashboard with both worksheets in the correct order

## Exercise 2

Create your custom D3 Sunburst Extension following the lesson guidelines..!

**Your Extension Must Include:**
- Proper manifest file (.trex) with your own information
- HTML file with clean styling and proper library imports
- JavaScript file with extension logic and D3 sunburst chart
- Interactive filtering between the sunburst chart and Tableau worksheets

**Additional Challenges:**
- Experiment with different D3 color schemes
- Add hover tooltips to display data values
- Implement smooth transitions when filters change
- Style your extension with custom CSS
- Test different hierarchical data arrangements

**Reference:** Explore different sunburst variations and advanced techniques at https://eurostat.github.io/d3.sunburst/

## Exercise 3 (Bonus)

Extend your sunburst chart with additional features:

- Add a legend explaining the hierarchy levels
- Implement zoom functionality for better navigation
- Create a reset button to clear all filters
- Add loading animations while data is being processed

## Technical Requirements

- Set up a local web server (`python -m http.server 8000` or `Node.js http-server`)
- Ensure your extension loads without errors in Tableau Desktop
- Test filter interactions work in both directions
- Validate data displays correctly at all hierarchy levels

## Deliverables

- Your complete extension folder containing:
  - `YourName_Sunburst.trex` manifest file
  - `index.html` main page
  - `script.js` extension logic
  - `lib/` folder with Tableau Extensions API library
- Screenshots of your working extension in Tableau
- Brief documentation explaining any custom features you added

## Submission

Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.

**Note:** Tableau Extensions require Tableau Desktop - they are not supported in Tableau Public.