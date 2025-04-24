<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Emma Reynolds - Virtual Assistant</title>
<script src="https://cdn.tailwindcss.com/3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#2563eb',secondary:'#93c5fd'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/remixicon@4.5.0/fonts/remixicon.css" rel="stylesheet">
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
body {
font-family: 'Inter', sans-serif;
}
.timeline-item::before {
content: '';
position: absolute;
left: -9px;
top: 0;
width: 18px;
height: 18px;
border-radius: 50%;
background-color: #4F46E5;
z-index: 1;
}
.timeline-item::after {
content: '';
position: absolute;
left: 0;
top: 0;
bottom: 0;
width: 1px;
background-color: #E5E7EB;
}
.timeline-item:last-child::after {
height: 0;
}
input::-webkit-outer-spin-button,
input::-webkit-inner-spin-button {
-webkit-appearance: none;
margin: 0;
}
input[type=number] {
-moz-appearance: textfield;
}
.skill-bar {
position: relative;
height: 8px;
border-radius: 4px;
background-color: #E5E7EB;
overflow: hidden;
}
.skill-progress {
position: absolute;
top: 0;
left: 0;
height: 100%;
background-color: #4F46E5;
border-radius: 4px;
}
.nav-link {
position: relative;
}
.nav-link::after {
content: '';
position: absolute;
bottom: -2px;
left: 0;
width: 0;
height: 2px;
background-color: #4F46E5;
transition: width 0.3s ease;
}
.nav-link.active::after,
.nav-link:hover::after {
width: 100%;
}
</style>
</head>
<body class="bg-[#F9F9F9] text-gray-800">
<!-- Header -->
<header class="sticky top-0 z-50 bg-[#1e40af] shadow-md">
<div class="container mx-auto px-4 py-4 flex justify-between items-center">
<div class="flex items-center">
<h1 class="text-2xl font-semibold text-white">Emma Reynolds</h1>
<span class="ml-3 text-sm text-white/80 font-medium">Virtual Assistant</span>
</div>
<nav class="hidden md:flex space-x-8">
<a href="#home" class="nav-link active text-white font-medium">Home</a>
<a href="#services" class="nav-link text-white/80 hover:text-white font-medium">Services</a>
<a href="#experience" class="nav-link text-white/80 hover:text-white font-medium">Experience</a>
<a href="#portfolio" class="nav-link text-white/80 hover:text-white font-medium">Portfolio</a>
<a href="#contact" class="nav-link text-white/80 hover:text-white font-medium">Contact</a>
</nav>
<button class="md:hidden w-10 h-10 flex items-center justify-center text-white">
<i class="ri-menu-line ri-lg"></i>
</button>
</div>
</header>
<!-- Hero Section -->
<section id="home" class="relative overflow-hidden py-16 md:py-24" style="background-image: url('https://readdy.ai/api/search-image?query=modern%20minimalist%20office%20interior%20with%20blue%20color%20scheme%2C%20floor%20to%20ceiling%20windows%2C%20sleek%20furniture%2C%20city%20skyline%20view%2C%20sophisticated%20workspace%2C%20cool%20lighting%2C%20premium%20finishes%2C%20ultra%20high%20end%20corporate%20environment%2C%20professional%20business%20setting%2C%20morning%20atmosphere%20with%20natural%20light%2C%208k%20ultra%20realistic&width=1920&height=1080&seq=1&orientation=landscape'); background-size: cover; background-position: center;">
<div class="absolute inset-0 bg-gradient-to-r from-white via-white/90 to-white/40"></div>
<div class="container mx-auto px-4 relative">
<div class="flex flex-col md:flex-row items-center">
<div class="md:w-1/2 mb-10 md:mb-0">
<h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">Your Dedicated Virtual Assistant</h2>
<p class="text-lg text-gray-700 mb-8 max-w-lg">As a seasoned virtual assistant with over 5 years of experience, I specialize in providing comprehensive executive support and business process optimization. My expertise spans document curation, digital marketing, and graphic design, along with strategic project management and sophisticated administrative solutions. I enable organizations to achieve operational excellence through meticulous attention to detail and proactive problem-solving approaches, delivering exceptional value across all aspects of business support.</p>
<div class="flex flex-wrap gap-4">
<button class="bg-primary text-white px-6 py-3 font-medium !rounded-button shadow-lg hover:shadow-xl transition-all whitespace-nowrap">Let's Connect</button>
<button class="bg-white text-primary border border-primary px-6 py-3 font-medium !rounded-button hover:bg-gray-50 transition-all whitespace-nowrap">View My Services</button>
</div>
</div>
<div class="md:w-1/2 flex justify-center">
<div class="relative w-64 h-64 md:w-80 md:h-80 rounded-full overflow-hidden border-4 border-white shadow-xl">
<img src="https://static.readdy.ai/image/555cf549ab80788018aac99b869c7aa7/82a28df2c013d5cb80bf88e51fc15cfb.jpeg" alt="Emma Reynolds" class="w-full h-full object-cover object-top">
</div>
</div>
</div>
</div>
</section>
<!-- Services Section -->
<section id="services" class="py-16 bg-[#F9F9F9]">
<div class="container mx-auto px-4">
<div class="text-center mb-16">
<h2 class="text-3xl font-bold text-gray-900 mb-4">My Services</h2>
<p class="text-gray-600 max-w-2xl mx-auto">I offer a comprehensive range of virtual assistance services tailored to meet your specific needs and help you focus on what matters most.</p>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<!-- Service 1 -->
<div class="bg-gray-50 p-8 rounded-lg shadow-sm hover:shadow-md transition-shadow">
<div class="w-14 h-14 bg-primary/10 rounded-lg flex items-center justify-center mb-6">
<i class="ri-mail-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3">Email Management</h3>
<p class="text-gray-300">Inbox organization, filtering important messages, drafting responses, and managing follow-ups to keep your communication efficient.</p>
</div>
<!-- Service 2 -->
<div class="bg-gray-50 p-8 rounded-lg shadow-sm hover:shadow-md transition-shadow">
<div class="w-14 h-14 bg-primary/10 rounded-lg flex items-center justify-center mb-6">
<i class="ri-calendar-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3">Calendar Organization</h3>
<p class="text-gray-300">Scheduling appointments, managing your calendar, sending reminders, and coordinating meetings to optimize your time.</p>
</div>
<!-- Service 3 -->
<div class="bg-gray-50 p-8 rounded-lg shadow-sm hover:shadow-md transition-shadow">
<div class="w-14 h-14 bg-primary/10 rounded-lg flex items-center justify-center mb-6">
<i class="ri-database-2-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3">Data Entry & Administration</h3>
<p class="text-gray-300">Accurate data entry, document preparation, file organization, and administrative support for your business operations.</p>
</div>
<!-- Service 4 -->
<div class="bg-gray-50 p-8 rounded-lg shadow-sm hover:shadow-md transition-shadow">
<div class="w-14 h-14 bg-primary/10 rounded-lg flex items-center justify-center mb-6">
<i class="ri-instagram-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3">Social Media Management</h3>
<p class="text-gray-300">Content scheduling, engagement monitoring, community management, and basic analytics reporting for your social platforms.</p>
</div>
<!-- Service 5 -->
<div class="bg-gray-50 p-8 rounded-lg shadow-sm hover:shadow-md transition-shadow">
<div class="w-14 h-14 bg-primary/10 rounded-lg flex items-center justify-center mb-6">
<i class="ri-customer-service-2-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3">Customer Support</h3>
<p class="text-gray-300">Responding to customer inquiries, managing tickets, providing information, and ensuring client satisfaction.</p>
</div>
<!-- Service 6 -->
<div class="bg-gray-50 p-8 rounded-lg shadow-sm hover:shadow-md transition-shadow">
<div class="w-14 h-14 bg-primary/10 rounded-lg flex items-center justify-center mb-6">
<i class="ri-task-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3">Project Coordination</h3>
<p class="text-gray-300">Task management, progress tracking, team coordination, and deadline monitoring to keep your projects on schedule.</p>
</div>
</div>
</div>
</section>
<!-- Experience & Skills Section -->
<section id="experience" class="py-16 bg-[#F9F9F9]">
<div class="container mx-auto px-4">
<div class="text-center mb-16">
<h2 class="text-3xl font-bold text-gray-900 mb-4">Experience & Skills</h2>
<p class="text-gray-600 max-w-2xl mx-auto">With over 5 years of experience as a virtual assistant, I've developed expertise in research, technical writing, graphic design, digital marketing (Meta Ads, TikTok, Google Ads), and administrative management, serving clients across various industries.</p>
</div>
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
<!-- Work Experience -->
<div>
<h3 class="text-2xl font-semibold mb-6">Work History</h3>
<div class="relative pl-10">
<!-- Experience 1 -->
<div class="timeline-item relative pb-12">
<div class="bg-white p-6 rounded-lg shadow-md">
<h4 class="text-lg font-semibold">Senior Virtual Assistant</h4>
<p class="text-primary font-medium">RemoteTeam Solutions</p>
<p class="text-sm text-gray-500 mb-3">Jan 2023 - Present</p>
<p class="text-gray-300">Providing comprehensive virtual assistance to C-level executives across multiple industries. Managing complex calendars, coordinating international travel, and handling sensitive communications.</p>
<div class="mt-4">
<span class="inline-block bg-primary/10 text-primary text-xs font-medium px-3 py-1 rounded-full mr-2 mb-2">Reduced email response time by 68%</span>
<span class="inline-block bg-primary/10 text-primary text-xs font-medium px-3 py-1 rounded-full mr-2 mb-2">Saved executives 15+ hours weekly</span>
</div>
</div>
</div>
<!-- Experience 2 -->
<div class="timeline-item relative pb-12">
<div class="bg-white p-6 rounded-lg shadow-md">
<h4 class="text-lg font-semibold">Virtual Executive Assistant</h4>
<p class="text-primary font-medium">Virtuoso Assistance Inc.</p>
<p class="text-sm text-gray-500 mb-3">Mar 2020 - Dec 2022</p>
<p class="text-gray-300">Supported multiple entrepreneurs and small business owners with administrative tasks, email management, and customer service. Implemented new systems for improved workflow efficiency.</p>
<div class="mt-4">
<span class="inline-block bg-primary/10 text-primary text-xs font-medium px-3 py-1 rounded-full mr-2 mb-2">Managed 5+ client accounts simultaneously</span>
<span class="inline-block bg-primary/10 text-primary text-xs font-medium px-3 py-1 rounded-full mr-2 mb-2">Improved client retention by 42%</span>
</div>
</div>
</div>
<!-- Experience 3 -->
<div class="timeline-item relative">
<div class="bg-white p-6 rounded-lg shadow-md">
<h4 class="text-lg font-semibold">Administrative Assistant</h4>
<p class="text-primary font-medium">Global Enterprises Ltd.</p>
<p class="text-sm text-gray-500 mb-3">Jun 2018 - Feb 2020</p>
<p class="text-gray-300">Handled general office administration, document management, and client communications. Assisted with event planning and coordination for company conferences.</p>
<div class="mt-4">
<span class="inline-block bg-primary/10 text-primary text-xs font-medium px-3 py-1 rounded-full mr-2 mb-2">Organized events for 200+ attendees</span>
<span class="inline-block bg-primary/10 text-primary text-xs font-medium px-3 py-1 rounded-full mr-2 mb-2">Digitized 1000+ documents</span>
</div>
</div>
</div>
</div>
</div>
<!-- Skills -->
<div>
<h3 class="text-2xl font-semibold mb-6">Skills & Expertise</h3>
<!-- Technical Skills -->
<div class="bg-white p-6 rounded-lg shadow-sm mb-8">
<h4 class="text-lg font-semibold mb-4">Technical Skills</h4>
<div class="mb-4">
<div class="flex justify-between mb-1">
<span class="text-gray-700 font-medium">Microsoft Office Suite</span>
<span class="text-primary font-medium">95%</span>
</div>
<div class="skill-bar">
<div class="skill-progress" style="width: 95%"></div>
</div>
</div>
<div class="mb-4">
<div class="flex justify-between mb-1">
<span class="text-gray-700 font-medium">Google Workspace</span>
<span class="text-primary font-medium">90%</span>
</div>
<div class="skill-bar">
<div class="skill-progress" style="width: 90%"></div>
</div>
</div>
<div class="mb-4">
<div class="flex justify-between mb-1">
<span class="text-gray-700 font-medium">CRM Systems</span>
<span class="text-primary font-medium">85%</span>
</div>
<div class="skill-bar">
<div class="skill-progress" style="width: 85%"></div>
</div>
</div>
<div class="mb-4">
<div class="flex justify-between mb-1">
<span class="text-gray-700 font-medium">Project Management Tools</span>
<span class="text-primary font-medium">88%</span>
</div>
<div class="skill-bar">
<div class="skill-progress" style="width: 88%"></div>
</div>
</div>
<div>
<div class="flex justify-between mb-1">
<span class="text-gray-700 font-medium">Social Media Platforms</span>
<span class="text-primary font-medium">92%</span>
</div>
<div class="skill-bar">
<div class="skill-progress" style="width: 92%"></div>
</div>
</div>
</div>
<!-- Certifications -->
<div class="bg-white p-6 rounded-lg shadow-md">
<h4 class="text-lg font-semibold mb-4">Certifications</h4>
<div class="flex items-start mb-4">
<div class="w-10 h-10 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-award-line text-primary"></i>
</div>
<div>
<h5 class="font-medium">Certified Virtual Assistant</h5>
<p class="text-sm text-gray-600">International Virtual Assistants Association</p>
</div>
</div>
<div class="flex items-start mb-4">
<div class="w-10 h-10 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-award-line text-primary"></i>
</div>
<div>
<h5 class="font-medium">Advanced Social Media Management</h5>
<p class="text-sm text-gray-600">Digital Marketing Institute</p>
</div>
</div>
<div class="flex items-start">
<div class="w-10 h-10 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-award-line text-primary"></i>
</div>
<div>
<h5 class="font-medium">Project Management Professional (PMP)</h5>
<p class="text-sm text-gray-600">Project Management Institute</p>
</div>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Portfolio Section -->
<section id="portfolio" class="py-16 bg-[#F9F9F9]">
<div class="container mx-auto px-4">
<div class="text-center mb-16">
<h2 class="text-3xl font-bold text-gray-900 mb-4">Portfolio Showcase</h2>
<p class="text-gray-600 max-w-2xl mx-auto">Browse through some of my recent projects and client success stories that demonstrate my capabilities as a virtual assistant.</p>
</div>
<!-- Portfolio Gallery -->
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-16">
<!-- Project 1 -->
<div class="bg-gray-50 rounded-lg overflow-hidden shadow-sm hover:shadow-md transition-shadow">
<div class="h-56 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=before%20and%20after%20comparison%20of%20organized%20email%20inbox%2C%20clean%20design%2C%20professional%20screenshot%2C%20organized%20folders%2C%20productivity%20improvement%20visualization%2C%20clear%20labels%2C%20business%20email%20organization%2C%20high%20quality&width=600&height=400&seq=3&orientation=landscape" alt="Email Management Project" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-2">Email Management Overhaul</h3>
<p class="text-gray-600 mb-4">Transformed a chaotic inbox with 10,000+ emails into an organized system with clear categories, automated filters, and efficient response protocols.</p>
<div class="flex justify-between items-center">
<span class="text-primary font-medium">Email Management</span>
<span class="bg-green-100 text-green-800 text-xs font-medium px-2.5 py-0.5 rounded">Completed</span>
</div>
</div>
</div>
<!-- Project 2 -->
<div class="bg-gray-50 rounded-lg overflow-hidden shadow-sm hover:shadow-md transition-shadow">
<div class="h-56 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=calendar%20organization%20system%2C%20professional%20calendar%20view%2C%20scheduled%20appointments%2C%20color-coded%20events%2C%20time%20management%2C%20productivity%20tool%2C%20clean%20design%2C%20business%20calendar&width=600&height=400&seq=4&orientation=landscape" alt="Calendar Organization Project" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-2">Executive Calendar Optimization</h3>
<p class="text-gray-600 mb-4">Designed and implemented a comprehensive calendar system for a C-suite executive, including color-coding, priority scheduling, and travel coordination.</p>
<div class="flex justify-between items-center">
<span class="text-primary font-medium">Calendar Management</span>
<span class="bg-green-100 text-green-800 text-xs font-medium px-2.5 py-0.5 rounded">Completed</span>
</div>
</div>
</div>
<!-- Project 3 -->
<div class="bg-gray-50 rounded-lg overflow-hidden shadow-sm hover:shadow-md transition-shadow">
<div class="h-56 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=social%20media%20content%20calendar%2C%20scheduled%20posts%2C%20engagement%20metrics%2C%20analytics%20dashboard%2C%20professional%20social%20media%20management%2C%20organized%20content%20plan%2C%20marketing%20strategy&width=600&height=400&seq=5&orientation=landscape" alt="Social Media Management Project" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-2">Social Media Growth Strategy</h3>
<p class="text-gray-600 mb-4">Developed and executed a comprehensive social media strategy for a small business, resulting in 150% follower growth and 200% engagement increase.</p>
<div class="flex justify-between items-center">
<span class="text-primary font-medium">Social Media</span>
<span class="bg-green-100 text-green-800 text-xs font-medium px-2.5 py-0.5 rounded">Completed</span>
</div>
</div>
</div>
</div>
<!-- Testimonials -->
<h3 class="text-2xl font-semibold text-center mb-8">Client Testimonials</h3>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<!-- Testimonial 1 -->
<div class="bg-white p-6 rounded-lg shadow-md">
<div class="flex items-center mb-4">
<div class="text-amber-400 flex">
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
</div>
</div>
<p class="text-gray-600 italic mb-6">"Emma has been an absolute game-changer for my business. Her attention to detail, proactive approach, and ability to anticipate my needs have freed up countless hours in my schedule. I couldn't recommend her highly enough!"</p>
<div class="flex items-center">
<div class="w-12 h-12 rounded-full overflow-hidden mr-4">
<img src="https://readdy.ai/api/search-image?query=professional%20headshot%20of%20middle-aged%20businessman%2C%20suit%2C%20neutral%20background%2C%20high%20quality%20portrait&width=100&height=100&seq=6&orientation=squarish" alt="Client" class="w-full h-full object-cover object-top">
</div>
<div>
<h4 class="font-semibold">Michael Richardson</h4>
<p class="text-sm text-gray-500">CEO, Innovate Solutions</p>
</div>
</div>
</div>
<!-- Testimonial 2 -->
<div class="bg-white p-6 rounded-lg shadow-md">
<div class="flex items-center mb-4">
<div class="text-amber-400 flex">
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
</div>
</div>
<p class="text-gray-600 italic mb-6">"Working with Emma has transformed how I manage my consulting practice. She handles everything from client communications to scheduling with incredible efficiency. My only regret is not hiring her sooner!"</p>
<div class="flex items-center">
<div class="w-12 h-12 rounded-full overflow-hidden mr-4">
<img src="https://readdy.ai/api/search-image?query=professional%20headshot%20of%20woman%20in%20business%20attire%2C%20confident%20smile%2C%20neutral%20background%2C%20high%20quality%20portrait&width=100&height=100&seq=7&orientation=squarish" alt="Client" class="w-full h-full object-cover object-top">
</div>
<div>
<h4 class="font-semibold">Sophia Martinez</h4>
<p class="text-sm text-gray-500">Principal Consultant, Clarity Consulting</p>
</div>
</div>
</div>
<!-- Testimonial 3 -->
<div class="bg-white p-6 rounded-lg shadow-md">
<div class="flex items-center mb-4">
<div class="text-amber-400 flex">
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-half-fill"></i>
</div>
</div>
<p class="text-gray-600 italic mb-6">"Emma's organizational skills are unmatched. She stepped in during a particularly chaotic time for our startup and implemented systems that have stood the test of time. She's professional, responsive, and incredibly talented."</p>
<div class="flex items-center">
<div class="w-12 h-12 rounded-full overflow-hidden mr-4">
<img src="https://readdy.ai/api/search-image?query=professional%20headshot%20of%20young%20entrepreneur%2C%20casual%20business%20attire%2C%20neutral%20background%2C%20high%20quality%20portrait&width=100&height=100&seq=8&orientation=squarish" alt="Client" class="w-full h-full object-cover object-top">
</div>
<div>
<h4 class="font-semibold">Daniel Thompson</h4>
<p class="text-sm text-gray-500">Founder, TechStart Ventures</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Contact Section -->
<section id="contact" class="py-16 bg-[#F9F9F9]">
<div class="container mx-auto px-4">
<div class="text-center mb-16">
<h2 class="text-3xl font-bold text-gray-900 mb-4">Let's Work Together</h2>
<p class="text-gray-600 max-w-2xl mx-auto">Ready to reclaim your time and boost your productivity? Get in touch to discuss how I can support your business needs.</p>
</div>
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
<!-- Contact Form -->
<div class="bg-white p-8 rounded-lg shadow-sm">
<h3 class="text-2xl font-semibold mb-6">Send Me a Message</h3>
<form>
<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
<div>
<label for="name" class="block text-sm font-medium text-gray-300 mb-2">Full Name</label>
<input type="text" id="name" class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" placeholder="Your name">
</div>
<div>
<label for="email" class="block text-sm font-medium text-gray-700 mb-2">Email Address</label>
<input type="email" id="email" class="w-full px-4 py-3 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" placeholder="Your email">
</div>
</div>
<div class="mb-6">
<label for="subject" class="block text-sm font-medium text-gray-700 mb-2">Subject</label>
<input type="text" id="subject" class="w-full px-4 py-3 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" placeholder="What is this regarding?">
</div>
<div class="mb-6">
<label for="message" class="block text-sm font-medium text-gray-700 mb-2">Message</label>
<textarea id="message" rows="5" class="w-full px-4 py-3 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" placeholder="Tell me about your project or needs..."></textarea>
</div>
<div class="mb-6">
<label class="flex items-center">
<div class="relative w-10 h-5 flex items-center">
<input type="checkbox" class="opacity-0 absolute w-0 h-0">
<span class="slider bg-gray-300 absolute cursor-pointer inset-0 rounded-full transition-all duration-300 before:absolute before:h-4 before:w-4 before:left-0.5 before:bottom-0.5 before:bg-white before:rounded-full before:transition-all before:duration-300"></span>
</div>
<span class="ml-3 text-sm text-gray-600">Subscribe to my newsletter for productivity tips</span>
</label>
</div>
<button type="submit" class="bg-primary text-white px-6 py-3 font-medium !rounded-button shadow hover:shadow-md transition-all whitespace-nowrap">Send Message</button>
</form>
</div>
<!-- Contact Information -->
<div>
<h3 class="text-2xl font-semibold mb-6">Contact Information</h3>
<div class="bg-white p-6 rounded-lg shadow-sm mb-8">
<div class="flex items-start mb-6">
<div class="w-10 h-10 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-mail-line text-primary"></i>
</div>
<div>
<h4 class="font-medium">Email</h4>
<p class="text-gray-300">emma.reynolds@virtualassistant.com</p>
<p class="text-sm text-gray-500 mt-1">I respond to all inquiries within 24 hours</p>
</div>
</div>
<div class="flex items-start mb-6">
<div class="w-10 h-10 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-time-line text-primary"></i>
</div>
<div>
<h4 class="font-medium">Business Hours</h4>
<p class="text-gray-300">Monday - Friday: 9:00 AM - 5:00 PM EST</p>
<p class="text-sm text-gray-500 mt-1">Weekend availability by arrangement</p>
</div>
</div>
<div class="flex items-start">
<div class="w-10 h-10 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-global-line text-primary"></i>
</div>
<div>
<h4 class="font-medium">Location</h4>
<p class="text-gray-300">Remote - Serving clients worldwide</p>
<p class="text-sm text-gray-500 mt-1">Video meetings available in your time zone</p>
</div>
</div>
</div>
<!-- Schedule a Call -->
<div class="bg-white p-6 rounded-lg shadow-md">
<h4 class="text-lg font-semibold mb-4">Schedule a Free Consultation</h4>
<p class="text-gray-600 mb-4">Book a 30-minute call to discuss your needs and how I can help you achieve your goals.</p>
<button class="bg-primary text-white px-6 py-3 font-medium !rounded-button shadow hover:shadow-md transition-all w-full whitespace-nowrap">
<i class="ri-calendar-line mr-2"></i> Book a Call
</button>
<div class="mt-6">
<h5 class="font-medium mb-3">Connect With Me</h5>
<div class="flex space-x-4">
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 hover:bg-primary/10 text-gray-600 hover:text-primary rounded-full transition-colors">
<i class="ri-linkedin-fill"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 hover:bg-primary/10 text-gray-600 hover:text-primary rounded-full transition-colors">
<i class="ri-twitter-fill"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 hover:bg-primary/10 text-gray-600 hover:text-primary rounded-full transition-colors">
<i class="ri-instagram-fill"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 hover:bg-primary/10 text-gray-600 hover:text-primary rounded-full transition-colors">
<i class="ri-facebook-fill"></i>
</a>
</div>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Footer -->
<footer class="bg-[#1e40af] text-white py-12">
<div class="container mx-auto px-4">
<div class="flex flex-col md:flex-row justify-between items-center mb-8">
<div class="mb-6 md:mb-0">
<h2 class="text-2xl font-semibold">Emma Reynolds</h2>
<p class="text-gray-400">Professional Virtual Assistant</p>
</div>
<div class="flex space-x-6">
<a href="#" class="text-gray-400 hover:text-white transition-colors">
<i class="ri-linkedin-fill ri-lg"></i>
</a>
<a href="#" class="text-gray-400 hover:text-white transition-colors">
<i class="ri-twitter-fill ri-lg"></i>
</a>
<a href="#" class="text-gray-400 hover:text-white transition-colors">
<i class="ri-instagram-fill ri-lg"></i>
</a>
<a href="#" class="text-gray-400 hover:text-white transition-colors">
<i class="ri-facebook-fill ri-lg"></i>
</a>
</div>
</div>
<div class="border-t border-gray-700 pt-8 flex flex-col md:flex-row justify-between">
<div class="mb-4 md:mb-0">
<p class="text-gray-400">&copy; 2025 Emma Reynolds. All rights reserved.</p>
</div>
<div class="flex flex-wrap gap-4">
<a href="#" class="text-gray-400 hover:text-white transition-colors">Privacy Policy</a>
<a href="#" class="text-gray-400 hover:text-white transition-colors">Terms of Service</a>
<a href="#" class="text-gray-400 hover:text-white transition-colors">Cookie Policy</a>
</div>
</div>
</div>
</footer>
<a href="#home" class="fixed bottom-6 right-6 w-12 h-12 bg-primary text-white rounded-full flex items-center justify-center shadow-lg hover:bg-primary/90 transition-colors">
<i class="ri-arrow-up-line ri-lg"></i>
</a>
<script>
document.addEventListener('DOMContentLoaded', function() {
// Smooth scrolling for anchor links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
anchor.addEventListener('click', function(e) {
e.preventDefault();
const targetId = this.getAttribute('href');
const targetElement = document.querySelector(targetId);
if (targetElement) {
window.scrollTo({
top: targetElement.offsetTop - 80,
behavior: 'smooth'
});
}
});
});
});
document.addEventListener('DOMContentLoaded', function() {
// Toggle switch functionality
const toggleSwitches = document.querySelectorAll('input[type="checkbox"]');
toggleSwitches.forEach(toggle => {
toggle.addEventListener('change', function() {
const slider = this.nextElementSibling;
if (this.checked) {
slider.classList.add('bg-primary');
slider.classList.remove('bg-gray-300');
slider.querySelector('before').style.transform = 'translateX(20px)';
} else {
slider.classList.remove('bg-primary');
slider.classList.add('bg-gray-300');
slider.querySelector('before').style.transform = 'translateX(0)';
}
});
});
});
document.addEventListener('DOMContentLoaded', function() {
// Active navigation link highlighting
const sections = document.querySelectorAll('section');
const navLinks = document.querySelectorAll('.nav-link');
window.addEventListener('scroll', function() {
let current = '';
sections.forEach(section => {
const sectionTop = section.offsetTop;
const sectionHeight = section.clientHeight;
if (window.pageYOffset >= sectionTop - 100) {
current = section.getAttribute('id');
}
});
navLinks.forEach(link => {
link.classList.remove('active', 'text-primary');
link.classList.add('text-gray-600');
if (link.getAttribute('href') === `#${current}`) {
link.classList.add('active', 'text-primary');
link.classList.remove('text-gray-600');
}
});
});
});
// Custom toggle switch styling
document.addEventListener('DOMContentLoaded', function() {
const toggles = document.querySelectorAll('input[type="checkbox"]');
toggles.forEach(toggle => {
toggle.addEventListener('change', function() {
const slider = this.nextElementSibling;
if (this.checked) {
slider.classList.add('bg-primary');
slider.classList.remove('bg-gray-300');
slider.style.setProperty('--before-transform', 'translateX(20px)');
} else {
slider.classList.remove('bg-primary');
slider.classList.add('bg-gray-300');
slider.style.setProperty('--before-transform', 'translateX(0)');
}
});
});
});
</script>
</body>
</html>
# online-resume
