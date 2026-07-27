# AI Formula Generator Prompt Pack

Welcome to the AI Formula Generator Prompt Pack, designed to assist spreadsheet users and developer teams in automating the generation of complex formulas and scripts within popular spreadsheet applications. This pack contains over 20 structured prompts, categorized to guide users in leveraging AI for their spreadsheet tasks efficiently.

## Overview

This prompt pack is ideal for those who want to simplify their work with spreadsheets, whether you are creating basic formulas, automating scripts, or managing data transformations. The prompts are categorized for easy navigation, each focusing on specific tasks to help you achieve your goals quickly and effectively.

## Contents of the Prompt Pack

The AI Formula Generator Prompt Pack includes the following categories of prompts:

- **Basic Formula Generation**: Generate basic formulas like SUM, AVERAGE, and COUNTIF.
  
- **Advanced Formula Techniques**: Utilize nested formulas and dynamic ranges to enhance functionality.

- **Script Automation**: Create scripts for tasks like auto-refreshing data or applying conditional formatting.

- **Data Transformation**: Transpose data and merge information from multiple sheets.

- **Error Handling and Debugging**: Identify and resolve common spreadsheet errors.

- **Optimization and Efficiency**: Improve the performance of formulas and manage spreadsheet size.

- **Data Visualization**: Develop dynamic charts and dashboards to present data effectively.

- **Miscellaneous**: Additional helpful prompts for unique challenges like extracting unique values or automating calendar entries.

## How to Use Each Prompt Category

### Basic Formula Generation
- **Summing Values**: Use prompts to generate formulas for simple summation needs.
- **Average Calculations**: Efficiently calculate averages across specified ranges.
- **Counting Conditions**: Draft COUNTIF formulas to filter and count specific values.

**Example Output**: 
1. "SUM(A1:A10)" 
2. "AVERAGE(B1:B20)" 
3. "COUNTIF(C1:C100, ">50")"

### Advanced Formula Techniques
- **Conditional Aggregation**: Create complex formulas for conditional sums.
- **Dynamic Ranges**: Specify how to handle dynamic data entries.
- **Nested IF Statements**: Categorize data using logical branching.

**Example Output**: 
1. "SUMIF(E:E, 'Completed', D:D)" 
2. "AVERAGE(OFFSET(F1,COUNTA(F:F)-10,0,10,1))" 
3. "IF(A1<100, 'Low', IF(A1<200, 'Medium', 'High'))"

### Script Automation
- **Data Refreshing**: Automate the updating of data, ensuring the latest information is always available.
- **Formatting Scripts**: Apply consistent formatting rules automatically.
  
**Example Output**: 
1. `function refreshData() { SpreadsheetApp.flush(); }`
2. `applyConditionalFormatting(range);`

### Data Transformation
- **Transposing and Merging**: Transform data layouts and consolidate information from various sources to a single sheet.

**Example Output**: 
1. `TRANSPOSE(A1:B10)` 
2. `MERGE({Sheet1!A1:A10, Sheet2!A1:A10}, " ")`

### Error Handling and Debugging
- **Error Detection**: Identify and highlight cells with errors to streamline debugging.
  
**Example Output**: 
1. `=IF(ISERROR(A1),"Error in A1",A1)`

### Optimization and Efficiency
- **Performance Tweaks**: Suggestions to optimize formulas for large datasets to reduce load times.

**Example Output**: 
1. "Consider using INDEX/MATCH instead of VLOOKUP for large datasets."

### Data Visualization
- **Creating Charts**: Use prompts to create dynamic charts that adjust as data changes.

**Example Output**: 
1. `=GETPIVOTDATA(...)` to generate pivot charts.

### Miscellaneous
- **Unique Values**: Extracting unique entries from lists quickly.

**Example Output**: 
1. `UNIQUE(A1:A100)`

## Tips for Best Results

- **Be Specific**: The clearer and more specific the prompt, the more tailored the generated formula or script will be.
- **Test Outputs**: Always verify generated formulas/scripts in a sample spreadsheet before implementation.
- **Explore Variations**: Feel free to modify prompts to fit your unique needs or scenarios.

## Conclusion

Utilize this AI Formula Generator Prompt Pack to maximize your productivity and reduce the complexity of working with spreadsheet formulas and scripts. Each prompt encourages exploration of spreadsheet potential with the aid of AI, streamlining your workflow and efficiency.
