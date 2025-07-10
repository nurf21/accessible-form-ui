# Accessible Profile Setup Form

<!-- ![Form UI Screenshot](screenshot.png) -->

A clean, accessible form UI with password visibility toggle and profile completeness tracking, built with pure HTML and CSS.

## Features

- **Modern Form Design**: Clean layout with intuitive form fields
- **Password Toggle**: Show/hide password icon
- **Profile Completeness Tracker**: Visual progress bar and checklist
- **Accessibility Focus**: Fully compliant with WCAG standards
- **Responsive Design**: Works on all device sizes
- **Error Handling**: Clear error messaging with proper ARIA attributes

## Accessibility Implementation

This form includes comprehensive accessibility features:

- Semantic HTML structure
- Proper labeling with `for` attributes
- Clear focus states for keyboard navigation
- ARIA attributes:
  - `aria-required` for required fields
  - `aria-invalid` for error states
  - `aria-describedby` for error messages
  - `aria-pressed` for toggle buttons
  - `aria-label` for icon buttons
- Sufficient color contrast (4.5:1 minimum)
- Screen reader friendly error messages
- Keyboard accessible toggle buttons

## Live Demo

[View Live Demo](https://nurf21.github.io/accessible-form-ui)

## Usage

This is a static UI component. The form includes the following sections:

1. **Personal Information**
   - Full name field
   - Email field with validation error example
   
2. **Password Management**
   - Password field
   - Confirm password field
   - Password visibility toggle icon

3. **Profile Completeness**
   - Progress bar showing 20% completion
   - Checklist of requirements to reach 100%

## Future Enhancements

This UI can be extended with JavaScript to add functionality:

- Form validation
- Password strength meter
- Profile completeness calculation
- Database integration
- Real-time error checking
- Password match verification

## Project Resources

This project is part of the Frontend Developer Roadmap:  
[Visit Project](https://roadmap.sh/projects/datepicker-ui)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.