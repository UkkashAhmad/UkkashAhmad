public class UkkashAhmad
{
    /// <summary>
    /// Full Stack Developer specializing in building scalable,
    /// secure and user-focused web applications. Strong command
    /// over frontend, backend, API design and database architecture.
    /// Always improving — always shipping.
    /// </summary>

    // Basic Info
    public string Name = "Ukkash Ahmad";
    public string Location = "Rawalpindi, Pakistan";
    public string Email = "ahmadukkash47@gmail.com";
    public string LinkedIn = "linkedin.com/in/ukkash-ahmad-60549a205";
    public string Phone = "+92 323 5943601";

    // ==============================================
    // SKILLS
    // ==============================================
    enum Frontend {
        ReactJS, NextJS, JavaScript, TypeScript,
        TailwindCSS, VueJS, NuxtJS, Axios, Pinia,
        Supabase, Firebase
    }

    enum Backend {
        NodeJS, Express, MySQL, JWT
    }

    enum Mobile {
        ReactNative
    }

    enum Tools {
        Git, GitHub, REST_API, Prisma, Mongoose
    }

    enum SoftSkills {
        ProblemSolving, Communication, Teamwork,
        Leadership, TimeManagement, Adaptability
    }

    // ==============================================
    // EXPERIENCE
    // ==============================================
    public static class Experience
    {
        public static void SignupSolution()
        {
            var Role = "Frontend Developer (Nuxt.js / Vue.js)";
            var Duration = "May 2025 - Present";
            var Summary = new string[] {
                "Built scalable and responsive web apps.",
                "Created reusable UI components using Nuxt, Vue & Tailwind.",
                "Integrated REST APIs with Axios & ShadCN.",
                "Followed Agile, Git workflows & optimized performance."
            };
        }

        public static void IngeneticLabs()
        {
            var Role = "Frontend Intern (Next.js, React.js)";
            var Duration = "Mar 2024 - Jun 2024";
            var Summary = new string[] {
                "Developed web apps in Next.js & React.",
                "Built reusable UI components.",
                "Improved app performance & UX."
            };
        }
    }

    // ==============================================
    // PROJECTS
    // ==============================================
    public static class Projects
    {
        public static void FoodOrderingApp()
        {
            var Stack = "NextJS, NodeJS, Express, MongoDB";
            var Highlights = new string[] {
                "Real-time order placement",
                "User authentication",
                "Clean API architecture",
                "Responsive UI & optimized performance"
            };
        }

        public static void InventoryManagement()
        {
            var Stack = "NextJS, ShadCN";
            var Highlights = new string[] {
                "Responsive UI",
                "Clean component architecture",
                "Smooth frontend integration"
            };
        }

        public static void EzLMS()
        {
            var Stack = "Nuxt 3, Vue 3, ShadCN, Nuxt UI, Tailwind, TS, Axios";
            var Highlights = new string[] {
                "Full LMS system with training & modules",
                "Compliance management",
                "Dashboards & multi-role modes",
                "Highly optimized performance"
            };
        }
    }

    // ==============================================
    // EDUCATION
    // ==============================================
    public static class Education
    {
        public static void Masters()
        {
            var Degree = "Masters in Arts";
            var Institution = "Jamia Arabia Islamia, Islamabad";
            var Duration = "2014 - 2021";
        }
    }

    // Helper
    public static string Range(string start, string end)
        => $"{start} - {end}";
}