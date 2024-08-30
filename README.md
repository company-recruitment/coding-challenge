# **Next.js Coding Challenge: Gamer Discussion Snippets**

![pixy-coding-challenge](https://raw.githubusercontent.com/company-recruitment/coding-challenge/main/assets/pixy-coding-challenge.png)

[![language](https://img.shields.io/badge/language-German-121212.svg?style=for-the-badge&labelColor=121212f2&color=9945FF)](https://github.com/company-recruitment/coding-challenge/blob/main/README-de.md)

Hi 👋! Thank you for taking the time to participate in this coding challenge. Your task is to develop a small but functional web application that provides a basic discussion feature. This task is designed to give us insight into your skills in Next.js, Tailwind CSS, PostgreSQL (Supabase), and the integration of UI components from [nyxbui.design](https://nyxbui.design).

#### **What We Expect**

We expect this task to take about 4-5 hours. The focus is on writing clean, well-structured code and implementing the key features.

#### **The Challenge**

Develop an application that allows users to create and display **short discussion snippets**. These snippets could be short opinions or questions about a specific game or topic.

**Advanced Features:**

1. **Create and Display Snippets:**

   - Users should be able to create short discussion posts (snippets) through a simple form.
   - These snippets should be stored in a PostgreSQL database (via Supabase).
   - A list of snippets should be displayed on the main page.

2. **Use `nyxbui.design` Components:**
   - Use components from `nyxbui.design` for the form and the display of snippets.

3. **User Authentication:**
   - Implement user authentication with Supabase Auth.
   - Only authenticated users should be able to create snippets.

4. **Comments on Snippets:**
   - Users should be able to add comments to existing snippets.
   - Comments should also be stored in the database and displayed.

5. **Real-time Updates:**
   - Implement real-time updates for snippets and comments with Supabase Realtime.

6. **Advanced Database Requirements:**
   - Design a database structure that stores user information, snippets, and comments.
   - Consider the relationships between the tables (e.g., users, snippets, comments).

7. **DRM Diagram:**
   - Create a DRM diagram (database relationship model) that shows the structure and relationships of your database.

8. **Environment Variables:**
   - Ensure that the environment variables (`NEXT_PUBLIC_SUPABASE_URL` and `NEXT_PUBLIC_SUPABASE_KEY`) are included in the email you send us.

#### **Supabase Setup**

To ensure all applicants have an optimal experience, set up your own Supabase project. Here is a step-by-step guide:

1. **Create a Supabase Account:**

   - Go to [supabase.com](https://supabase.com) and sign up.
   - Create a new project. Note the `API URL` and `anon key` that you will need later.

2. **Create the Necessary Tables:**

   - Think about which tables you need and which columns make sense. This could be a table for snippets and one for comments, where the content and other relevant information are stored.

3. **Configure Your Next.js Project:**

   - Use the provided `.env.local.example` file to configure the Supabase URL and anon key in your `.env.local` file:

   ```plaintext
   NEXT_PUBLIC_SUPABASE_URL=https://your-project.supabase.co
   NEXT_PUBLIC_SUPABASE_KEY=your-anon-key
   ```

4. **Install Supabase:**

   - If not already done, install the Supabase JavaScript SDK:

   ```bash
   npm install @supabase/supabase-js
   ```

5. **Connect Your Project to Supabase:**
   - In your Next.js project, you can now use the Supabase client library to access your database.

#### **Preconfigured Project**

We provide you with a base project preconfigured with Next.js, Tailwind CSS, and `nyxbui.design`. You just need to clone it and follow the steps above to set up Supabase.

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/company-recruitment/coding-challenge.git
   cd coding-challenge
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Start the Development Server:**
   ```bash
   npm run dev
   ```

#### **FAQs**

- **What if I have trouble setting up Supabase?** The Supabase documentation is a good starting point. This task is also designed to test your ability to use new tools and find your way around independently.
- **Should I implement specific features?** **No, all mentioned features must be implemented.** We are looking for a solid foundation that shows how you solve challenges.

#### **Good Luck! 💪**

Once you are done, send us a confirmation email with the environment variables and the DRM diagram. After your submission, we will get in touch with you.
