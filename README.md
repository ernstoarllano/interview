# Dispel Technical Interview

Welcome to the Dispel Technical Interview! This assessment is thoughtfully designed to evaluate candidates' technical proficiency, problem-solving skills, and suitability for various roles within Dispel. As a candidate, you can anticipate engaging in a series of challenges, coding exercises, and discussions that will assess your knowledge of relevant technologies, coding practices, and problem-solving methodologies.

## What to Expect

The interview process is carefully crafted to identify individuals who not only possess a deep understanding of technical concepts but also demonstrate the ability to apply these skills in real-world scenarios. Successful candidates will showcase a robust foundation in coding, effective problem-solving strategies, and the capacity to contribute meaningfully to Dispel's technical initiatives.

## Getting Started

To begin, run the development server using one of the following commands based on your preference:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Technical Requirement: Fetching and Rendering GitHub User Data

Your assignment involves fetching user data from the GitHub API and rendering this information on the page. Additionally, you are required to create a user detail page that shows detailed information about a selected user, including 10 of their repositories, followers and organizations. This exercise serves as a practical assessment of your ability to interact with external APIs, present data in a client application, and implement detailed user views. Good luck with your task!

Please note: GitHub has a rate limit for its API. To ensure a smooth experience during the technical interview, we encourage you to create a personal access token. You can find detailed instructions on how to create and manage your personal access token [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens). This will help you avoid any potential rate-limiting issues and ensure you can fully showcase your skills. Good luck!

### Requirements

- Create a list of users that displays the users avatar and name, also include a link to a user detail page.
- Create a user detail page that displays the users avater and name, also include five followers and five organizations along with 10 repos.

### Endpoints

[API Docs](https://docs.github.com/en/rest/users/users?apiVersion=2022-11-28)

- `https://api.github.com/users`
- `https://api.github.com/users/${user}`
- `https://api.github.com/users/${user}/followers`
- `https://api.github.com/users/${user}/orgs`
- `https://api.github.com/search/users?q=${user}`

## Notes

Feel free to leverage your preferred method for data fetching—whether it's `SWR`, `TanStack Query`, or, for the daring and adventurous, diving into the world of `React Server Components`. Your comfort and expertise are paramount in showcasing your skills during this task.

Remember to enjoy the process and have fun! Life's too short to be too serious—let your creativity shine and make the most out of this coding adventure. Happy coding!
