# TeamStation AI - Nearshore IT Talent Pricing Calculator

## Overview
The **TeamStation AI Nearshore IT Talent Pricing Calculator** is a web-based tool designed to help companies estimate the cost of building nearshore IT teams with talent from Latin America. Users can select roles, seniority levels, and the number of team members to calculate an estimated monthly cost.

## Features
- **Dynamic Role Selection:** Choose from a variety of IT roles such as AI Prompt Engineer, Software Architect, DevOps Engineer, etc.
- **Seniority Levels:** Assign Proficient, Mid-Level, Senior, or Expert/Certified experience levels to each role.
- **Real-Time Cost Estimation:** Calculate estimated hourly and monthly costs based on role and seniority.
- **Multiple Role Support:** Add multiple roles to estimate the cost of an entire team.
- **Reset and Update Functionality:** Easily modify selections or reset the calculator.

## Tech Stack
- **Frontend:** HTML, CSS (Poppins font for modern UI)
- **JavaScript:** Used for dynamic form handling and real-time price calculations
- **Deployment:** Can be hosted on GitHub Pages, AWS S3, or any static file hosting service

## Installation
To run the pricing calculator locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/TeamStationAI/nearshore-pricing-calculator.git

# Navigate into the project directory
cd nearshore-pricing-calculator

# Open index.html in your browser
open index.html   # Mac
start index.html  # Windows
xdg-open index.html  # Linux
```

Alternatively, you can directly open `index.html` in any modern web browser.

## Usage Instructions
1. **Select Roles:** Choose an IT role from the dropdown menu.
2. **Choose Seniority Level:** Select Proficient, Mid-Level, Senior, or Expert.
3. **Enter Team Size:** Input the number of engineers needed per role.
4. **Calculate Cost:** Click **Calculate Total Estimated Monthly Cost** to see cost estimates.
5. **Modify as Needed:** Add more roles, adjust levels, or reset the form.

## Pricing Model
The cost estimation is based on **hourly rates** for each role and seniority level:
- **Proficient:** $20 - $30/hr
- **Mid-Level:** $30 - $40/hr
- **Senior:** $40 - $50/hr
- **Expert/Certified:** $50 - $60/hr

> *Each role has an estimated cost range based on market rates and real-world hiring trends.*

## Contributing
We welcome contributions! If you'd like to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the **MIT License** - see the `LICENSE` file for details.

## Contact
For questions or feedback, reach out to [TeamStation AI](https://www.teamstation.dev) or email us at **lonniet@teamstation.io**.
