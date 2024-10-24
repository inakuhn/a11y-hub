# 🛠️ A11y Project Overview

The A11y project is dedicated to ensuring that applications are accessible to all users, including those with disabilities. This README provides a comprehensive summary of design principles, testing methods, best practices, and essential resources related to accessibility. Contributions from the community are welcome to enhance accessibility across all platforms.

## 📋 Table of Contents

1. [👋 Introduction](#-introduction)
2. [🎨 Design Principles](#-design-principles)
3. [🧪 Testing and Validation](#-testing-and-validation)
4. [💡 Best Practices](#-best-practices)
5. [🔗 Resources](#-resources)
6. [🛠️ Plugins and Tools](#%EF%B8%8F-plugins-and-tools)
7. [🤝 Contributing](#-contributing)

---

## 👋 Introduction

Accessibility (A11y) focuses on designing and developing products that can be used by people of all abilities and disabilities. The goal is to create inclusive applications that provide a seamless experience for everyone.

## 🎨 Design Principles

### Importance of Atomic Design Pattern

Implementing the **Atomic Design Pattern** is key to integrating accessibility at every level of application design. By breaking down the user interface into smaller, reusable components (atoms, molecules, organisms), each element can be made accessible, ensuring consistency and usability across the application. This approach promotes the creation of robust, scalable, and maintainable designs that inherently support accessibility.

For more details on Atomic Design, refer to [Atomic Design by Brad Frost](http://bradfrost.com/blog/post/atomic-web-design/){:target="_blank"}.

### Key Design Principles

**1. Role and Label Clarity**
* **Roles:** Define the purpose of each element (e.g., button, input, heading) to assist screen readers in understanding their functionality.
* **Labels:** Provide descriptive labels for all interactive elements (e.g., buttons, links) to convey their purpose and functionality to users with visual impairments.

**2. Grouping for Context**
* **Grouping:** Organize related elements into logical groups to improve navigation and comprehension.
* **Labels for Groups:** Assign clear labels to groups to provide context and aid in understanding their relationship to other elements.

**3. Hints and Instructions**
* **Hints:** Offer helpful hints to guide users through complex interactions or provide additional information.
* **Instructions:** Clearly communicate requirements and expectations for input fields to ensure accurate data entry.

For specific guidance on accessibility principles across different platforms, explore the following resources:
- **Principles for accessible design (Material Design)** [Accessibility & Material Design](https://m3.material.io/foundations/overview/principles){:target="_blank"}
- **Android**: [Accessibility Principles for Android Apps](https://developer.android.com/guide/topics/ui/accessibility/principles?authuser=1){:target="_blank"}, [Make Your Android App More Accessible](https://developer.android.com/courses/pathways/make-your-android-app-accessible){:target="_blank"}, [Testing Android App Accessibility](https://developer.android.com/guide/topics/ui/accessibility/testing?authuser=1&continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fmake-your-android-app-accessible%3Fauthuser%3D1%23article-https%3A%2F%2Fdeveloper.android.com%2Fguide%2Ftopics%2Fui%2Faccessibility%2Ftesting){:target="_blank"}, [Android Developers Blog on Accessibility](https://android-developers.googleblog.com/2012/04/accessibility-are-you-serving-all-your-users.html){:target="_blank"}
- **iOS**: [iOS Accessibility Programming Guide](https://developer.apple.com/documentation/uikit/accessibility){:target="_blank"} - Provides an overview of implementing and enhancing accessibility features in iOS applications.
- **Web**: [Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/){:target="_blank"}, [WCAG 2.1 Checklist](https://webaim.org/standards/wcag/checklist){:target="_blank"}, [Mobile Accessibility Guidelines by W3C](https://www.w3.org/WAI/standards-guidelines/mobile/){:target="_blank"}, [Understanding Cognitive Accessibility](https://www.w3.org/WAI/people-use-web/abilities-barriers/cognitive/){:target="_blank"}

## 🧪 Testing and Validation

Testing is crucial in verifying that applications meet accessibility standards. Utilize the following tools and methods:

- **🔧 Automated Tools**: Use tools like Axe, Lighthouse, and Wave to identify common accessibility issues.
- **👨‍🏫 Manual Testing**: Includes testing with keyboard-only navigation, screen readers, and evaluating color contrast ratios.
- **👥 User Testing**: Engage users with disabilities to test the application and provide valuable feedback.
- **Chrome Testing**: https://developer.chrome.com/docs/lighthouse/overview?hl=de

For detailed testing guidelines and tools, explore the following resources:

- **Android**: [Guide to Testing Android App Accessibility](https://developer.android.com/guide/topics/ui/accessibility/testing){:target="_blank"}
- **Web**: [WebAIM’s WCAG 2.1 Checklist](https://webaim.org/standards/wcag/checklist){:target="_blank"}

### 📑 Accessibility Test Cases

Define and document specific test cases to validate the accessibility of applications.

## 💡 Best Practices

To ensure applications are accessible across platforms, consider these best practices:

- **Use Semantic Elements**: Apply appropriate semantic elements or components that convey meaning and structure, such as headings, lists, and buttons.
- **Keyboard and Touch Accessibility**: Ensure all interactive elements can be navigated and activated using both keyboard (or equivalent) and touch input.
- **Provide Alternative Text**: Include descriptive alternative text for images, icons, and other non-text content.
- **Accessible Colors and Contrast**: Use color combinations with sufficient contrast to ensure readability for users with visual impairments.
- **Consistent and Predictable Navigation**: Design navigation patterns that are consistent and predictable across different screens and platforms.
- **Support Screen Readers**: Ensure that applications work well with screen readers by providing meaningful labels, hints, and roles.
- **Focus Management**: Implement proper focus management to ensure that focus is visible and intuitive when navigating through the interface.
- **Avoid Relying on Color Alone**: Do not rely solely on color to convey information; use text, icons, or patterns as additional indicators.
- **Test Across Devices**: Regularly test applications on various devices and operating systems to identify and resolve platform-specific accessibility issues.
- **Use ARIA Wisely**: On the web, apply ARIA (Accessible Rich Internet Applications) attributes only when necessary, ensuring they are used correctly to enhance accessibility.

For platform-specific guidelines, refer to:

- **Android**: [Accessibility Principles for Android Apps](https://developer.android.com/guide/topics/ui/accessibility/principles?authuser=1){:target="_blank"}
- **iOS**: [iOS Accessibility Programming Guide](https://developer.apple.com/documentation/uikit/accessibility){:target="_blank"}
- **Web**: [WCAG Accessibility Guidelines 2.2](https://www.w3.org/TR/WCAG22/){:target="_blank"}


## 🔗 Resources

Explore these valuable resources to learn more about accessibility:

- **W3C Web Accessibility Initiative (WAI)**: [W3C Web Accessibility Initiative](https://www.w3.org/WAI/){:target="_blank"}
- **WCAG 2.2 Guidelines**: [https://www.w3.org/WAI/standards-guidelines/wcag/](https://www.w3.org/WAI/standards-guidelines/wcag/){:target="_blank"}
- **WCAG Overview**: [https://www.w3.org/WAI/test-evaluate/](https://www.w3.org/WAI/test-evaluate/){:target="_blank"}
- **WCAG Pattern Overview**: A great overview for common patterns [https://www.w3.org/WAI/ARIA/apg/patterns/](https://www.w3.org/WAI/ARIA/apg/patterns/){:target="_blank"}
- **Inclusive Design Principles**: [Inclusive Design Principles](https://inclusivedesignprinciples.org/){:target="_blank"}
- **W3C Accessibility Perspective Videos**: [W3C Accessibility Perspective Videos](https://www.w3.org/WAI/perspective-videos/){:target="_blank"}
- **Understanding Cognitive Accessibility**: [Understanding Cognitive Accessibility](https://www.w3.org/WAI/people-use-web/abilities-barriers/cognitive/){:target="_blank"}
- **Accessibility Testing Checklist**: [Accessibility Testing Checklist](https://developer.android.com/guide/topics/ui/accessibility/testing?authuser=1&continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fmake-your-android-app-accessible%3Fauthuser%3D1%23article-https%3A%2F%2Fdeveloper.android.com%2Fguide%2Ftopics%2Fui%2Faccessibility%2Ftesting){:target="_blank"}
- **Are You Serving All Your Users?**: [Are You Serving All Your Users?](https://android-developers.googleblog.com/2012/04/accessibility-are-you-serving-all-your.html){:target="_blank"}
- **All Platforms**: Provides a comprehensive checklist for accessibility across all platforms. [Accessibility Checklist - MagentaA11y](https://www.magentaa11y.com/){:target="_blank"}
- **Android**: [Make Your Android App More Accessible](https://developer.android.com/courses/pathways/make-your-android-app-accessible){:target="_blank"}, [Accessibility Principles for Android Apps](https://developer.android.com/guide/topics/ui/accessibility/principles?authuser=1){:target="_blank"}, [Testing Android App Accessibility](https://developer.android.com/guide/topics/ui/accessibility/testing){:target="_blank"}, [Android Developers Blog on Accessibility](https://android-developers.googleblog.com/2012/04/accessibility-are-you-serving-all-your-users.html){:target="_blank"}, [Designing Accessible Mobile Apps](https://developer.android.com/design/ui/mobile/guides/foundations/accessibility?hl=en&authuser=1#){:target="_blank"}
- **iOS**: [iOS Accessibility Programming Guide](https://developer.apple.com/documentation/uikit/accessibility){:target="_blank"}
- **Web**: [What is Accessibility? — IxDF](https://www.interaction-design.org/literature/topics/accessibility){:target="_blank"}
- **European accessiblity act**: [https://web-directive.eu/#toc4 & https://www.youtube.com/live/AHxasDBBskE](https://web-directive.eu/#toc4 & https://www.youtube.com/live/AHxasDBBskE){:target="_blank"}


## 🛠️ Plugins and Tools


- **The A11Y Project**: Easy to read & follow check list [https://www.a11yproject.com/checklist/](https://www.a11yproject.com/checklist/){:target="_blank"}
- **Web AIM Check List**: Official wcag list [https://webaim.org/standards/wcag/checklist](https://webaim.org/standards/wcag/checklist){:target="_blank"}
- **Designing with Accessibility in Mind Workshop**: Usefull links, AI prompts and presentation material [https://github.com/mpaiva/a11y-workshop/tree/main](https://github.com/mpaiva/a11y-workshop/tree/main){:target="_blank"}
- **Figma Plugin Include**: Spec tool from ebay [https://www.figma.com/community/plugin/1208180794570801545/includeaccessibility-annotations](https://www.figma.com/community/plugin/1208180794570801545/includeaccessibility-annotations){:target="_blank"}
- **Figma Plugin WCAG Plugin**: Creates a11y guidelines as cards [https://www.figma.com/community/plugin/1373362852131056921/wcag-plugin](https://www.figma.com/community/plugin/1373362852131056921/wcag-plugin){:target="_blank"}
- **Figma Plugin Stark and Chrome Plugin**: Make everything accessible from the start. [https://www.figma.com/community/plugin/732603254453395948/stark-contrast-accessibility-checker](https://www.figma.com/community/plugin/732603254453395948/stark-contrast-accessibility-checker){:target="_blank"} & [https://chromewebstore.google.com/detail/stark-accessibility-check/fkfaapnmfippddbeemjjbclenphooipm](https://chromewebstore.google.com/detail/stark-accessibility-check/fkfaapnmfippddbeemjjbclenphooipm){:target="_blank"}
- **Accessbility Posters in German**: [https://github.com/UKHomeOffice/posters/blob/master/accessibility/dos-donts/posters_de/accessibilty-posters-set-de.pdf](https://github.com/UKHomeOffice/posters/blob/master/accessibility/dos-donts/posters_de/accessibilty-posters-set-de.pdf){:target="_blank"}

![accessibilty-posters-set](https://github.com/user-attachments/assets/ef7b03c9-2ee9-43ce-a0db-a0b0ef892494){:target="_blank"}


## 🤝 Contributing

Contributions are encouraged to improve accessibility.
Feel free to create MR with improvements to this README.

