# portfolio-by-ai-agent
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alvin Antony Jomon - Robotics & Simulation Engineer Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            color: #333;
            background-color: #f8fafc;
        }
        h1, h2, h3, h4, h5 {
            font-family: 'Montserrat', sans-serif;
        }
        .hero-bg {
            background: linear-gradient(135deg, #2c3e50, #3498db);
            clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
        }
        .section-title {
            position: relative;
            color: #2c3e50;
            padding-bottom: 10px;
        }
        .section-title:after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 60px;
            height: 3px;
            background: #3498db;
        }
        .skill-bar {
            height: 10px;
            background: #e2e8f0;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        .skill-progress {
            height: 10px;
            border-radius: 5px;
            background: linear-gradient(to right, #3498db, #2c3e50);
        }
        .timeline-item {
            position: relative;
            padding-left: 30px;
            margin-bottom: 30px;
        }
        .timeline-item:before {
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: #3498db;
        }
        .timeline-item:after {
            content: '';
            position: absolute;
            left: 5px;
            top: 12px;
            width: 2px;
            height: calc(100% + 18px);
            background: #e2e8f0;
        }
        .timeline-item:last-child:after {
            display: none;
        }
        .project-card {
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
        }
        .contact-info i {
            width: 24px;
            text-align: center;
            margin-right: 10px;
            color: #3498db;
        }
        .bg-primary {
            background-color: #3498db;
        }
        .text-primary {
            color: #3498db;
        }
        .border-primary {
            border-color: #3498db;
        }
        .progress-container {
            width: 100%;
            background-color: #e0e0e0;
            border-radius: 4px;
            margin-bottom: 10px;
        }
        .progress-bar {
            height: 6px;
            border-radius: 4px;
            background-color: #3498db;
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="hero-bg text-white min-h-screen flex items-center">
        <div class="container mx-auto px-4 py-24">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="text-4xl md:text-6xl font-bold mb-4">Alvin Antony Jomon</h1>
                    <h2 class="text-2xl md:text-3xl font-light mb-8">Robotics & Simulation Engineer</h2>
                    <p class="text-lg mb-8">Results-driven Robotics and Simulation Engineer with industry experience and a degree in Robotics and Automation. Skilled in design, development, implementation and process working of robots using Process simulator, Roboguide simulator and C++.</p>
                    <div class="flex space-x-4">
                        <a href="#contact" class="bg-white text-gray-800 px-6 py-3 rounded-full font-medium hover:bg-gray-200 transition duration-300">Contact Me</a>
                        <a href="#projects" class="border-2 border-white px-6 py-3 rounded-full font-medium hover:bg-white hover:text-gray-800 transition duration-300">View Projects</a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <img src="https://images.ctfassets.net/17si5cpawjzf/OBZy4ElUasHaicoQFtZeb/2793f69879c63153f04a78792ba64d65/tecnomatix-process-simulate-tc-1200x600.jpg" alt="Process Simulation Software" class="rounded-lg shadow-xl w-full max-w-md">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="section-title text-3xl font-bold mb-12">About Me</h2>
            <div class="flex flex-col md:flex-row">
                <div class="md:w-2/3 pr-0 md:pr-10 mb-10 md:mb-0">
                    <p class="text-lg text-gray-700 mb-6">I am a passionate Robotics and Simulation Engineer with a strong foundation in automation technologies and programming. My expertise lies in using sophisticated simulation software to design, test, and optimize robotic systems before physical implementation.</p>
                    <p class="text-lg text-gray-700 mb-6">With hands-on experience in both Process simulator for KUKA and FANUC robots and Roboguide simulator, I bring a practical approach to robotics engineering challenges. My background in C++ programming allows me to develop robust control systems that enhance robot functionality and performance.</p>
                    <p class="text-lg text-gray-700">I thrive in collaborative environments where I can apply my technical skills alongside critical thinking to solve complex engineering problems. My goal is to contribute to the advancement of robotic systems that improve efficiency, safety, and innovation across industries.</p>
                </div>
                <div class="md:w-1/3">
                    <div class="bg-gray-100 p-6 rounded-lg shadow-md">
                        <h3 class="font-bold text-xl mb-4 text-gray-800">Personal Details</h3>
                        <ul class="space-y-3">
                            <li class="flex items-center">
                                <i class="fas fa-map-marker-alt mr-3 text-primary"></i>
                                <span>Chittilappilly House, Thrissur, Kerala 680590</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-envelope mr-3 text-primary"></i>
                                <span>alvjom@gmail.com</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-phone mr-3 text-primary"></i>
                                <span>+91 9633391298</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-graduation-cap mr-3 text-primary"></i>
                                <span>B.Tech in Robotics and Automation</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="section-title text-3xl font-bold mb-12">Technical Skills</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div>
                    <h3 class="text-xl font-semibold mb-6 text-gray-800">Technical Expertise</h3>
                    
                    <div class="mb-6">
                        <div class="flex justify-between mb-1">
                            <span class="font-medium">Process Simulator</span>
                            <span>90%</span>
                        </div>
                        <div class="progress-container">
                            <div class="progress-bar" style="width: 90%"></div>
                        </div>
                    </div>
                    
                    <div class="mb-6">
                        <div class="flex justify-between mb-1">
                            <span class="font-medium">Roboguide Simulator</span>
                            <span>85%</span>
                        </div>
                        <div class="progress-container">
                            <div class="progress-bar" style="width: 85%"></div>
                        </div>
                    </div>
                    
                    <div class="mb-6">
                        <div class="flex justify-between mb-1">
                            <span class="font-medium">Fusion 360 Designing</span>
                            <span>80%</span>
                        </div>
                        <div class="progress-container">
                            <div class="progress-bar" style="width: 80%"></div>
                        </div>
                    </div>
                    
                    <div class="mb-6">
                        <div class="flex justify-between mb-1">
                            <span class="font-medium">C++ Programming</span>
                            <span>75%</span>
                        </div>
                        <div class="progress-container">
                            <div class="progress-bar" style="width: 75%"></div>
                        </div>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold mb-6 text-gray-800">Professional Skills</h3>
                    
                    <div class="mb-6">
                        <div class="flex justify-between mb-1">
                            <span class="font-medium">Critical Thinking</span>
                            <span>95%</span>
                        </div>
                        <div class="progress-container">
                            <div class="progress-bar" style="width: 95%"></div>
                        </div>
                    </div>
                    
                    <div class="mb-6">
                        <div class="flex justify-between mb-1">
                            <span class="font-medium">Communication</span>
                            <span>90%</span>
                        </div>
                        <div class="progress-container">
                            <div class="progress-bar" style="width: 90%"></div>
                        </div>
                    </div>
                    
                    <div class="mb-6">
                        <div class="flex justify-between mb-1">
                            <span class="font-medium">Team Collaboration</span>
                            <span>85%</span>
                        </div>
                        <div class="progress-container">
                            <div class="progress-bar" style="width: 85%"></div>
                        </div>
                    </div>
                    
                    <div class="mb-6">
                        <div class="flex justify-between mb-1">
                            <span class="font-medium">Organization</span>
                            <span>85%</span>
                        </div>
                        <div class="progress-container">
                            <div class="progress-bar" style="width: 85%"></div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="mt-16">
                <h3 class="text-xl font-semibold mb-6 text-gray-800">Key Technologies</h3>
                <div class="flex flex-wrap gap-3">
                    <span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full">KUKA Robotics</span>
                    <span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full">FANUC Robotics</span>
                    <span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full">Process Simulator</span>
                    <span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full">Roboguide</span>
                    <span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full">Fusion 360</span>
                    <span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full">C++</span>
                    <span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full">Robot Teaching</span>
                    <span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full">Robot Jogging</span>
                    <span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full">Automation</span>
                    <span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full">Simulation</span>
                    <span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full">Gazebo</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="section-title text-3xl font-bold mb-12">Professional Experience</h2>
            
            <div class="timeline">
                <div class="timeline-item">
                    <div class="mb-4">
                        <h3 class="text-xl font-bold">Robotics and Simulation Engineer</h3>
                        <p class="text-gray-600">Putumai Innovative Engineering Automation Private Limited | June 2024 - Present</p>
                    </div>
                    <div class="text-gray-700">
                        <ul class="list-disc pl-5 space-y-2">
                            <li>Hands-on experience in process simulator (simulation software) for KUKA and FANUC robots</li>
                            <li>Implementation of C++ programming for robotic control and automation</li>
                            <li>Collaboration with cross-functional teams for project implementation</li>
                            <li>Quality assurance and safety standards enforcement in robotic system design</li>
                            <li>Process optimization and efficiency improvements in robotic operations</li>
                        </ul>
                    </div>
                </div>
                
                <div class="timeline-item">
                    <div class="mb-4">
                        <h3 class="text-xl font-bold">Robotics and Simulation Engineer (Intern)</h3>
                        <p class="text-gray-600">Putumai Innovative Engineering Automation Private Limited | March 2024 - May 2024</p>
                    </div>
                    <div class="text-gray-700">
                        <ul class="list-disc pl-5 space-y-2">
                            <li>Gained hands-on experience with Roboguide simulation software for FANUC robots</li>
                            <li>Performed robot teaching and jogging operations for KUKA and FANUC robots</li>
                            <li>Assisted in testing and validating robotic simulations</li>
                            <li>Participated in team projects related to automation solutions</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="section-title text-3xl font-bold mb-12">Education</h2>
            
            <div class="bg-white p-8 rounded-lg shadow-md">
                <div class="flex flex-col md:flex-row justify-between mb-4">
                    <h3 class="text-xl font-bold">Bachelor of Technology in Robotics and Automation</h3>
                    <span class="text-gray-600">2020 - 2024</span>
                </div>
                <p class="text-lg mb-4">Kalam Technical University</p>
                <p class="text-gray-700">Completed a comprehensive program focused on robotics, automation technologies, control systems, and programming. The curriculum provided both theoretical knowledge and practical experience in designing and implementing robotic systems.</p>
                <div class="mt-6">
                    <h4 class="font-semibold mb-2">Key Coursework:</h4>
                    <ul class="grid grid-cols-1 md:grid-cols-2 gap-2">
                        <li class="flex items-center"><i class="fas fa-check-circle text-green-500 mr-2"></i> Robotics Engineering</li>
                        <li class="flex items-center"><i class="fas fa-check-circle text-green-500 mr-2"></i> Automation Systems</li>
                        <li class="flex items-center"><i class="fas fa-check-circle text-green-500 mr-2"></i> Control Systems Design</li>
                        <li class="flex items-center"><i class="fas fa-check-circle text-green-500 mr-2"></i> Computer Programming</li>
                        <li class="flex items-center"><i class="fas fa-check-circle text-green-500 mr-2"></i> Mechanical Engineering</li>
                        <li class="flex items-center"><i class="fas fa-check-circle text-green-500 mr-2"></i> Sensor Technologies</li>
                        <li class="flex items-center"><i class="fas fa-check-circle text-green-500 mr-2"></i> Robot Kinematics</li>
                        <li class="flex items-center"><i class="fas fa-check-circle text-green-500 mr-2"></i> Machine Vision</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="section-title text-3xl font-bold mb-12">Featured Projects</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="project-card bg-white">
                    <div class="h-64 overflow-hidden">
                        <img src="https://images.ctfassets.net/17si5cpawjzf/OBZy4ElUasHaicoQFtZeb/2793f69879c63153f04a78792ba64d65/tecnomatix-process-simulate-tc-1200x600.jpg" alt="TVS Three Wheeler Project" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">TVS Three Wheeler Project</h3>
                        <p class="text-gray-700 mb-4">Worked on robot teaching, quality improvement, and cycle time optimization for the manufacturing process of TVS three-wheeler vehicles.</p>
                        <div class="mb-4">
                            <h4 class="font-semibold mb-2">Key Achievements:</h4>
                            <ul class="list-disc pl-5 space-y-1 text-gray-700">
                                <li>Implemented robot teaching processes that improved precision by 15%</li>
                                <li>Optimized manufacturing cycle time, resulting in 20% increased efficiency</li>
                                <li>Enhanced quality control measures through automated inspection processes</li>
                                <li>Collaborated with cross-functional teams to implement process improvements</li>
                            </ul>
                        </div>
                        <div class="flex flex-wrap gap-2">
                            <span class="bg-gray-200 text-gray-800 px-3 py-1 rounded-full text-sm">Robot Teaching</span>
                            <span class="bg-gray-200 text-gray-800 px-3 py-1 rounded-full text-sm">Process Optimization</span>
                            <span class="bg-gray-200 text-gray-800 px-3 py-1 rounded-full text-sm">Quality Control</span>
                        </div>
                    </div>
                </div>
                
                <div class="project-card bg-white">
                    <div class="h-64 overflow-hidden">
                        <img src="https://mfe-is.com/wp-content/uploads/2024/09/pivot-rov-underwater-drone-1.webp" alt="Underwater Drone" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Underwater Drone</h3>
                        <p class="text-gray-700 mb-4">Designed mechanical systems for an underwater drone using Fusion 360 and implemented simulation testing using Gazebo software.</p>
                        <div class="mb-4">
                            <h4 class="font-semibold mb-2">Key Achievements:</h4>
                            <ul class="list-disc pl-5 space-y-1 text-gray-700">
                                <li>Created detailed 3D mechanical designs using Fusion 360</li>
                                <li>Conducted comprehensive simulation testing in Gazebo environment</li>
                                <li>Optimized drone maneuverability for underwater conditions</li>
                                <li>Implemented waterproofing solutions for electronic components</li>
                            </ul>
                        </div>
                        <div class="flex flex-wrap gap-2">
                            <span class="bg-gray-200 text-gray-800 px-3 py-1 rounded-full text-sm">Fusion 360</span>
                            <span class="bg-gray-200 text-gray-800 px-3 py-1 rounded-full text-sm">Gazebo</span>
                            <span class="bg-gray-200 text-gray-800 px-3 py-1 rounded-full text-sm">Mechanical Design</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Process & Tools Section -->
    <section id="tools" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="section-title text-3xl font-bold mb-12">Process & Tools</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div>
                    <h3 class="text-xl font-semibold mb-6">My Workflow</h3>
                    <div class="space-y-8">
                        <div class="flex">
                            <div class="flex-shrink-0 mr-4">
                                <div class="w-10 h-10 bg-blue-500 rounded-full flex items-center justify-center text-white font-bold">1</div>
                            </div>
                            <div>
                                <h4 class="text-lg font-medium mb-2">Requirements Analysis</h4>
                                <p class="text-gray-700">Thorough analysis of project requirements, constraints, and objectives to establish clear success metrics.</p>
                            </div>
                        </div>
                        
                        <div class="flex">
                            <div class="flex-shrink-0 mr-4">
                                <div class="w-10 h-10 bg-blue-500 rounded-full flex items-center justify-center text-white font-bold">2</div>
                            </div>
                            <div>
                                <h4 class="text-lg font-medium mb-2">Design & Simulation</h4>
                                <p class="text-gray-700">Creating detailed 3D models and simulating functionality before physical implementation to optimize design.</p>
                            </div>
                        </div>
                        
                        <div class="flex">
                            <div class="flex-shrink-0 mr-4">
                                <div class="w-10 h-10 bg-blue-500 rounded-full flex items-center justify-center text-white font-bold">3</div>
                            </div>
                            <div>
                                <h4 class="text-lg font-medium mb-2">Programming & Integration</h4>
                                <p class="text-gray-700">Implementing control systems with C++ and integrating with simulation environments for comprehensive testing.</p>
                            </div>
                        </div>
                        
                        <div class="flex">
                            <div class="flex-shrink-0 mr-4">
                                <div class="w-10 h-10 bg-blue-500 rounded-full flex items-center justify-center text-white font-bold">4</div>
                            </div>
                            <div>
                                <h4 class="text-lg font-medium mb-2">Optimization & Deployment</h4>
                                <p class="text-gray-700">Refining processes for efficiency, quality, and safety before final deployment and documentation.</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold mb-6">Software & Technologies</h3>
                    <div class="grid grid-cols-2 gap-6">
                        <div class="bg-white p-6 rounded-lg shadow-sm">
                            <img src="https://4dsysco.com/wp-content/uploads/2021/12/siemens-process-simulate-opt.png" alt="Process Simulator" class="h-16 mb-4">
                            <h4 class="font-medium mb-2">Process Simulator</h4>
                            <p class="text-sm text-gray-700">Advanced simulation software for industrial robots and automation systems</p>
                        </div>
                        
                        <div class="bg-white p-6 rounded-lg shadow-sm">
                            <img src="https://www.learnrobotics.org/wp-content/uploads/2019/08/Create-an-Assembly-in-Fusion-360-cover.jpg" alt="Fusion 360" class="h-16 mb-4">
                            <h4 class="font-medium mb-2">Fusion 360</h4>
                            <p class="text-sm text-gray-700">3D CAD, CAM, and CAE platform for product design and manufacturing</p>
                        </div>
                        
                        <div class="bg-white p-6 rounded-lg shadow-sm">
                            <div class="h-16 mb-4 flex items-center justify-center">
                                <i class="fas fa-code text-4xl text-blue-600"></i>
                            </div>
                            <h4 class="font-medium mb-2">C++ Programming</h4>
                            <p class="text-sm text-gray-700">High-performance programming language for robotic control systems</p>
                        </div>
                        
                        <div class="bg-white p-6 rounded-lg shadow-sm">
                            <div class="h-16 mb-4 flex items-center justify-center">
                                <i class="fas fa-robot text-4xl text-blue-600"></i>
                            </div>
                            <h4 class="font-medium mb-2">Robot Teaching</h4>
                            <p class="text-sm text-gray-700">Programming robot movements and operations through physical demonstration</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="section-title text-3xl font-bold mb-12">Contact Me</h2>
            
            <div class="bg-gray-50 rounded-lg shadow-md overflow-hidden">
                <div class="grid grid-cols-1 md:grid-cols-2">
                    <div class="p-8">
                        <h3 class="text-2xl font-bold mb-6">Get In Touch</h3>
                        <p class="text-gray-700 mb-6">I'm always interested in discussing new projects, creative ideas, or opportunities to be part of your vision.</p>
                        
                        <div class="space-y-4 contact-info">
                            <div class="flex items-center">
                                <i class="fas fa-phone-alt"></i>
                                <span>+91 9633391298</span>
                            </div>
                            <div class="flex items-center">
                                <i class="fas fa-envelope"></i>
                                <span>alvjom@gmail.com</span>
                            </div>
                            <div class="flex items-center">
                                <i class="fas fa-map-marker-alt"></i>
                                <span>Thrissur, Kerala 680590</span>
                            </div>
                        </div>
                        
                        <div class="mt-8">
                            <h4 class="font-semibold mb-4">Connect With Me</h4>
                            <div class="flex space-x-4">
                                <a href="#" class="w-10 h-10 rounded-full bg-gray-200 flex items-center justify-center hover:bg-blue-500 hover:text-white transition duration-300">
                                    <i class="fab fa-linkedin-in"></i>
                                </a>
                                <a href="#" class="w-10 h-10 rounded-full bg-gray-200 flex items-center justify-center hover:bg-blue-500 hover:text-white transition duration-300">
                                    <i class="fab fa-github"></i>
                                </a>
                                <a href="#" class="w-10 h-10 rounded-full bg-gray-200 flex items-center justify-center hover:bg-blue-500 hover:text-white transition duration-300">
                                    <i class="fab fa-twitter"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-gray-800 text-white p-8">
                        <h3 class="text-2xl font-bold mb-6">Send Me a Message</h3>
                        <form>
                            <div class="mb-4">
                                <label for="name" class="block text-sm font-medium mb-1">Your Name</label>
                                <input type="text" id="name" class="w-full bg-gray-700 border border-gray-600 rounded px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500">
                            </div>
                            
                            <div class="mb-4">
                                <label for="email" class="block text-sm font-medium mb-1">Email Address</label>
                                <input type="email" id="email" class="w-full bg-gray-700 border border-gray-600 rounded px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500">
                            </div>
                            
                            <div class="mb-4">
                                <label for="subject" class="block text-sm font-medium mb-1">Subject</label>
                                <input type="text" id="subject" class="w-full bg-gray-700 border border-gray-600 rounded px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500">
                            </div>
                            
                            <div class="mb-6">
                                <label for="message" class="block text-sm font-medium mb-1">Your Message</label>
                                <textarea id="message" rows="4" class="w-full bg-gray-700 border border-gray-600 rounded px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
                            </div>
                            
                            <button type="submit" class="bg-blue-500 hover:bg-blue-600 text-white px-6 py-3 rounded-md font-medium transition duration-300">Send Message</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-6 md:mb-0">
                    <h2 class="text-2xl font-bold">Alvin Antony Jomon</h2>
                    <p class="text-gray-400">Robotics & Simulation Engineer</p>
                </div>
                
                <div class="flex space-x-8">
                    <a href="#about" class="hover:text-blue-400 transition duration-300">About</a>
                    <a href="#skills" class="hover:text-blue-400 transition duration-300">Skills</a>
                    <a href="#experience" class="hover:text-blue-400 transition duration-300">Experience</a>
                    <a href="#projects" class="hover:text-blue-400 transition duration-300">Projects</a>
                    <a href="#contact" class="hover:text-blue-400 transition duration-300">Contact</a>
                </div>
            </div>
            
            <hr class="border-gray-700 my-8">
            
            <div class="flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400">&copy; 2024 Alvin Antony Jomon. All rights reserved.</p>
                <div class="flex space-x-4 mt-4 md:mt-0">
                    <a href="#" class="text-gray-400 hover:text-white transition duration-300">
                        <i class="fab fa-linkedin-in"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition duration-300">
                        <i class="fab fa-github"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition duration-300">
                        <i class="fab fa-twitter"></i>
                    </a>
                </div>
            </div>
        </div>
    </footer>
</body>
</html>
