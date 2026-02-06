<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Volantiq Solutions - AI Automation & Intelligent Agents</title>
    <meta name="description" content="Empower your business with AI automation, agents, and workflow optimization. Boost productivity, scalability, and ROI with Volantiq Solutions.">
    <meta name="keywords" content="AI automation, AI agents, workflow automation, business process optimization, custom AI solutions">
    <link rel="icon" href="logo.png">
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.9.1/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.9.1/ScrollTrigger.min.js"></script>
    <style>
        body { font-family: 'Inter', sans-serif; background: linear-gradient(135deg, #0f172a 0%, #1e3a8a 100%); color: #ffffff; }
        .hero-bg { background: url('https://via.placeholder.com/1920x1080/1e3a8a/ffffff?text=AI+Neural+Network') no-repeat center/cover; position: relative; }
        .hero-bg::before { content: ''; position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.5); }
        .gradient-text { background: linear-gradient(45deg, #3b82f6, #8b5cf6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .animate-pulse { animation: pulse 2s infinite; }
        .service-card { transition: transform 0.3s ease, box-shadow 0.3s ease; }
        .service-card:hover { transform: translateY(-10px); box-shadow: 0 10px 30px rgba(59, 130, 246, 0.3); }
    </style>
</head>
<body class="text-white">
    <!-- Header / Navigation -->
    <header class="fixed top-0 w-full bg-navy bg-opacity-90 backdrop-blur-md z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <img src="logo.png" alt="Volantiq Solutions Logo" class="h-10">
            <ul class="hidden md:flex space-x-8">
                <li><a href="#home" class="hover:text-blue-400 transition">Home</a></li>
                <li><a href="#services" class="hover:text-blue-400 transition">Services</a></li>
                <li><a href="#solutions" class="hover:text-blue-400 transition">Solutions</a></li>
                <li><a href="#about" class="hover:text-blue-400 transition">About</a></li>
                <li><a href="#portfolio" class="hover:text-blue-400 transition">Portfolio</a></li>
                <li><a href="#blog" class="hover:text-blue-400 transition">Blog</a></li>
                <li><a href="#contact" class="hover:text-blue-400 transition">Contact</a></li>
            </ul>
            <button class="md:hidden"><i class="fas fa-bars"></i></button>
        </nav>
    </header>

    <!-- Homepage Section -->
    <section id="home" class="hero-bg min-h-screen flex items-center justify-center text-center relative">
        <div class="container mx-auto px-6 z-10">
            <h1 class="text-5xl md:text-7xl font-bold mb-4 gradient-text animate-pulse">Volantiq Solutions — Powering Businesses with AI Automation & Intelligent Agents</h1>
            <p class="text-xl md:text-2xl mb-8">AI that automates workflows, boosts productivity, and scales operations.</p>
            <div class="space-x-4">
                <a href="#contact" class="bg-blue-600 hover:bg-blue-700 px-8 py-4 rounded-lg font-semibold transition">Get a Free Consultation</a>
                <a href="#services" class="border border-white hover:bg-white hover:text-navy px-8 py-4 rounded-lg font-semibold transition">See Our Solutions</a>
            </div>
            <!-- Animated AI Visuals (Circuits/Neural Networks) -->
            <div class="mt-12">
                <svg class="w-full h-64" viewBox="0 0 800 400">
                    <defs><linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="100%"><stop offset="0%" style="stop-color:#3b82f6"/><stop offset="100%" style="stop-color:#8b5cf6"/></linearGradient></defs>
                    <path d="M100 200 Q200 100 300 200 T500 200 Q600 300 700 200" stroke="url(#grad)" stroke-width="4" fill="none" class="animate-pulse"/>
                    <circle cx="100" cy="200" r="10" fill="#3b82f6"/><circle cx="300" cy="200" r="10" fill="#8b5cf6"/><circle cx="500" cy="200" r="10" fill="#3b82f6"/><circle cx="700" cy="200" r="10" fill="#8b5cf6"/>
                </svg>
            </div>
        </div>
    </section>

    <!-- Key Services Overview -->
    <section class="py-20 bg-gray-900">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-4xl font-bold mb-12">Our AI-Powered Services</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="service-card bg-navy p-6 rounded-lg">
                    <i class="fas fa-robot text-4xl text-blue-400 mb-4"></i>
                    <h3 class="text-2xl font-semibold mb-4">AI Agents for Business</h3>
                    <p>Intelligent agents that handle tasks autonomously, from data analysis to decision-making.</p>
                </div>
                <div class="service-card bg-navy p-6 rounded-lg">
                    <i class="fas fa-cogs text-4xl text-blue-400 mb-4"></i>
                    <h3 class="text-2xl font-semibold mb-4">Workflow Automation</h3>
                    <p>Streamline processes with AI-driven automation for maximum efficiency.</p>
                </div>
                <div class="service-card bg-navy p-6 rounded-lg">
                    <i class="fas fa-brain text-4xl text-blue-400 mb-4"></i>
                    <h3 class="text-2xl font-semibold mb-4">Custom AI Solutions</h3>
                    <p>Tailored AI software to meet your unique business needs.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose Us -->
    <section class="py-20 bg-gradient-to-r from-blue-900 to-purple-900">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-4xl font-bold mb-12">Why Choose Volantiq Solutions?</h2>
            <div class="grid md:grid-cols-4 gap-8">
                <div><i class="fas fa-tachometer-alt text-4xl text-blue-400 mb-4"></i><h3>Speed</h3><p>Lightning-fast AI implementations.</p></div>
                <div><i class="fas fa-expand-arrows-alt text-4xl text-blue-400 mb-4"></i><h3>Scalability</h3><p>Grow with AI that adapts.</p></div>
                <div><i class="fas fa-chart-line text-4xl text-blue-400 mb-4"></i><h3>ROI</h3><p>Measurable returns on investment.</p></div>
                <div><i class="fas fa-lightbulb text-4xl text-blue-400 mb-4"></i><h3>Innovation</h3><p>Cutting-edge AI technology.</p></div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-20 bg-gray-900">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-4xl font-bold mb-12">What Our Clients Say</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-navy p-6 rounded-lg"><p>"Volantiq's AI agents boosted our productivity by 40%!"</p><cite>- Tech Startup CEO</cite></div>
                <div class="bg-navy p-6 rounded-lg"><p>"ROI in just 3 months. Game-changer for our operations."</p><cite>- E-Commerce Director</cite></div>
            </div>
        </div>
    </section>

    <!-- Case Studies Preview -->
    <section class="py-20 bg-gradient-to-r from-purple-900 to-blue-900">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-4xl font-bold mb-12">Case Studies</h2>
            <div class="bg-navy p-8 rounded-lg"><h3>Healthcare Automation</h3><p>Problem: Manual data entry. Solution: AI agents. Result: 50% time savings, 30% ROI.</p></div>
        </div>
    </section>

    <!-- Contact CTA -->
    <section class="py-20 bg-gray-900 text-center">
        <h2 class="text-4xl font-bold mb-8">Ready to Automate Your Business?</h2>
        <a href="#contact" class="bg-blue-600 hover:bg-blue-700 px-8 py-4 rounded-lg font-semibold transition">Get Started</a>
    </section>

    <!-- Services Page Section -->
    <section id="services" class="py-20 bg-gray-800">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold text-center mb-12">Our Services</h2>
            <div class="space-y-12">
                <!-- AI Agents for Business -->
                <div class="bg-navy p-8 rounded-lg">
                    <h3 class="text-3xl font-semibold mb-4">AI Agents for Business</h3>
                    <p>Description: Autonomous AI agents for task automation.</p>
                    <p>Benefits: Efficiency, accuracy.</p>
                    <p>Use Cases: Data processing, customer interactions.</p>
                    <a href="#contact" class="bg-blue-600 px-6 py-3 rounded mt-4 inline-block">Learn More</a>
                </div>
                <!-- Repeat for other services: AI Automation, Customer Support AI Bots, etc. (Similar structure) -->
                <div class="bg-navy p-8 rounded-lg">
                    <h3 class="text-3xl font-semibold mb-4">AI Automation & Workflow Automation</h3>
                    <p>Description: Streamline repetitive tasks.</p>
                    <p>Benefits: Time savings, error reduction.</p>
                    <p>Use Cases: Invoice processing, email sorting.</p>
                    <a href="#contact" class="bg-blue-600 px-6 py-3 rounded mt-4 inline-block">Get Started</a>
                </div>
                <!-- Add similar blocks for all listed services -->
            </div>
        </div>
    </section>

    <!-- Solutions / Use Cases Page Section -->
    <section id="solutions" class="py-20 bg-gray-900">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold text-center mb-12">Industry Solutions</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-navy p-6 rounded-lg">
                    <h3 class="text-2xl font-semibold">Real Estate</h3>
                    <p>AI automates property listings, lead generation, and virtual tours, increasing sales by 25%.</p>
                </div>
                <!-- Repeat for E-Commerce, Healthcare, Finance, Law Firms, Startups, Enterprises -->
                <div class="bg-navy p-6 rounded-lg">
                    <h3 class="text-2xl font-semibold">Healthcare</h3>
                    <p>AI optimizes patient data management and diagnostics, reducing errors by 30%.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Us Page Section -->
    <section id="about" class="py-20 bg-gradient-to-r from-blue-900 to-purple-900">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-4xl font-bold mb-8">About Volantiq Solutions</h2>
            <p class="text-xl mb-4">Mission: Empower businesses with intelligent automation.</p>
            <p class="text-xl mb-4">Vision: Lead the future of AI-powered operations.</p>
            <p>Why Us? Innovative team, proven results, AI expertise.</p>
        </div>
    </section>

    <!-- Portfolio / Case Studies Section -->
    <section id="portfolio" class="py-20 bg-gray-800">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold text-center mb-12">Portfolio</h2>
            <div class="bg-navy p-8 rounded-lg">
                <h3>Project: E-Commerce Automation</h3>
                <p>Problem: Manual order processing. Solution: AI workflow bots. Results: 40% efficiency gain, $500K ROI.</p>
            </div>
        </div>
    </section>

    <!-- Blog / Insights Section -->
    <section id="blog" class="py-20 bg-gray-900">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold text-center mb-12">AI Insights</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-navy p-6 rounded-lg">
                    <h3>Latest AI Trends</h3>
                    <p>Exploring the future of AI agents.</p>
                </div>
                <!-- Add more blog posts -->
            </div>
        </div>
    </section>

    <!-- Contact Page Section -->
    <section id="contact" class="py-20 bg-gradient-to-r from-purple-900 to-blue-900">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-4xl font-bold mb-8">Let’s Automate Your Business</h2>
            <form class="max-w-md mx-auto" action="https://formspree.io/your-email" method="POST">
                <input type="text" name="name" placeholder="Name" class="w-full p-4 mb-4 bg-navy rounded" required>
                <input type="email" name="email" placeholder="Email" class="w-full p-4 mb-4 bg-navy rounded" required>
                <textarea name="message" placeholder="Message" class="w-full p-4 mb-4 bg-navy rounded" required></textarea>
                <button type="submit" class="bg-blue-600 px-8 py-4 rounded-lg font-semibold">Send Message</button>
            </form>
            <p class="mt-8">Email: info@volantiqsolutions.com | WhatsApp: <a href="https://wa.me/1234567890" class="text-blue-400">Chat Now</a></p>
            <p>Book a Meeting: <a href="https://calendly.com/volantiq" class="text-blue-400">Calendly</a></p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-navy
