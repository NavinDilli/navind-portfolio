# Navin D — Portfolio Project Handoff

## Project Overview
Professional portfolio website for Navin D, Mechanical R&D Lead at Tutr Hyperloop.
Built with vanilla HTML, CSS, and JavaScript — no frameworks, no build step required.

---

## File Structure

```
portfolio/
├── index.html                    # Home page (510 lines)
├── project-tophat.html           # Top Hat detail page (319 lines)
├── project-vacuum.html          # Vacuum Chamber detail page (357 lines)
├── project-digitaltwin.html     # Digital Twin detail page (353 lines)
├── style.css                     # Complete stylesheet (2059 lines)
├── script.js                     # Interactions & animations (276 lines)
├── HANDOFF.md                    # This file
├── assets/
│   ├── Navin_D_Resume_Styled_07_07.docx   # Resume download
│   └── images/
│       ├── profile.png           # Profile photo
│       ├── tophat-hero.jpg       # Top Hat CAD render
│       ├── tophat-3dprint.jpg    # 3D printed prototype
│       ├── tophat-3dprint2.jpg   # 3D print detail
│       ├── tophat-pattern.jpg    # MDF master pattern
│       ├── tophat-pattern-nose.jpg
│       ├── tophat-pattern-body.jpg
│       ├── tophat-pod1.jpg       # On pod - side
│       ├── tophat-pod2.jpg       # On pod - rear
│       ├── tophat-pod3.jpg       # In front of tube
│       ├── tophat-standalone.jpg # Final assembly
│       ├── tophat-minister.jpg   # Railway Minister showcase
│       ├── vacuum-hero.jpg         # Chamber on test rig
│       ├── vacuum-layup.jpg      # CF hand lay-up
│       ├── vacuum-flange.jpg     # Al flange with O-ring
│       ├── vacuum-door.jpg       # Door with feedthroughs
│       ├── vacuum-saddle.jpg     # With support saddle
│       ├── vacuum-testing.jpg    # Before testing
│       ├── vacuum-tube.jpg       # 8.6m test facility
│       ├── vacuum-tubedoor.jpg   # Test facility door
│       ├── vacuum-battery.jpg    # Battery inside chamber
│       ├── vacuum-v1failed.jpg   # V1.0 failed prototype
│       ├── vacuum-feedthrough.jpg
│       ├── vacuum-feedthrough-power.jpg
│       ├── dt-hero.jpg           # Full workstation
│       ├── dt-strain.jpg         # Strain gauge close-up
│       ├── dt-ina101.jpg         # INA101 + DAQ
│       ├── dt-scale.jpg          # Instrumented scale
│       ├── dt-display.jpg        # Live deflection display
│       ├── dt-matlab.jpg         # MATLAB dashboard
│       └── dt-workstation.jpg    # Workstation overview
```

---

## Pages Summary

### index.html — Home Page
| Section | Description |
|---------|-------------|
| Hero | Name, headline, stats grid (3+ yrs, 3 projects, ₹42L+, 5+ vendors), profile photo with rotating ring, CTAs |
| About | Professional narrative + 4 skill cards (CFD, Digital Twins, Composites, FEA) |
| Experience | Timeline with 3 roles, "Current" and "Promoted" badges, skill tags |
| Projects | 3 preview cards linking to detail pages |
| Education | M.E. Aerospace + B.E. Mechanical cards |
| Academic | 4 research/project cards (transonic flow, buffet control, time-motion, biomass stove) |
| Contact | Email, LinkedIn, Resume download CTAs |
| Footer | Nav links + copyright |

### project-tophat.html — Hyperloop Top Hat
| Section | Images Used |
|---------|-------------|
| Hero | tophat-hero.jpg |
| Overview | tophat-standalone.jpg |
| CFD & Design | tophat-3dprint.jpg |
| Manufacturing | tophat-pattern.jpg |
| Integration | tophat-pod3.jpg |
| Gallery | tophat-hero, tophat-3dprint2, tophat-pattern-nose, tophat-pattern-body, tophat-pod1, tophat-pod2 |
| Key Results | 6 stat cards |
| Deployment | tophat-minister.jpg |

### project-vacuum.html — Composite Vacuum Pressure Chamber
| Section | Images Used |
|---------|-------------|
| Hero | vacuum-hero.jpg |
| Overview | vacuum-testing.jpg |
| Failure Analysis | vacuum-v1failed.jpg |
| Redesign | vacuum-layup.jpg |
| Feedthroughs | vacuum-door.jpg |
| Gallery | vacuum-layup, vacuum-flange, vacuum-feedthrough, vacuum-feedthrough-power, vacuum-tube, vacuum-battery |
| Key Results | 6 stat cards |
| Testing | vacuum-saddle.jpg |
| Deployment | vacuum-tubedoor.jpg |

### project-digitaltwin.html — Structural Digital Twin
| Section | Images Used |
|---------|-------------|
| Hero | dt-hero.jpg |
| Overview | dt-workstation.jpg |
| Instrumentation | dt-strain.jpg |
| DAQ & Signal | dt-ina101.jpg |
| Software | dt-matlab.jpg |
| Gallery | dt-hero, dt-strain, dt-ina101, dt-scale, dt-display |
| Key Results | 6 stat cards |
| Testing | dt-scale.jpg |
| Deployment | dt-workstation.jpg |

---

## Design System

### Colors
| Token | Value | Usage |
|-------|-------|-------|
| --bg-primary | #0a0a0f | Page background |
| --bg-secondary | #0f1117 | Alt section background |
| --bg-card | #161b22 | Card backgrounds |
| --accent-primary | #3b82f6 | Primary blue |
| --accent-secondary | #22d3ee | Cyan accent |
| --text-primary | #f8fafc | Headings |
| --text-secondary | #94a3b8 | Body text |
| --text-muted | #64748b | Captions, labels |
| --border | #1e293b | Card borders |

### Typography
| Role | Font | Weights |
|------|------|---------|
| Body | Inter | 300-800 |
| Mono/Accents | JetBrains Mono | 400-600 |

### Responsive Breakpoints
| Breakpoint | Behavior |
|------------|----------|
| > 1024px | Full layout, 2-column grids |
| 768-1024px | Single column, stacked layouts |
| < 768px | Mobile nav hamburger, single column everything |
| < 480px | Compact stats, full-width buttons |

---

## Features Implemented

### Phase 1 (Complete)
- [x] Fixed navbar with scroll blur effect
- [x] Hero with animated entrance, parallax glow, stats grid
- [x] Profile photo with rotating gradient ring
- [x] "Available for Opportunities" pulse badge
- [x] About section with 4 skill cards (hover lift)
- [x] Experience timeline with animated line, badges, tags
- [x] Project preview cards with hover overlays
- [x] Education & Academic sections
- [x] Contact with icon CTAs
- [x] Footer with nav links
- [x] Mobile responsive (hamburger nav, grid collapse)
- [x] Scroll-triggered fade-in animations
- [x] Custom scrollbar styling

### Phase 2 (Complete)
- [x] 3 standalone project detail pages
- [x] Full-width hero images with gradient overlays
- [x] Horizontal stat bars per project
- [x] Alternating narrative layouts (text + image)
- [x] Responsive image galleries with hover zoom
- [x] Lightbox modal (click to expand, Escape to close)
- [x] Key Results stat card grids
- [x] Project-to-project navigation
- [x] Consistent footer across all pages
- [x] Cross-page navigation (home nav links work on project pages)

---

## Known Issues & Phase 3/4 TODO

### Performance
- [ ] **Image optimization**: Several images are 2-3MB each (vacuum-tube.jpg, vacuum-testing.jpg, tophat-pod1.jpg, etc.). Should compress to ~200KB for web. Use tinypng.com or ImageMagick.
- [ ] **Lazy loading**: Already implemented via `loading="lazy"` on all images.
- [ ] **Favicon**: Not yet added. Add a favicon.ico or favicon.png.

### Content
- [ ] **Skills/Tools section**: Could add a dedicated section with proficiency bars or a radar chart showing expertise across CFD, FEA, CAD, Digital Twins, Programming, Composites.
- [ ] **Certifications**: Could add a brief certifications section from the old resume (Stanford CodeinPlace, Coursera, workshops).
- [ ] **Internships**: Could mention Simulation Lab Ltd and EagleBurgmann internships briefly.

### Polish
- [ ] **SEO meta tags**: Add Open Graph tags, description meta, Twitter cards.
- [ ] **Accessibility**: Add aria-labels to all interactive elements, ensure color contrast passes WCAG AA.
- [ ] **Print styles**: Add `@media print` styles for resume-friendly printing.
- [ ] **Dark mode toggle**: Currently fixed dark. Could add light mode toggle (not essential).
- [ ] **404 page**: Add a simple 404.html.

### Deployment
- [ ] **Hosting**: Can deploy to GitHub Pages, Netlify, Vercel, or any static host.
- [ ] **Custom domain**: If desired, configure DNS.
- [ ] **Analytics**: Add Google Analytics or Plausible (optional).

---

## How to Continue in a New Conversation

To resume work, tell the AI:

> "Continue building Navin's portfolio from the handoff. I want to do [Phase 3 / Phase 4 / specific feature]."

The AI will:
1. Read HANDOFF.md for context
2. Read all existing files
3. Continue from where we left off

### Suggested Next Steps (pick one)

**Option A — Phase 3: Skills Section**
Add a visual skills/tools section with proficiency indicators between Academic and Contact.

**Option B — Phase 4: Image Optimization + Deploy**
Compress all images, add favicon, add SEO meta tags, deploy to a hosting platform.

**Option C — Polish Pass**
Add hover effects to gallery items, improve mobile gallery layout, add loading states.

**Option D — Content Expansion**
Add certifications, internships, or a blog/articles section.

---

## Quick Start (Local Preview)

```bash
# Option 1: Open directly in browser
open index.html

# Option 2: Simple Python server
cd portfolio
python3 -m http.server 8000
# Then visit http://localhost:8000

# Option 3: VS Code Live Server extension
# Right-click index.html → "Open with Live Server"
```

---

## Contact Info (for reference)
- Name: Navin D
- Title: Mechanical R&D Lead
- Email: navintommy123@gmail.com
- LinkedIn: linkedin.com/in/navind-rnd
- Location: Chennai, TN
- Phone: NOT included on website (per request)

---

*Handoff created: 2026-08-07*
*Last build: Phase 1 + Phase 2 Complete*
*Total lines of code: ~3,874*
*Total image assets: 33*
