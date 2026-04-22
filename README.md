# Ôn Thi Bằng Lái Xe (Driving License Exam Preparation)

An Android application designed to help users prepare for driving license exams in Vietnam, covering both motorbike and car licenses.

## Features

- **Theory Study:** Access and study the full set of 600 official theory questions.
- **Mock Tests:** Simulate real exam conditions with timed practice tests tailored to specific license types.
- **Traffic Signs:** A comprehensive gallery of Vietnamese traffic signs, categorized for easy learning.
- **Exam Tips:** Helpful tips and strategies to improve exam performance.
- **License Selection:** Supports various license categories, including:
    - Motorbike: A1, A2, A3, A4
    - Car: B1, B2, C, D, E, F

## Project Structure

- `app/src/main/java/com/example/btlapp`: Contains the Java source code for activities, models, and repositories.
- `app/src/main/res`: Contains UI layouts, strings, and other resources.
- `app/src/main/assets`: Includes JSON data for questions (`600question.json`) and traffic signs (`bien_bao.json`).

## Technical Stack

- **Platform:** Android
- **Language:** Java
- **UI Framework:** Android Material Design
- **Database:** SQLite (managed via `DatabaseHelper.java`)
- **Data Format:** JSON for static question sets

## Getting Started

1. Clone this repository.
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
4. Run the app on an Android Emulator or a physical device (Minimum SDK: 24).

## License

This project is for educational purposes.
