# Project Summary
SynergySphere is an advanced team collaboration platform tailored for enhancing productivity and streamlining communication within teams across India. The application features project management, task tracking, and team discussions, all designed with a modern, responsive UI using React, TailwindCSS, and shadcn/ui components. It aims to support teams in managing projects effectively while being culturally relevant.

# Project Module Description
- **Authentication**: User login, signup, and profile management with localized names.
- **Dashboard**: Overview of all projects with task summaries, featuring localized project names.
- **Project Detail Hub**: Detailed view of projects including tasks, discussions, and visualizations.
- **Task Management**: Create, edit, and manage tasks with various statuses, using culturally relevant examples.
- **Discussion System**: Threaded discussions for project-level communication.
- **Notifications**: Alerts for task assignments and updates.
- **Data Visualizations**: Charts to track project progress and task distribution.

# Directory Tree
```
shadcn-ui/
├── README.md               # Project overview and documentation
├── components.json         # Component definitions
├── eslint.config.js        # ESLint configuration
├── index.html              # Main HTML file
├── package.json            # Project dependencies and scripts
├── postcss.config.js       # PostCSS configuration
├── public/                 # Public assets
│   ├── favicon.svg         # Favicon for the application
│   └── robots.txt          # Robots.txt for SEO
├── src/                    # Source files
│   ├── App.css             # Global CSS styles
│   ├── App.tsx             # Main application component
│   ├── components/         # Reusable UI components
│   ├── contexts/           # Context providers for auth and theme
│   ├── hooks/              # Custom hooks
│   ├── pages/              # Application pages
│   └── lib/                # Utility functions
├── tailwind.config.ts      # Tailwind CSS configuration
├── template_config.json     # Template configuration for UI
├── todo.md                 # Implementation plan
├── tsconfig.app.json       # TypeScript configuration for app
├── tsconfig.json           # General TypeScript configuration
├── tsconfig.node.json      # TypeScript configuration for Node
└── vite.config.ts          # Vite configuration
```

# File Description Inventory
- **README.md**: Overview and setup instructions for the project.
- **components.json**: Definitions and metadata for UI components.
- **eslint.config.js**: Configuration file for ESLint to enforce coding standards.
- **index.html**: The entry point of the application.
- **package.json**: Contains project dependencies, scripts, and metadata.
- **postcss.config.js**: Configuration for PostCSS processing.
- **src/App.tsx**: Main application component that sets up routing and context providers.
- **src/pages/**: Contains all the main pages of the application, such as Login, Dashboard, and Project Detail.
- **src/components/**: Contains reusable UI components.
- **src/contexts/**: Context files for managing authentication and theme state.
- **src/hooks/**: Custom hooks for managing mobile state and other functionalities.
- **src/lib/**: Utility functions used throughout the application.

# Technology Stack
- **Frontend**: React 18, TypeScript, TailwindCSS, shadcn/ui components, Lucide React icons.
- **State Management**: React Query for data fetching and state management, Context API for authentication and theme.
- **Build Tool**: Vite for fast development and build processes.

# Usage
1. **Install Dependencies**: Run `pnpm install` to install all project dependencies.
2. **Build the Project**: Use `pnpm run build` to create a production build.
3. **Run the Development Server**: Execute `pnpm run dev` to start the application in development mode.
