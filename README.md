# Planner Diário — Daily Schedule Planner

A premium, modern daily planner web application for organizing your schedule with precision. All data is saved automatically in your browser's localStorage.

## Features

- **Interactive Schedule Management**: Add, edit, and delete time blocks for your daily activities
- **Smart Time Calculations**: Enter start time + duration OR start + end time, and the app calculates the missing value automatically
- **Drag & Drop Reordering**: Easily rearrange your schedule by dragging blocks
- **Category System**: Organize activities by categories (Study, University, Health, Life, Admin, Rest)
- **Weekly Planning**: Manage schedules for all 7 days of the week
- **Search & Filter**: Quickly find activities by name, time, or category
- **Data Persistence**: Auto-save to localStorage with JSON export/import functionality
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Completion Tracking**: Check off completed activities and track your progress

## How to Run

Simply open `docs/index.html` in any modern web browser. No build process or dependencies required.

For local development with live reload:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve docs

# Then open http://localhost:8000 in your browser
```

## Usage

### Adding Blocks
1. Click the "Adicionar bloco" button
2. Fill in start time, activity name, duration, category, and details
3. The app automatically calculates end times

### Smart Time Entry
- **Option 1**: Enter start time (08:00) + duration (1h30) → End time calculated automatically
- **Option 2**: Enter start time (08:00) + end time (09:30) → Duration calculated automatically
- Supports multiple duration formats: `90` (minutes), `1h30`, `1:30`, `45min`

### Organizing Your Schedule
- **Drag to reorder**: Hover over a row and drag the handle (⋮⋮) to reorder blocks
- **Sort by time**: Click "Ordenar" to sort all blocks chronologically
- **Search**: Type in the search box to filter by activity name, time, or category
- **Filter**: Use the category dropdown to show only specific types of activities

### Data Management
- **Auto-save**: All changes are saved automatically to localStorage
- **Export**: Download your schedule as a JSON file
- **Import**: Load a previously exported JSON file
- **Reset**: Restore the default template schedule
- **Clear**: Remove all blocks from the current week

## What Changed

### Before vs After Improvements

#### Visual Design
- ✅ **Modern Dark Theme**: Refined color palette inspired by GitHub's design system with better contrast ratios
- ✅ **Premium Typography**: Improved font stack, sizing, and spacing for better readability
- ✅ **Enhanced Spacing**: Consistent 8px spacing system with better breathing room
- ✅ **Sophisticated Gradients**: Subtle background gradients for depth without distraction
- ✅ **Micro-interactions**: Smooth 180ms transitions on all interactive elements
- ✅ **Better Visual Hierarchy**: Clear distinction between primary, secondary, and tertiary actions

#### User Interface
- ✅ **Hero Header**: Clean, compelling introduction with clear subtitle explaining functionality
- ✅ **Elevated KPI Cards**: Interactive metric cards with hover effects showing total blocks, planned time, and completions
- ✅ **Refined Controls Bar**: Better organized form fields with clear labels and improved focus states
- ✅ **Premium Buttons**: Multiple button styles (primary, danger, ghost) with appropriate visual weight
- ✅ **Enhanced Table**: Improved input fields that appear on hover, better column widths, sticky header
- ✅ **Smart Drag Handle**: Appears on hover for cleaner default appearance
- ✅ **Completion States**: Completed rows have reduced opacity for better visual scanning
- ✅ **Better Action Buttons**: Action buttons appear on row hover to reduce visual clutter

#### User Experience
- ✅ **Improved First Impression**: Clear value proposition and feature explanation
- ✅ **Better Affordances**: Hover states, focus states, and transitions make interactions obvious
- ✅ **Enhanced Feedback**: Improved toast notifications with smooth animations
- ✅ **Keyboard Navigation**: Proper focus-visible states for keyboard users
- ✅ **Mobile Optimization**: Responsive layout that adapts gracefully to small screens
- ✅ **Accessibility**: Improved contrast ratios, ARIA labels, and semantic HTML

#### Technical Improvements
- ✅ **CSS Architecture**: Organized CSS with clear sections and better naming conventions
- ✅ **Modern CSS**: Custom properties, modern layout (Grid, Flexbox), responsive design
- ✅ **Smooth Animations**: Purposeful animations using cubic-bezier easing
- ✅ **Custom Scrollbars**: Styled scrollbars that match the dark theme
- ✅ **Loading States**: CSS framework for loading animations (ready for future use)
- ✅ **Better Comments**: CSS sections clearly marked for maintainability

### All Original Features Preserved
- ✅ localStorage persistence (v2 format with v1 migration)
- ✅ Add, edit, delete, duplicate blocks
- ✅ Drag & drop reordering
- ✅ Smart time/duration calculations
- ✅ Search and filter functionality
- ✅ Export/import JSON
- ✅ Week management
- ✅ Category system
- ✅ Completion tracking
- ✅ Auto-save functionality

## Browser Support

Works on all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+

## Data Storage

All data is stored in your browser's localStorage under the key `agenda_planner_v2`. The app includes automatic migration from v1 format if detected.

## Screenshots

*(Screenshots can be added here)*

## License

Open source - feel free to use and modify as needed.

## Credits

Redesigned with a focus on premium UI/UX, modern design principles, and exceptional usability.
