# Mini programs Guide lines

Telegram, Wechat and many other chinese products are called as **mini app runtime environments**


### What this repository contains
This **repository** contains all what you need from resources, case studies and real life examples on how to architect and implement **the** mini-programs in the best way to increase the success of you mini program application.

### What you will find?
- **Introduction**
  - [Why you need to read this guidelines?](/introduction/0.why-to-read.md)
- **Development environment:**
  - What is mini app?
  - What is the host app ( Super app ) ?
  - In what language the mini app is written?
  - The reason to use tailwind instead of regular css and scss? 
  - Why using Svelte as the main framework for the mini app programming?
- **Design guidelines:**
  - Why this is differ from host app to another?
  - Layout standards
  - Color schemes
  - Typography
  - Iconography
- **User experience:** 
  - Navigation patterns:
  - User interactions
  - Accessibility considerations
- **Performance Standards:**
  - Load Times: Recommended load times for mini apps.
  - Resource Usage: Guidelines for efficient use of memory, CPU, and battery.
  - Optimizations: Tips for optimizing performance (e.g., lazy loading, caching strategies).
- **Security Guidelines**
  - Data Privacy: How to handle user data responsibly and comply with relevant regulations.
  - Authentication: Standards for user authentication and session management.
  - API Security: Secure use of APIs, including authentication, rate limiting, and encryption.
- **Coding Standards**
  - Code Quality: Best practices for writing clean, maintainable code.
    - Naming conventions
    - Code organization
    - Commenting and documentation
  - Testing: Guidelines for testing mini apps, including unit tests, integration tests, and end-to-end tests.
- **API Usage**
  - Available APIs: List and describe the APIs provided by the host application.
  - Rate Limits: Any rate limits or usage quotas.
  - Error Handling: How to handle and report errors when using APIs.
- **Compliance and Legal**
  - Regulatory Compliance: Ensure mini apps comply with relevant laws and regulations (e.g., GDPR, CCPA).
  - Terms of Service: Outline the terms of service that developers must agree to.
- **Submission and Review Process**
  - Submission Guidelines: How to submit a mini app for review.
  - Review Criteria: What the review team looks for when evaluating mini apps.
  - Approval Process: Steps and timelines for the approval process.
- **Maintenance and Updates**
  - Versioning: Guidelines for versioning mini apps.
  - Update Process: How to handle updates, including notifying users and managing downtime.
  - Deprecation Policy: How to phase out older versions or unsupported mini apps.
- **Support and Resources**
  - Developer Support: How developers can get help (e.g., support channels, documentation).
  - Community Resources: Links to forums, tutorials, and other resources for developers.
- **Examples and Best Practices**
  - Sample Mini Apps: Provide examples of well-designed mini apps.
  - Case Studies: Share case studies or success stories.


### what is  mini app/program runtime environment?
**A mini app runtime environment:** is a lightweight platform or ecosystem that allows small, often specialized applications (mini apps) or sometimes called mini programs to run within a larger application or framework. Here are the basics:

**Mini Apps or (Mini programs):** These are small, standalone applications designed to perform specific tasks. They are often simpler and faster than full-fledged applications.

**Host Application:** This is the main application that provides the environment for mini apps to run. For example, a social media platform or an e-commerce app can act as a host for various mini apps.

**Runtime Environment:** This refers to the infrastructure and tools that allow mini apps to run. It includes the necessary libraries, APIs (Application Programming Interfaces), and services that mini apps use to function.


### What this repository includes?
- **UI/UX:** A complete design system, UI Kits and examples on how to design you mini app
- **Technical decisions:** Will show you various ways to architect you app 

### Key Components
- **Container:** The host app acts as a container for mini apps. It manages their lifecycle, including launching, running, and closing them.

- **APIs:** The runtime environment provides APIs that mini apps use to interact with the host app and its resources. These APIs can handle things like user authentication, data storage, and network requests.

- **Security:** The environment ensures that mini apps run in a secure and isolated manner, preventing them from accessing sensitive data or resources of the host app or other mini apps.

- **Performance:** Since mini apps are lightweight, they can load and run quickly, providing a seamless user experience and later you will see why we are using svelte as example of a mini app it's an example of a performant framework compared to other frameworks.

### Examples
- **WeChat Mini Programs:** These are mini apps that run within the WeChat app, offering services like shopping, gaming, and utilities without the need to download separate apps.
- **Facebook Instant Games:** Small games that run within the Facebook app, allowing users to play without leaving the platform.
- **Telegram mini apps:** These are mini apps that run within the telegram app.
  
Benefits
Convenience: Users can access multiple services within a single app without the need to download and install multiple apps.
Speed: Mini apps are designed to be fast and responsive.
Integration: They can leverage the existing user base and features of the host app, providing a cohesive experience.
Conclusion
Mini app runtime environments make it easy to deliver specialized functionality within larger applications, enhancing user experience by providing quick, integrated, and secure access to various services.