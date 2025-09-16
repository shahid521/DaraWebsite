# Dara App Design Guidelines

## Design Approach
**Reference-Based Approach**: Exact replication of the طرب (Tarab) app interface with modern web adaptations while maintaining the original's visual identity and user experience patterns.

## Core Design Elements

### Color Palette
- **Background**: Deep navy/dark blue (220 15% 12%)
- **Surface elements**: Slightly lighter blue-gray (220 15% 18%)
- **Primary accent**: Bright blue (210 100% 60%)
- **Text primary**: White (0 0% 95%)
- **Text secondary**: Light gray (220 10% 70%)
- **Button backgrounds**: Semi-transparent overlays (220 20% 25% / 0.8)

### Typography
- **Primary font**: System font stack for Arabic/English compatibility
- **Headers**: Medium weight, clean sans-serif
- **Body text**: Regular weight with good readability
- **Icon labels**: Small, uppercase for platform names

### Layout System
**Spacing**: Tailwind units of 2, 4, 6, and 8 (p-2, h-8, m-4, gap-6)
- Consistent 4-unit spacing between major sections
- 2-unit padding for buttons and small elements
- 6-unit margins for visual separation

### Component Library

#### Header
- Three-section layout: Help button (left), audio waveform logo (center), Share button (right)
- Clean, minimal design with proper Arabic text support

#### Search Section
- Large, prominent search input with placeholder text
- Right-aligned arrow button for search execution
- Subtle border and rounded corners

#### Platform Grid
- 3x3 grid layout for platform buttons
- Each button contains icon and platform name
- Consistent sizing and spacing
- Semi-transparent background overlays

#### Bottom Navigation
- Four main tabs: Sources, Files, Playlists, More
- Active state indication
- Arabic text labels with proper RTL support

### Special Considerations
- **RTL Layout**: Full Arabic language support with proper text direction
- **Mobile-First**: Optimized for mobile viewing with touch-friendly interactions
- **Dark Theme**: Consistent dark mode throughout the entire interface
- **Platform Consistency**: Maintain exact visual hierarchy and spacing as the original

### Interactive Elements
- Subtle hover states for platform buttons
- Clean focus indicators for accessibility
- Smooth transitions without distracting animations
- Touch-optimized button sizes (minimum 44px target areas)

### Visual Hierarchy
- Search functionality as primary focus
- Platform integration buttons as secondary actions
- Navigation and utility functions as tertiary elements
- Clear visual separation between functional areas

This design maintains the exact look and feel of the original طرب app while ensuring web compatibility and modern usability standards.