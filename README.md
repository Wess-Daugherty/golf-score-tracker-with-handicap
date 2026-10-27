# golf score tracker with handicap

java app that can track and save scores, find courses, and create a handicap index.

## The Problem

As a golfer, It is hard to get an accurate handicap index. Right now, the handicap index most people use is locked behind a USGA membership, which most weekend warriors wont want to pay for, including me.

## How It Works

- Gets score input from user and saves it to a file
- Finds courses in a database of over 30,000 courses and saves used courses for later use
- Calculates the golfer's handicap index using previously saved scores and courses.

## Tech Stack

- **Language:** Java
- **Libraries:** N/A
- **External tools:** OpenGolfAPI

## Setup

Step 1: clone golf score tracker repo into your local machine:

```bash
git clone https://github.com/Wess-Daugherty/golf-score-tracker-with-handicap.git
cd golf-score-tracker-wtih-handicap
```

Step 2a: if you are using the terminal, create a new directory and compile the java files - 
```bash
mkdir -p {directory name}

javac -d {directory name} src/**/*.java
```

Step 2b: if using IDE, open your desired IDE with java installed, and go to Select File > Open and choose the cloned folder. The files should now show up in your IDE.
## Usage


Step 3a: if using the terminal, use bash command to run main file
```bash
java -cp bin {main class name}
```
Step 3b: if using IDE, navigate to main file and run like any other java file.

## Roadmap

Features you haven't built yet but plan to (pull these from your
"Schedule" quadrant in the Eisenhower Matrix).

- [ ] Add GUI for simple and user-friendly usage of the app
- [ ] Add ability to add hole-by-hole tracking of score
- [ ] Add satellite or graphical representation of each hole

## Author

Wessley Daugherty - [GitHub](github.com/Wess-Daugherty)

