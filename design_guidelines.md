# Design Guidelines: Saffron Distribution Management Software Landing Page

## Design Approach
**Reference-Based Approach**: Drawing inspiration from modern SaaS landing pages like Notion, Linear, and HubSpot, adapted for Persian RTL layout and agricultural/distribution industry context.

## Core Design Principles
- **Persian RTL Layout**: Complete right-to-left design with Persian typography
- **Trust & Professionalism**: Clean, authoritative design that builds confidence with distribution managers
- **Lead-Focused**: Every design element guides toward mobile number capture
- **Industry-Authentic**: Real saffron farming and distribution imagery throughout

## Typography
**Primary Font**: Vazirmatn or Estedad (modern Persian web fonts via Google Fonts)
- Hero headline: 700 weight, 3xl to 5xl size
- Section headers: 600 weight, 2xl to 3xl size
- Body text: 400 weight, base to lg size
- CTA buttons: 600 weight, lg size
- Form labels/inputs: 400 weight, base size

## Layout System
**Spacing Units**: Tailwind units of 4, 6, 8, 12, 16, 20, 24 (focus on 8, 16, 24 for major spacing)
- Section vertical padding: py-16 (mobile), py-24 (desktop)
- Container max-width: max-w-7xl with px-6 (mobile), px-8 (desktop)
- Grid gaps: gap-8 for feature cards, gap-6 for smaller elements

## Color Palette (Saffron Theme)
**Foundation Colors**:
- Golden/Orange gradient backgrounds for hero and CTAs (saffron stigma inspired)
- Soft green accents for secondary elements (saffron leaf inspired)
- White/cream backgrounds for content sections
- Deep warm gray for text hierarchy
- Subtle gradients from golden to orange for emphasis areas

## Component Library

### Header
- Full-width header with logo on right (RTL)
- Navigation links in center (if any)
- Primary CTA button on left
- Sticky on scroll with subtle shadow
- Height: h-16 to h-20

### Hero Section
- **Large hero image**: Full-width background showing saffron distribution manager reviewing dashboard or workers processing saffron flowers
- Height: min-h-screen on desktop, min-h-[600px] on mobile
- Content overlay with gradient backdrop
- Headline, subheadline, and primary CTA vertically centered
- Two-column layout on desktop: text content (right) with 40% width, visual space (left) 60%
- Mobile: single column, stacked layout

### Features Section (4 Key Benefits)
- 2x2 grid on desktop (grid-cols-2 lg:grid-cols-2)
- Single column on mobile
- Each feature card includes:
  - Relevant icon (from Heroicons - document, chart, shield, clock symbols)
  - Bold title
  - 2-3 line description
  - Subtle hover lift effect
- Cards with soft white backgrounds, rounded corners (rounded-xl), subtle shadows

### Complementary Services Section
- 4-column grid on desktop (lg:grid-cols-4), 2 on tablet (md:grid-cols-2), 1 on mobile
- Icon + title + short description format
- Minimalist card design with border instead of shadow
- Focus on mobile app, scoring system, notifications, web dashboard

### Analytics & Reports Section
- **Large dashboard preview image**: Showing sample charts, tables, and metrics
- Two-column layout: Image (60%) + descriptive text (40%)
- Include 3 specific callouts:
  - Delivery and return tracking
  - Financial reports and settlement status
  - Worker/driver rankings
- Use subtle data visualization colors (blues, greens for positive metrics)

### Lead Capture Form
- **Prominent placement**: Full-width section with saffron-gradient background
- Centered, max-width container (max-w-md)
- Single input field: phone number with Persian placeholder "۰۹xxxxxxxxx"
- Large, high-contrast submit button: "دریافت مشاوره رایگان"
- Form validation for Iranian mobile format (09xxxxxxxxx)
- Success message display area below form
- Trust indicator: Small text mentioning "مشاوره رایگان" (free consultation)

### Footer
- Three-column layout on desktop
- Logo and tagline (right column)
- Quick links (center column)
- Contact info (left column)
- Copyright and trust badges at bottom

## Images Strategy

### Required Images:
1. **Hero Background**: Saffron distribution manager in warehouse/office using tablet/computer with visible saffron product
2. **Feature Support**: Worker hands processing saffron, close-up of saffron stigmas
3. **Dashboard Preview**: Screenshot of analytics dashboard with Persian text showing charts and data tables
4. **Mobile App Mockup**: Smartphone showing the worker mobile app interface
5. **Team/Workers**: Authentic photo of distribution team or pickers at work

### Image Treatment:
- Hero: Full-bleed with 40% dark gradient overlay for text readability
- Feature images: Rounded corners (rounded-lg), aspect-ratio-video
- Dashboard: Subtle shadow, slight perspective tilt for depth
- All images: Professional quality, authentic to saffron industry

## Animations
**Minimal and purposeful**:
- Fade-in on scroll for feature cards
- Smooth hover transitions for interactive elements (scale: 1.02, shadow increase)
- Form submission: Success checkmark animation
- No complex scroll-triggered animations

## Accessibility & RTL Considerations
- Complete RTL layout: dir="rtl" on HTML
- Proper Persian number formatting
- High contrast ratios for readability
- Form labels properly associated
- Touch-friendly button sizes (min 44x44px)
- Persian phone number validation pattern

## Mobile-First Priorities
- Hero text readable without zooming
- CTAs thumb-reachable
- Forms autofocus and zoom-friendly
- Images optimized for mobile bandwidth
- Collapsible sections if needed

## Conversion Optimization
- Above-the-fold CTA in hero
- Repeated CTA in features section
- Trust signals: "رایگان" (free), professional imagery
- Minimal form friction (phone only)
- Clear value proposition in every section
- Success confirmation with reassuring message