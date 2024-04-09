---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

## Plot licence expiration counts

<iframe src="bar_plot.html" width="100%" height="500" frameborder="0"></iframe>

**Description**:
This plot visualizes the count of licenses expiring each year, categorized by their status (e.g., Active, Not Renewed). Users can select a specific year using a slider to see the distribution of license statuses for that year.

**Design Choices**:

- **Encoding Types**: The x-axis represents the license statuses, and the y-axis represents the count of licenses. The bars are colored by license status to differentiate between them.
- **Color Scheme**: The color scheme is categorical, with different colors representing different license statuses. This choice was made to easily distinguish between the statuses.

**Data Transformations**:
The 'Expiration Date' column was converted to a datetime format, and a new column 'Expiration Year' was extracted to facilitate filtering by year.

**Interactivity**:
A slider was added to allow users to select a specific year. This interactivity helps users focus on the data for a particular year and makes the visualization more dynamic and informative.

---

## License vs status

<iframe src="licenseVsStatus.html" width="100%" height="500" frameborder="0"></iframe>

**Description**:
This plot shows the count of licenses for each license type, further categorized by their status. Users can select a license type from a dropdown menu to see the distribution of license statuses for that type.

**Design Choices**:

- **Encoding Types**: The x-axis represents the license statuses, and the y-axis represents the count of licenses. The bars are colored by license status to differentiate between them.
- **Color Scheme**: The color scheme is categorical, with different colors representing different license statuses. This choice was made to easily distinguish between the statuses.

**Data Transformations**:
No significant data transformations were performed for this plot.

**Interactivity**:
A dropdown menu was added to allow users to select a specific license type. This interactivity helps users focus on the data for a particular license type and makes the visualization more dynamic and informative.
