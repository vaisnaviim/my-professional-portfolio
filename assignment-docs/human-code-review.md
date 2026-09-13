# Inspect, Test, and Review

## Code Review

### 1. `index.html` – Profile and Resume Content

**What the AI changed:**  

The AI replaced generic template content with professional information from`content-notes.md`. It also reorganized sections of the portfolio to better match the information available in my notes.

**What I verified:**  

I compared the website content with `content-notes.md` and checked my
professional information, experience, education, skills, activities, and
awards for accuracy. I also checked for remaining template content or
information that was not supported by my notes.

**Changes made after review:**  

The main information was accurate, but I found several organizational and
content-presentation issues. I changed Professional Focus to Professional
Interests with content that better represents my interests. I also moved
Professional Activities and Awards & Recognition from the Contact section
to the Resume section and updated the section icons to better represent
the content.


### 2. `index.html` and `assets/js/script.js` – Navigation and Sections

**What the AI changed:**  

The AI removed unused template sections, including Portfolio and Blog, and updated the remaining navigation and section structure.

**What I verified:**  

I tested the About, Resume, and Contact navigation links and checked that
each one displayed the correct section. I also checked that removing unused template sections did not leave unnecessary navigation items or broken page behavior.

**Changes made after review:**  

After the Phase 2 changes, the Resume and Contact links stopped working. I detected this during testing and had the navigation corrected before
committing the changes. I tested the links again after the correction to
confirm that they worked properly.


### 3. `assets/css/style.css` – Styling, Responsiveness, and Accessibility

**What the AI changed:**  

The AI personalized the site's styling using my Olive Garden Feast color
palette: Olive Leaf, Black Forest, Cornsilk, Light Caramel, and Copper. It also made changes intended to improve readability, keyboard focus visibility, and responsive presentation.

**What I verified:**  

I reviewed the website on desktop and at narrower screen sizes. I checked
that the new colors were applied consistently, text remained readable,
keyboard focus was visible, and the existing layout continued to function
without obvious overlap or display problems.

**Changes made after review:**  

I accepted the overall color direction and accessibility improvements.
After reviewing the visual presentation, I made additional styling changes to the Contact section to improve spacing, sizing, alignment, and the presentation of the LinkedIn card. I also identified the Skills section and memoji-style images as areas that still need further revision before final testing.


## Additional Findings from My Human Review

Although the website was functional after the initial AI-assisted changes,my review identified several areas that still did not accurately represent the portfolio I wanted to present.


### 1. Professional Interests

The original Professional Focus section did not feel like an accurate
representation of my professional interests.

**Change made after review:**  

I changed Professional Focus to Professional Interests and updated the
section to include Artificial Intelligence, Technology & Innovation,
Cybersecurity, and Learning & Personal Growth. I also replaced the generic template icons with icons that better represent each interest.


### 2. Testimonial

The current testimonial is generic template content rather than an actual
testimonial given about me.

**Decision:**  

Replace the template testimonial with a real testimonial that I have
received and approved for use on the public portfolio.


### 3. Clients Section

The Clients section was part of the original portfolio template and was
not relevant to my professional portfolio.

**Change made after review:**  

I removed the Clients section because it did not contain information
relevant to my professional background.


### 4. Skills Organization

The current Skills section presents the skills as a single list. Although
the information is available, the presentation makes it difficult to
quickly understand the different areas of my experience.

**Decision:**  

Reorganize the existing skills into meaningful categories. Only skills
supported by `content-notes.md` will be used.


### 5. Professional Activities and Awards & Recognition

Professional Activities and Awards & Recognition were displayed on the
Contact page. During my review, I determined that this was not an
appropriate location for this information.

**Change made after review:**  

I moved Professional Activities and Awards & Recognition to the Resume
section. I also updated the Resume section icons for Education, Experience, Professional Activities, and Awards & Recognition to make the sections easier to identify.


### 6. Memoji / Visuals

The current memoji-style images do not match the professional and personal style I want for the portfolio.

**Decision:**  

Replace the existing memoji-style visuals with icons that better match
the professional appearance and personal style of the site.


### 7. Contact Section

During my review, I found that the Contact page contained additional
Location and Focus Areas cards that were unnecessary and made the section
more complicated than needed.

**Change made after review:**  

I simplified the Contact page to focus on my LinkedIn information. I
removed the Location and Focus Areas cards, added a short introduction,
and refined the LinkedIn card layout and styling to make the section
cleaner and more consistent with the rest of the portfolio.


## Human Review Conclusion

The AI-assisted changes provided a functional starting point, but my review showed that functionality alone was not enough to consider the portfolio complete. I identified issues involving content relevance, organization, navigation, accessibility, and personal presentation.

Some of these issues were corrected during the review process, while others were identified for additional revision before final testing. This review helped me verify the AI-generated work rather than accepting the generated changes without inspection.