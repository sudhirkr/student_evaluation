# FINAL CONSOLIDATED EVALUATION REPORT (PHASE 3)

## 1. Evaluation Summary
This report concludes the rigorous 3-phase evaluation of 10 student projects.
- **Phase 1**: Code Audit & Planning.
- **Phase 2**: Initial Execution & Deployment Check.
- **Phase 3**: Complex Retesting & Strict Deployment Verification.

### Top Performers
1. **Text Extraction**: **10/10**. Flawless deployment, robust complex PDF handling.
2. **File Ingestion**: **10/10**. Perfect recursion and type spoofing detection.
3. **Pothole Detection**: **9.5/10**. Excellent CV implementation, bonus for high complexity.
4. **Voice Interview**: **8.5/10**. Solid Web App, adjusted for medium complexity.

### Critical Failures & Adjustments
1. **Presidio PII Detection**: **2.5 -> 4.0**. Deployment Failed (404), but High Complexity code earned a bonus.
2. **AI Interview Companion**: **6.0 -> 6.5**. Missing AI Chat on live site, but backend complexity earned a small bonus.
3. **Resume Screening**: **5.5 -> 4.5**. **Deceptive "Fake AI"** + Low Complexity resulted in a penalty.

## 2. Final Scoreboard (Normalized by Complexity)

The **Normalized Score** balances the raw Phase 3 score (heavy on deployment) with the **Technical Complexity** of the codebase. High-complexity projects (CV, NLP, Recursion) receive a "Difficulty Bonus," while low-complexity wrappers are adjusted to reflect their simpler scope.

| Project Name | Complexity | Raw Score | **Normalized Score** | Rationale |
| :--- | :---: | :---: | :---: | :--- |
| **Text Extraction** | High | 10.0 | **10.0** | Perfect Execution of High Complexity (OCR + PDF Parsing). |
| **File Ingestion** | High | 10.0 | **10.0** | Complex Recursion & Magic Byte logic perfectly implemented. |
| **Pothole Detection** | High | 9.0 | **9.5** | **+0.5 Bonus**. Computer Vision (YOLO) is technically demanding and works well. |
| **Voice Interview** | Medium | 9.0 | **8.5** | **-0.5 Adj**. Solid Standard Web App, but less complex than CV/NLP. |
| **AI Video Generator** | Medium | 7.5 | **7.5** | **Neutral**. API orchestration is standard difficulty. |
| **AI Blog Generator** | Low | 7.0 | **6.5** | **-0.5 Adj**. Simple prompt wrapper. Good execution, low difficulty. |
| **AI Interview Companion** | Med-High | 6.0 | **6.5** | **+0.5 Bonus**. Complex state management attempted, despite missing UI. |
| **Adaptive Screening** | Low | 6.0 | **5.5** | **-0.5 Adj**. Basic logic looping, lacks advanced complexity. |
| **Resume Screening** | Low | 5.5 | **4.5** | **-1.0 Penalty**. Fake AI + Low Complexity (Simple Regex/Strings). |
| **Presidio PII** | High | 2.5 | **4.0** | **+1.5 Bonus**. Excellent local NLP code (Custom NER) deserves credit despite 404. |
| **Redaction II** | Med-High | 3.0 | **4.0** | **+1.0 Bonus**. Strong local logic (CV/PDF) partially redeems missing deploy. |
| **GitHub Plagiarism** | Med-High | 2.5 | **3.5** | **+1.0 Bonus**. Algorithmic complexity (Diffs) acknowledged. |

## 3. detailed Phase 3 Findings
Please refer to individual reports within this directory (`Final_Evaluation_Reports`) for logs and reproduction details.
