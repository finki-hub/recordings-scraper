# FINKI Hub / Recordings Scraper

Use this to get the links of all recordings within a Courses (Moodle) course, and generates a screenshot of the entire course.

## Quick Setup

1. Clone the repository: `git clone https://github.com/finki-hub/recordings-scraper.git`
2. Install dependencies: `npm i`
3. Build the project: `npm run build`
4. Run it: `npm run start <cookie> <url>`, where `cookie` is your `MoodleSession` cookie, and `url` is the url of the course

Once run, a Chrome window opens and locates all the recordings within the course. Don't close it, as it will close itself when it's done. The results will be written in the `output` directory.

## License

This project is licensed under the terms of the MIT license.
