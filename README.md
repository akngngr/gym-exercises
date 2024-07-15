
# Workout App

Workout App is a comprehensive gym exercise platform that allows users to search all kinds of exercises by muscle group, exercise, or equipment type. With functionality to choose exercise categories and specific muscle groups, users can browse more than one thousand exercises with practical examples, pagination, exercise details, related videos from YouTube, similar exercises, and much more.

![enter image description here](https://akin-gungor.vercel.app/assets/gym-2dec05a0.png)

## Features

- **Exercise Search**: Search exercises by muscle group, exercise, or equipment type.
- **Exercise Categories**: Choose from various exercise categories and specific muscle groups.
- **Extensive Exercise Database**: Browse over one thousand exercises with practical examples.
- **Exercise Details**: View detailed information about each exercise.
- **Related Videos**: Pull and display related exercise videos from YouTube.
- **Similar Exercises**: Discover similar exercises for variety in workouts.
- **Pagination**: Efficiently browse through exercises with pagination.

## Technologies Used

- **Next.js**: A React framework for server-side rendering and static site generation.
- **Supabase**: An open-source backend as a service (BaaS) providing a real-time database and authentication.
- **CSS**: For styling the application and ensuring a responsive design.

## Installation

Follow these steps to get the project up and running on your local machine.

1. **Clone the repository:**
   git clone https://github.com/akngngr/gym-exercises.git
   cd gym-exercises

 2.  **Install dependencies:**
  
     `npm install` 
    
3.  **Set up Supabase:**
    
    -   Create a new project on [Supabase](https://supabase.io/).
    -   Get the API URL and Anon Key from the project settings.
    -   Create a `.env.local` file in the root directory and add the following environment variables   
        
        `NEXT_PUBLIC_SUPABASE_URL=your-supabase-url`
        `NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key` 
        
4.  **Start the development server:**
          
    `npm run dev` 
    
5.  **Build for production:**
    
    ```
    npm run build
    npm start
## Usage

1.  Open your browser and navigate to `http://localhost:3000`.
2.  Use the search feature to find exercises by muscle group, exercise, or equipment type.
3.  Explore exercise details, related YouTube videos, and similar exercises.


## Contributing

We welcome contributions to enhance the functionality and user experience of the Workout App. Please follow these steps to contribute:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature-branch`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature-branch`).
6.  Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any inquiries or feedback, please contact via [email](mailto:akingungor04@gmail.com).

## Acknowledgments

-   [Next.js](https://nextjs.org/) for the React framework.
-   [Supabase](https://supabase.io/) for the backend services.
-   [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) for styling.
