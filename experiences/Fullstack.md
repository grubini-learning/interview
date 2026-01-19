# Fullstack

## CollaborateMD

At CollaborateMD, I resolved a critical billing accuracy issue where patient payment amounts were displaying incorrect decimal values. I approached this systematically by first investigating the Angular frontend to determine whether the issue stemmed from UI rendering or input validation constraints. After confirming the frontend was functioning correctly, I traced the data flow through the Java backend to identify where the numerical precision was being lost during database retrieval and processing. I discovered the root cause was improper decimal handling in the backend service layer and implemented a DecimalFormat solution to ensure consistent two-decimal precision throughout the application, resolving the discrepancy and maintaining financial accuracy for patient billing.
