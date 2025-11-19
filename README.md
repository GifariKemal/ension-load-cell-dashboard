# Tension Load Cell Dashboard

A web-based dashboard application for monitoring tension load cell data and generating thorough examination reports for lifting gears.

## Overview

This dashboard provides real-time monitoring of load cell measurements and comprehensive reporting capabilities for lifting equipment inspections. Built for **PT SPEKTRA MEGAH SEMESTA**, it combines data visualization with standardized examination reporting compliant with Lifting Equipment Engineers Association (LEEA) Technical Requirements.

## Features

### Dashboard

- **Real-time Load Monitoring**: Display current load values with live status indicators
- **Interactive Trend Chart**: Visualize load vs. time data with hover details
- **Peak Value Tracking**: Monitor maximum and minimum load readings
- **Status Indicators**: Visual LED-style indicators for system status
- **User Information**: Display current operator details

### Examination Report Generator

The application includes a comprehensive 8-section examination form:

1. **Document Header**: Report metadata and identification
2. **Identity of Parties & Location**: Employer and examination site details
3. **Equipment Identity**: Equipment specifications and identification
4. **Technical Test Results**: Test load measurements and calculations
5. **Examination Category & Interval**: Inspection classification and scheduling
6. **Defects Findings & Follow-up**: Defect identification and remediation tracking
7. **Officers & Authorization**: Inspector details and certifications
8. **Import Image**: Visual documentation upload and management

### Additional Capabilities

- **PDF Export**: Generate professional PDF reports with company branding
- **Image Management**: Upload, label, and organize inspection photos
- **Data Persistence**: Auto-save form data to prevent data loss
- **Responsive Design**: Optimized for various screen sizes
- **Print-friendly Output**: Clean formatting for hard copy reports

## Technology Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS variables and flexbox/grid layouts
- **Vanilla JavaScript**: No framework dependencies for maximum compatibility
- **Chart.js**: Interactive data visualization
- **html2canvas**: Client-side screenshot and PDF generation

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, or Edge)
- No server-side dependencies required

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/GifariKemal/ension-load-cell-dashboard.git
   cd ension-load-cell-dashboard
   ```

2. Open the application:
   ```bash
   # Simply open index.html in your web browser
   open index.html  # macOS
   # or
   start index.html  # Windows
   # or
   xdg-open index.html  # Linux
   ```

   Alternatively, serve it with a local web server:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## Usage

### Navigation

The application features a sidebar navigation with three main sections:

- **Dashboard**: Real-time load cell monitoring and data visualization
- **Form**: Thorough examination report creation and editing
- **Print**: Preview and export reports

### Data Entry

1. Navigate to the **Form** section
2. Complete each section sequentially using the navigation buttons
3. Upload inspection images in Section 8
4. Review all data in the **Print** preview
5. Export to PDF when ready

### Monitoring

1. Navigate to the **Dashboard** section
2. View real-time load readings
3. Monitor the trend chart for load patterns
4. Check peak values and system status

## Configuration

### Customization

Edit the CSS variables in `index.html` to customize the appearance:

```css
:root {
  --primary: #0C6B58;      /* Primary brand color */
  --accent: #16B091;       /* Accent color */
  --bg: #f5f7f9;          /* Background color */
  --surface: #ffffff;      /* Surface/card color */
  /* ... more variables ... */
}
```

### Company Branding

Update the company name and logo by modifying the header section in `index.html`.

## Browser Compatibility

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

## License

This project is proprietary software developed for PT SPEKTRA MEGAH SEMESTA.

## Support

For support, please contact the development team or submit an issue in the repository.

## Compliance

This application generates reports compliant with:
- Lifting Equipment Engineers Association (LEEA) Technical Requirements
- Indonesian workplace safety standards

---

**PT SPEKTRA MEGAH SEMESTA**
*Professional Load Cell Monitoring & Lifting Equipment Inspection*
