## Flask Application Design

### HTML Files

- **index.html**:
   - Main HTML file for the application.
   - Contains the form for selecting start and end dates and a container for displaying the retrieved data.

### Routes

- **root**:
   - Home page of the application.
   - Renders the index.html file.

- **get_data**:
   - Accepts start and end date parameters from the index.html form.
   - Queries the database to retrieve data within the specified date range.
   - Renders the index.html file with the retrieved data displayed in the container.