# EcoDispose Testing Log

## Overview

This document records the testing carried out on the EcoDispose system. It includes both successful tests and errors encountered during development, along with the corrective actions taken.

---

## Test Results

### Test 1: Privacy Policy Display
- **Date:** 28/05/26  
- **Test:** Print privacy policy to the user  
- **Expected Result:** Privacy policy displays correctly without syntax or spelling errors  
- **Actual Result:** As expected  
- **Status:** ✅ Pass  
- **Fix Required:** None  

---

### Test 2: Function Indentation Error
- **Date:** 28/05/26  
- **Test:** Launching and testing the program  
- **Expected Result:** Program runs correctly  
- **Actual Result:** Indentation error occurred  
- **Status:** ❌ Fail  
- **Fix Required:** All code inside functions must be indented correctly  

---

### Test 3: User Input Error
- **Date:** 28/05/26  
- **Test:** Testing user input for device serial number  
- **Expected Result:** User can input serial number  
- **Actual Result:** Syntax error due to missing commas  
- **Status:** ❌ Fail  
- **Fix Required:** Add missing commas in dictionary  

---

### Test 4: Colon Syntax Error
- **Date:** 28/05/26  
- **Test:** Running the program  
- **Expected Result:** Program runs without syntax errors  
- **Actual Result:** Error caused by incorrect use of colon after `device.append(device):`  
- **Status:** ❌ Fail  
- **Fix Required:** Remove colon (colons are only used to start blocks like if/for/functions)  

---

### Test 5: View Devices Function Error
- **Date:** 28/05/26  
- **Test:** Viewing devices after input  
- **Expected Result:** Device list displays correctly  
- **Actual Result:** Failed due to spelling mistake  
- **Status:** ❌ Fail  
- **Fix Required:** Correct typo in code  

---

### Test 6: View Devices Success
- **Date:** 28/05/26  
- **Test:** Viewing stored devices  
- **Expected Result:** Devices previously added are displayed  
- **Actual Result:** As expected  
- **Status:** ✅ Pass  
- **Fix Required:** None  

---

### Test 7: Waste Classification Function
- **Date:** 28/05/26  
- **Test:** Selecting waste classification  
- **Expected Result:** Menu shows Reuse, Recycle, Dispose options  
- **Actual Result:** As expected  
- **Status:** ✅ Pass  
- **Fix Required:** None  

---

### Test 8: Invalid Device ID Handling
- **Date:** 28/05/26  
- **Test:** Entering an invalid device ID  
- **Expected Result:** Error message "Device not found"  
- **Actual Result:** As expected  
- **Status:** ✅ Pass  
- **Fix Required:** None  

---

## Conclusion

The testing process identified several syntax and logic errors during development, including indentation issues, missing commas, and incorrect use of colons. These were corrected, resulting in a fully functional system. Final testing confirmed that all core features operate as expected.
