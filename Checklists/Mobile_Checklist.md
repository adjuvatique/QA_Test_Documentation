# 1. Summary Tab
| Field          | Value          |
|----------------|----------------|
| Project Name   | [Rapid_Devs_Test]     |
| Version        | 1.2.3          |
| QA Owner       | [Alex_B]    |
| Last Updated    | 2024-06-20     |
| Coverage       | 85% (Core Features) |

# 2. Test Matrix (Main Tab)
| ID  | Test Scenario          | Test Type   | Android (v13) | iOS (v17) | Status | Notes                     |
|-----|------------------------|-------------|----------------|-----------|--------|---------------------------|
| M1  | App Install/Update     | Installation| ✅ Pass        | ✅ Pass   | Done   |                           |
| M2  | Login (Biometric)      | Functional  | ✅ Pass        | ❌ Fail   | Blocked| Face ID not working       |
| M3  | Offline Mode           | Performance | ⚠️ Retest      | ✅ Pass   | Pending| Memory leak on Android    |
| ... | ...                    | ...         | ...            | ...       | ...    | ...                       |

# 3. Device Coverage
| Device Model   | OS Version | Screen Size | Tested By | Date       |
|----------------|------------|-------------|-----------|------------|
| Pixel 7 Pro    | Android 14 | 6.7"       | [A_B]     | 2024-06-15 |
| iPhone 15      | iOS 17.5   | 6.1"       | [A_B]     | 2024-06-16 |

# 4. Key Metrics
| Metric            | Target   | Actual   |
|-------------------|----------|----------|
| Crash Rate        | <0.1%    | 0.05%    |
| ANR Rate          | <0.5%    | 0.2%     |
| Cold Start Time   | <1.5s    | 1.2s     |
