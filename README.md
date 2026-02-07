# student_evaluation

This repository contains tools and reports for evaluating student performance and handling sensitive data redaction.

## Project Structure

- `file-level-redaction/`: Contains artifacts related to deep dive reports and file-level redaction testing.
  - `deep_dive_report.md`: Detailed analysis of evaluation results.
  - `test_data/`: Sample files (PDF, Word, Excel, Images) used for testing redaction capabilities.
  - `verification_results/`: Redacted output files for verification.

## Getting Started

To run the verification tests, ensure you have the necessary dependencies installed for document processing and image analysis.

## Evaluation Workflow

1. Data Collection: Gathering student evaluation records.
2. Redaction: Applying automated redaction to protect sensitive information across various file formats.
3. Verification: Manually or automatically verifying the correctness of the redacted output.
4. Reporting: Generating deep dive reports based on the verified data.
