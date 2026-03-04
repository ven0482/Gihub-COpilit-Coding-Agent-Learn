## Program Overview

This is an educational website designed for a school environment. The primary users are **students** and **teachers**. The goal is to create a simple, intuitive platform that supports learning and classroom management.

### School & Educational Context

- This website is built for an academic institution to support teaching and learning
- The platform should be user-friendly for both classroom instruction and independent student work
- All features should align with educational best practices and support different learning styles

### About the Teachers & Staff

The staff members using this platform are **not technical**. They may have limited experience with software and technology. When communicating with or building features for staff:

- **Use simple, non-technical language** - Avoid software jargon and technical terminology
- **Prioritize ease of use** - Features should be intuitive and require minimal training
- **Provide clear guidance** - Instructions should be straightforward and easy to follow
- **Test for clarity** - Consider whether a teacher without technical skills can understand and use the feature

## User Experience Guidelines

### For Students
- Keep the interface clean and simple
- Provide clear navigation and obvious next steps
- Use friendly, encouraging language
- Ensure mobile-friendly design where possible

### For Teachers
- Minimize complexity in administrative tasks
- Provide helpful feedback and error messages in simple terms
- Make common tasks accessible with minimal clicks
- Support offline capabilities where practical

## Code Maintenance Standards

To ensure the codebase remains maintainable by non-technical staff and student developers:

- **Write easy-to-understand code** - Prioritize readability over clever solutions
- **Use clear naming conventions** - Variable and function names should clearly describe their purpose
- **Add helpful comments** - Explain the "why" behind complex logic
- **Avoid unnecessary complexity** - Keep solutions straightforward and easy to debug
- **Organize files logically** - Use a clear directory structure that reflects the site's organization

## Program Architecture

- **Website only** - Focus on web-based solutions for maximum accessibility
- **No additional apps or services** - Keep everything in the website to reduce complexity
- **No command-line tools** - Teachers and students should interact through the web interface only
- **Modular file structure** - Use organized directories instead of single large files (e.g., `/pages`, `/styles`, `/scripts`, `/components`)
- **Permitted technologies only** - Use only:
  - **HTML** - For structure and content
  - **CSS** - For styling and layout
  - **JavaScript** - For interactivity and client-side logic
  - **Python** - For backend/server logic only
  - *No other languages or frameworks*

## Development Environment

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).