# Frontend Assignment

## Get Started

- Setup a React Project with CRA / Vite / Parcel / Any (Seperate Repository - Not this one)
- Codebase should be only in Typescript
- Run `npm install` and run `generate` command to generate fake data
- Run `npm start` to start the mock API server
- Replicate the design from the figma with React.

## Things to Do

- Should have Unit tests wherever it's crucial. Use `react-testing-library` for atleast one component test.
- Table should be built with `@tanstack/react-table` library. (https://github.com/TanStack/table) with **server side** _pagination_ and _sorting_ support.
  > Tip : See https://github.com/typicode/json-server#slice, where you can use the `X-Total-Count` and refer the `@tanstack/react-table` examples.
- Source code and tests should be in Typescript
- Maintain pagination and sort state in Redux Slice (use Redux Toolkit)
- Use RTK query to fetch the data from the mock API server (or a custom hook with axios or fetch, but prefer RTK query)
- Show a table Loading state while the data is being fetched
- Generate Test Coverage result (optional)

## Things to Note

- Split the components in a way so that it's easily testable.
- Follow the patterns https://www.patterns.dev/
- Use any styling of your choice

## Features of the Table

- Should be server side paginated (Both Number of Rows Per page and Page index )
- Should be server side sorted

# Figma Link

https://www.figma.com/file/O7m4YzZEeScwJOblFMphgR/FE-Assignment---Issue-Tracker?node-id=1-3&t=PyIOcykRFltJgQf8-4
