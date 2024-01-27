# Roufianomore
**_An automation script for Erganis check-in/check-out "roufianos" system._**

Automate your daily check-in and check-out routine in Erganis. This script monitors your Google Calendar events for the day and triggers actions on the Erganis platform accordingly.

[![Schedule Check-in/Check-out](https://github.com/patriarxis/roufianomore/actions/workflows/main.yml/badge.svg)](https://github.com/patriarxis/roufianomore/actions/workflows/main.yml)

## Table of Contents

- [Overview](#overview)
- [Usage](#usage)
- [Contributing](#contributing)
- [Donate](#donate)
- [License](#license)

## Overview

This GitHub Actions script, named "Schedule Check-in/Check-out," is designed to streamline your daily check-in and check-out process. It connects to your Google Calendar, identifies events for the day, and triggers actions on [ergani.softone.gr](https://ergani.softone.gr/) at the specified check-in and check-out times.

## Usage

1. **Setup Google Calendar URL:**
   - Obtain the URL of your Google Calendar that you want to monitor for check-in/check-out events.
   - Add the Google Calendar URL as a secret named `GOOGLE_CALENDAR_URL` in your GitHub repository.

2. **Set Credentials:**
   - Create GitHub secrets for your SoftOne platform credentials:
     - `USERNAME`: Your SoftOne username.
     - `PASSWORD`: Your SoftOne password.

3. **Trigger Schedule:**
   - The script is configured to run automatically every day at 6:00 AM UTC. This schedule can be adjusted to your preferences by modifying the cron expression in the [GitHub Actions workflow file](.github/workflows/main.yml).

4. **Monitor Actions:**
   - Keep track of the script's execution by visiting the [GitHub Actions page](https://github.com/patriarxis/roufianomore/actions).

**Note:** Before relying on this automation, thoroughly review and understand the script's functionality. Ensure that the Google Calendar URL, SoftOne platform credentials, and schedule meet your specific requirements.

## Contributing

Contributions are welcome! If you encounter any issues or have improvements to suggest, feel free to open an issue or submit a pull request.

## Donate

If you find this script helpful and would like to support the project, consider buying me a coffee!

[![Buy Me a Coffee](https://patriarxis.com/assets/donate-button.svg)](https://revolut.me/patriarxis)

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the script according to your needs.
