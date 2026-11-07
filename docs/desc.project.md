Project 1 — Personal Profile Page
1. Project Brief

A personal profile page to introduce themselves to potential employers, collaborators, and clients. The page should be professional, accessible, responsive, and easy to maintain. This is a common real-world starting point for personal branding and portfolio sites.
1. Functional Requirements

Create a single-page profile that includes:

    A site header
    A navigation menu (even if it only links to sections on the same page)
    A hero/introduction section
    A profile image
    A short biography
    A skills section
    An education or experience section
    A hobbies/interests section
    A contact section
    A footer

3. HTML Requirements

Use semantic HTML appropriately, including:

    <!DOCTYPE html>
    <html lang="...">
    <head> with essential metadata
    <body>
    <header>
    <nav>
    <main>
    Multiple <section> elements
    <article> only if it represents self-contained content
    <aside> only if it adds complementary information
    <footer>
    Ordered or unordered lists where appropriate
    <figure> and <figcaption> for the profile image
    Meaningful headings with a correct hierarchy (h1 followed by logical subsections)
    Internal navigation using fragment links

Think carefully about whether each semantic element is appropriate rather than using every tag simply because it exists.
4. CSS Requirements

Practice:

    CSS custom properties (:root)
    Universal selector reset (or a modern minimal reset)
    Box model
    Typography
    Margin and padding
    Borders
    Border radius
    Colors
    Backgrounds
    Basic gradients (optional)
    Shadows
    Flexbox for simple layouts
    Responsive units (rem, %, vw where appropriate)
    clamp() for at least one font size
    Logical properties (e.g., margin-block, padding-inline)
    Hover and focus states for interactive elements

Do not use CSS Grid yet; we'll introduce it later.
5. Accessibility Requirements

Your page must include:

    A skip link
    Descriptive alt text for the profile image
    Visible keyboard focus styles
    Sufficient color contrast
    Landmarks (header, main, footer, etc.)
    Descriptive link text (avoid "Click here")
    Respect for prefers-reduced-motion if you add transitions or animations

6. Responsive Requirements

Use a mobile-first approach.

Design should work well at approximately:

    320px+
    768px+
    1024px+
    1440px+

Test that text remains readable and navigation is usable at each size.
7. Performance Requirements

Aim for:

    Low selector specificity
    Reusable classes
    Minimal nesting
    Efficient CSS
    No unnecessary wrappers
    No inline styles

8. SEO Requirements

Include:

    Descriptive <title>
    Meta description
    Viewport meta tag
    Open Graph metadata (at least og:title and og:description)
    A clear heading hierarchy
    Meaningful image alt text

Think about what additional structured data might benefit a personal profile, even if you don't implement it yet.
9. Validation Requirements

Before submitting, check that:

    HTML validates without errors.
    CSS validates without errors.
    Keyboard navigation works.
    There are no obvious accessibility issues.
    The layout remains usable across the required breakpoints.