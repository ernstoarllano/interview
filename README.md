# Dispel Technical Interview

Welcome to the Dispel Technical Interview! This assessment is thoughtfully designed to evaluate candidates' technical proficiency, problem-solving skills, and suitability for various roles within Dispel. As a candidate, you can anticipate engaging in a series of challenges, coding exercises, and discussions that will assess your knowledge of relevant technologies, coding practices, and problem-solving methodologies.

## What to Expect

The interview process is carefully crafted to identify individuals who not only possess a deep understanding of technical concepts but also demonstrate the ability to apply these skills in real-world scenarios. Successful candidates will showcase a robust foundation in coding, effective problem-solving strategies, and the capacity to contribute meaningfully to Dispel's technical initiatives.

## Getting Started

To begin, start the database and run the development server:

```bash
yarn db:up
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Technical Requirement: Simple Blog Application

Your assignment is to build a simple blog application using Next.js, Prisma, and PostgreSQL. The blog should allow users to view a list of blog posts and click into each post to see its details.

### Requirements

- **Home Page:**

  - Display a list of the 5 most recent blog posts
  - For each post, show:
    - Title
    - Short content preview
    - Author name
    - Link to the full post

- **Blog Detail Page:**

  - Display the full blog post content
  - Show:
    - Title
    - Full content
    - Author information
    - Creation date
  - Include a way to navigate back to the home page

- **Data Modeling:**
  - Implement a relationship between Users and Posts
  - Each post must be associated with an author (User)
  - Design the schema to support:
    - Post creation and management
    - Author attribution

### Technical Stack

- Next.js (App Router)
- Prisma (PostgreSQL)
- TypeScript
- Tailwind CSS
- Shadcn UI (optional, for consistent styling)

### Database Setup

The project includes a PostgreSQL database running in Docker. The Prisma schema is set up with a basic `Post` model. You'll need to:

1. Design and implement the User model
2. Establish the relationship between Users and Posts
3. Create appropriate migrations
4. Update the application to handle the user-post relationship

```bash
# Start the database
yarn db:up

# Run migrations (after editing the Prisma schema)
npx prisma migrate dev --name <migration-name>

# Open Prisma Studio to view/edit data
npx prisma studio
```

### Documentation

- [Next.js App Router](https://nextjs.org/docs/app/getting-started)
- [Prisma Documentation](https://www.prisma.io/docs)
- [Tailwind CSS](https://tailwindcss.com/docs)
- [Shadcn UI](https://ui.shadcn.com/)

## Notes

Feel free to leverage your preferred method for data fetching—whether it's `TanStack Query`, `React Server Components`, or another approach. Your comfort and expertise are paramount in showcasing your skills during this task.

Remember to enjoy the process and have fun! Life's too short to be too serious—let your creativity shine and make the most out of this coding adventure. Happy coding!
