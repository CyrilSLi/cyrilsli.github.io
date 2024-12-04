# edugameconvert, a tool to convert questions between educational game platforms

The current supported platforms are Kahoot, Quizizz, Blooket, Gimkit, and ClassQuiz.

Paste the URL of a question set in the box above, select the platform to convert to, and click "Convert!"
A file would be downloaded with the converted questions, which you can import into the selected platform.
Information and warnings would be displayed here. Enjoy!

Each platform has different import limitations. The tool would attempt to convert as much as possible.
Supported question types and fields when exporting to each platform are listed below:
- Kahoot:    MCQ (max 4 answers), time limit (limited options)
- Quizizz:   MCQ (max 5 answers), time limit (limited options), Typing (max 5 answers), Image (URL)
- Blooket:   MCQ (max 4 answers), time limit (max 300 seconds), Typing (max 4 answers)
- Gimkit:    MCQ (max 4 answers, only 1 correct), no time limit
- ClassQuiz: MCQ (max 4 answers), time limit (max 999 seconds), Typing (max 4 answers)

## Usage Instructions

### 1. Paste the URL of a question set from Kahoot, Quizizz, or Blooket into the top box.
- The set must be public and cannot be a game or homework link (i.e. the list of questions must be visible).
- Example URLs (your link does not have to be in this exact format, it just must contain the game ID):
  - Kahoot: https://create.kahoot.it/details/a1b2c3d4-a1b2-a1b2-a1b2-a1b2c3d4e5f6
  - Quizizz: https://quizizz.com/admin/quiz/a1b2c3d4e5f6a1b2c3d4e5f6/game-name
  - Blooket: https://dashboard.blooket.com/set/a1b2c3d4e5f6a1b2c3d4e5f6
  - Gimkit: https://www.gimkit.com/view/a1b2c3d4e5f6a1b2c3d4e5f6
  - ClassQuiz: https://classquiz.de/view/a1b2c3d4-a1b2-a1b2-a1b2-a1b2c3d4e5f6

### 2. Select the platform you want to convert the questions to.
- _Tip: Even though some button outlines are not visible, everything can be selected using the keyboard._

### 3. Click the <b>Convert!</b> button and save the generated .xlsx or .csv (depending on the platform) file.
- If no file is generated, please raise an issue on the GitHub repository with the following information:
  - Question set URL
  - Platform you tried to convert to
  - Information displayed in the output box
  - Any errors and the game JSON (if available) displayed in the browser console
- The output box displays import & export statistics and any warnings generated during the conversion.
  - A count is shown for each supported question type: MCQ, MSQ (multiselect MCQ), and Typing.

### 4. Import the file into the selected platform.
- **Remember to check questions and answers after importing!** Please report any issues you encounter.
- Do not use the templates provided in the guides, upload the generated file directly.