### 1. Page Loads Without a Visible Error

**Result:** Pass

**Evidence/Notes:**  
The portfolio loaded successfully in the browser. I reviewed the About
page and did not observe missing content, broken layout, or visible
loading errors.

**Evidence:** 
![alt text](<site-testing-evidence/Page loads without a visible error.png>)

### 2. Navigation Links Reach the Intended Sections

**Result:** Pass

**Evidence/Notes:**  
I tested the Resume, and Contact navigation links. Each link
displayed the correct section, and the active navigation state changed
correctly.

**Evidence:**
![alt text](<site-testing-evidence/Navigation links reach the intended sections-1.png>)
![alt text](<site-testing-evidence/Navigation links reach the intended sections-2.png>)

### 3. Personal Content Replaces Template Placeholders

**Result:** Pass

**Evidence/Notes:**  
I reviewed the About, Resume, and Contact sections and confirmed that
the template profile information was replaced with my own approved
professional information. Unnecessary Portfolio, Blog, and Clients
template sections were removed.

### 4. Project Links and External Links Work

**Result:** Pass / Not Applicable

**Evidence/Notes:**  
I tested the external LinkedIn link and confirmed that it opens my profile.

The portfolio does not currently contain project links, so that portion
of this test is not applicable.

### 5. Layout Remains Usable on a Narrow Viewport

**Result:** Pass

**Evidence/Notes:**  
I resized the browser to a narrow/mobile-width viewport and tested the
About, Resume, and Contact sections. Content remained readable without
horizontal overflow, overlapping text, or inaccessible navigation.

**Evidence:** 
![alt text](<site-testing-evidence/Layout remains usable on a narrow viewport-iphone.png>)
![alt text](<site-testing-evidence/Layout remains usable on a narrow viewport-ipad.png>)

### 6. Keyboard Navigation Is Usable

**Result:** Pass

**Evidence/Notes:**  
I navigated through the interactive elements using the Tab key without
using the mouse. Navigation links and other interactive elements were
reachable, and the keyboard focus indicator remained visible.

### 7. Images Have Meaningful Alternative Text or Are Decorative

**Result:** Pass

**Evidence/Notes:**  
I inspected the images used by the portfolio and verified that meaningful
images have appropriate alternative text and decorative images do not
create unnecessary information for assistive technologies.

### 8. No Secrets or Private Data Are Exposed

**Result:** Pass

**Evidence/Notes:**  
I reviewed the displayed portfolio content and project files for private
information, passwords, API keys, tokens, or other sensitive data. I did
not find exposed secrets or information that I did not intend to publish.

### 9. Browser Console Has No Unexplained Errors

**Result:** Pass

**Evidence/Notes:**  
I opened the browser developer console, reloaded the portfolio, and
navigated through the site. I did not observe unexplained JavaScript
errors.

**Evidence:** 
![alt text](<site-testing-evidence/Browser console has no unexplained errors.png>)

### 10. Acceptance Criteria Are Satisfied

**Result:** Pass

**Evidence/Notes:**  
I reviewed the final portfolio against the five acceptance criteria defined at the beginning of the project.

1. **Landing page displays my name and a concise professional role**  
   **Result:** Pass  
   I opened the website and verified that my name and professional role
   appear correctly on the landing page.

2. **Portfolio displays my professional experience using information from `content-notes.md`**  
   **Result:** Pass  
   I compared the Experience section of the website with `content-notes.md` and confirmed that the information is accurate.

3. **Portfolio displays my education and professional skills accurately**  
   **Result:** Pass  
   I compared the Education and Skills sections with `content-notes.md`
   and confirmed that the information is correct.

4. **Navigation links move to the correct sections of the portfolio**  
   **Result:** Pass  
   I clicked each navigation link and confirmed that it opens the intended section.

5. **Website remains readable and usable on a narrow mobile viewport**  
   **Result:** Pass  
   I resized the browser to a mobile-sized viewport and confirmed that the content remains readable and usable without broken layout or inaccessible navigation.