# grade-filter-including-selected

const selectedGrade = "III";

const filteredGrades = gradesList.filter(grade => {
  const selectedGradeIndex = gradesList.findIndex(g => g.name === selectedGrade);
  const currentGradeIndex = gradesList.findIndex(g => g.name === grade.name);
  return currentGradeIndex >= selectedGradeIndex;
}); here need to filter including selected grade

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/grade-filter-including-selected.git
cd grade-filter-including-selected
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Tech stack

- [Vite](https://vitejs.dev/)
- [React](https://react.dev/)
- [Chakra UI](https://chakra-ui.com/)

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
