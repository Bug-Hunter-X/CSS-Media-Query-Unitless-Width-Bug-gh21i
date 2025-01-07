# CSS Media Query Unitless Width Bug

This repository demonstrates a subtle bug in CSS involving unitless values for the `width` property within media queries.  The bug causes unexpected layout behavior, as a unitless value is interpreted as pixels instead of a percentage.  The solution involves explicitly specifying the percentage unit.