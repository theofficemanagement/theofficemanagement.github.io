<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Office: A Case Study in Bad Management</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
        }
        .hero-image {
            background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1522202176988-66273c2fd55f?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            height: 50vh;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            position: relative;
        }
        .theory-card {
            transition: transform 0.3s ease;
        }
        .theory-card:hover {
            transform: translateY(-5px);
        }
        .character-card {
            transition: all 0.3s ease;
        }
        .character-card:hover {
            transform: scale(1.03);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-gray-900 text-white shadow-lg">
        <div class="container mx-auto px-6 py-3">
            <div class="flex items-center justify-between">
                <div class="flex items-center">
                    <svg class="h-8 w-8 text-blue-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
                    </svg>
                    <span class="ml-2 text-xl font-semibold">Office Management Study</span>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="text-blue-400">Home</a>
                    <a href="#about" class="hover:text-blue-400">About</a>
                    <a href="#failures" class="hover:text-blue-400">Case Studies</a>
                    <a href="#real-world" class="hover:text-blue-400">Real World</a>
                    <a href="#lessons" class="hover:text-blue-400">Lessons</a>
                </div>
                <button class="md:hidden focus:outline-none">
                    <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                    </svg>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-image flex items-center justify-center">
        <div class="text-center px-4">
            <h1 class="text-4xl md:text-6xl font-bold text-white mb-4">The Office</h1>
            <h2 class="text-2xl md:text-3xl font-semibold text-blue-300 mb-8">A Case Study in Bad Management</h2>
            <p class="text-xl text-white max-w-2xl mx-auto">Analyzing poor management examples from Dunder Mifflin through the lens of established management theories.</p>
            <a href="#failures" class="mt-8 inline-block bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-lg transition duration-300">
                Explore Case Studies
            </a>
        </div>
    </section>

    <!-- Introduction Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto text-center">
                <h2 class="text-3xl font-bold text-gray-800 mb-6">Why Study The Office?</h2>
                <p class="text-lg text-gray-600 mb-8">
                    While "The Office" is primarily a comedy, it provides surprisingly accurate portrayals of management failures that plague real-world organizations. By examining Michael Scott's leadership through academic management theories, we can extract valuable lessons about what not to do as a manager.
                </p>
                <div class="flex flex-wrap justify-center gap-6 mt-10">
                    <div class="bg-gray-100 p-6 rounded-lg shadow-md theory-card w-full sm:w-1/2 lg:w-1/4">
                        <div class="text-blue-600 mb-4">
                            <svg class="h-10 w-10 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-2 text-gray-800">Scientific Management</h3>
                        <p class="text-gray-600">Analyzing Michael's inefficiency through Frederick Taylor's principles</p>
                    </div>
                    <div class="bg-gray-100 p-6 rounded-lg shadow-md theory-card w-full sm:w-1/2 lg:w-1/4">
                        <div class="text-blue-600 mb-4">
                            <svg class="h-10 w-10 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-2 text-gray-800">Administrative Theory</h3>
                        <p class="text-gray-600">Examining failures in Henri Fayol's 14 principles</p>
                    </div>
                    <div class="bg-gray-100 p-6 rounded-lg shadow-md theory-card w-full sm:w-1/2 lg:w-1/4">
                        <div class="text-blue-600 mb-4">
                            <svg class="h-10 w-10 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-3L13.732 4c-.77-1.333-2.694-1.333-3.464 0L3.34 16c-.77 1.333.192 3 1.732 3z" />
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-2 text-gray-800">Human Relations</h3>
                        <p class="text-gray-600">Understanding Elton Mayo's focus on employee happiness</p>
                    </div>
                    <div class="bg-gray-100 p-6 rounded-lg shadow-md theory-card w-full sm:w-1/2 lg:w-1/4">
                        <div class="text-blue-600 mb-4">
                            <svg class="h-10 w-10 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2" />
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-2 text-gray-800">Theory X & Y</h3>
                        <p class="text-gray-600">Evaluating Douglas McGregor's assumptions about workers</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About the Show Section -->
    <section id="about" class="py-16 bg-gray-100">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">About Dunder Mifflin</h2>
            <div class="flex flex-wrap -mx-4">
                <div class="w-full lg:w-1/2 px-4 mb-8 lg:mb-0">
                    <div class="bg-white p-8 rounded-lg shadow-md h-full">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-4">The Paper Company</h3>
                        <p class="text-gray-600 mb-4">
                            Dunder Mifflin is a fictional mid-sized paper company with branches across the northeastern United States. The Scranton branch, where most of the show takes place, is portrayed as having particularly dysfunctional management and office culture.
                        </p>
                        <p class="text-gray-600">
                            Despite being in a declining industry (paper sales in the digital age), the company survives through a combination of loyal customers, corporate inertia, and the occasional competent decision by its eccentric employees.
                        </p>
                        <div class="mt-6">
                            <img src="https://images.unsplash.com/photo-1521791055366-0d553872125f?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Office workspace" class="rounded-lg shadow-md w-full">
                        </div>
                    </div>
                </div>
                <div class="w-full lg:w-1/2 px-4">
                    <h3 class="text-2xl font-semibold text-gray-800 mb-6 text-center lg:text-left">Key Characters</h3>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div class="bg-white p-6 rounded-lg shadow-md character-card">
                            <div class="flex items-center mb-4">
                                <div class="h-16 w-16 rounded-full bg-blue-100 flex items-center justify-center mr-4">
                                    <svg class="h-8 w-8 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                    </svg>
                                </div>
                                <h4 class="text-xl font-semibold">Michael Scott</h4>
                            </div>
                            <p class="text-gray-600">
                                Regional Manager with poor leadership skills who constantly seeks approval from his employees while making inappropriate comments and decisions.
                            </p>
                        </div>
                        <div class="bg-white p-6 rounded-lg shadow-md character-card">
                            <div class="flex items-center mb-4">
                                <div class="h-16 w-16 rounded-full bg-blue-100 flex items-center justify-center mr-4">
                                    <svg class="h-8 w-8 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                    </svg>
                                </div>
                                <h4 class="text-xl font-semibold">Dwight Schrute</h4>
                            </div>
                            <p class="text-gray-600">
                                Assistant to the Regional Manager with extreme loyalty to authority but poor interpersonal skills and frequent conflicts with coworkers.
                            </p>
                        </div>
                        <div class="bg-white p-6 rounded-lg shadow-md character-card">
                            <div class="flex items-center mb-4">
                                <div class="h-16 w-16 rounded-full bg-blue-100 flex items-center justify-center mr-4">
                                    <svg class="h-8 w-8 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round, stroke-width="2" d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                    </svg>
                                </div>
                                <h4 class="text-xl font-semibold">Jim Halpert</h4>
                            </div>
                            <p class="text-gray-600">
                                Sales representative who is competent but frequently disengaged, spending much of his time pranking Dwight rather than focusing on work.
                            </p>
                        </div>
                        <div class="bg-white p-6 rounded-lg shadow-md character-card">
                            <div class="flex items-center mb-4">
                                <div class="h-16 w-16 rounded-full bg-blue-100 flex items-center justify-center mr-4">
                                    <svg class="h-8 w-8 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                    </svg>
                                </div>
                                <h4 class="text-xl font-semibold">Pam Beesly</h4>
                            </div>
                            <p class="text-gray-600">
                                Receptionist turned sales representative who often serves as the voice of reason but struggles with assertiveness and career advancement.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Management Failures Section -->
    <section id="failures" class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Management Failures & Theories</h2>
            
            <!-- Section A -->
            <div class="mb-20">
                <div class="flex flex-col lg:flex-row items-center mb-8">
                    <div class="lg:w-1/3 mb-6 lg:mb-0 lg:pr-8">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-4">Scientific Management Failures</h3>
                        <p class="text-gray-600 mb-4">
                            Michael Scott consistently ignores Frederick Taylor's principles of scientific management, resulting in wasted time, unclear job roles, and inefficient work methods throughout the office.
                        </p>
                        <div class="bg-blue-50 p-4 rounded-lg border-l-4 border-blue-500">
                            <h4 class="font-semibold text-blue-800 mb-2">Taylor's Scientific Management (1911)</h4>
                            <p class="text-blue-700">
                                Taylor advocated for scientifically studying work methods to determine the most efficient way to perform tasks, clear division of responsibilities, and cooperation between workers and management.
                            </p>
                        </div>
                    </div>
                    <div class="lg:w-2/3 bg-gray-100 p-8 rounded-lg">
                        <div class="flex flex-col md:flex-row">
                            <div class="md:w-1/2 mb-6 md:mb-0 md:pr-4">
                                <h4 class="text-xl font-semibold text-gray-800 mb-3">The Scene: "The Fire" Episode</h4>
                                <p class="text-gray-600 mb-4">
                                    During a fire drill, complete chaos ensues as no one knows proper procedures. Michael wastes time with inappropriate jokes while employees improvise unsafe solutions like throwing chairs out windows.
                                </p>
                                <div class="bg-white p-4 rounded-lg shadow-sm mb-4">
                                    <h5 class="font-semibold text-gray-700">Theory Application</h5>
                                    <p class="text-gray-600">
                                        This demonstrates the complete absence of scientific management principles. There's no standardized method for emergencies, no clear chain of command, and no efficient procedures - the exact opposite of Taylor's recommendations.
                                    </p>
                                </div>
                            </div>
                            <div class="md:w-1/2 md:pl-4">
                                <h4 class="text-xl font-semibold text-gray-800 mb-3">The Lesson for Managers</h4>
                                <ul class="space-y-3">
                                    <li class="flex items-start">
                                        <svg class="h-5 w-5 text-green-500 mr-2 mt-0.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>
                                        <span class="text-gray-700">Develop standardized methods for key tasks and procedures</span>
                                    </li>
                                    <li class="flex items-start">
                                        <svg class="h-5 w-5 text-green-500 mr-2 mt-0.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>
                                        <span class="text-gray-700">Clearly define roles and responsibilities</span>
                                    </li>
                                    <li class="flex items-start">
                                        <svg class="h-5 w-5 text-green-500 mr-2 mt-0.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>
                                        <span class="text-gray-700">Train employees in proper procedures rather than relying on improvisation</span>
                                    </li>
                                </ul>
                                <div class="mt-6 bg-gray-200 p-4 rounded-lg">
                                    <img src="https://images.unsplash.com/photo-1579389083078-4e7018379f7e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Efficient workplace" class="rounded-lg w-full">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Section B -->
            <div class="mb-20">
                <div class="flex flex-col lg:flex-row items-center mb-8">
                    <div class="lg:w-1/3 mb-6 lg:mb-0 lg:pr-8">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-4">Administrative Theory Failures</h3>
                        <p class="text-gray-600 mb-4">
                            Dunder Mifflin Scranton violates nearly all of Henri Fayol's 14 principles of management, particularly in areas of planning, coordination, and organizational structure.
                        </p>
                        <div class="bg-blue-50 p-4 rounded-lg border-l-4 border-blue-500">
                            <h4 class="font-semibold text-blue-800 mb-2">Fayol's Administrative Theory (1916)</h4>
                            <p class="text-blue-700">
                                Fayol outlined 14 principles including division of work, authority and responsibility, unity of command, unity of direction, and subordination of individual interests to general interests.
                            </p>
                        </div>
                    </div>
                    <div class="lg:w-2/3 bg-gray-100 p-8 rounded-lg">
                        <div class="flex flex-col md:flex-row">
                            <div class="md:w-1/2 mb-6 md:mb-0 md:pr-4">
                                <h4 class="text-xl font-semibold text-gray-800 mb-3">The Scene: "Branch Wars" Episode</h4>
                                <p class="text-gray-600 mb-4">
                                    Michael leads employees on an unauthorized mission to sabotage a competing branch, showing no regard for company hierarchy, policies, or proper channels of authority.
                                </p>
                                <div class="bg-white p-4 rounded-lg shadow-sm mb-4">
                                    <h5 class="font-semibold text-gray-700">Theory Application</h5>
                                    <p class="text-gray-600">
                                        This violates multiple Fayol principles: unity of command (employees receiving conflicting orders), unity of direction (no common objective), subordination of individual interests (Michael's ego over company needs), and proper authority structure.
                                    </p>
                                </div>
                            </div>
                            <div class="md:w-1/2 md:pl-4">
                                <h4 class="text-xl font-semibold text-gray-800 mb-3">The Lesson for Managers</h4>
                                <ul class="space-y-3">
                                    <li class="flex items-start">
                                        <svg class="h-5 w-5 text-green-500 mr-2 mt-0.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>
                                        <span class="text-gray-700">Establish clear organizational structure and chains of command</span>
                                    </li>
                                    <li class="flex items-start">
                                        <svg class="h-5 w-5 text-green-500 mr-2 mt-0.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>
                                        <span class="text-gray-700">Ensure all actions align with organizational objectives</span>
                                    </li>
                                    <li class="flex items-start">
                                        <svg class="h-5 w-5 text-green-500 mr-2 mt-0.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>
                                        <span class="text-gray-700">Balance authority with corresponding responsibility</span>
                                    </li>
                                </ul>
                                <div class="mt-6 bg-gray-200 p-4 rounded-lg">
                                    <img src="https://images.unsplash.com/photo-1552664730-d307ca884978?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Organizational structure" class="rounded-lg w-full">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Section C -->
            <div class="mb-20">
                <div class="flex flex-col lg:flex-row items-center mb-8">
                    <div class="lg:w-1/3 mb-6 lg:mb-0 lg:pr-8">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-4">Human Relations Theory Misapplication</h3>
                        <p class="text-gray-600 mb-4">
                            Michael Scott's obsession with being liked by his employees represents an exaggerated and misguided interpretation of Elton Mayo's human relations theory.
                        </p>
                        <div class="bg-blue-50 p-4 rounded-lg border-l-4 border-blue-500">
                            <h4 class="font-semibold text-blue-800 mb-2">Mayo's Human Relations Theory (1930s)</h4>
                            <p class="text-blue-700">
                                Mayo's Hawthorne studies showed that social factors and employee satisfaction impact productivity. However, this doesn't mean managers should prioritize popularity over performance.
                            </p>
                        </div>
                    </div>
                    <div class="lg:w-2/3 bg-gray-100 p-8 rounded-lg">
                        <div class="flex flex-col md:flex-row">
                            <div class="md:w-1/2 mb-6 md:mb-0 md:pr-4">
                                <h4 class="text-xl font-semibold text-gray-800 mb-3">The Scene: "Performance Review" Episode</h4>
                                <p class="text-gray-600 mb-4">
                                    Michael conducts employee reviews but can't deliver any constructive criticism, instead giving everyone glowing reviews to avoid conflict and maintain his popularity.
                                </p>
                                <div class="bg-white p-4 rounded-lg shadow-sm mb-4">
                                    <h5 class="font-semibold text-gray-700">Theory Application</h5>
                                    <p class="text-gray-600">
                                        While Mayo showed the importance of employee satisfaction, Michael takes this to an extreme where popularity becomes the sole objective, undermining performance management and organizational effectiveness.
                                    </p>
                                </div>
                            </div>
                            <div class="md:w-1/2 md:pl-4">
                                <h4 class="text-xl font-semibold text-gray-800 mb-3">The Lesson for Managers</h4>
                                <ul class="space-y-3">
                                    <li class="flex items-start">
                                        <svg class="h-5 w-5 text-green-500 mr-2 mt-0.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>
                                        <span class="text-gray-700">Balance employee satisfaction with performance expectations</span>
                                    </li>
                                    <li class="flex items-start">
                                        <svg class="h-5 w-5 text-green-500 mr-2 mt-0.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>
                                        <span class="text-gray-700">Provide constructive feedback even when difficult</span>
                                    </li>
                                    <li class="flex items-start">
                                        <svg class="h-5 w-5 text-green-500 mr-2 mt-0.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>
                                        <span class="text-gray-700">Recognize that respect is more important than popularity</span>
                                    </li>
                                </ul>
                                <div class="mt-6 bg-gray-200 p-4 rounded-lg">
                                    <img src="https://images.unsplash.com/photo-1556760544-74068565fdf3?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Employee relations" class="rounded-lg w-full">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Section D -->
            <div>
                <div class="flex flex-col lg:flex-row items-center mb-8">
                    <div class="lg:w-1/3 mb-6 lg:mb-0 lg:pr-8">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-4">Theory X & Y Mismatch</h3>
                        <p class="text-gray-600 mb-4">
                            Michael Scott assumes his employees are self-motivated (Theory Y) but fails to provide the proper structure, support, or environment that Theory Y workers need to thrive.
                        </p>
                        <div class="bg-blue-50 p-4 rounded-lg border-l-4 border-blue-500">
                            <h4 class="font-semibold text-blue-800 mb-2">McGregor's Theory X & Y (1960)</h4>
                            <p class="text-blue-700">
                                Theory X assumes workers need control/direction, while Theory Y assumes they're self-motivated. Effective Theory Y management requires creating conditions where this motivation can flourish.
                            </p>
                        </div>
                    </div>
                    <div class="lg:w-2/3 bg-gray-100 p-8 rounded-lg">
                        <div class="flex flex-col md:flex-row">
                            <div class="md:w-1/2 mb-6 md:mb-0 md:pr-4">
                                <h4 class="text-xl font-semibold text-gray-800 mb-3">The Scene: "The Surplus" Episode</h4>
                                <p class="text-gray-600 mb-4">
                                    Michael lets employees democratically decide how to spend a budget surplus, resulting in chaos as personal agendas dominate. He then overrides their decision anyway when corporate disapproves.
                                </p>
                                <div class="bg-white p-4 rounded-lg shadow-sm mb-4">
                                    <h5 class="font-semibold text-gray-700">Theory Application</h5>
                                    <p class="text-gray-600">
                                        Michael applies Theory Y principles (employee participation) without providing necessary structure or following through. This creates frustration rather than motivation, showing that Theory Y requires more than just good intentions.
                                    </p>
                                </div>
                            </div>
                            <div class="md:w-1/2 md:pl-4">
                                <h4 class="text-xl font-semibold text-gray-800 mb-3">The Lesson for Managers</h4>
                                <ul class="space-y-3">
                                    <li class="flex items-start">
                                        <svg class="h-5 w-5 text-green-500 mr-2 mt-0.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>
                                        <span class="text-gray-700">If assuming Theory Y, create proper conditions for self-direction</span>
                                    </li>
                                    <li class="flex items-start">
                                        <svg class="h-5 w-5 text-green-500 mr-2 mt-0.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>
                                        <span class="text-gray-700">Provide clear parameters for employee autonomy</span>
                                    </li>
                                    <li class="flex items-start">
                                        <svg class="h-5 w-5 text-green-500 mr-2 mt-0.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>
                                        <span class="text-gray-700">Follow through on participatory decisions or don't offer them</span>
                                    </li>
                                </ul>
                                <div class="mt-6 bg-gray-200 p-4 rounded-lg">
                                    <img src="https://images.unsplash.com/photo-1450101499163-c8848c66ca85?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Employee motivation" class="rounded-lg w-full">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Real-World Connection Section -->
    <section id="real-world" class="py-16 bg-gray-100">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto">
                <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Real-World Connection: Dunder Mifflin vs. Twitter/X</h2>
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <div class="md:flex">
                        <div class="md:w-1/2 p-8">
                            <h3 class="text-2xl font-semibold text-gray-800 mb-4">Dunder Mifflin Parallels</h3>
                            <ul class="space-y-4">
                                <li class="flex items-start">
                                    <div class="flex-shrink-0 h-6 w-6 rounded-full bg-blue-100 flex items-center justify-center mr-3">
                                        <svg class="h-4 w-4 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                                        </svg>
                                    </div>
                                    <p class="text-gray-600">Incompetent leadership more focused on being liked than achieving results</p>
                                </li>
                                <li class="flex items-start">
                                    <div class="flex-shrink-0 h-6 w-6 rounded-full bg-blue-100 flex items-center justify-center mr-3">
                                        <svg class="h-4 w-4 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                                        </svg>
                                    </div>
                                    <p class="text-gray-600">Impulsive decision-making without proper analysis or consultation</p>
                                </li>
                                <li class="flex items-start">
                                    <div class="flex-shrink-0 h-6 w-6 rounded-full bg-blue-100 flex items-center justify-center mr-3">
                                        <svg class="h-4 w-4 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                                        </svg>
                                    </div>
                                    <p class="text-gray-600">High employee turnover due to poor management and toxic culture</p>
                                </li>
                                <li class="flex items-start">
                                    <div class="flex-shrink-0 h-6 w-6 rounded-full bg-blue-100 flex items-center justify-center mr-3">
                                        <svg class="h-4 w-4 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                                        </svg>
                                    </div>
                                    <p class="text-gray-600">Public relations disasters from inappropriate comments and actions</p>
                                </li>
                            </ul>
                        </div>
                        <div class="md:w-1/2 bg-blue-600 p-8 text-white">
                            <h3 class="text-2xl font-semibold mb-4">Elon Musk's Twitter/X Management</h3>
                            <div class="mb-6">
                                <div class="flex items-center mb-2">
                                    <svg class="h-5 w-5 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                                    </svg>
                                    <span class="font-semibold">Leadership Style</span>
                                </div>
                                <p class="pl-7">Musk's erratic, impulsive leadership style mirrors Michael Scott's, with sudden policy changes and public outbursts replacing thoughtful management.</p>
                            </div>
                            <div class="mb-6">
                                <div class="flex items-center mb-2">
                                    <svg class="h-5 w-5 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                                    </svg>
                                    <span class="font-semibold">Employee Relations</span>
                                </div>
                                <p class="pl-7">Like Dunder Mifflin, Twitter/X has suffered mass resignations and low morale due to poor communication, sudden layoffs, and unrealistic demands.</p>
                            </div>
                            <div>
                                <div class="flex items-center mb-2">
                                    <svg class="h-5 w-5 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.172 16.172a4 4 0 015.656 0M9 10h.01M15 10h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                                    </svg>
                                    <span class="font-semibold">Decision Making</span>
                                </div>
                                <p class="pl-7">Musk's abrupt decisions (like banning then unbanning accounts) reflect the same lack of rational process seen in Michael Scott's management.</p>
                            </div>
                        </div>
                    </div>
                    <div class="p-8 bg-gray-50">
                        <h3 class="text-xl font-semibold text-gray-800 mb-4">Key Takeaway</h3>
                        <p class="text-gray-600">
                            While exaggerated for comedy, The Office's portrayal of bad management contains important lessons for real-world organizations. The Twitter/X case demonstrates how even successful companies can fall into similar patterns of dysfunction when leadership lacks proper management skills and emotional intelligence.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Lessons for Managers Section -->
    <section id="lessons" class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Lessons for Managers</h2>
            <div class="max-w-4xl mx-auto">
                <div class="grid md:grid-cols-2 gap-8">
                    <div class="bg-gray-50 p-8 rounded-lg shadow-sm">
                        <div class="flex items-center mb-4">
                            <div class="h-12 w-12 rounded-full bg-blue-100 flex items-center justify-center mr-4">
                                <span class="text-blue-600 font-bold text-xl">1</span>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-800">Apply Scientific Management Properly</h3>
                        </div>
                        <p class="text-gray-600">
                            Implement Taylor's principles by establishing efficient work methods, clear job roles, and proper training. Avoid Michael's haphazard approach that leads to wasted time and unsafe improvisation during critical situations.
                        </p>
                    </div>
                    <div class="bg-gray-50 p-8 rounded-lg shadow-sm">
                        <div class="flex items-center mb-4">
                            <div class="h-12 w-12 rounded-full bg-blue-100 flex items-center justify-center mr-4">
                                <span class="text-blue-600 font-bold text-xl">2</span>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-800">Follow Administrative Principles</h3>
                        </div>
                        <p class="text-gray-600">
                            Structure your organization according to Fayol's principles with clear chains of command, unity of direction, and proper coordination. Don't let personal agendas or ego-driven decisions undermine organizational objectives.
                        </p>
                    </div>
                    <div class="bg-gray-50 p-8 rounded-lg shadow-sm">
                        <div class="flex items-center mb-4">
                            <div class="h-12 w-12 rounded-full bg-blue-100 flex items-center justify-center mr-4">
                                <span class="text-blue-600 font-bold text-xl">3</span>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-800">Balance Human Relations with Performance</h3>
                        </div>
                        <p class="text-gray-600">
                            While employee satisfaction matters (Mayo), don't sacrifice performance management for popularity like Michael. Provide constructive feedback and maintain appropriate professional boundaries.
                        </p>
                    </div>
                    <div class="bg-gray-50 p-8 rounded-lg shadow-sm">
                        <div class="flex items-center mb-4">
                            <div class="h-12 w-12 rounded-full bg-blue-100 flex items-center justify-center mr-4">
                                <span class="text-blue-600 font-bold text-xl">4</span>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-800">Implement Theory Y Correctly</h3>
                        </div>
                        <p class="text-gray-600">
                            If you assume employees are self-motivated (McGregor's Theory Y), create the proper structure and environment for this to flourish. Don't just give autonomy without support like Michael's failed democratic exercises.
                        </p>
                    </div>
                </div>
                <div class="mt-12 bg-blue-50 p-8 rounded-lg border-l-4 border-blue-500">
                    <h3 class="text-xl font-semibold text-blue-800 mb-4">Final Thought</h3>
                    <p class="text-blue-700">
                        The Office provides exaggerated but insightful examples of management failures. By understanding these four key theories and how Michael Scott violates them, managers can avoid similar mistakes and create more effective, productive workplaces.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- References Section -->
    <section class="py-16 bg-gray-100">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto">
                <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">📚 Key Management Theories from Class in The Office</h2>
                <div class="bg-white p-8 rounded-lg shadow-sm">
                    <p class="text-lg text-gray-700 mb-6">
                        These four core theories from our class help explain management in The Office:
                    </p>
                    
                    <div class="mb-8">
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">Scientific Management (Frederick Taylor)</h3>
                        <p class="text-gray-600 pl-4 border-l-4 border-blue-500">
                            Michael often ignores efficient work methods, resulting in wasted time and unclear job roles — the opposite of Taylor's approach.
                        </p>
                    </div>
                    
                    <div class="mb-8">
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">Administrative Theory (Henri Fayol)</h3>
                        <p class="text-gray-600 pl-4 border-l-4 border-blue-500">
                            The lack of proper planning, coordination, and authority structure at Dunder Mifflin shows failures in Fayol's 14 principles.
                        </p>
                    </div>
                    
                    <div class="mb-8">
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">Human Relations Theory (Elton Mayo)</h3>
                        <p class="text-gray-600 pl-4 border-l-4 border-blue-500">
                            Michael's obsession with being liked shows an exaggerated focus on employee happiness over productivity.
                        </p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">Theory X and Theory Y (Douglas McGregor)</h3>
                        <p class="text-gray-600 pl-4 border-l-4 border-blue-500">
                            Michael treats workers like Theory Y — assuming they're self-motivated — but doesn't provide proper structure or support.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-8">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-4 md:mb-0">
                    <div class="flex items-center">
                        <svg class="h-8 w-8 text-blue-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
                        </svg>
                        <span class="ml-2 text-xl font-semibold">Office Management Study</span>
                    </div>
                    <p class="mt-2 text-gray-400">Analyzing management through The Office</p>
                </div>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-white">
                        <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z" />
                        </svg>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white">
                        <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z" />
                        </svg>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white">
                        <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z" />
                        </svg>
                    </a>
                </div>
            </div>
            <div class="mt-8 border-t border-gray-800 pt-8 flex flex-col md:flex-row justify-between">
                <p class="text-gray-400 text-sm">
                    © 2023 Office Management Study. All rights reserved.
                </p>
                <div class="mt-4 md:mt-0">
                    <a href="#" class="text-gray-400 hover:text-white text-sm mr-4">Privacy Policy</a>
                    <a href="#" class="text-gray-400 hover:text-white text-sm mr-4">Terms of Service</a>
                    <a href="#" class="text-gray-400 hover:text-white text-sm">Contact</a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Mobile menu toggle functionality would go here
        // This is a placeholder for actual implementation
    </script>
</body>
</html>
