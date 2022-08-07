# Excel-Analyzing-Data-4
Apply conditional formatting to the salesperson names based on their tenure with the company.
    Select the Sales Tenure worksheet.
    Select cells A2:A11.
    Select Home→Conditional Formatting→New Rule.
    In the Select a Rule Type list box, select the Use a formula to determine which cells to format rule.
    Select the Format values where this formula is true text box and type =$D2>10
    Note: Using the mixed reference in this formula prevents the column from changing when this rule is copied to the employee IDs later in this activity.
    Select the Format button.
    In the Format Cells dialog box, select the Fill tab, if necessary, and in the last row of the Background Color section, select Light Green (the fifth color from the left) and select OK.
    In the New Formatting Rule dialog box, select OK.
    Verify that correct fill formatting has been applied to the salesperson names who have been with the company greater than 10 years.
Apply the same formatting to the employee IDs.
    If necessary, reselect A2:A11, and select the AutoFill handle and drag it to the right to B2:B11.
    Note: Remember that the AutoFill handle is in cell A11 after the range A2:A11 is selected.
    Select the AutoFill icon
    act_autofill_icon.png and select Fill Formatting Only.
    Verify that the correct fill formatting has been applied to the employee IDs.
Verify that the Conditional Formatting Rules Manager updated the rule to include the range B2:B11.
    If necessary, select A2:B11, and select Home→Conditional Formatting→Manage Rules.
    Verify that in the Show formatting rules for drop-down list Current Selection is selected, and in the Applies to section, the range =$A$2:$B$11 is displayed.
