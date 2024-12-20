## Data Management and Cleaning Guidelines

### Naming the Data
- Maintain **consistency** in naming datasets. Have Content_Changes_Change; Use "_"rather than blank 
- Use **labels** for datasets.
- Include a **note sheet** in your file to document the data cleaning process.

### Data Considerations
1. **ID**:
   - Avoid using strings (e.g., names) as identifiers.
   - Assign unique IDs wherever possible.
2. **Missing Data**:
   - Document and address missing data systematically.
3. **Units**:
   - Ensure units of measurement are standardized and documented.
4. **Scale**:
   - Pay special attention to scaling, especially for financial data.
   - Consider whether skewed data should be log-transformed or not.

### Lessons
- **Avoid cleaning data directly in Excel**:
  - Changes made in Excel are difficult to track.
  - Use tools like **Stata**, **R**, or **Python** for data cleaning.
  - Write detailed notes to document your code and cleaning steps.
  - Seperate the data cleaning code with regression code 

### Data Storage
- Save a backup copy of your data in a reliable storage service:
  - Dropbox
  - OneDrive
  - Google Drive

### Quality Assurance
- Better have a **second person** review your data cleaning process to ensure accuracy and reliability.
