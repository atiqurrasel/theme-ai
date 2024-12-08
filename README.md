
# Halal Investment Screening Website

**A sample static website that provides insights into halal-compliant investing, inspired by Wahed’s approach.**  
This project integrates basic information pages, a contact form, and a simple “Halal Metric” calculator that checks whether a stock’s financial structure is considered halal-compliant based on a simplified heuristic.

## Features

- **Home Page:**  
  Introduces the concept of halal-compliant investing and highlights the site’s AI-inspired approach.
  
- **About Page:**  
  Describes the project’s mission, values, and the importance of ethical, halal-driven investment strategies.
  
- **Contact Page:**  
  Provides an email contact for visitors to reach out with questions, comments, or partnership inquiries.
  
- **Calculate Page:**  
  Allows users to enter a stock ticker symbol and determine if it meets basic halal criteria. For demonstration purposes, this logic is currently mocked—future enhancements can incorporate real financial data from an API such as Yahoo Finance.

## Technologies Used

- **HTML5 & CSS3:**  
  Semantic markup and responsive design using modern HTML and CSS.
  
- **Vanilla JavaScript:**  
  Basic DOM manipulation and event handling for the halal metrics calculator.  
  *(In the current demo code, the logic is mocked. Actual integration with a stock market data API would require a backend or client-side fetch to a public API.)*

- **Normalize.css:**  
  Ensures consistent styling across different browsers by normalizing default CSS rules.

## Getting Started

1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/your-username/halal-investment-screening.git
   ```
   
2. **Open the Project Locally:**  
   Open `index.html` in your web browser. No server setup is required as this is a static website.

3. **Navigate the Pages:**  
   - **Home (`index.html`)** – Overview and introduction  
   - **About (`about.html`)** – Mission and values  
   - **Contact (`contact.html`)** – Reach out for more info  
   - **Calculate (`calculate.html`)** – Enter a stock ticker and check compliance
   
## Future Enhancements

- **Real Data Integration:**  
  Connect the `calculate.html` page to a real financial API (e.g., Yahoo Finance) to fetch actual company financial metrics and apply halal screening criteria.
  
- **Expanded Criteria:**  
  Incorporate more nuanced criteria for halal compliance, potentially including debt ratios, interest income thresholds, and screening against a robust set of Shariah-compliant standards.

- **Accessibility & Internationalization:**  
  Continue improving accessibility features, test with screen readers, and consider translations for a global audience.

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request. Ensure that your additions align with the project’s goals of educational, ethical, and user-friendly content.

## License

This project is provided as-is for demonstration and educational purposes. It does not offer financial advice. Consider adding an open-source license of your choice (e.g., MIT License) if you wish to make the code freely available under defined terms.

